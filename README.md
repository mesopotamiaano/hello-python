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

5/25〜27
Pythonの関数化をさらに進めた。  
前回までに作った `get_grade()` と `create_result()` を使い、今回は「全員分を処理する関数」と「条件に合う人だけ処理する関数」を作った。create_passed_results()
for in if >= 80点以上だけを処理。

5/28
2026/5/28 学習
前回までに作った関数を復習した
新しく is_passed(student)関数を作った
80点以上かどうかを True / False で返す処理を書いた
create_passed_results(students)の中で is_passed(student)を使った
条件に合う人だけをresultsに追加する流れを確認した

使ったデータ
 python
students = [
    {"name": "tanaka", "score": 80},
    {"name": "sato", "score": 60},
    {"name": "suzuki", "score": 80｝］

2026/6/2 学習ログ
今日やったこと
* 5分問題で get_grade() / create_result() の復習をした
* student["score"] の値を関数に渡す流れを確認した
* get_average(students) 関数を使って平均点を出す処理を学習した
* is_above_average(student, average) 関数で、平均以上かどうかを判定する処理を学習した
* create_above_average_results(students) で、平均以上の人だけを結果リストに入れる処理を学習した
* カンマ抜けによる SyntaxError を確認した
* 「内容は理解できるが、自力実装はまだ難しい」という現在地を確認した

2026/6/3〜6/4 学習ログ 学習テーマ
Pythonの `list` / `dict` / `for` / `if` / `append()` を使って、学生データを分析する練習を行った。  
特に、平均点・平均以上の判定・最高得点者・最低得点者を扱った。
  平均点を出す関数
使用したデータ
python
students = [
    {"name": "tanaka", "score": 80},
    {"name": "sato", "score": 60},
    {"name": "suzuki", "score": 90},
    {"name": "yamada", "score": 70}
]

2026/6/7 
今日やったこと
* 最高得点者を探す処理を復習した
* 最高得点者を辞書として保存する処理を確認した
* その処理を get_top_student(students) という関数にした
* return で最高得点者の辞書を返す流れを学習した
* インデントエラーを確認し、Pythonでは字下げが重要であることを再確認した

2026/6/8 
* 前回の get_top_student(students) の復習をした
* その逆パターンとして get_bottom_student(students) を作った
* 最低得点者を辞書として返す関数を実装した
* bottom_student = {} と bottom_score = 999 の役割を確認した
* return bottom_student で、最低得点者の辞書を返す流れを学習した
* インデントの位置にも注意した

2026/6/9 
* get_top_student(students) と get_bottom_student(students) の復習をした
* 最高得点者と最低得点者を、1つの関数でまとめて返す練習をした
* get_score_summary(students) を作った
* top / bottom / average を1つの辞書にまとめて返した
* average = total / count は、for 文が終わったあと、return の前に書くのが自然だと確認した

2026/6/10 
* get_average(students) の復習をした
* 昨日作った get_score_summary(students) を整理した
* 平均を出す処理を get_average() という別関数に分けた
* get_score_summary() の中で get_average(students) を呼び出す形にした
* 「全部1つの関数に書く場合」と「小さい関数に分ける場合」の違いを確認した

2026/6/11 
* get_top_student(students) の復習をした
* get_bottom_student(students) の復習をした
* get_average(students) の復習をした
* 3つの小さい関数を組み合わせて get_score_summary(students) を作った
* 最高得点者・最低得点者・平均点を1つの辞書にまとめて返した
* 現在の理解度として、「見れば理解できるが、まだ完全に1人で設計して書く段階ではない」と確認した
* 次回からSQLに戻る方針を確認した

2026/6/13 
Pythonはいったん区切り、SQLの復習に戻った。
今日は主に AND / OR / NOT / LIKE / LIMIT / IS NULL を学習した。

2026/6/14 
SQLの復習として、COUNT / AVG / GROUP BY / WHERE を学習した。
前回までの条件検索に加えて、今日は「人数を数える」「平均を出す」「グループごとに集計する」練習を行った。
name     score    grade
tanaka   90       A
sato     60       C
suzuki   80       B
yamada   70       C
 理解したこと
COUNT(*) は件数を数える
AVG(score) は平均を出す
GROUP BY はグループごとにまとめる
WHERE を使うと、条件に合うデータだけを対象にできる
 次回やること
HAVING を学習する。
WHERE は集計前の条件、HAVING は集計後の条件という違いを確認する。

2026/6/15 
SQLの集計処理を中心に、GROUP BY / HAVING / COUNT / AVG / AS を復習した。
今日は成果物作成ではなく、SQLの学習セット数を増やす練習を行った。
