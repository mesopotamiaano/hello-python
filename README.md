

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

2026/6/20 学習ログ
今日やったこと
SQLで取得した結果を、Pythonで辞書リストに変換する練習を続けた。
* rows / row / row[0] / row[1] の意味を復習した
* タプルとは何かを確認した
* SQLの結果を cursor.fetchall() で取得した
* rows に入ったタプルのリストを、辞書のリストに変換した
* students_data に名前と点数の辞書を追加した
* result = {"students": students_data} の形でデータをまとめた
* 辞書リスト変換の処理を convert_rows_to_students(rows) という関数にした
* 関数を使って、全員一覧と80点以上の一覧を作った
* AVG(sc.score) を使って平均点を出した
* fetchall() と fetchone() の違いを確認した
理解したこと
* rows は、SQLから取ってきたタプルのリスト
* row は、rows の中の1行分のタプル
* row[0] は名前
* row[1] は点数
* タプルは、複数の値をひとまとめにしたもの
* SQLの結果は、最初は ('tanaka', 90) のようなタプルで返ってくる
* それを {"name": "tanaka", "score": 90} のような辞書に変換すると、PythonやAPIで使いやすくなる
* students_data.append(student) は、1人分の辞書をリストに追加している
* 関数にすると、毎回for文を書かなくてよくなる
* fetchall() は複数行をまとめて取る
* fetchone() は1行だけ取る
* 平均点のように結果が1つだけの場合は、fetchone() を使って取り出せる
次回やること
次回は、平均点の取り出しを復習する。
* fetchall() と fetchone() の違い
* average_row = cursor.fetchone() の意味
* average_score = average_row[0] の意味
* all_students / high_score_students / average_score を1つの result にまとめる練習
* 余裕があれば、これらを関数化してミニ成果物に近づける

2026/6/22 学習ログ
今日やったこと
前回の続きとして、fetchall() と fetchone() の違いを復習し、全員一覧・80点以上一覧・平均点を1つの result にまとめる練習をした。
* fetchall() と fetchone() の違いを確認した
* average_row = cursor.fetchone() の意味を確認した
* average_score = average_row[0] で平均点を取り出した
* convert_rows_to_students(rows) を使って、SQL結果を辞書リストに変換した
* 全員の一覧を all_students に入れた
* 80点以上の一覧を high_score_students に入れた
* 平均点を average_score に入れた
* 最後に students / high_score_students / average_score を1つの result にまとめた

2026/6/25 学習ログ
今日やったこと
前回までに作った all_students、high_score_students、average_score を復習し、それらを1つの result にまとめる処理を確認した。
さらに、処理全体を get_score_summary() という関数にまとめる練習をした。
* convert_rows_to_students(rows) を使って、SQLの結果を辞書リストに変換した
* 全員一覧を all_students に入れた
* 80点以上の一覧を high_score_students に入れた
* 平均点を average_score に入れた
* result = {"students": ..., "high_score_students": ..., "average_score": ...} の形でまとめた
* get_score_summary() を作り、成績まとめを一気に返す関数にした
* summary = get_score_summary() で関数を実行し、返ってきた結果を summary に入れた
* summary["students"]、summary["high_score_students"]、summary["average_score"] で中身を取り出した

2026/6/26 学習ログ
今日やったこと
前日の get_score_summary() を復習し、さらに処理を小さい関数に分ける練習をした。
その後、名前検索の関数 search_students_by_name(keyword) を作った。
* get_all_students() を作り、全員一覧を返す関数にした
* get_high_score_students() を作り、80点以上の人だけを返す関数にした
* get_average_score() を作り、平均点を返す関数にした
* get_score_summary() の中で3つの関数を呼び出し、まとめて result にした
* LIKE '%a%' を使って、名前に a を含む人を検索した
* keyword = "a" と search_word = f"%{keyword}%" を使って、検索文字を変数で扱った
* WHERE s.name LIKE ? と (search_word,) を使って、SQLに検索条件を渡した
* search_students_by_name(keyword) を作り、名前検索を関数化した
* "a" で検索して、tanaka、yamada、sato を出した
* "su" で検索して、suzuki を出した

次回やること
次回は今日の内容を復習する。
* get_all_students() の復習
* get_high_score_students() の復習
* get_average_score() の復習
* get_score_summary() の復習
* search_students_by_name(keyword) の復習
* f"%{keyword}%" の意味をもう一度確認する
* 余裕があれば、これらをまとめて「学生成績管理ミニアプリ」として整理する

2026/7/13 学習ログ
今日やったこと
PC復活後の復習として、これまで学習したSQL・Python・関数の内容を総復習した。
* rows、row、row[0]、row[1] の意味を復習
* SELECT、FROM、JOIN、ON、WHERE、ORDER BY の役割を復習
* convert_rows_to_students() の処理を復習
* get_all_students()
* get_high_score_students()
* get_average_score()
* get_score_summary()
* search_students_by_name() の役割を復習
* 新しく「引数（parameter）」を使う関数を学習
* get_students_over_score(score) を考え、固定条件ではなく自由な点数で検索できる仕組みを理解した

2026/7/22 学習レジュメ

今日は前回学習した引数を使う関数の復習を行い、get_students_over_score(score) の仕組みを中心に理解を深めた。

まず、関数の流れを確認し、score は検索したい点数を表す引数であり、? にはその値が入ること、(score,) はその値をSQLへ渡すためのタプルであることを学んだ。また、rows = cursor.fetchall() はSQLの検索結果をすべて取得し、convert_rows_to_students(rows) はその結果を辞書のリストへ変換する役割を持ち、return students が最終的な検索結果を返すことを復習した。

さらに、get_students_over_score(80)、get_students_over_score(60)、get_students_over_score(90) の実行結果を考え、同じ関数でも引数を変えるだけで異なる結果を取得できることを理解した。また、>= を <= に変更すると指定した点数以下を取得でき、DESC を ASC に変更すると点数の低い順に並び替えられることも確認した。

2026/7/23 学習レジュメ

今日はこれまで学習してきた内容の総復習を行い、関数を見ながらではあるが自分で組み立てる練習を行った。また、新しく引数を2つ使う関数を作成し、SQLへ複数の値を渡す方法を学習した。

まず、convert_rows_to_students(rows) を見ずに書くことに挑戦したが、この関数はまだコードを見ないと書くことが難しかった。一方で、get_students_over_score(score) はSQLや fetchall()、convert_rows_to_students() を組み合わせてほぼ自力で作成することができ、前回より理解が深まっていることを実感した。

その後、新しく get_students_between_score(min_score, max_score) を作成した。最初は ORDER BY を書き忘れたり、convert_rows_to_students(rows) の代わりに自分自身の関数を呼び出してしまうミスがあったが、修正後は正常に動作した。WHERE sc.score >= ? AND sc.score <= ? とすることで、指定した点数の範囲内の生徒だけを取得できることを確認した。また、(min_score, max_score) と書くことで、2つの値をSQLへ渡していることを理解した。

総復習では、fetchall() はSQLの検索結果をPythonへ取得するために使われること、convert_rows_to_students(rows) は検索結果を辞書のリストへ変換する役割を持つことを説明できた。また、FastAPIで使用する @app.get("/students/{score}") の {score} が、これまで学習してきた関数の引数 score と同じ役割を持つことも理解した。

さらに、get_students_over_score(score) と get_students_between_score(min_score, max_score) を比較し、後者は点数の範囲を自由に指定できるため、より汎用性が高く再利用しやすい関数であることを説明できた。

今日の成果

* get_students_over_score(score) をほぼ自力で作成できた。
* get_students_between_score(min_score, max_score) を作成し、引数を2つ使う方法を理解した。
* SQLへ複数の値を渡す方法を学んだ。
* fetchall() と convert_rows_to_students() の役割を説明できるようになった。
* 関数の再利用性（汎用性）の考え方を理解した。
* FastAPIで使う引数の考え方が、現在学習しているPythonの関数とつながることを理解した。

現在の理解度

約97％

convert_rows_to_students() はまだ見ながら書く必要があるものの、get_students_over_score() や get_students_between_score() は流れを理解しながら組み立てられるようになってきた。コードを丸暗記する段階ではなく、「処理の流れを理解して必要に応じて書ける」段階へ着実に成長している。

次回の予定

次回からはいよいよFastAPIの学習を開始する。これまで作成したSQL・Pythonの関数を利用しながら、ブラウザからデータを取得できるWeb APIを作成し、バックエンド開発の第一歩を学んでいく。

2026/7/25 学習レジュメ

今日はFastAPIの学習を開始した。from fastapi import FastAPI はFastAPIライブラリを使えるようにするための文であり、app = FastAPI() はWebアプリの本体を作成することを学んだ。また、@app.get("/") はブラウザで指定したURLにアクセスしたときに関数を実行する仕組みであり、return の内容がブラウザへJSON形式で返されることを理解した。さらに、@app.get("/students") や @app.get("/students/{score}") を通して、これまで作成したPythonの関数をブラウザから利用できるようになることを学んだ。FastAPIになってもPythonやSQLの処理内容は変わらず、呼び出し方が変わるだけであることを理解した。FastAPIのインストールはまだできていないため、次回は環境構築を行い、実際にブラウザでAPIを動かす予定。

2026/7/26 学習レジュメ

今日はFastAPIを実際に動かす環境を構築し、main.py を作成してUvicornを起動した。ブラウザで http://127.0.0.1:8000/ を開き、{"message":"Hello FastAPI!"} が表示されることを確認し、初めてFastAPIアプリを動かすことができた。また、app = FastAPI() はWebアプリを作成し、@app.get("/") はトップページへのアクセス時に home() を実行すること、return の内容がブラウザへ返される仕組みを学んだ。FastAPIは新しい処理を書くものではなく、これまで作成したPythonの関数をブラウザから利用できるようにする仕組みであることを理解した。次回は /docs を使い、APIの動作確認とこれまで作成した関数をFastAPIから呼び出す方法を学習する予定。

2026/7/27 学習レジュメ

今日はFastAPIの/docs（Swagger UI）を使い、APIの一覧や動作確認ができることを学んだ。また、@app.get("/")と@app.get("/hello")を比較し、URLごとに実行される関数が変わる仕組みを理解した。{"detail":"Not Found"}の原因は、Jupyterのセルではなくmain.pyを更新する必要があることだと分かった。まだFastAPIの全体像は完全には理解できていないが、「ブラウザ → URL → FastAPI → 対応する関数 → return → ブラウザ」という基本的な流れは理解できた。

2026/7/28 学習レジュメ

今日はFastAPIで生徒一覧と指定点以上の生徒を返すAPIを作成した。/studentsでは全員のデータを返し、/students/over/{score}ではURLから受け取った点数を基準に、生徒を1人ずつ確認して条件を満たす人だけを返す仕組みを学んだ。また、score: intは点数を整数として受け取る指定であり、result.append(student)は条件に合う生徒の辞書を結果リストへ追加する処理だと理解した。/docsからもAPIを実行し、入力した点数によって返る結果が変わることを確認できた。今日はSQLを使わず、FastAPIのURL・引数・関数・返り値の流れに集中した。

2026/7/30 学習レジュメ

今日はFastAPIで、名前検索と点数条件を組み合わせた検索APIを作成した。?keyword=a&min_score=60&max_score=80のように、複数のクエリパラメータを&で区切って渡す方法を学んだ。また、name_matchとscore_matchには文字や点数そのものではなく、条件を満たすかどうかのTrue / Falseが入ること、andは両方がTrueのときだけ結果へ追加することを理解した。同じ/students/filterを二重に定義すると古い処理が使われる問題も確認し、不要な定義を削除する必要があると分かった。さらに、min_scoreの未入力や文字列入力によるエラーを通して、FastAPIが必須項目や型を自動で確認してくれる利点を学んだ。

