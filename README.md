# Tour_of_Cosmos

Golangは理解済みという前提で、Cosmosを段階的に学ぶためのロードマップリポジトリです。各フェーズのフォルダには「やること」と参考リンクをまとめています。順に進めることで、Cosmos SDK → IBC → コンセンサス → Relayer → 実チェーン理解と深掘りできます。

## 何を学ぶか（全体像）
1. **Cosmos SDK**: 独自L1チェーンを作るための基礎構造。
2. **IBC-Go**: IBCの公式実装をコードで追う。
3. **CometBFT**: コンセンサスと分散合意の理解。
4. **Hermes（番外編）**: IBC Relayerの設計思想。
5. **実チェーン**: Cosmos Hub / Osmosis を読む。

## フェーズ別フォルダ
- [Phase 1: Cosmos SDK](01-cosmos-sdk/README.md)
- [Phase 2: IBC-Go](02-ibc-go/README.md)
- [Phase 3: CometBFT](03-cometbft/README.md)
- [Phase 4: Hermes（番外編）](04-hermes-relayer/README.md)
- [Phase 5: 実チェーンで学ぶ](05-real-chains/README.md)
