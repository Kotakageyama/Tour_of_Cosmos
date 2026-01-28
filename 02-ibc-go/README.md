# Phase 2: IBC-Go

## 目的
- IBCの公式実装を読み、"使う"ではなく"作る"視点を身につける。
- Packet lifecycle（送信/受信/タイムアウト/アクノリッジ）をコードで追う。

## 進め方（やること）
1. IBCの基礎概念（Client/Connection/Channel/Packet）を整理する。
2. Packet lifecycleを追い、送信からACKまでの処理を辿る。
3. Timeout と Acknowledgement の仕様を理解する。
4. テストコードやexampleを読み、具体的なパケット処理の例を確認する。

## 参考リンク
- ibc-go GitHub: https://github.com/cosmos/ibc-go
- IBC Docs: https://ibc.cosmos.network
- IBC Specs: https://github.com/cosmos/ibc
- Packet lifecycle (Docs): https://ibc.cosmos.network/main/ibc/overview.html

## 成果物イメージ
- Packet lifecycleの処理フロー図 or 箇条書きメモ。
- Timeout/Ackのケース別まとめ。
