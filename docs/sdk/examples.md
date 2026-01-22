# SDK Examples

> Code examples for `@beeper/desktop-api`

## Installation

```bash
npm install @beeper/desktop-api
# or
pnpm add @beeper/desktop-api
```

## Basic Usage

### Initialize Client

```typescript
import BeeperDesktop from "@beeper/desktop-api";

const client = new BeeperDesktop({
  accessToken: process.env.BEEPER_ACCESS_TOKEN,
  baseURL: "http://localhost:23373", // default
});
```

### List Accounts

```typescript
const accounts = await client.accounts.list();
console.log(accounts);
```

### Search Chats

```typescript
const result = await client.chats.search({ query: "family" });
console.log(result.data);
```

### Send Message

```typescript
await client.messages.send(chatID, {
  text: "Hello from the SDK!",
});
```

### Focus App

```typescript
// Focus Beeper window
await client.app.focus();

// Focus specific chat
await client.app.focus({ chatID: "some-chat-id" });
```

---

## More Examples

- [Raycast Extension](https://github.com/beeper/raycast) - Real-world SDK usage
- [Official SDK Repo](https://github.com/beeper/desktop-api-js)

---

## References

[^1]: [@beeper/desktop-api npm](https://npmjs.com/package/@beeper/desktop-api)
