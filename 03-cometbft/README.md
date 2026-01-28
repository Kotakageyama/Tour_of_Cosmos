# Phase 3: CometBFT

## 目的
- Cosmos系チェーンのコンセンサスエンジンを理解する。
- フォークが起きる理由や分散合意の限界を掴む。

## 進め方（やること）
1. CometBFTの構成要素（Consensus, Mempool, P2P, ABCI）を整理する。
2. コンセンサスの流れ（Proposal -> Prevote -> Precommit -> Commit）を追う。
3. フォークが起きる条件と対策を理解する。
4. テストや設計ドキュメントを読み、現実の障害パターンを想像する。

## 参考リンク
- CometBFT GitHub: https://github.com/cometbft/cometbft
- CometBFT Docs: https://docs.cometbft.com
- Tendermint (参考): https://docs.tendermint.com

## 成果物イメージ
- コンセンサスのステップ別メモ。
- フォーク発生条件の整理。