2026/7/31 学習レジュメ

今日はFastAPIとSQLiteを接続し、データベース内の生徒情報をSQLで取得してブラウザへ返すAPIを作成した。データベースは、データを整理して保存し、SQLで必要な情報を検索する仕組みであると学んだ。また、古いstudents.dbのテーブル構造が残ったことでエラーが発生し、エラー文を確認してデータベースを削除・再作成することで解決した。現在はコードを見ながら軽く説明できる段階なので、次回以降は新しい内容を増やしすぎず、穴埋め問題とエラー検索の練習で定着を進める。

2026/8/4・8/6 学習レジュメ

FastAPI・SQLite・SQLの役割と処理の流れを復習し、SQLの取得結果を辞書リストへ変換する関数や、指定点以上・以下の生徒を取得する処理を確認した。今回は/students/under/{score}を追加し、指定点以下の生徒を低い順に表示するAPIを完成させた。途中で、appの未定義、テーブル未作成、初期化関数の呼び忘れ、タプル間のカンマ抜けなどのエラーが発生したが、エラー文の最後を確認して一つずつ修正した。最終的に60点以下としてItoとSatoを正しく表示できた。今後も用語やコードの意味を答えるアウトプット問題を繰り返し、見ずに書くことより、処理の役割を理解して直せる力を定着させる。

2026/8/7 学習レジュメ

今日はFastAPI・SQLite・SQLの復習を中心に、AS、JOIN、ON、WHERE、fetchall()、conn、cursor、initialize_database()などの役割をアウトプット形式で確認した。さらに、/students/under/{score}を使って50点以下・70点以下・100点以下の表示を確認し、ASCとDESCを切り替えて並び順の違いも実践した。前回より短い30分で一通り確認できたので、今後も同じ用語や処理を繰り返し問題形式で復習して定着を進める。

2026/8/8 学習レジュメ

今日はFastAPI・SQLite・SQLの復習を20分行い、AS、JOIN、ON、WHERE、ASC、DESC、conn、cursor、fetchall()、initialize_database()、(score,)の意味をアウトプット形式で確認した。特にWHEREは条件で絞り込む、cursorはSQLを実行する操作役、fetchall()は検索結果をすべて取得する処理だと整理した。また、/students/under/70では?に70だけが入り、その条件によって50・60・70点の生徒が取得される流れも確認した。次回もこの3点を中心に反復して定着させる。

2026/8/9 学習レジュメ

今日はFastAPI・SQLite・SQLの基本用語を15分で復習した。WHEREは条件に合うデータを絞り込む、cursorはSQLを実行する操作役、fetchall()はSQLの検索結果をすべて取得する、connはデータベースとの接続、(score,)はPythonのscoreをSQLの?へ渡すための1要素タプルであることを確認した。また、rowsにはタプルのリストが入り、それをconvert_rows_to_students(rows)で辞書のリストへ変換する流れも復習した。エラーについては、NameErrorは名前の未定義やスペルミス、no such tableはテーブルが存在しない、今回のtuple object is not callableはカンマ抜けを疑うことを確認した。次回もfetchall()とconnを重点的に反復して定着させる。

2026/8/13 学習レジュメ

今日はFastAPI・SQLite・SQLの基礎をアウトプット中心で復習した。connはデータベース接続、cursorはSQLの操作役、cursor.execute()はSQL実行、fetchall()は検索結果をすべて取得する処理だと整理した。また、(score,)でPythonの点数をSQLの?へ渡し、取得したタプルのリストをconvert_rows_to_students(rows)で辞書のリストへ変換する流れを確認した。さらに、FastAPI・PostgreSQL・Dockerはそれぞれ別の技術で、FastAPIはAPIを作る、PostgreSQLはデータを保存する、Dockerは実行環境をまとめる役割だと理解した。最後に、FastAPI → Python関数 → DB接続 → SQL実行 → fetchall() → 辞書リスト変換 → ブラウザへ返すという全体の処理順もかなり定着した。

2026/8/14 学習レジュメ

今日はFastAPIのGET APIを復習した後、新しくPOSTとPydanticを学んだ。POST /studentsでJSON形式の生徒データを送信し、StudentCreate(BaseModel)でname: str、score: intという入力データの型を定義した。Pydanticは送られてきたデータの形や型を確認する役割があり、Swagger UIの/docsから{"name":"Kato","score":85}を送信して、200レスポンスで同じ内容が返ることを確認した。今回はまだSQLiteへの保存はしておらず、次回はPOSTで受け取ったデータをSQLのINSERTで保存する流れに進む。

2026/8/15 学習レジュメ

今日はPOSTで受け取ったデータを、SQLiteへ実際に保存する処理を学んだ。INSERTでデータを追加し、cursor.lastrowidで追加した生徒のIDを取得、commit()で変更を確定して保存する流れを確認した。StudentCreateで受け取ったstudent.nameとstudent.scoreをadd_student()へ渡し、studentsとscoresの2つのテーブルへ保存した。最後にGET /students/under/100でKato・85が表示され、POSTした内容が本当にDBへ保存されたことを確認できた。

2026/8/17 学習レジュメ

今日はadd_student(name, score)を1行ずつ分解して理解した。connでSQLiteに接続し、cursorでSQLを操作、最初のINSERTで名前をstudentsテーブルへ追加する流れを確認した。lastrowidでは最後に追加した生徒のIDを取得し、そのIDと点数を(student_id, score)としてscoresテーブルへ保存することを学んだ。また、commit()で変更を確定・保存し、close()でDB接続を閉じ、最後にid・name・scoreを辞書で返す流れを整理した。Kato・85の場合、studentsのID=6とscoresのstudent_id=6がつながることで、名前と点数が同じ生徒のデータとして関連付けられることも理解した。

2026/8/18 学習レジュメ

今日はadd_student()の復習をした後、新しくDELETEによるデータ削除を学んだ。DELETE FROM ... WHERE ...で削除対象を指定し、(student_id,)でPythonのIDをSQLの?へ渡す流れを確認した。Katoのデータはstudentsとscoresの2つのテーブルに分かれているため、両方からID=6を削除し、commit()で変更を確定した。

FastAPIでは@app.delete("/students/{student_id}")を使い、Swagger UIからID=6をDELETEした。最後にGETで確認し、Kato・85が一覧から消えていることを確認できた。これでCRUDのうち、Create＝追加、Read＝取得、Delete＝削除まで実際に動かせるようになった。次はUpdate＝更新に進む予定。

2026/8/25 学習レジュメ

今日はCRUDの復習後、最後に残っていたUpdate（更新）を学習した。UPDATEで既存データを書き換え、SETで新しい値、WHEREで更新対象を指定する流れを確認した。FastAPIではPUTを使い、ID=3のYamadaを70点から95点へ更新し、GETで実際に変更されたことを確認できた。

これでCRUDのCreate＝追加、Read＝取得、Update＝更新、Delete＝削除を一通り実装できた。コードをゼロから書く段階にはまだ達していないが、各処理の意味はかなり追えるようになっている。次回は新しい内容より、CRUDの検索練習・穴埋め・一部分を自力で書く練習を中心に定着させる。

2026/8/26 学習レジュメ

今日はCRUDとSQLite操作の定着練習を行った。データベース接続、SQLの操作役、SQLの実行、変更の確定、最後に追加した行のID取得など、これまで使ってきた基本処理を復習した。

その後、コードの穴埋め問題とPCでの自力記述に取り組んだ。追加処理では、名前や点数をSQLへ渡す流れを確認し、更新処理では「scoresテーブルを更新し、新しい点数を設定し、student_idで対象を指定する」という構造を整理した。95点とID3を使う場合は、ID3の生徒の点数を95点に更新する意味になる。

削除処理では、「studentsテーブルから、指定したIDのデータだけを削除する」という形を練習した。DELETEの後にFROMでテーブル名を書き、WHEREで削除対象を指定する流れを確認した。

現在は、コードを見れば理解できる段階から、SQLの基本構造なら見ずに書き始められる段階へ進んでいる。ただし、データベース接続の書き方や、更新時のSET、削除時のFROMなど細かい部分はまだ抜けるため、次回も穴埋め問題と一部分を自力で書く練習を続ける。

2026/9/1 学習レジュメ

今日はCRUDの定着を目的に、SQLとSQLite操作の検索練習・穴埋め・自力記述を行った。connect＝DB接続、cursor＝SQL操作役、execute＝SQL実行、fetchall()＝検索結果をすべて取得、commit()＝変更の確定、lastrowid＝最後に追加した行のID取得を復習した。
UPDATEでは、UPDATE → SET → WHEREの基本構造を確認し、ID=3の生徒を95点に更新するSQLをほぼ自力で書けた。DELETEでも、DELETE FROM → WHEREという構造を確認し、IDを指定して削除する処理を練習した。
最後にINSERTを復習し、INSERT INTO students (name) VALUES (?)はstudentsテーブルのname列に値を追加する意味で、("Kato",)の,は1要素のタプルを作るためだと整理した。
現在は、SQLの基本構造は見ずにある程度書けるようになってきた一方、execute()の中への書き方、テーブル名、カンマなど細かい部分はまだ抜けるため、次回も穴埋めと部分的な自力記述を続けて定着させる。

2026/9/3 学習レジュメ
今日はCRUDの定着を目的に、SQLの検索練習・穴埋め・自力記述を行った。cursor.execute()には「SQL文」と「?に渡す値」をセットで入れることを確認し、INSERT・UPDATE・DELETEの基本構造を繰り返し練習した。
INSERTでは、studentsテーブルのname列に値を追加し、VALUES (?)と1要素タプルを使ってPython側の値をSQLへ渡す流れを確認した。UPDATEではUPDATE → SET → WHERE、DELETEではDELETE FROM → WHEREの形を自力でかなり書けるようになった。
2セット目では、add_student()の流れを分解し、名前を追加→lastrowidでID取得→IDと点数をscoresへ追加→commit()で保存→returnで辞書をFastAPI側へ返す流れを確認した。現在はSQLの骨格はかなり自力で書けるようになっており、今後はexecute()のカンマやテーブル名など細かい部分を反復して定着させる。

2026/9/14 学習レジュメ
今日はFastAPIのエラー処理とCRUDの復習を行った。新しくHTTPExceptionを使い、UPDATEやDELETEの前にSELECTとfetchone()で指定IDの生徒が存在するか確認し、存在しない場合は404 Student not foundを返す処理を実装した。fetchone()は1件取得し、見つからない場合はNoneになることも確認した。
後半はCRUDを復習し、Create＝INSERT / POST、Read＝SELECT / GET、Update＝UPDATE / PUT、Delete＝DELETE / DELETEという対応を整理した。CRUDの意味やSQLの骨格はかなり残っている一方、HTTPメソッドやfetchone()・fetchall()など細部はまだ混ざるため、今後も穴埋めと自力記述を繰り返して定着させる。

2026/9/15 学習レジュメ
今日はCRUDと404エラー処理を10分で復習した。FastAPIではCreate＝POST、Read＝GET、Update＝PUT、Delete＝DELETEと対応することを確認した。また、fetchone()は検索結果を1行取得し、対象が見つからない場合はNoneになることを復習した。

