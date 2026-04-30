# @beeper/desktop-api Changelog

> [npm](https://npmjs.com/package/@beeper/desktop-api) · [GitHub](https://github.com/beeper/desktop-api-js) · [JSON Feed](../../feeds/releases.json)

---

## Latest Version

`[official]` Check back soon — automation will populate this!

---

## Version History

## v4.7.1 - 2026-04-08

`[official]`

The official TypeScript library for the Beeper Desktop API

→ [npm](https://www.npmjs.com/package/@beeper/desktop-api/v/4.7.1)

---

## v4.7.1 - 2026-04-08

`[official]`

### 4.7.1 (2026-04-07)

Full Changelog: [v4.7.0...v4.7.1](https://github.com/beeper/desktop-api-js/compare/v4.7.0...v4.7.1)

### Bug Fixes

* escape MCP `instructions` backticks as necessary ([5054afe](https://github.com/beeper/desktop-api-js/commit/5054afe374e27b9aec675a7d53d30dcaf0a7a351))
* **internal:** gitignore generated `oidc` dir ([4ed5379](https://github.com/beeper/desktop-api-js/commit/4ed5379638ea7b0d9f8ee38b7c085088f9ee77d1))


### Chores

* **ci:** escape input path in publish-npm workflow ([542eb4d](https://github.com/beeper/desktop-api-js/commit/542eb4d6449db180fe9cd7d4bbc48fe67275c5a2))
* **ci:** skip lint on metadata-only changes ([c829f2e](https://github.com/beeper/desktop-api-js/commit/c829f2e95c7ff077a9bf30a0ca31256313d28e28))
* **internal:** codegen related update ([8fce23c](https://github.com/beeper/desktop-api-js/commit/8fce23c041ec6b450ab34dabaf96c913dbc3ad5e))
* **internal:** codegen related update ([5152f44](https://github.com/beeper/desktop-api-js/commit/5152f44ac234096181c741ce83c2e93c96a76702))
* **internal:** fix MCP docker image builds in yarn projects ([60ccb25](https://github.com/beeper/desktop-api-js/commit/60ccb2538c55d36737c0800fb1c29be21bfad1c3))
* **internal:** fix MCP server import ordering ([85ed5e7](https://github.com/beeper/desktop-api-js/commit/85ed5e74f405a3aeff2c999aa4c0fa183994d6f4))
* **internal:** fix MCP server TS errors that occur with required client options ([39f92ad](https://github.com/beeper/desktop-api-js/commit/39f92ad78be85d04b893d23d2c9cf5c655176fdc))
* **internal:** improve local docs search for MCP servers ([b0c172b](https://github.com/beeper/desktop-api-js/commit/b0c172b07c42f07ed9ed7d8c7eb6ed838d44926c))
* **internal:** improve local docs search for MCP servers ([2627f4e](https://github.com/beeper/desktop-api-js/commit/2627f4eba72b3859c2c8ea7f86ae43595b9ca4c2))
* **internal:** make generated MCP servers compatible with Cloudflare worker environments ([51ed091](https://github.com/beeper/desktop-api-js/commit/51ed09114417dd970167ef9e02663f729cc3ffa8))
* **internal:** support custom-instructions-path flag in MCP servers ([8888fc6](https://github.com/beeper/desktop-api-js/commit/8888fc6c71cc76c2153e8d6f11960b522153a9b8))
* **internal:** support local docs search in MCP servers ([7e09d80](https://github.com/beeper/desktop-api-js/commit/7e09d80e2309890331d4a3e5c4ae006ef911e369))
* **internal:** support type annotations when running MCP in local execution mode ([dad62ee](https://github.com/beeper/desktop-api-js/commit/dad62ee551a6ad54e08c670beef89d91534f4ae2))
* **internal:** support x-stainless-mcp-client-envs header in MCP servers ([f152521](https://github.com/beeper/desktop-api-js/commit/f152521d3d12eebf07826d8494e619f22a856eb5))
* **internal:** support x-stainless-mcp-client-permissions headers in MCP servers ([b714f03](https://github.com/beeper/desktop-api-js/commit/b714f0318bfde5ccdf2ef1f9e9679d2d6267a926))
* **internal:** tweak CI branches ([9b5fa46](https://github.com/beeper/desktop-api-js/commit/9b5fa462f35e2476f528a8b5b432e870651b4ae9))
* **internal:** update gitignore ([701eec1](https://github.com/beeper/desktop-api-js/commit/701eec1214e0ef23d92a4dbfb6f9bc660e93f79c))
* **internal:** update multipart form array serialization ([d137743](https://github.com/beeper/desktop-api-js/commit/d137743aa7ccfc9a3a0b51580a098210ab42b592))
* **internal:** use link instead of file in MCP server package.json files ([5a05063](https://github.com/beeper/desktop-api-js/commit/5a050630b6b6850ed634045a906e5f6929b66714))
* **mcp-server:** add support for session id, forward client info ([1bb26fb](https://github.com/beeper/desktop-api-js/commit/1bb26fbea126c85c3ae80704b536ce0322319081))
* **mcp-server:** log client info ([1a44cd2](https://github.com/beeper/desktop-api-js/commit/1a44cd28811d29a94d18274c8a9bebd750bbc1f2))
* **tests:** bump steady to v0.19.4 ([21244db](https://github.com/beeper/desktop-api-js/commit/21244db3761dd06eef1cbd431ee988dafed9e0b9))
* **tests:** bump steady to v0.19.5 ([afd0423](https://github.com/beeper/desktop-api-js/commit/afd0423f3fe2664e660ada160f79b111947cefb9))
* **tests:** bump steady to v0.19.6 ([9226701](https://github.com/beeper/desktop-api-js/commit/9226701faed2318b21d08d2d89208639628e3307))
* **tests:** bump steady to v0.19.7 ([e681061](https://github.com/beeper/desktop-api-js/commit/e681061239598ef4cb16a05ff80406b54934bfad))
* **tests:** bump steady to v0.20.1 ([812a0fd](https://github.com/beeper/desktop-api-js/commit/812a0fd7e4f7c45b8cc94da84fc7a1afbafc94e2))
* **tests:** bump steady to v0.20.2 ([64f4360](https://github.com/beeper/desktop-api-js/commit/64f4360bcf2a11212c64ddad4921b6cc3a2c48be))
* update SDK settings ([d4a125e](https://github.com/beeper/desktop-api-js/commit/d4a125ec0947b1e2f95d56ee9293254c6225118f))


### Refactors

* **tests:** switch from prism to steady ([215316c](https://github.com/beeper/desktop-api-js/commit/215316c820ab2067a629b325e87f99bc4352f163))

→ [Release Notes](https://github.com/beeper/desktop-api-js/releases/tag/v4.7.1)

---

<!-- Automation adds entries here -->

Coming soon...

---

## References

<!-- References added by automation -->
