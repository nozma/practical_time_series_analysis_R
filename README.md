- [O'Reilly Japan - 実践 時系列解析](https://www.oreilly.co.jp/books/9784873119601/)のコードをR中心に書き直したもの。
- どうしても必要そうならPythonをreticulateパッケージから使う方針で。

### 利用したRのパッケージ

- `readr`...サンプルデータの読み込みに利用。
- `dplyr`...データ変換、結合などに利用。
- `tidyr`...`unnest`とかで利用。
- `lubridate`...時間・日付の処理。
- `purrr`...`map`など。