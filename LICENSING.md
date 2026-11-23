# Licensing

Roboto SAI work is licensed in tiers. Every tier leaves ownership with the Owner, Roberto Villarreal Martinez; none of
them hands anyone ownership. This folder holds the templates. Each repository carries the one that applies to it.

| Tier | Used for | Template | SPDX id |
|---|---|---|---|
| **RVM License** (sovereign, the default) | Anything the Owner creates or owns that doesn't name another license. All rights reserved. | [`LICENSE` in Roboto-SAI-LLC/Roboto-SAI-LLC](https://github.com/Roboto-SAI-LLC/Roboto-SAI-LLC/blob/HEAD/LICENSE) | `LicenseRef-RVM` |
| **PolyForm Noncommercial 1.0.0** | Public repos people may read and use, but not commercially without signed permission. | [`licenses/PolyForm-Noncommercial-1.0.0.md`](licenses/PolyForm-Noncommercial-1.0.0.md) | `PolyForm-Noncommercial-1.0.0` |
| **Apache License 2.0** | Public repos released as open source. Credit required; no rights to the Roboto SAI name or marks. | [`licenses/Apache-2.0.txt`](licenses/Apache-2.0.txt) | `Apache-2.0` |
| **RVM Partner Agreement** (draft, not in force) | A signed, mutual agreement with a partner company for joint work. | [`licenses/RVM-Partner-Agreement-DRAFT.md`](licenses/RVM-Partner-Agreement-DRAFT.md) | n/a |

## Which one applies

1. If a repository has its own `LICENSE` file, that file governs the repository. A repository whose `LICENSE` is
   PolyForm Noncommercial or Apache 2.0 is under that public tier, and the RVM License does not apply to it.
2. If a repository has no `LICENSE` file, the RVM License applies to work the Owner created or owns.
3. Forks of other people's projects keep their upstream licenses. The RobotoSairif fonts are under the SIL Open Font
   License.
4. A written agreement signed by the Owner governs what it covers.

## Applying a public tier to a repository

- **PolyForm Noncommercial:** copy `licenses/PolyForm-Noncommercial-1.0.0.md` into the repository as `LICENSE.md`,
  keeping the `Required Notice:` line at the top.
- **Apache 2.0:** copy `licenses/Apache-2.0.txt` into the repository as `LICENSE`, and add a `NOTICE` file with the
  copyright line.

Questions or permission requests: roberto@roboto-sai.com