2026/9/17 学習レジュメ
今日はCRUDとHTTPステータスコードの復習・実践を行った。最初に、Create＝POST / INSERT、Read＝GET / SELECT、Update＝PUT / UPDATE、Delete＝DELETE / DELETEという対応を確認した。また、fetchone()は検索結果を1行取得し、見つからない場合はNoneになること、fetchall()は検索結果をすべて取得すること、commit()はDBへの変更を確定・保存することを復習した。
その後、HTTPステータスコードを学び、200は一般的な成功、201は新規作成成功、404は指定したデータが見つからない、422は入力データの型や内容に問題がある場合に返ることを確認した。POST /students に status_code=201 を追加し、Kato・85点を登録したところ、実際に201が返ることを確認できた。
さらに、score: int に対して "abc" を送信し、FastAPI / PydanticがDB処理に入る前の入力チェック段階で処理を止め、422を返すことをSwagger UIで確認した。現在はCRUDの意味と基本構造はかなり定着しており、今後はHTTPステータスコードとFastAPI側の処理をコードと結びつけて覚えていく段階。

2026/9/18 学習レジュメ
今日はCRUDとHTTPステータスコードを20分で復習した。Create＝INSERT / POST、Read＝SELECT / GET、Update＝UPDATE / PUT、Delete＝DELETE / DELETEの対応を確認した。また、fetchone()は検索結果を1行取得し、見つからない場合はNoneになること、404はデータが見つからない、422は入力データの型や内容に問題がある場合に返ることを復習した。
最初はPOSTとPUTが少し混ざったが、最後にはPOST＝新規追加、PUT＝更新、POST成功＝201、存在しないID＝404、型エラー＝422まで正しく整理できた。

2026/9/19 学習レジュメ
今日はCRUD・HTTPステータスコードを復習し、Create＝INSERT / POST、Read＝SELECT / GET、Update＝UPDATE / PUT、Delete＝DELETE / DELETEの対応を確認した。fetchone()は検索結果を1行取得し、見つからない場合はNone、fetchall()は検索結果をすべて取得することも復習した。
後半はPydanticの値チェックを学び、score: int = Field(ge=0, le=100)で、scoreを整数かつ0以上100以下に制限できることを確認した。ge=0は0以上、le=100は100以下を意味し、85は通るが、-10や150は不正な値として弾ける。Pydanticは型だけでなく、値の範囲もチェックできることを学んだ。

2026/9/20 学習レジュメ
今日はまずCRUD、FastAPI、HTTPステータスコード、Pydanticの復習を行った。SQLはデータベースを操作するための言語で、FastAPIはブラウザやアプリからの要求を受け取り、Pythonの処理結果を返す仕組みであることを確認した。CRUDは、Create＝INSERT / POST、Read＝SELECT / GET、Update＝UPDATE / PUT、Delete＝DELETE / DELETEという対応を復習した。また、fetchone()は検索結果を1行取得し、fetchall()は検索結果をすべて取得すること、commit()はDBへの変更を確定・保存することも確認した。
後半ではPydanticの入力チェックを進めた。Fieldを使って、名前は1文字以上20文字以下、点数は0以上100以下に制限する設定を追加した。name=""を送ると422、score=150を送っても422になることをSwagger UIで実際に確認できた。途中でmin_lengthをmim_lengthと書いていたスペルミスが原因で空文字が通ってしまったが、保存先、クラスの重複、読み込み状態、Schemaの確認まで順番に切り分けて原因を特定できた。
今日の重要点は、Pydanticは型だけでなく値の範囲や文字数もチェックでき、不正なデータをDBに入る前に422で止められるということ。次回はこの入力チェックを軽く復習してから、FastAPIの次の内容へ進めればよい。

2026/9/21 学習レジュメ
今日はPCを使わず、CRUD・FastAPI・Pydantic・エラー処理を復習した。Create＝INSERT / POST、Read＝SELECT / GET、Update＝UPDATE / PUT、Delete＝DELETE / DELETEの対応を確認し、fetchone()は検索結果を1行取得、fetchall()は全件取得、commit()はDBへの変更を確定・保存する処理だと整理した。
また、201＝新規作成成功、404＝データが見つからない、422＝入力データの型や内容がルールに合っていないことを復習した。Pydanticでは名前を1〜20文字、点数を0〜100の整数に制限できることも確認した。
最後に処理の流れを確認し、正常なPOSTは「FastAPI → Pydantic → INSERT → commit → return → 201」、不正な入力はPydanticで止まり422、存在しないIDの更新は「SELECT → fetchone() → None確認 → 404」で終了することを整理し

9/22
今日はPythonの辞書から値を取り出す方法と、SQLの条件抽出を復習した。product["price"] で価格を取り出して比較すること、< は未満、<= は以下を表すことを確認した。SQLでは、SELECT で取得する列、FROM でテーブル、WHERE で条件を指定する。次回は、この形を見ずに書けるように復習する。

2026/9/23 学習レジュメ
今日は前半でFastAPIのResponse Modelを学び、StudentCreateは入力用、StudentResponseは出力用であることを整理した。response_model=StudentResponseをPOSTに追加し、実際にid・name・scoreの形で201レスポンスが返ることをSwagger UIで確認した。また、Response Modelにない余計な項目は除外され、必須項目が不足すると出力チェックでエラーになることも学んだ。
後半はPCを使ってCRUDの自力記述を復習した。sqlite3.connect()、conn.cursor()から始め、INSERT、conn.commit()、conn.close()、UPDATE、DELETE、SELECTまで見ずに書く練習を行った。特にUPDATE scores SET score = ? WHERE student_id = ?やDELETE FROM scores WHERE student_id = ?はかなり自力で書けるようになった。一方で、fetchone()とfetchall()、conn.commit()・conn.close()など細部はまだ混ざるため、次回も短く復習する。

2026/9/24 学習レジュメ
今日はSQLite操作の基本と、FastAPI・Pydantic・Response Modelの流れを復習した。connect()はDB接続、cursor()はSQL操作役、execute()はSQL実行、commit()は変更の確定・保存、fetchone()は検索結果を1行取得、fetchall()は全件取得する処理だと整理した。
後半では、StudentCreateは入力用、StudentResponseは出力用であることを確認した。response_model=StudentResponseはAPIから返すデータの形を決め、必要な項目が不足するとエラー、余計な項目は除外されることを学んだ。また、新しい生徒を追加する流れとして、POST受信 → Pydanticで入力チェック → INSERT → lastrowidでID取得 → commit() → StudentResponseで出力確認 → 201で返す、という全体像をコードと結びつけて確認した。
Pydanticは、FastAPIで扱うデータの型・形・条件を決めてチェックする役割があり、入力だけでなく出力の確認にも使えることを整理した。

2026/09/25 
今日はPythonとSQLで、80点以上の人の抽出と人数の集計を復習した。Pythonでは条件に合うたびに count = count + 1 で人数を増やし、SQLでは COUNT(*) で数える。次回はPythonのカウント処理を復習する。

2026/9/25 学習レジュメ
今日はCRUD、Pydantic、Response Modelの復習から始め、StudentCreateは入力用、StudentResponseは出力用、response_modelは返すデータの形を決めるものだと整理した。fetchone()は1行、fetchall()は全件取得、commit()はDBへの変更を確定、lastrowidは最後に追加した行のIDを取得することも確認した。
その後、AS、JOIN、row / rows、list[StudentResponse]を復習した。ASは別名を付ける、JOINは別テーブルを関連するIDで結合する、rowは1行、rowsは複数行全体という違いを確認した。また、SELECT s.id, s.name, sc.scoreで取得した結果をrow[0] / row[1] / row[2]として辞書化し、list[StudentResponse]で複数人分の出力を管理する流れを実際に動かした。
後半はSQLの条件検索を練習し、>=、<=、ASC、DESC、BETWEENを使って、70点以上、75〜90点などの範囲検索を書いた。最後に/students/range/{min_score}/{max_score}という新しいGET APIを作成し、URLから2つの値を受け取り、SQLのBETWEENで範囲検索して複数人を返す処理まで完成させた。
途中で500エラーが出たが、関数名の違いやsc.scoreのスペルミスを確認して修正し、最終的にGET /students/range/75/90で200レスポンスが返るところまで確認できた。SQL部分はかなり自力で書けるようになってきた一方、FastAPIのルート定義や関数の配置はまだ見ながらの方が安定するため、次回もそこを重点的に復習する。

2026/9/27 学習レジュメ
今日は昨日作った点数範囲検索APIを中心に、FastAPIのルート定義とDB関数のつながりを復習した。ASは別名を付ける、JOINはテーブル同士を結合する、fetchone()は1行取得、fetchall()は検索結果全体を取得することを確認した。また、StudentCreateは入力用、StudentResponseは出力用、list[StudentResponse]は複数人分の出力に使うことも整理した。
PC実践では、get_students_by_score_range(min_score, max_score)をほぼ自力で再構築し、SELECT、JOIN、BETWEEN、ORDER BY DESC、fetchall()、conn.close()まで書けた。一方、最後のreturn convert_rows_to_students(rows)はまだ見ないと出にくかったため、今後の復習ポイントになった。
FastAPI側では、/students/range/{min_score}/{max_score}、response_model=list[StudentResponse]、min_score: int、max_score: int、return get_students_by_score_range(min_score, max_score)という流れを分解して練習した。最初は見ないと難しかったが、穴埋め形式にすると正しく書けるようになった。
最後に応用として、指定点以上の生徒を取得するget_students_over_score(score)を書いた。WHERE sc.score >= ?やORDER BY sc.score DESCは見ずに書けたが、JOIN scores AS sc、(score,)、convert_rows_to_students(rows)など関数名・変数名のつなぎ部分ではミスがあった。現状は、SQL本体はかなり自力で書ける一方、FastAPIのルート定義と関数同士の接続部分はまだ反復が必要という段階。次回はそこを重点的に復習する。

2026/9/28 学習レジュメ
今日は短時間で、FastAPIのルート定義とDB検索関数のつながりを重点的に復習した。StudentCreateは入力用、StudentResponseは出力用、list[StudentResponse]は複数人分の出力に使うことを確認した。また、fetchone()は検索結果を1行取得、fetchall()は検索結果全体を取得する処理だと整理した。
後半では、/students/over/{score} の流れを確認した。FastAPI側のread_students_over_score(score)でURLから点数を受け取り、DB検索用のget_students_over_score(score)へ渡す。その後、SQLで指定点以上を検索し、fetchall()で複数行を取得、convert_rows_to_students(rows)で辞書のリストに変換し、list[StudentResponse]として返す流れを復習した。
今回の課題は、FastAPI側の関数read_students_over_score()と、DB検索側のget_students_over_score()が混ざりやすい点だった。今後は「FastAPI側は受付、DB関数側は検索」という役割分担を意識して反復する。

2026/9/29 学習レジュメ
今日は、FastAPI側の関数とDB検索側の関数の役割を重点的に復習した。read_students_over_score(score)はFastAPI側でURLから値を受け取る受付役、get_students_over_score(score)は実際にDB検索を行う関数だと整理した。
また、fetchone()は検索結果を1行取得、fetchall()は複数行をすべて取得し、convert_rows_to_students(rows)でタプルのリストを辞書のリストに変換する流れを確認した。
FastAPI側では、1人分を返す場合はStudentResponse、複数人を返す場合はlist[StudentResponse]を使うことを復習した。今回はほとんど正しく答えられており、特にread_...とget_...の役割分担、fetchall()から辞書リストへ変換する流れがかなり定着してきた。

