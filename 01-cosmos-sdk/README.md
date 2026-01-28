# Phase 1: Cosmos SDK

## 目的
- Cosmos SDKで独自L1チェーンを作るための基礎構造を理解する。
- 「業務アプリ脳」から「プロトコル脳」への切り替えを行う。

## 進め方（やること）
1. Cosmos SDKのアーキテクチャをざっくり把握する（モジュール構成、ABCI、BaseApp）。
2. 最小構成のチェーンテンプレートを読み、モジュール1個を自作する。
3. KVStoreを触り、状態管理の流れ（Msg -> Handler/MsgServer -> Keeper -> Store）を追う。
4. BeginBlocker / EndBlockerの役割と実行順序を理解する。
5. CLI/RESTでTxを投げて、状態更新が行われるところまで確認する。

## 参考リンク
- Cosmos SDK GitHub: https://github.com/cosmos/cosmos-sdk
- Cosmos SDK Docs: https://docs.cosmos.network
- Building Modules (Docs): https://docs.cosmos.network/main/building-modules/intro
- Ignite CLI (chain scaffold): https://github.com/ignite/cli

## 成果物イメージ
- 自作モジュールの雛形（Msg/MsgServer/Keeper/Store）を持つ最小チェーン。
- BeginBlocker/EndBlockerの役割と用途のメモ。
