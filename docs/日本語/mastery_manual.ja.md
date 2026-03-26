# マスタリーマニュアル (運用・保守者向け)

## cf.rbcc の重要ポイント
- `last write time` はOS更新時刻と整合チェックされる。
- `user!!` フラグ付き:
  - 例: `$`last write time yyyy/mm/dd hh:mm:ss.xx user!!`$`
  - 手編集を示す。
  - 許容範囲外の時刻差は警告表示（読み込みは継続）。
  - 差分書き込み時に `user!!` は除去される。

## 差分更新
- 変更キーのみ更新。
- 変更が1つでもあれば `last write time` を更新。
- format崩れやversion不一致時は全体再整形。

## ライセンス
- `LICENSE.md`。