2026/9/30 学習レジュメ
今日は、FastAPI側のread_students_over_score()とDB検索側　get_students_over_score()の役割を復習した。fetchone()は1行、fetchall()は複数行を取得し、convert_rows_to_students(rows)でタプルのリストを辞書のリストに変換する流れも確認した。
また、複数人を返すときはlist[StudentResponse]を使い、処理の流れは FastAPIでscore受取 → DB関数呼出 → SQL検索 → fetchall → 辞書リスト変換 → 出力確認 → ブラウザへ返す と整理した。

2026/10/1 学習レジュメ
今日は、これまで作ったFastAPIとSQLiteの流れを復習しつつ、/students/over/{score}という新しいGET APIを追加した。read_students_over_score()はFastAPI側、get_students_over_score()はDB検索側という役割分担を確認した。
SQLでは、WHERE sc.score >= ?で指定点以上を抽出し、ORDER BY sc.score DESCで高い順に並べる処理を書いた。fetchall()で複数行を取得し、convert_rows_to_students(rows)でタプルのリストを辞書のリストに変換し、list[StudentResponse]として返す流れも確認した。
途中ではJOIN scores AS sc、(score,)、s.idなど細かい部分にミスはあったが、SQLの骨組みやfetchall()、conn.close()、変換処理はかなり自力で書けるようになってきた。最後はSwaggerで/students/over/80を実行し、80点以上の生徒が高い順に返ることを確認して、200レスポンスまで成功した。

2026/10/2 学習レジュメ
今日は、指定点以下の生徒を取得するGET APIを復習した。DB側ではWHERE sc.score <= ?で指定点以下を抽出し、ORDER BY sc.score ASCで低い順に並べ、fetchall()で複数行を取得してconvert_rows_to_students(rows)で辞書のリストに変換する流れを確認した。
FastAPI側では、read_students_under_score()からget_students_under_score()を呼び出す流れを練習した。今回は、JOIN scores AS scと書くところをstudentsとしてしまった点、複数人を返すためresponse_model=list[StudentResponse]が必要な点が復習ポイントになった。
全体として、SQLの<=・ASC・fetchall()・変換処理はかなり定着してきており、今後はテーブル名、関数名、response_modelなど細かい接続部分の正確さを重点的に固める。

2026/10/3 学習レジュメ
今日は、under / over / range の3種類の検索APIを通して、FastAPI側とDB検索側のつながりを重点的に復習した。read_... はFastAPI側の受付、get_... はDB検索側という役割を確認し、fetchall()で複数行を取得し、convert_rows_to_students(rows)でタプルのリストを辞書のリストに変換する流れも整理した。
PC実践では、get_students_under_score(score)をかなり自力で書けた。JOIN scores AS sc、WHERE sc.score <= ?、ORDER BY sc.score ASC、fetchall()、conn.close()、convert_rows_to_students(rows)まで正しくつなげられた。一方で、cursor.execute()を閉じる)、response_modelの表記、StudentResponseのクラス名など、細かい記述ミスが残った。
全体として、SQLの骨組みとDB処理はかなり定着してきており、今後は 関数名・クラス名・引数名・括弧など細部の正確さ を重点的に固める段階に入っている。

2026/10/4 学習レジュメ
今日は、PythonとSQLで「500円以下の商品を取り出す・数える」練習をした。Pythonではproduct["price"]で価格を取り出し、ifで条件を判定する。ifの末尾の:と字下げに注意する。
SQLでは、productsがテーブル名、priceが列名。COUNT(*)で件数を数え、WHERE price <= 500で条件を指定する。価格の条件にscoreを使わないことと、<=は境界の値も含むことを確認した。

2026/10/5 
今日は、PythonとSQLで400円以下の商品を扱う練習をした。Pythonではproduct["price"]で価格を取り出し、<= 400で条件を判定する。価格で判定し、product["name"]で名前を表示するように、使う値を区別する。辞書の取り出しは[]、表示はprint()を使う。

SQLでは、SELECT COUNT(*) FROM products WHERE price <= 400;で条件に合う商品数を数える文を、自分で正しく書けた。

2026/10/6 学習レジュメ

今日は、FastAPI側とDB検索側の役割分担を中心に復習した。read_students_under_score()はFastAPI側、get_students_under_score()はDB検索側で、FastAPIがURLから値を受け取り、DB関数へ渡し、SQL検索結果を返す流れを確認した。fetchone()は1行、fetchall()は複数行を取得し、convert_rows_to_students(rows)でタプルのリストを辞書のリストへ変換することも復習した。

SQLでは、ASで別名を付け、JOINでstudentsとscoresを結合し、ON s.id = sc.student_idで対応する生徒と点数をつなげる処理を確認した。また、WHEREで点数条件を指定し、ORDER BY ... DESCで高い順に並べる流れも練習した。

後半は別の「学生検索API」のチャットで続けて学習し、名前と点数をJOINして条件検索するSQLや、FastAPIから検索結果を返す流れを復習した。全体としてSQLの意味はかなり理解できている一方、FastAPI側の関数名・response_model・型指定・コードの細かい接続部分はまだ反復が必要な段階。

2026/10/7 学習レジュメ

今日はGET系APIの復習から始め、under / over / range の検索処理をかなり自力で書けることを確認した。JOIN scores AS sc、WHERE、ASC / DESC、fetchall()、list[StudentResponse]、score: intなど、以前ミスしやすかった部分もかなり安定してきた。

後半はPOSTに進み、StudentCreateは入力用、StudentResponseは出力用と整理した。INSERT INTO studentsで名前を追加し、cursor.lastrowidで新しく作った生徒IDを取得、そのIDと点数をscoresへINSERTし、commit()で確定する流れを学んだ。

FastAPI側では、create_student()が入力を受け取る受付役、add_student()がDBへ追加する処理を担当することを確認した。また、status_code=201は「新規作成に成功したら201 Createdを返す」という意味だと理解した。次回はPOSTのadd_student()とcreate_student()を自力で書けるように反復する。

2026/10/8 学習レジュメ

今日はFastAPIのPOST処理を重点的に復習した。StudentCreateは入力用、StudentResponseは出力用であり、create_student()がFastAPI側、add_student()がDB側の関数であることを確認した。

PC実践では、INSERT INTO studentsで名前を追加し、cursor.lastrowidで新しいIDを取得、INSERT INTO scoresで点数を登録し、commit()で保存する流れを練習した。処理の順番は理解できているが、(name,)、(student_id, score)、cursor.lastrowid、関数名や括弧などの記述にはまだ課題が残った。

また、Swaggerから入力するのはnameとscoreであり、idはDB側で自動生成されることを理解した。student.nameとstudent.scoreは、受け取った生徒データから名前と点数を取り出してDB関数に渡すために使う。

次回はPOSTのコードを穴埋めと自力記述で反復し、Swaggerで201 Createdを確認することを目標にする。

2026/10/9 学習レジュメ（45分×2セット・計90分）

今日はFastAPIのPOST（追加）の復習と、PUT（更新）の新規学習を行った。

1セット目：POSTの復習と実践

StudentCreateが入力用、StudentResponseが出力用であることを確認した。DB側のadd_student()をほぼ自力で記述でき、INSERT、cursor.lastrowid、commit()の使い方を復習した。特に、IDは自分で入力するのではなく、DBが自動生成することを再確認した。

SwaggerではPOSTの201 Createdを確認し、追加した生徒をGETで取得することにも成功した。POSTからDB保存、GETによる取得までの一連の流れを理解できた。

2セット目：PUTの学習と実践

新しくPUTを学習し、SQLのUPDATE、SET、WHEREの役割を理解した。DB側のupdate_student_score()をほぼ自力で記述でき、FastAPI側のPUTとの接続も練習した。

既存のmain.pyには、生徒IDの存在確認と、存在しない場合に404エラーを返す処理が実装されていることも学んだ。SwaggerでID14のSatoの点数を85点から95点に更新し、GETで変更が保存されていることを確認できた。

また、パスパラメータとクエリパラメータの違いを重点的に学習した。パスは主に対象の指定、クエリは検索条件などの指定に使われること、intやstrは受け取るデータの型を指定することを理解した。

現在の課題と次回の予定

GETは比較的安定し、POSTも実装・動作確認までできるようになった。一方、PUTはまだコードを完全に覚えきれていないため、次回も45分間、PCでの自力記述を中心に復習する。

その後、DELETE（削除）を学習し、最後にCRUD全体を使った軽い総合アウトプット演習を行う。

現在の進捗：CRUDの4機能のうち、GET・POST・PUTの3機能を学習済み。残りはDELETE。

プログラミング学習レジュメ

2026年10月10日（土）

① 今日の学習内容

Python・SQLiteを使い、CRUD（作成・取得・更新・削除）の基本構文を復習した。

* SELECT：条件を指定したデータ取得。fetchone()も復習。
* INSERT：最初は構文を間違えたが、2回目は正しく記述できた。
* UPDATE：SQL構文は覚えていたが、プレースホルダーに渡す値の順番を間違えた。再挑戦では正解。
* DELETE：基本構造は覚えていたが、DELETEの後に不要な列名を書いてしまった。
* commit()・close()：保存処理と接続終了を確認した。

② 現在の課題

* SQLの構文は理解しているが、まだ完全には定着していない。
* ? に渡す引数の順番に注意が必要。
* Python関数とデータベース処理の連携は復習が必要。
* FastAPIのGET・POST・PUT・DELETEについては、自力で書けるか不安があるため、次回確認する。

③ 次回の学習予定

1. SQLの軽い復習テスト。
2. delete_student(student_id) 関数を自力で完成させる。
3. Python関数からDB操作を実行する練習。
4. FastAPIの基本構文を確認し、DB関数との連携を段階的に復習する。

④ 今日の振り返り

以前学んだ内容を忘れている部分があったが、繰り返すことで正しく書けるようになった。

今後は新しい知識を急いで増やすのではなく、何も見ずにコードを書ける状態を目指す。

特にPython関数とFastAPIを重点的に復習し、CRUD全体を自力で実装できるようにする。

10/11 学習レジュメ

今日はFastAPIのPUT（更新）をPCで復習した。update_student_score()を自力で記述し、SQLのUPDATE・SET・WHERE、変数名、引数の順番などの間違いを修正した。

また、FastAPI側の@app.put()も練習し、student_idは更新対象のID、new_scoreは変更後の点数であることを再確認した。

今後の課題は、SQLの書式とFastAPIの関数を見ずに正確に書けるようにすること。次回もPUTを復習し、定着したらDELETEへ進む。

10/12 学習レジュメ

今日はFastAPIのPUT（更新）を重点的に復習し、DB接続、SQLのUPDATE、存在確認、404エラー処理までPCで自力記述した。細かな構文ミスはあったものの、修正を重ねてコードを完成させた。

Swaggerでは存在しないIDを指定し、404 Not Foundが正しく返ることを確認できた。

後半はDELETE（削除）の基礎を学習した。DELETE FROMとWHEREの役割、2つのテーブルからデータを削除する必要性、commit()による保存を理解した。

次回はDELETEのPC実践を行い、その後CRUD全体の総合アウトプットに進む。

10/13 学習レジュメ

今日はCRUD最後のDELETE（削除）を中心に学習した。PCでdelete_student()を自力記述し、SELECTによる存在確認、fetchone()、404エラー処理、2つのテーブルからのDELETE、commit()まで一連の流れを練習した。

