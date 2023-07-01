# ICP AZLE Message Project

Based on [TypeScript Smart Contract 101 | Dacade](https://dacade.org/communities/icp/courses/typescript-smart-contract-101)

## Start DFX 

```
% dfx start --background --clean

Running dfx start for version 0.14.1
Using the default definition for the 'local' shared network because /Users/warun/.config/dfx/networks.json does not exist.
Initialized replica.
Dashboard: http://localhost:61502/_/dashboard
```

## Deploy SmartContract

```
% dfx deploy                                                        
Deploying all canisters.
Creating a wallet canister on the local network.
The wallet canister on the "local" network for user "default" is "bnz7o-iuaaa-aaaaa-qaaaa-cai"
Creating canisters...
Creating canister message_board...
message_board canister created with canister id: bkyz2-fmaaa-aaaaa-qaaaq-cai
Building canisters...
Executing 'npx azle message_board'

Building canister message_board

[1/2] 🔨 Compiling TypeScript... 3.42s
[2/2] 🚧 Building Wasm binary... 6.89s

Done in 11.30s.

🎉 Built canister message_board at .azle/message_board/message_board.wasm.gz
Installing canisters...
Creating UI canister on the local network.
The UI canister on the "local" network is "bd3sg-teaaa-aaaaa-qaaba-cai"
Installing code for canister message_board, with canister ID bkyz2-fmaaa-aaaaa-qaaaq-cai
Deployed canisters.
URLs:
  Backend canister via Candid interface:
    message_board: http://127.0.0.1:4943/?canisterId=bd3sg-teaaa-aaaaa-qaaba-cai&id=bkyz2-fmaaa-aaaaa-qaaaq-cai
```

## Stop DFX

```
% dfx stop
Using the default definition for the 'local' shared network because /Users/warun/.config/dfx/networks.json does not exist.
Stopping canister http adapter...
Stopped.
Stopping the replica...
Stopped.
Stopping icx-proxy...
Stopped.
```
