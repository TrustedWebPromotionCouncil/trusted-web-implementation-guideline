# Trusted Web デザインパターン（TWDP）

Trusted Webは、既存のインターネットとウェブというインフラの上に新たなTrustの枠組みをオーバーレイで付加することを目指します。Trusted Web デザインパターン TWDPは利用者から見てTrusted Webの目指すべき方向性に即した設計や実装する際のプラクティスとして利用することができます。

[https://trustedweb.go.jp/](https://trustedweb.go.jp/)

## TWDPにおける用語

| 項番 | 用語     | 解説 |
| ---- | -------- | ---- |
| 1    | Issuer   |  エンティティが、1 つまたは複数の対象に関する主張を行い、これらの主張から検証可能なクレデンシャル を作成し、検証可能なクレデンシャルを保持者に送信することによって実行できる役割。 |
| 2    | Holder   |  エンティティが 1 つまたは複数の検証可能なクレデンシャルを所有し、それらから提示を生成する ことによって果たす役割。保持者は通常、常にではないが、保持している検証可能なクレデンシャルのサブジェクトである。保持者はクレデンシャル・リポジトリに自分のクレデンシャルを保管する。  |
| 3    | Verifier |  エンティティが 1 つ以上の検証可能なクレデンシャルを受け取ることによって果たす役割で、任意 で処理のために検証可能な提示の中にある。他の仕様では、この概念を依拠当事者と呼ぶ場合もある。  |
| 4    | 検証鍵   |  公開鍵暗号の鍵ペアにおける、公開鍵。 |
| 5    | 署名鍵 |  公開鍵暗号の鍵ペアにおける、秘密鍵。 |


## アイコン集
![icon集](media/icons.png)

## Trusted Web デザインパターン（TWDP）一覧

* [Aパターン（IssuerとVerifierの分離）](./A_パターン/README.md)
* [Bパターン（1対1でのデータのやり取り）](./B_パターン/README.md)
* [Cパターン（本人であることの証明）](./C_パターン/README.md)

## Trusted Webの目指すべき方向性

Trusted Webが実現を目指すTrustの仕組みは、特定のサービスに過度に依存せず、

* ユーザ（自然人又は法人）自身が自らに関連するデータをコントロールすることを可能とし、
* データのやり取りにおける合意形成の仕組みを取り入れ、その合意の履行のトレースを可能としつつ、
* 検証（verify）できる領域を拡大することにより、Trustの向上を目指すものである。


## Trusted Webアーキテクチャ

Trusted Webにおけるアーキテクチャは以下の５の構成要素からなります。

### Entity

### Verifiable Identity

### Verifiable Data

### Verifiable Messaging

### Verifiable Data Community