途中で変数名や括弧、returnの記述にミスがあったが、修正を重ねて基本的なコードを組み立てられた。また、DELETEはデータを削除する処理、returnは結果を返す処理であることを確認した。

次回の課題は、SwaggerでDELETEの動作確認を行うこと。その後、GET・POST・PUT・DELETEを組み合わせた軽いCRUD総合アウトプットに進む。

10/14 学習レジュメ

今日はFastAPIのDELETE（削除）の動作確認と、CRUD全体の復習を行った。

Swaggerでテスト用の生徒をPOSTで追加し、DELETEで削除した後、GETで削除結果を確認できた。これにより、CRUDの4機能すべてを一通り実践できた。

後半はCRUDの総合アウトプットを行い、POST・GET・PUT・DELETEとSQL命令の対応を全問正解した。一方、FastAPI側とDB側の関数名、URLのパスパラメータの書き方にはまだ課題が残った。

次回はPCでCRUD全体の軽い総合実装演習を行い、コードを自力で書く力を定着させる。

10/15 学習レジュメ

今日はCRUDの総合アウトプットとして、GET（取得）とPOST（追加）をPCで自力記述した。

GETでは、SQLのSELECT・JOIN・WHERE・ORDER BY、fetchall()、FastAPIのresponse_modelまでほぼ自力で書くことができ、理解が定着してきた。

POSTでは、処理の流れは覚えていたものの、INSERT INTOのSQL構文や変数名にミスがあった。修正を重ねてコードを完成させ、lastrowidによるID取得、2つのテーブルへの追加、StudentCreateとStudentResponseの役割を復習した。

今後の課題は、POSTのSQL構文を見ずに書けるようにすること。次回はPUT・DELETEの総合アウトプットにも取り組み、CRUD全体の定着を目指す。

10/16 学習レジュメ

今日はCRUD総合アウトプットの後半として、PUT（更新）とDELETE（削除）を復習した。

PUTでは、DB接続、SELECTによる存在確認、fetchone()、404エラー処理、UPDATE、FastAPIとの接続までPCで自力記述した。SQL構文や変数名にミスがあったが、修正を重ねて基本コードを完成させた。

DELETEでは、2つのテーブルから削除するSQLとFastAPIの関数呼び出しを復習した。

現在の課題は、SQLの列名とPythonの変数名を正確に使い分けること。次回はCRUD全体の短い復習テストを行い、苦手部分を定着させた後、Git・GitHubの学習に進む予定。

Python・SQL・FastAPI 学習レジュメ（2026/10/17）

本日は45分×3セット、合計135分の学習を実施した。

第1セット：POSTの復習

CRUDの確認テストで10問中9問正解。POSTのDB関数を自力で記述し、INSERT、lastrowid、commit、closeの処理を確認した。また、StudentCreateによる入力データの受け取り方、リクエストボディ、FastAPI側とDB側の関数の役割を復習した。

第2セット：PUTの復習・実践

UPDATEのSQL構文を自力で修正し、update_student_score()を記述した。cursorの作成、fetchone()による存在確認、404エラー処理で間違いがあったが、ヒントをもとに修正できた。また、データベースの接続先やimportに関するエラーも解決し、更新関数の実行に成功した。

第3セット：PUTの動作確認・DELETEの復習

SwaggerからPUTを実行し、HTTP 200を確認。SQLiteでも更新後の85点が保存されていることを確認できた。

DELETEでは、scoresテーブルとstudentsテーブルの削除順序、WHEREの条件、Pythonの変数名とSQLの列名の違いを復習した。commit・close、存在確認、404エラー処理まで記述できたが、DELETEの実行確認は未実施。

本日の評価・課題

CRUDの基本的な処理の流れは理解が進んでいる。特にPUTは、FastAPIからSQLiteへの更新と保存確認まで成功した。一方、関数全体の自力記述、変数の扱い、処理順序にはまだ不安定な部分がある。

次回の予定

DELETEのSwagger動作確認とSQLiteでの削除結果確認を行い、その後CRUD全体の小規模な総合演習に進む。

Python・SQL・FastAPI 学習レジュメ（2026/10/18

第1セット：DELETEの動作確認・検索練習

SQL・CRUDの検索練習を行い、SELECT、WHERE、fetchone、fetchall、lastrowidの役割を復習した。

その後、Swaggerでテスト用学生をPOSTで登録し、DELETEで削除した。SQLiteのstudents・scores両テーブルからデータが削除されていることを確認し、存在しない学生IDへのDELETEでHTTP 404が返ることも確認できた。

一方、DBファイル名、SQLの列名、import、インデントで間違いが発生したため、引き続き復習が必要。

第2セット：GET・POST・PUTの総合復習

GETでは、JOINの結合条件やfetchallを自力で修正した。closeとreturnの順番、インデントを修正し、80点以上の学生を取得する関数の実行に成功した。

POSTでは、lastrowidによる新規学生IDの取得と、INSERT時の値の順番をヒントなしで修正できた。

PUTでは、FastAPI側の引数名とDB関数に渡す値の順番を自力で修正した。

また、POSTで登録した学生のIDを利用し、PUTで点数を更新してGETで結果を確認する連携方法を新しく学んだ。

本日の評価と課題

CRUDの基本的なSQL構文やバグ修正能力は改善している。特にPOST・PUTのバグ修正は自力で成功した。

一方、Pythonのインデント、DB接続、変数の扱い、処理順序にはまだ不安定な部分がある。

今後は、既習内容の検索練習とコードの自力記述を継続し、ヒントなしで再現できる力を強化する。

次回の学習予定

1. CRUD全体の検索練習・弱点復習
2. POST・GET・PUT・DELETEを組み合わせた小規模な実践課題
3. 自力記述の定着度確認

今後の見通し： あと2〜3セット（90〜135分程度）を目安にCRUDの基礎を一区切りとし、Git・GitHubの学習へ進む。Git学習開始後も、SQL・CRUDの検索練習は継続する。

Python・SQL・FastAPI 学習レジュメ（2026/10/19）

① 第1セット：CRUDの総合復習・API連携

UPDATE・DELETEのSQLをヒントなしで正しく記述できた。

FastAPIのPOST関数も自力で記述し、URLの複数形とresponse_modelの大文字・小文字の間違いを修正した。

さらに、Swaggerを使って初めてPOST → PUT → GET → DELETEを連続して実行した。

* POST：学生ID15を70点で登録（HTTP 201）
* PUT：70点から95点に更新（HTTP 200）
* GET：95点に更新されたことを確認（HTTP 200）
* DELETE：学生ID15を削除（HTTP 200）

最後に、PUTのDB関数をほぼ自力で記述できた。SQLに渡す変数の順番のみヒント後に修正した。

② 第2セット：DB関数の自力実装・最終診断

POST（新規登録）

studentsとscoresへのINSERT、cursor.lastrowidによるID取得、commit()、close()、辞書による返却を記述した。

SQLと値の順番は正確で、処理の流れも再現できた。ただし、関数全体の実行確認は行っていない。

GET（検索）

学生IDで検索するDB関数を作成した。

SELECT、JOIN、WHERE、fetchone()を自力で記述できた。引数に固定値を使用したこと、検索結果の保存先、return、括弧の不足については修正が必要だった。

修正後、get_student_by_id(1)を実行し、(1, 'Tanaka', 90)の取得に成功した。

DELETE（削除）

学生の存在確認、fetchone()、404エラー処理、2テーブルからの削除、commit()、close()、辞書の返却まで実装した。

最初はSQLの列名idとPython変数student_idを混同したが、ヒント後に修正できた。

404処理と2つのDELETE文は自力で正確に記述できた。最後に、返却する辞書のキー名はAPIの仕様によって決まり、Pythonの固定ルールではないことも理解した。

DELETE関数全体の実行確認は行っていない。

③ 本日の具体的な評価

改善が確認できた点

* SQLのUPDATE・DELETEをヒントなしで記述できた。
* DB接続、カーソル作成、commit、close、インデントの正確性が改善した。
* POSTのlastrowidと2テーブルへのINSERTを再現できた。
* GETでJOINを使用した検索関数を作成し、実行に成功した。
* DELETEの404エラー処理と削除処理を自力で記述できた。
* Swaggerを通してCRUDの4操作を連携させることができた。

まだ定着していない点

* SQLの列名とPythonの変数名を混同することがある。
* fetchone()で取得した結果と、関数の引数・戻り値の区別が不安定。
* UPDATEでSQLの?に渡す値の順番を間違えることがある。
* 括弧、キー名、引数などの細かな記述ミスが残っている。
* CRUD全関数を完全にヒントなしで実装できるかは未確認。

総合評価

CRUDの基本的なSQL構文と処理の仕組みは理解できており、実際のAPI操作にも成功している。

以前と比較すると、DB関数を部分的に自力記述する能力が改善した。特にDELETEの存在確認・404処理・2テーブル削除は、比較的安定して書けるようになっている。

一方、GETの引数と戻り値、Pythonの変数の扱いは繰り返し練習が必要である。

現段階は、CRUDの基本的な実装経験を積み終え、自力記述の定着を進める段階と評価する。

④ 学習内容の整理・SOARの活用

CRUDの4操作について、意味・SQL構文・DB関数・FastAPIとの対応を表や図に整理した。

また、SOAR学習法の考え方を取り入れ、情報を選択・体系化・関連付けし、その後に検索練習で理解を確認する学習方針を検討した。

今後は、作成したCRUD早見表を復習資料として活用し、表を見ずにコードを思い出して書く練習を継続する。

⑤ 次回の学習予定

次回からGit・GitHubの基礎学習に進む。

まずはGitとGitHubの違い、変更履歴の管理、repository、commitなどの基本概念を学ぶ。

実際に使用しているmain.pyを題材に、Gitでコードを管理する方法を練習する。

同時に、毎回5〜10分程度のPython・SQL・CRUD検索練習を継続し、今回見つかった弱点を補強する。

今後の重点目標： Git・GitHubを習得しながら、CRUDを資料なしでも安定して記述・修正できる状態を目指す。

プログラミング学習レジュメ｜2026年10月20日
Gitの初回学習

① 本日の学習目標

これまで学習してきたPython・SQL・FastAPIのCRUD実装を踏まえ、新しくGit・GitHubの学習を開始した。

本日の目標は、Gitの基本的な仕組みを理解し、実際にPythonファイルの変更履歴を保存できるようになること。

② 本日の学習内容

1. GitとGitHubの基本概念

Gitはプログラムの変更履歴を管理するツールであり、GitHubはGitで管理したコードをオンラインで保存・共有し、共同開発に活用できるサービスであると学んだ。

特に、GitはPC内だけでも使用でき、GitHubにアップロードしなくても履歴を管理できることを理解した。

2. Gitのインストール・初期設定

Windows PowerShellを使用してGitの動作確認を行った。

最初はGitが認識されなかったため、Git for Windowsをインストールした。

git --versionを実行し、バージョン2.56.0が表示されることを確認した。

その後、GitHubのメールアドレス非公開設定を確認し、Gitのユーザー名と非公開用メールアドレスを設定した。

途中、コマンドのスペースや引用符の入力ミスによってエラーが発生したが、修正後は正常に設定できた。

3. Gitリポジトリの作成

PowerShellで次のコマンドを実行した。

* mkdir git-practice：練習用フォルダを作成
* cd git-practice：作成したフォルダに移動
* git init：Gitリポジトリを初期化
* git status：リポジトリの状態を確認

git initによって、通常のフォルダをGitで管理できるようにした。

