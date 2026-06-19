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
今日の到達
* HAVING COUNT(*) >= 2 を使えた
* HAVING AVG(score) >= 75 を使えた
* GROUP BY と AVG を組み合わせられた
* COUNT と AVG を同時に出せた
* AS count / AS avg_score の意味を理解した
* WHERE と HAVING の違いを確認できた
次回
IS NOT NULL
JOINの入口
または、SQL復習問題


2026/6/16 学習ログ
今日やったこと
SQLを中心に6セット学習した。
* IS NULL / IS NOT NULL を使って、値が空のデータ・値が入っているデータを抽出した
* Pythonの None がSQLでは NULL として扱われることを確認した
* ORDER BY / ASC / DESC / LIMIT を復習した
* 数字の並び替えと名前の並び替えの違いを確認した
* GROUP BY grade でgradeごとの人数を数えた
* JOIN を使って、students テーブルと scores テーブルをつなげた
* AS を使って、テーブル名や列名を短く・分かりやすくした
* WHERE / ORDER BY / LIMIT をJOINと組み合わせて使った
理解したこと
* IS NULL は値が入っていないデータを探す
* IS NOT NULL は値が入っているデータを探す
* Pythonの None はSQLでは NULL になる
* ORDER BY score ASC は点数が低い順
* ORDER BY score DESC は点数が高い順
* ORDER BY name ASC は名前のアルファベット順
* ORDER BY name DESC は名前の逆順
* LIMIT 2 は結果を上から2件だけ表示する
* GROUP BY grade はgradeごとにまとめる
* JOIN は別々のテーブルをつなげる
* ON students.id = scores.student_id は、同じID同士をつなげる条件
* students AS s は students を s と省略する
* scores AS sc は scores を sc と省略する
* s.name は students.name のこと
* sc.score は scores.score のこと
次回やること
次回は、今日やったJOINをもう少し復習する。
* JOIN の基本形をもう一度書く
* ON の意味を確認する
* WHERE とJOINを組み合わせる
* ORDER BY / LIMIT とJOINを組み合わせる
* 余裕があれば、ミニ成果物に向けてSQLの検索・一覧表示に入る

2026/6/17 学習ログ
今日やったこと
SQLで JOIN を中心に復習した。
* students テーブルと scores テーブルを作成した
* JOIN を使って、学生名と点数をつなげて表示した
* WHERE sc.score >= 80 で80点以上の人だけを抽出した
* LIKE '%a%' を使って、名前に a を含む人を検索した
* ORDER BY sc.score DESC で点数が高い順に並べた
* LIMIT 2 を使って上位2人だけ表示した
* COUNT(*) で人数を数えた
* AVG(sc.score) で平均点を出した
* SELECT s.name, sc.score、COUNT(*)、AVG(sc.score) の使い分けを練習した
理解したこと
* JOIN は別々のテーブルをつなげるために使う
* ON s.id = sc.student_id は、students 側の id と scores 側の student_id が同じ行同士をつなげる条件
* s.name は students テーブルの名前
* sc.score は scores テーブルの点数
* WHERE を使うと、条件に合うデータだけを取り出せる
* LIKE '%a%' は、名前に a を含む人を探す
* ORDER BY sc.score DESC は、点数が高い順に並べる
* LIMIT 2 は、結果を上から2件だけ表示する
* SELECT s.name, sc.score は、1人1人の名前と点数を一覧表示する
* SELECT COUNT(*) は、人数・件数を数える
* SELECT AVG(sc.score) は、平均点を出す
次回やること
次回は、今日の内容を使ってミニ成果物に近い形に進む。
* 学生一覧を表示するSQL
* 名前検索するSQL
* 80点以上の人を表示するSQL
* 点数ランキングを表示するSQL
* 人数・平均点をまとめて出すSQL
余裕があれば、SQLの結果をPythonの変数に入れて、ミニ成果物の形に近づける。

2026/6/18 学習ログ
今日やったこと
SQLで取得した結果を、Python側で扱う練習をした。
* JOIN を使って students テーブルと scores テーブルをつなげた
* WHERE sc.score >= 80 で80点以上の人を抽出した
* ORDER BY sc.score DESC で点数が高い順に並べた
* SQLの実行結果を cursor.fetchall() で取得した
* SQLの結果を students_list や high_score_students などのPython変数に入れた
* SQLの結果を rows に入れ、for文で1行ずつ取り出した
* タプルのデータを辞書に変換した
* 辞書をリストに追加して、APIの返り値に近い形を作った
理解したこと
* cursor.fetchall() は、SQLの実行結果をまとめて取得する
* print(cursor.fetchall()) は結果を表示するだけ
* students_list = cursor.fetchall() のように変数に入れると、あとからPythonで使える
* rows はSQLの結果全体を入れるPythonの変数
* row は rows の中から1行ずつ取り出すための仮の変数名
* row[0] は1行の中の1個目のデータで、今回は名前
* row[1] は1行の中の2個目のデータで、今回は点数
* students_data = [] は、変換した辞書を入れていくための空リスト
* students_data.append(student) は、名前と点数を入れた辞書をリストに追加する
* result = {"students": students_data} は、生徒データをまとめた辞書を作っている
次回やること
次回は、今日の内容をもう一度復習する。
* rows = cursor.fetchall() の意味を確認する
* for row in rows: の使い方を復習する
* row[0] と row[1] の意味を確認する
* SQL結果を辞書リストに変換する練習をもう一度行う
* 余裕があれば、ミニ成果物として「学生一覧データ」をPythonで返す形に近づける

2026/6/19 学習ログ
今日やったこと
SQLで取得した結果を、Pythonで辞書リストに変換する練習をした。
* students テーブルと scores テーブルをJOINした
* cursor.fetchall() でSQLの結果を rows に入れた
* rows の中身を for row in rows: で1行ずつ取り出した
* row[0] と row[1] を使って、名前と点数を取り出した
* 名前と点数を辞書に変換した
* 辞書を students_data に追加した
* result = {"students": students_data} の形で、APIっぽい返り値を作った
* 80点以上の人だけを抽出して、high_score_students に辞書リストとしてまとめた
理解したこと
* rows はSQLから取ってきた結果で、タプルのリストになっている
* row は rows の中から1行ずつ取り出したもの
* row[0] は名前
* row[1] は点数
* students_data = [] は、辞書を入れるための空リスト
* student = {"name": row[0], "score": row[1]} で、1人分のデータを辞書にできる
* students_data.append(student) は、作った辞書をリストに追加している
* students_data[0] は、リストの中の1人目の辞書を取り出す
* first_student["name"] は、1人目の辞書から名前を取り出す
* first_student["score"] は、1人目の辞書から点数を取り出す
* result = {"students": students_data} は、学生データをまとめた辞書を作っている
次回やること
次回は、今日の変換処理をもう一度復習する。
* rows = cursor.fetchall() の意味を確認する
* for row in rows: の流れを復習する
* row[0] / row[1] の使い方を復習する
* students_data.append(student) の意味を確認する
* 余裕があれば、SQL結果を辞書リストにする処理を関数化する


