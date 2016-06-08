# SensorBee + Jubatus Classifier

SensorBee + Jubatus プラグインで Iris データセットの分類を行うサンプルです。

## 使い方

SensorBee サーバをビルドします。

```
build_sensorbee
```

SensorBee サーバを実行します。

```
./sensorbee run -c sensorbee.yaml
```

`result.jsonl` (`iris.jsonl` に予測結果フィールド `EstimatedSpecies` が足されたもの) が生成されます。