4. Pythonファイルの作成とステージング

notepad hello.pyを実行してPythonファイルを作成した。

ファイルには以下のコードを記述した。

print("Hello Git")

その後、git statusでhello.pyがUntracked（未追跡）として表示されることを確認した。

続いて、git add hello.pyを実行し、ファイルをステージングした。

再度git statusを実行すると、Changes to be committedと表示され、commitの準備ができたことを確認した。

5. 初めてのcommitと履歴確認

次のコマンドを実行した。

git commit -m "Add hello.py"

最初はユーザー情報が未設定だったためエラーになったが、設定後に再実行して成功した。

初回commitの短縮IDは11e0b5a。

さらに、

git log --oneline

を実行し、保存した変更履歴が表示されることを確認した。

これにより、ファイル作成 → git add → git commit → git logという基本操作を一通り経験した。

③ 本日の具体的な評価

評価項目	評価
GitとGitHubの役割の理解	○ 基本概念を学習
Gitの環境構築	◎ 完了
フォルダ作成・移動	◎ 成功
git init	◎ 成功
git status	◎ 成功
git add	◎ 成功
git commit	◎ 成功
git log	◎ 成功
コマンドの自力再現	未確認
変更履歴の仕組みの理解	△ 定着途中

良かった点

Gitのインストールから最初のcommitまで、一連の作業を完了できた。

途中でエラーが発生しても、原因を確認して修正し、作業を継続できた。

また、GitHubの非公開メールアドレスを設定し、今後の開発に使用できる環境を整えた。

今後の課題

1. コマンドの意味の定着

git addとgit commitの違いについて、「変更と変更した記録」と説明できたものの、正確な役割の区別はまだ曖昧である。

git addは記録する変更の準備、git commitは変更履歴の記録と理解する必要がある。

2. コマンドの自力記述

本日は提示されたコマンドを実行する形式だったため、何も見ずに自力で記述できるかは未確認。

今後は検索練習を取り入れ、コマンドを思い出して入力する機会を設ける。

3. ファイルの変更管理

今回は新規ファイルの登録と初回commitまで学習した。

ファイルを修正した際にGitが変更をどう認識するか、複数のcommitがどのように管理されるかは未学習。

④ 総合評価

本日の到達段階：Gitの初期設定・基本操作の導入完了

Gitの環境構築と最初のcommitに成功し、変更履歴を保存する一連の流れを体験できた。

一方、現時点では説明を見ながら操作している段階であり、Gitの基本コマンドが定着したとはまだ判断できない。

今後は、実際にファイルを変更し、差分確認・再commit・履歴の確認を繰り返すことで、Gitを自力で扱える状態を目指す。

⑤ 次回の学習予定

次回は、今回作成したgit-practiceフォルダとhello.pyを使用して学習を継続する。

優先する学習内容

1. hello.pyを編集し、変更をGitで検出する。
2. git diffで変更前後の違いを確認する。
3. git addとgit commitで2回目の変更履歴を保存する。
4. git log --onelineで複数の履歴を確認する。
5. Gitの基本コマンドをヒントなしで回答する検索練習を行う。

その後、GitHubへのリポジトリ公開・pushなどの学習に進む。

また、Python・SQL・FastAPIのCRUDについても、忘却を防ぐために毎回5〜10分程度の自力記述・検索練習を継続する。

⑥ 今後の目標

短期目標は、Gitの基本操作を定着させ、Python・FastAPIの成果物をGitHubで管理できるようになること。

中期的には、GitHubに学習成果や制作したアプリケーションを蓄積し、将来のバックエンドエンジニアのインターン応募やAI・ロボティクス分野への就職活動に活用できるポートフォリオを構築する。

次回の重点：Gitの変更管理を実践しながら、自力で操作できる力を身につける。

プログラミング学習レジュメ｜2026年10月21日

学習テーマ：Gitの変更管理・2回目のcommit・検索練習

① 本日の学習目標

前日に学習したGitの基本操作を復習し、Pythonファイルの変更から履歴の保存までを実践する。

特に、git status・git diff・git add・git commit・git logの役割を理解し、コマンドを自力で記述できるようになることを目標とした。

② 本日の学習内容

1. Gitの検索練習

前日に学習した基本コマンドについて、資料を見ずに回答した。

3問中2問正解。

git commitとgit statusは正しく回答できたが、git addを変更履歴の保存と勘違いしていた。

復習によって、git addは記録する変更の準備、git commitは変更履歴の記録であることを再確認した。

2. Pythonファイルの変更

前日に作成したgit-practiceフォルダへ移動し、hello.pyを編集した。

print("Hello Git")
print("Gitの変更練習")

git statusを実行し、modified: hello.pyと表示されることを確認した。

これにより、Gitが既存ファイルの変更を検出する仕組みを実践的に学んだ。

3. git diffによる変更内容の確認

git diff hello.pyを実行し、変更前と変更後のコードを比較した。

赤色の-は削除された行、緑色の+は追加された行を意味することを学習した。

途中でPythonコードに余計な文字が混入していたため、メモ帳で修正し、再度差分を確認した。

また、ファイル末尾の改行の有無によっても差分が表示されることを知った。

4. 2回目のgit add・git commit

変更したPythonファイルのステージングと履歴保存を実践した。

最初はgit addのみを入力し、対象ファイルの指定が不足していた。

その後、git add hello.pyを実行してステージングに成功した。

続いて、git commitを入力したところ、Vimというテキストエディタが起動した。

エディタを終了してから、以下のコマンドを実行した。

git commit -m "Update hello.py"

結果、2回目のcommitに成功した。

commit ID：****f938510

5. git logによる履歴確認

過去の履歴を確認する問題では、最初にgit statusを入力してしまった。

復習後、git log --onelineを実行し、以下の2件が記録されていることを確認した。

f938510 Update hello.py
11e0b5a Add hello.py

これにより、Gitが変更履歴を積み重ねて管理する仕組みを確認できた。

6. 最終検索練習・理解度確認

最後に、6つの基本コマンドの意味を自分の言葉で説明した。

結果：6問中5問正解

git status・git diff・git add・git commit・git logの役割は正しく説明できた。

一方、git initをファイル変更のコマンドと誤認していたため、リポジトリを初期化するコマンドであることを復習した。

操作順序についても、git diffが抜けていたため、変更確認から履歴保存までの流れを再整理した。

③ 本日の具体的な評価

評価項目	評価
Git基本コマンドの理解	○ 6問中5問正解
git status	◎ 実行成功
git diff	◎ 実行成功
git add	△ 対象ファイルの指定にヒント
git commit	○ エラー修正後に成功
git log	△ 最初はstatusと混同
Pythonファイルの編集	◎
2回目のcommit	◎
コマンドの自力再現	△ 定着途中

改善が確認できた点

前日は新規ファイルの登録と初回commitが中心だったが、今回は既存ファイルを変更し、その差分を確認して再commitするところまで実践できた。

また、最終検索練習では6つの基本コマンドのうち5つの役割を正しく説明できた。

特に、学習開始時に間違えていたgit addとgit commitの違いを、終了時には正確に説明できるようになった点は明確な改善である。

今後の課題

1. コマンドの自力記述

役割を理解していても、実際にコマンドを書く段階では忘れることがある。

特に、git addのファイル指定、git commit -m、git log --onelineの定着が必要。

2. 操作順序の理解

ファイル変更後に何を確認し、どの順番で記録するのかを、資料なしで再現する必要がある。

3. GitとPython・SQLの並行学習

Gitに集中することで、これまで学習したPython・SQL・FastAPIのCRUDを忘れないよう、継続的な検索練習が必要である。

④ 本日の総合評価

学習到達段階：Gitの基本操作を実行できる段階。自力運用は定着途中。

前日から着実に進歩しており、Gitの環境構築と初回commitに加え、既存ファイルの変更・差分確認・再commit・履歴確認まで経験できた。

操作の実行能力は向上しているが、コマンドを完全に暗記して自力で使用するには、もう少し反復が必要である。

現時点では、新しいGitコマンドを増やすより、既習の6つのコマンドを確実に定着させることが優先される。

⑤ 次回の学習予定｜10月22日

第1部：Gitコマンドのノート整理（10分）

6つのGitコマンドについて、意味・書き方・操作順序を自分の言葉で整理する。

第2部：Gitの検索練習（5〜10分）

資料を見ずにコマンドを回答し、前日の弱点が改善しているか確認する。

第3部：Python・SQL・FastAPIのCRUD復習（残り時間）

これまで学習したCRUDの主要部分を復習する。

特に、SQLのUPDATE・DELETE、PythonのDB関数、FastAPIのルーティングと引数の扱いを重点的に確認する。

既習内容を反復しながら、Gitとバックエンド開発の知識を並行して定着させる。

⑥ 今後の学習方針

Gitについては、基本コマンドの定着後、.gitignore・GitHubへのpush・リポジトリ管理へ進む。

その後、これまで開発したFastAPIのCRUDアプリケーションをGitHubで管理し、実際の成果物として整理する。

将来的なバックエンドエンジニアのインターン応募、さらにAI・ロボティクス分野への進路につなげるため、コードを書く能力と開発管理能力の両方を高める。

次回の最優先課題：Gitの自力再現と、CRUDの知識定着。

プログラミング学習レジュメ｜2026年10月22日

学習テーマ：Git・SQL・CRUDのノート整理と、FastAPI・Pydanticの理解

① 本日の学習目標

これまで学習したGit・PowerShell・SQL・CRUDの知識を整理し、資料を見なくてもコマンドや構文を思い出せるようにする。

ノートを縦半分に折り、左側に問題、右側に答えを書くことで、今後の検索練習に活用できる形式にする。

今回は新しい内容を進めるよりも、既習知識の定着を優先した。

② 本日の学習内容

1. Git・PowerShellのコマンド整理

Gitの基本コマンドに加え、PowerShellで使用するフォルダ操作も整理した。

PowerShell

* mkdir：フォルダを作成
* cd：フォルダを移動
* cd ..：1つ上のフォルダに戻る
* pwd：現在の場所を確認
* notepad：メモ帳でファイルを開く

Git

* git init：リポジトリを初期化
* git status：現在の状態を確認
* git diff：変更内容を確認
* git add：変更をステージング
* git commit：変更履歴を記録
* git log：過去の履歴を確認

単にコマンド名を覚えるのではなく、使用目的・書き方・操作順序を関連付けて覚える方針とした。

2. SQL・CRUDのノート整理

CRUDの4つの基本操作と、それぞれに対応するSQL・HTTPメソッドを整理した。

操作	SQL	HTTP
Create	INSERT INTO	POST
Read	SELECT	GET
Update	UPDATE	PUT
Delete	DELETE FROM	DELETE

特に、以前学習した複数テーブルの結合と条件付き検索を重点的に確認した。

cursor.execute(
    """
    SELECT s.id, s.name, sc.score
    FROM students AS s
    JOIN scores AS sc
    ON s.id = sc.student_id
    WHERE sc.score >= ?
    ORDER BY sc.score DESC
    """,
    (80,)
)
rows = cursor.fetchall()

SELECT・FROM・AS・JOIN・ON・WHERE・ORDER BYなどの意味を整理した。

また、?によるプレースホルダーや、Pythonから値を渡すタプルの役割についても復習した。

3. FastAPIのresponse_modelについて理解を深めた

以前使用した以下の記述について質問し、使い分けを確認した。

response_model=StudentResponse
response_model=list[StudentResponse]

