# Breaking Changes

This is a history of NIP changes that potentially break pre-existing implementations, in
reverse chronological order.

| Date        | Commit    | NIP      | Change |
| ----------- | --------- | -------- | ------ |
| 2024-02-16  | [cbec02ab](https://github.com/nostr-protocol/nips/commit/cbec02ab) | [NIP-49](49.md) | Password first normalized to NFKC |
| 2024-02-15  | [afbb8dd0](https://github.com/nostr-protocol/nips/commit/afbb8dd0) | [NIP-39](39.md) | PGP identity was removed |
| 2024-02-07  | [d3dad114](https://github.com/nostr-protocol/nips/commit/d3dad114)  | [NIP-46](46.md) | Connection token format was changed |
| 2024-01-30  | [1a2b21b6](https://github.com/nostr-protocol/nips/commit/1a2b21b6)  | [NIP-59](59.md) | 'p' tag became optional |
| 2023-01-27  | [c2f34817](https://github.com/nostr-protocol/nips/commit/c2f34817)  | [NIP-47](47.md) | optional expiration tag should be honored |
| 2024-01-10  | [3d8652ea](https://github.com/nostr-protocol/nips/commit/3d8652ea)  | [NIP-02](02.md) | list entries should be chronological |
| 2024-01-10  | [3d8652ea](https://github.com/nostr-protocol/nips/commit/3d8652ea)  | [NIP-51](51.md) | list entries should be chronological |
| 2023-12-30  | [29869821](https://github.com/nostr-protocol/nips/commit/29869821)  | [NIP-52](52.md) | 'name' tag was removed (use 'title' tag instead) |
| 2023-12-27  | [17c67ef5](https://github.com/nostr-protocol/nips/commit/17c67ef5)  | [NIP-94](94.md) | 'aes-256-gcm' tag was removed |
| 2023-12-03  | [0ba45895](https://github.com/nostr-protocol/nips/commit/0ba45895)  | [NIP-01](01.md) | WebSocket status code `4000` was replaced by 'CLOSED' message |
| 2023-11-28  | [6de35f9e](https://github.com/nostr-protocol/nips/commit/6de35f9e)  | [NIP-89](89.md) | 'client' tag value was changed |
| 2023-11-20  | [7822a8b1](https://github.com/nostr-protocol/nips/commit/7822a8b1)  | [NIP-51](51.md) | `kind: 30000` and `kind: 30001` were deprecated |
| 2023-11-11  | [cbdca1e9](https://github.com/nostr-protocol/nips/commit/cbdca1e9)  | [NIP-84](84.md) | 'range' tag was removed |
| 2023-11-07  | [108b7f16](https://github.com/nostr-protocol/nips/commit/108b7f16)  | [NIP-01](01.md) | 'OK' message must have 4 items |
| 2023-10-17  | [cf672b76](https://github.com/nostr-protocol/nips/commit/cf672b76)  | [NIP-03](03.md) | 'block' tag was removed |
| 2023-09-29  | [7dc6385f](https://github.com/nostr-protocol/nips/commit/7dc6385f)  | [NIP-57](57.md) | optional 'a' tag was included in `zap receipt` |
| 2023-08-21  | [89915e02](https://github.com/nostr-protocol/nips/commit/89915e02)  | [NIP-11](11.md) | 'min_prefix' was removed |
| 2023-08-20  | [37c4375e](https://github.com/nostr-protocol/nips/commit/37c4375e)  | [NIP-01](01.md) | replaceable events with same timestamp should be retained event with lowest id |
| 2023-08-15  | [88ee873c](https://github.com/nostr-protocol/nips/commit/88ee873c)  | [NIP-15](15.md) | 'countries' tag was renamed to 'regions' |
| 2023-08-11  | [d87f8617](https://github.com/nostr-protocol/nips/commit/d87f8617)  | [NIP-25](25.md) | empty `content` should be considered as "+" |
| 2023-08-01  | [5d63b157](https://github.com/nostr-protocol/nips/commit/5d63b157)  | [NIP-57](57.md) | 'zap' tag was changed |

Breaking changes prior to 2023-08-01 are not yet documented.

## NOTES

- If it isn't clear that a change is breaking or not, we list it.
- The date is the date it was merged, not necessarily the date of the commit.