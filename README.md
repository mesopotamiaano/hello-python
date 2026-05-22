# hello-python

今日できたこと
GitHubアカウントを作成
Hello_pythonファイルを持ってきた
起動した
pandas 行列、.mean()をした

3/2
pandas　DataFrame作成 条件抽出(ブールインデックス)　列ベクトル演算　割合計算.mean()　.locによる条件代入を学んだ

3/3
pandas CSV作成, read_csv読み込み ,groupby分解,　計算.mean,max,min,count .agg一括集計, 辞書集計, 条件抽出

3/4
pandas ブール配列の理解, &/|の基礎結合,  丸括弧が必要な理由, 条件抽出+並び替えの合成, 処理の順番を構造で考える力

3/5
pandasの欠損地(NaN)の理解, .isna().dropna().fillna()の使い方, fillna()は新しいSeriesを返すため、代入が必要, 列計算で新しい列を作成

3/6
pandas基礎　平均を出す、　条件抽出,　並び替え、　新しい列を作る、　分析に使う

3/7
groupby, agg複数集計
3/9)
value_counts, crosstab二つ項目の関係を見る, 条件抽出, 
3/10
SCVファイル作成df.to_csv("sales_data.csv", index=False)保存, CSVファイル読み込みpd.read_csv, データ確認df.head()
3/11
.mean(), .max(), .min(). sort_values(), 条件抽出df[条件], groupby()グループ集計
3/14
pandas value_counts, crosstab, print(),if,else,for,～:はブロック開始
3/16
python関数, def/引数/return, 辞書, キーと値,データ取得,データ追加
3/17
list,dict  forで一つずつ取り出す, ifで条件分岐, p["キー"]で値を取り出す, count = 0数える準備, count += 1条件に合うものをカウント, データ処理の流れ　データ取り出す条件集計。
3/18
listの作成[], appendでデータ追加, count,total,result
3/19
Pythonの関数の理解と実装、データ処理を関数としてまとめる練習、合計平均のロジック、returnの動きと重要性、インテスドの理解
MISS=returnをfor文の前に書いてしまい、一件しか処理されなかった。
3/20
ファイル操作（読み込み、書き込み) データ処理（分割、数値変換、条件抽出）　例外処理（try\except） continueによるスキップ変換。
学び　ファイルは作成＞読み込み＞処理＞保存　　
3/21
関数化、ファイル操作、例外処理、continueによるスキップ処理、条件変更、出力形式の変更、カウント処理
3/22
前回の復習込めてcount人数, total合計 平均点をだした 
3/23
ファイル操作（読み込みreadlines）,データ分割（split),例外処理（try/except),条件分岐,リストにデータを保存（append）sum/len
3/24
def is_pass true,False判定

3/25 関数 def calc_average(scores):   return sum(scores) / len(scores) 平均を計算する処理

3/27~31 関数、ファイル操作、例外処理、データ構造、データ処理　parse_lineでコード整理、役割分担

４月まとめ
python
for文の反復処理　if/elif/else  変数の更新処理　　count += 1個数を数える　total += scoreで合計を出す　avg = total/ countで合計を計算　条件に合うデータだけを抽出して処理する練習　
SQL
SELECT FROM WHERE ORDER BY  COUNT AVG MAX サブクエリ
Python ＊ SQLの連携
sqlite3を使って: テーブル作成、データ追加　fetchall()で取得　Pythonでループ処理　SQLで取得したデータをPythonで集計

５月～２０日ごろ
復習SELECT,FROM,WHERE,ORDER BY,COUNT, AVG, サブクエリ,pythonのsqlite3との連携, fetchall()
Pythonでデータを扱う基礎をした。特に、SQLで扱っていたようなデータを、Pythonのlist,dict で処理する練習を行った。

5/21
pythonの関数defを学習した。　get_grade関数を作った。
点数に応じてA/B/Cを返す処理を書いた。
studentsのデータに対して関数を使ってgradeを付けた。resultsリストに新しい辞書データを追加した。

5/22
前回作ったget_grade(score)関数を復習した。新しくcreate_result(student)関数を作った。一人分の辞書データを受け取って新しい辞書データに変換した。for文で全員分にcreate_result()を使いresults リストを作った。関数同士のつながりを確認した。