StudentResponseは学生1件を返す場合、list[StudentResponse]は学生の一覧を返す場合に利用する。

また、response_modelはGETやPOSTだけでなく、PUT・DELETEでも利用できるが、返すデータの形式に合わせて指定する必要があると理解した。

4. CRUDとGitの今後の学習範囲を確認

CRUDの基本操作は一通り実装経験があるものの、自力で一連のAPIを構築する力はまだ定着途中であることを確認した。

Gitについても、現在のローカル操作に加えて、今後はGitHubとの連携、ブランチ管理、変更の取り消し、.gitignoreなどを学習する予定である。

5. Pydanticの復習を次回課題に追加

以前軽く学習したPydanticの内容を忘れていることに気づき、復習が必要と判断した。

今後の学習対象として、以下を追加した。

* BaseModelによるデータモデルの定義
* StudentCreateとStudentResponseの違い
* Field()による値の制限
* response_modelとの関係
* model_dump()による辞書への変換

Pydanticの解説と復習カードは用意したが、本日は時間が終了したため、ノートへの記入と復習問題は翌日に持ち越した。

③ 本日の進捗・評価

学習項目	状況
Gitのノート整理	完了
PowerShellのコマンド整理	完了
CRUD・SQLのノート整理	完了
response_modelの理解	説明を確認
Python・SQLiteのDB操作整理	次回以降
HTTPException・404処理	次回以降
FastAPIの構文整理	次回以降
Pydanticの復習	次回予定

良かった点

1. 知識の定着を意識した学習に切り替えられた

コマンドを繰り返し眺めるのではなく、答えを隠して思い出す形式のノート作成に取り組んだ。

2. SQLとFastAPIの関連性を整理できた

SQLの構文だけではなく、それぞれがCRUDのどの処理に対応するのかを整理した。

3. 自分で不足している知識を発見できた

response_modelの使い方やPydanticの記憶が曖昧になっていることに気づき、今後の復習課題として明確にできた。

改善すべき点

1. 自力想起の確認がまだ必要

本日はノート整理が中心だったため、実際に資料なしでコードを記述できるかは十分に検証できていない。

2. 個別知識をつなぐ練習が必要

SQL・PythonのDB関数・Pydantic・FastAPIを、それぞれ単体で理解するだけでなく、一連のCRUD処理として組み合わせる練習が必要である。

④ 本日の総合評価

学習到達段階：既習知識の体系的な整理を進めた段階。自力再現力は今後検証する。

本日はプログラムの実装を行っていないため、コードの記述能力そのものが向上したかは判断できない。

一方で、GitとSQLの基本事項をノートに整理し、今後の検索練習に使える復習資料を作成できた点は成果である。

知識を忘れることへの対策として、継続的に使える学習環境を整えた。

⑤ 次回の学習予定｜10月23日

第1部：Pydanticのノート整理

BaseModel・Field・StudentCreate・StudentResponse・response_modelなどをまとめる。

第2部：Pydanticの復習問題

用意済みの復習カードを使い、理解できた部分と忘れていた部分を確認する。

第3部：Python・SQLite・FastAPIの復習

時間があれば、DB接続・cursor.execute()・fetchone()・fetchall()・HTTPExceptionによる404処理などを整理する。

ノートの整理が終わり次第、短いコード記述問題へ移行する。

⑥ 今後の学習方針

Git・SQL・Python・Pydantic・FastAPIを個別に暗記するだけではなく、学生管理APIの作成という一つの目的に結び付けて理解する。

今後は以下の順番で学習を進める。

1. ノート整理による知識の体系化
2. 検索練習による記憶の定着
3. CRUDの自力実装
4. Gitによる変更履歴の管理
5. GitHubへの成果物公開

次回の最優先課題：Pydanticの復習と、SQL・FastAPIの自力再現力の強化。

プログラミング学習レジュメ｜2026年10月22日（第2セット）

学習テーマ：Python・SQLite・FastAPI・HTTPExceptionのノート整理

① 本日の学習目標

1セット目に整理したGit・PowerShell・SQL・CRUDの知識に加え、Pythonからデータベースを操作する方法や、FastAPIでAPIを構築するための基本構文を整理する。

ノートを縦半分に折り、左側に問題、右側に答えを書くことで、後日資料を見ずにコードを思い出せるようにする。

② 本日の学習内容

1. Python・SQLiteの基本操作

PythonからSQLiteのデータベースを操作するための構文を整理した。

主な学習内容：

* sqlite3.connect()：データベースへの接続
* conn.cursor()：カーソルの作成
* cursor.execute()：SQLの実行
* cursor.fetchone()：1行の取得
* cursor.fetchall()：複数行の取得
* cursor.lastrowid：直前にINSERTした行のID取得
* conn.commit()：変更の確定
* conn.close()：接続の終了
* return：関数から結果を返す

以前のCRUD実装で使用したコードを、役割ごとに整理した。

2. HTTPExceptionと404エラー処理

データベースに対象の学生が存在しない場合のエラー処理について整理した。

row = cursor.fetchone()
if row is None:
    conn.close()
    raise HTTPException(
        status_code=404,
        detail="Student not found"
    )

if row is Noneによる条件分岐、raiseによる例外の発生、HTTPExceptionの役割を復習した。

また、404エラーが対象データの不存在を表すことを確認した。

3. FastAPIの基本構文

CRUDとHTTPメソッドの関係を整理した。

* @app.post()：データの登録
* @app.get()：データの取得
* @app.put()：データの更新
* @app.delete()：データの削除

さらに、"/students/{student_id}"のようなパスパラメータや、student_id: intによる型指定についてもノートにまとめた。

FastAPIの関数がPythonのデータベース操作関数を呼び出し、結果をAPIのレスポンスとして返す仕組みを整理した。

4. response_modelの使い分け

以前学習した以下の記述について、理解を深めた。

response_model=StudentResponse
response_model=list[StudentResponse]

StudentResponseは学生1件の出力形式、list[StudentResponse]は学生情報の一覧の出力形式を指定する。

response_modelはGET・POSTだけでなく、PUT・DELETEにも指定できるが、実際に返すデータの形式に一致させる必要があることを確認した。

5. Pydanticの復習課題を追加

以前学習したPydanticの知識が曖昧になっていることを認識し、翌日の学習課題に追加した。

復習対象は以下の内容とする。

* BaseModel
* StudentCreate
* StudentResponse
* Field()
* response_model
* model_dump()

Pydanticについては解説と復習問題を確認する準備をしたが、時間の都合により本日のノート作成対象からは除外した。

③ 本日の進捗

学習項目	進捗
Git・PowerShell	第1セットで整理完了
CRUD・SQL	第1セットで整理完了
Python・SQLite	ノート整理完了
HTTPException・404処理	ノート整理完了
FastAPIの構文	ノート整理完了
response_modelの使い分け	解説を確認
Pydantic	翌日に持ち越し
CRUD自力記述演習	未実施

④ 本日の評価

評価：既習知識の体系化が進展。自力再現力は未検証。

本日は新しいプログラムの実装ではなく、これまでに学習した内容の復習と整理を中心に取り組んだ。

特に、SQLからPythonのデータベース操作、FastAPIのAPI処理まで、CRUDを構成する主要な要素を一通りノートにまとめることができた。

一方で、ノートにまとめた構文を資料なしで正確に書けるかは、まだ確認できていない。

今後はノートを繰り返し読み返すだけでなく、答えを隠して実際にコードを記述する検索練習を行う必要がある。

⑤ 次回の学習予定｜10月23日

第1部：Pydanticのノート整理

BaseModel・Field()・StudentCreate・StudentResponseなどの基本構文を整理する。

第2部：Pydanticの復習

用意済みの10問を使って、基本的な役割や構文を思い出せるか確認する。

第3部：CRUDの検索練習

時間があれば、SQL・Python・FastAPIのコードを自力で記述する練習を行う。

特に以下を重点的に確認する。

* SQLのUPDATE・DELETE
* cursor.execute()とプレースホルダー
* fetchone()・fetchall()
* HTTPException(status_code=404)
* FastAPIのデコレーターと関数定義

⑥ 今後の学習方針

CRUDの基本操作は一通り実装経験があり、ノート整理もPydanticを除いて完了した。

今後は知識のインプットからアウトプットへ徐々に比重を移し、資料を見ずに学生管理APIを構築できることを目指す。

その後は、Gitによるコードの履歴管理、GitHubへの公開、ブランチ操作などの学習へ進む。

次回の最優先課題：Pydanticの理解と、CRUDの自力記述能力の確認。

プログラミング学習レジュメ｜2026年10月23日

学習テーマ：Pydanticの基礎理解・モデル定義・FastAPIとの連携

① 本日の学習目標

前日にノート整理を終えたGit・SQL・Python・SQLite・FastAPIに続き、Pydanticの基礎知識を復習する。

特に、BaseModel・Field()・StudentCreate・StudentResponseの役割を理解し、入力モデルと出力モデルを自力で記述できるようになることを目標とした。

また、PydanticとFastAPIの連携を理解し、CRUDの総合演習に必要な基礎を固める。

② 本日の学習内容

1. Pydanticの役割の理解

Pydanticについて、最初はデータ型や条件を固定する仕組みという認識だったが、解説を通して理解を深めた。

Pydanticは、データの形式や条件を定義し、実際のデータがそれらの条件を満たしているか検証するライブラリである。

学生管理APIを例に、次の役割の違いを確認した。

* FastAPI：HTTPリクエストの受付とAPI処理
* Pydantic：データの型や条件の検証
* SQLite：データの保存・取得・更新・削除

また、入力値がPydanticの条件に違反した場合、通常は422エラーとなり、データベースへの登録処理に進まないことを理解した。

2. StudentCreateとStudentResponseの違い

学生登録用の入力モデルと、学生情報を返す出力モデルについて学習した。

from pydantic import BaseModel, Field
class StudentCreate(BaseModel):
    name: str
    score: int = Field(ge=0, le=100)
class StudentResponse(BaseModel):
    id: int
    name: str
    score: int

StudentCreateは登録時に必要な名前と点数を定義する。

StudentResponseは、登録後に生成される学生IDを含めた出力形式を定義する。

入力と出力で必要な項目が異なるため、モデルを分けて利用することを理解した。

3. Fieldによる入力条件の検証

Field(ge=0, le=100)の意味を確認した。

* ge=0：0以上
* le=100：100以下

検索練習ではge=1と記述してしまい、0点も許可する場合はge=0が必要であることを復習した。

構文自体は自力で再現できており、数値条件の確認が今後の課題となった。

4. FastAPIとPydanticの連携

以下のPOST処理について、それぞれの構文の役割を確認した。

@app.post(
    "/students",
    response_model=StudentResponse
)
def create_student(student: StudentCreate):
    return add_student(student.name, student.score)

主な確認内容：

* student: StudentCreate：入力データの形式を指定する
* response_model=StudentResponse：出力データの形式を指定する
* student.name：入力モデルから名前を取り出す
* student.score：入力モデルから点数を取り出す
* add_student()：取り出した値をDB登録用の関数へ渡す

最初はadd_student()の引数について、studentに値を入れる処理と誤解していた。

解説後は、studentから値を取り出して別の関数へ渡す処理であることを理解し、穴埋め問題に正解できた。

5. Pydanticの自力記述練習

StudentCreateを自力で記述した。

モデル名、BaseModelの継承、データ型、Field()の構文は正確だったが、点数の最小値を1と指定していたため修正した。

続いて、StudentResponseも自力で記述した。

