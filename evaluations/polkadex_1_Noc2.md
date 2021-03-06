# Evaluation

* **Acceptance:** In Progress
* **PR Link:** https://github.com/w3f/Open-Grants-Program/pull/50
* **Milestone:** 1
* **Kusama Identity:** [HFG4FvoJv8uanizzetS1tPA6wigNAiKuEHKcm1NaKNNDwve](https://polkascan.io/pre/kusama/account/HFG4FvoJv8uanizzetS1tPA6wigNAiKuEHKcm1NaKNNDwve)
* **Previously successfully merged evaluation:** All evaluations by Noc2

| Number | Deliverable | Accepted | Link | Evaluation Notes |
| ------------- | ------------- | ------------- | ------------- |------------- |
| 0. | Apache License 2.0 | <ul><li>[x] </li></ul>| [License](https://github.com/Polkadex-Substrate/Polkadex/blob/master/LICENSE)| - | 
| 1. | Refactor Trading Engine in DEX pallet |<ul><li>[ ] </li></ul>| [Polkadex Pallet](https://github.com/Polkadex-Substrate/Polkadex/blob/17f5d0faa079b1fadc44c24b784d430eaf8b037c/pallets/polkadex/src/lib.rs) | Compiles, Can not really test refactoring
| 2. | Optimize Storage access |<ul><li>[ ] </li></ul>|  | Not clear how they optimized it
| 3. | Check for Data errors |<ul><li>[x] </li></ul>| [Polkadex Pallet](https://github.com/Polkadex-Substrate/Polkadex/blob/17f5d0faa079b1fadc44c24b784d430eaf8b037c/pallets/polkadex/src/lib.rs) | Integrated .ok_or, but no tests for it
| 4. | Market Data API |<ul><li>[x] </li></ul>| [Market Data](https://github.com/Polkadex-Substrate/Polkadex/blob/17f5d0faa079b1fadc44c24b784d430eaf8b037c/pallets/polkadex/src/lib.rs#L113) |  stored on the chain 
| 5. | Enable Market Data RPC |<ul><li>[x] </li></ul>| [Market Data RPC](https://github.com/Polkadex-Substrate/Polkadex/blob/17f5d0faa079b1fadc44c24b784d430eaf8b037c/pallets/polkadex/rpc/src/lib.rs#L33) |  Implemented
| 6. | Unit tests  |<ul><li>[ ] </li></ul>| [JS Tests](https://github.com/Polkadex-Substrate/Polkadex/blob/17f5d0faa079b1fadc44c24b784d430eaf8b037c/tests/engine-tests/basic-tests.js), [tests](https://github.com/Polkadex-Substrate/Polkadex/blob/master/pallets/polkadex/src/lib.rs) | No unit tests in rust  
| 7. | Documentation |<ul><li>[ ] </li></ul>| [Polkadex Pallet](https://github.com/Polkadex-Substrate/Polkadex/blob/17f5d0faa079b1fadc44c24b784d430eaf8b037c/pallets/polkadex/src/lib.rs#L128), [Doc Repo](https://github.com/Polkadex-Substrate/Documentation) |  cargo doc support, additionally repo containing documentation, I tried to follow the tutorial and did run in some issues 
| 8. | Docker Container |<ul><li>[x] </li></ul>| [Docker Compose File](https://github.com/Polkadex-Substrate/Polkadex/blob/17f5d0faa079b1fadc44c24b784d430eaf8b037c/docker-compose.yml) | - |

## General Notes

