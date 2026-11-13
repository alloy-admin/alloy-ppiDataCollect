# Alloy. ppi_dataCollect

Tool for collecting per-shot data from network directories (Windows, no installation required).

Download the latest release from the [Releases](https://github.com/alloy-admin/alloy-ppiDataCollect/releases) page.

## 使い方

1. [Releases](https://github.com/alloy-admin/alloy-ppiDataCollect/releases/latest) から `ppi_dataCollect.zip` をダウンロードし、書き込みのできるフォルダに展開します（インストールは要りません）。
2. `ppi_dataCollect\ppi_dataCollect.exe` を起動します。
3. **プロジェクト**を選びます。「更新」でサーバーのフォルダの一覧を読み直します。
4. **収集データ**を、次のどちらかで指定します。
   - 各段のプルダウンで選ぶ（「すべて」も選べます）。
   - 「カットリストを読み込む…」で `.txt` / `.csv` を読む。1 行に 1 カットを `episode_sequence_shot` の形で書きます（`#` から後はメモ）。「解除」でプルダウンに戻ります。
5. **保存先**を「選ぶ…」で決めます。中に日付のフォルダ（例: `261113`、既にあれば `261113_2`）ができます。止まった収集の続きをするときは、前の日付のフォルダそのものを選びます。
6. 「検索」で集める物を確かめ、「収集」でコピーします。「中止」で止められます。

- 集めるのは、選んだ段より下のすべてです。バージョンは最新だけです。
- 見つからない物、空や作りかけのバージョンは集めず、別の窓にパスを出します（「コピー」で写せます）。
- 保存先に記録 `ppi_collect_log_<日時>.txt` を残します。コピー元は変えません。
- バージョンは画面の右下に出ます。