必要な項目とデータ型は正確だったが、クラス内のインデントが不足していたため修正した。

最後に、FastAPIのPOST処理における入力モデルと出力モデルの穴埋め問題に取り組み、2問とも正解した。

6. SQL・CRUDの復習

Pydanticの練習後、SQLのUPDATEを復習する予定だったが、45分に達したため未実施となった。

次回はUPDATEの自力記述から再開する。

③ 本日の学習評価

学習項目	評価
Pydanticの役割	◎ 概念を理解
BaseModelの継承	◎ 自力記述成功
StudentCreate	◎ ほぼ正確に記述
StudentResponse	○ インデントに課題
Field()	○ 条件の数値に注意
入力・出力モデルの使い分け	◎ 正解
student.name・student.score	◎ 修正後に自力回答
FastAPIとの連携	◎ 穴埋め2問正解
SQLのUPDATE	次回に持ち越し
CRUD総合演習	未実施

④ 改善が確認できた点

1. Pydanticの役割を具体的に理解できた

学習開始時点ではPydanticの目的が曖昧だったが、データ検証の具体例を通して、FastAPIやSQLiteとの役割の違いを理解できた。

2. 入力モデルと出力モデルを区別できた

StudentCreateとStudentResponseについて、両者の用途を正確に回答できた。

また、FastAPIのresponse_modelにどちらを指定するべきかも正しく判断できた。

3. モデル定義を自力で書くことができた

単なる選択問題だけでなく、class StudentCreate(BaseModel):などのコードを自力で記述できた。

これは前日のノート整理から、実際のアウトプットへ学習を進められた成果である。

⑤ 今後の課題

1. コードの細部の正確性

ge=0とge=1の違いや、Pythonのインデントなど、細部のミスを減らす必要がある。

2. FastAPIとDB関数の連携

入力モデルの属性を取り出し、Python関数に渡す処理について理解は進んだが、今後は実際に一連の処理を自力で記述する練習が必要である。

3. CRUD全体の自力再現

Pydanticの短い問題では正解できたものの、SQL・SQLite・FastAPIを組み合わせた完全なCRUD処理については、まだ自力記述能力を確認できていない。

⑥ 本日の総合評価

学習到達段階：Pydanticの基礎概念を理解し、モデル定義とFastAPI連携の短いコードを再現できる段階。

今回の学習では、Pydanticの意味を覚えるだけでなく、具体的な入力データと出力データを使い、なぜモデルを分ける必要があるのかを理解できた。

また、コード記述問題にも概ね正確に回答できており、理解とアウトプットの両面で進歩が確認できた。

ただし、独立した短い問題での成果であるため、実際のAPI全体を自力で実装できるかは今後の総合演習で評価する必要がある。

⑦ 次回の学習予定｜10月24日

第1部：Pydanticの短時間復習（5分）

StudentCreate・StudentResponse・Field()・response_modelの役割と構文を確認する。

第2部：SQL・CRUDの検索練習（20分）

前回途中で終了したUPDATEのSQL記述から再開する。

特に、UPDATE・SET・WHERE、プレースホルダーとPythonの引数の対応を重点的に練習する。

第3部：Python・FastAPIの検索練習（15分）

cursor.execute()・fetchone()・fetchall()・HTTPException・FastAPIの関数定義について復習する。

第4部：Gitの検索練習（5分）

基本コマンドを資料なしで思い出し、忘却を防ぐ。

⑧ 今後の学習方針

Pydanticの基礎復習が進んだため、次回以降はSQL・Python・FastAPIのCRUD検索練習に重点を移す。

個別の構文を覚えるだけでなく、入力データの検証からデータベース操作、APIレスポンスまでを一連の処理として理解する。

最終的には、学生管理APIを資料に頼らず自力で実装し、Gitで変更履歴を管理してGitHubに公開できる状態を目指す。

次回の最優先課題：SQLのUPDATEの自力記述と、CRUD全体の知識定着。

プログラミング学習レジュメ｜2026年10月24日

学習テーマ：Pydantic・SQL・CRUD・FastAPI・Gitの検索練習

① 本日の学習目標

前日に復習したPydanticの知識を定着させるとともに、SQL・Python・FastAPIを組み合わせたCRUDの自力記述能力を強化する。

特に、SQLのUPDATE・DELETE、プレースホルダー、404エラー処理、FastAPIのDELETEルーティングを重点的に練習する。

最後にGitの基本コマンドを復習し、継続的な記憶の定着を図る。

② 本日の学習内容

1. Pydanticの検索練習

StudentCreateとStudentResponseの役割について回答した。

* StudentCreate：入力データの形式を定義する
* StudentResponse：出力データの形式を定義する

役割の違いは正しく回答できた。

続いて、StudentCreateを自力で記述した。

from pydantic import BaseModel, Field
class StudentCreate(BaseModel):
    name: str
    score: int = Field(ge=0, le=100)

最初の回答ではclassを忘れ、Field()の書き方にも誤りがあった。

再挑戦ではclassやge・leを正しく書けたが、Field()の配置とインデントに課題が残った。

学習成果：入力・出力の役割は理解しているが、モデル定義の構文には反復練習が必要。

2. SQL UPDATEの復習

学生の点数を更新するSQLについて、自力記述を行った。

UPDATE scores
SET score = ?
WHERE student_id = ?;

scoresテーブルとstudent_idの指定は正しく回答できたが、SET score = ?の比較・代入部分を書き忘れた。

その後、PythonからSQLに値を渡す問題に取り組んだ。

cursor.execute(
    """
    UPDATE scores
    SET score = ?
    WHERE student_id = ?
    """,
    (90, 5)
)

学生IDが5の学生を90点に更新する場合、(90, 5)と渡すことを正しく回答できた。

プレースホルダーの順番については、以前より理解が定着していることを確認した。

3. conn.commit()の復習

SQLのUPDATE実行後に、変更を確定するコードを問われた。

conn.commit()

ノーヒントで正解した。

SQLiteの変更を確定するための基本操作を正確に思い出せている。

4. SQL DELETEの復習

学生IDを指定して点数データを削除するSQLを記述した。

DELETE FROM scores
WHERE student_id = ?;

テーブル名とWHERE条件の両方を正しく回答できた。

また、cursor.execute()に渡す引数として、1要素のタプル(5,)も自力で回答した。

5. HTTPException・404エラー処理

データベースに対象の学生が存在しない場合の処理を復習した。

row = cursor.fetchone()
if row is None:
    raise HTTPException(
        status_code=404,
        detail="Student not found"
    )

検索練習では以下の3項目をすべて正しく回答した。

* fetchone()：検索結果を1行取得
* None：対象データが存在しないことを判定
* 404：対象が見つからない場合のHTTPステータスコード

404エラー処理に必要な基本知識は、正確に思い出せている。

6. DELETE関数の総合記述

学生IDを指定し、scoresとstudentsの両テーブルからデータを削除する処理を自力記述した。

以下のSQLが正しい構文である。

cursor.execute(
    "DELETE FROM scores WHERE student_id = ?",
    (student_id,)
)
cursor.execute(
    "DELETE FROM students WHERE id = ?",
    (student_id,)
)
conn.commit()
conn.close()
return {"delete_id": student_id}

最初の回答では以下の誤りがあった。

* scoresテーブルの条件をscoreとしてしまった
* studentsテーブルの条件をnameとしてしまった
* cursor.execute()のスペルと引数の位置を間違えた
* 定義していないname・scoreをreturnで返そうとした

特に、scores.student_idとstudents.idの違いを再確認した。

一方、conn.commit()とconn.close()は正しく自力記述できていた。

7. FastAPIのDELETE処理

PythonのDB関数をFastAPIから呼び出す練習を行った。

@app.delete("/students/{student_id}")
def remove_student(student_id: int):
    return delete_student(student_id)

deleteとdelete_studentの2か所を正しく回答できた。

HTTPメソッドとDB操作関数をつなげる基本構造は理解できている。

8. Gitコマンドの検索練習

最後にGitの基本コマンドについて3問の検索練習を行った。

結果：3問中2問正解、1問部分正解。

* git status：正解
* git add hello.py：正解
* git log --oneline：gitを書き忘れた

過去の履歴を確認する役割は理解しているため、今後はコマンド全体を正確に書けるようにする。

③ 本日の学習評価

学習項目	評価
Pydanticの役割	◎
Pydanticモデルの自力記述	△
SQL UPDATE	○
プレースホルダーの順序	◎
conn.commit()	◎
SQL DELETEの単体問題	◎
fetchone()・404処理	◎
DELETE関数の総合記述	△
FastAPIのDELETE	◎
Git基本コマンド	○

④ 改善が確認できた点

1. SQLのプレースホルダーの理解が進んだ

UPDATEの値の順番を、ノーヒントで正しく回答できた。

2. CRUDの個別構文が定着してきた

DELETE FROM・fetchone()・conn.commit()・conn.close()などの構文を正確に思い出せた。

3. FastAPIとDB関数の関係を理解できている

DELETEルーティングからdelete_student()を呼び出すコードを正しく回答できた。

4. Gitの基本コマンドを継続して復習できた

git statusとgit add hello.pyを正しく回答できた。

⑤ 今後の課題

1. SQLのWHERE条件を正確に区別する

studentsテーブルではid、scoresテーブルではstudent_idを使用する。

対象テーブルの列構造を確認し、誤って点数や名前を条件に指定しないようにする。

2. Pythonの関数呼び出しを正確に書く

cursor.execute()のスペル、括弧、タプルを渡す位置を重点的に復習する。

3. Pydanticの構文を安定させる

class、インデント、Field()の配置について反復する。

4. CRUD全体の自力記述能力を強化する

個別の穴埋め問題では正解できているが、複数の処理を一続きで書く場合には誤りが増える。

今後は、SQL単体からDB関数、FastAPIまで段階的に組み合わせる練習を増やす。

⑥ 本日の総合評価

学習到達段階：個別構文の理解・想起は改善しているが、CRUDの総合的な自力実装は定着途中。

Pydantic・SQL・Python・FastAPI・Gitを横断して復習し、現在の理解度を確認できた。

特に、プレースホルダーの順番、トランザクションの確定、404エラー処理、FastAPIのDELETEルーティングでは正確な回答ができた。

一方、DELETE関数全体を自力で記述した際には、WHERE句やPython構文、返却値に複数の誤りが見られた。

このことから、今後は個別知識を覚えるだけではなく、実際の処理の流れに沿ってコードを組み立てる練習が必要である。

⑦ 次回の学習予定｜10月25日

第1部：前日の弱点復習（10分）

Pydanticのモデル定義、SQLのUPDATE、students.idとscores.student_idの使い分けを確認する。

第2部：DELETE関数の再実装（20分）

学生の存在確認、404エラー、2つのDELETE文、commit()、close()、returnを一続きで記述する。

最初は一部ヒントを使用し、徐々にヒントを減らす。

第3部：FastAPI・Gitの検索練習（15分）

FastAPIのGET・POST・PUT・DELETEの関数定義を復習し、Gitの基本コマンドも確認する。

⑧ 今後の学習方針

今後は短い穴埋め問題から、実際の処理を組み立てる総合演習へ段階的に移行する。

特に、学生管理APIのCRUDをSQL・Python・Pydantic・FastAPIまで一貫して自力実装できることを中期目標とする。

その後、Gitによる変更履歴の管理とGitHubへの公開を進め、バックエンド開発の成果物として完成させる。

次回の最優先課題：DELETE関数の自力再現と、SQLのWHERE条件の正確な理解。
