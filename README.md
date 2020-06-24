# Project No.2 : TODAY SNS
<h1># Project No.2 </h1>
<h2>1. Project Name: TODAY SNS</h2>


<h2>2. 開発目的とプロジェクト概要</h2>

 1) 開発目的 : <br>
 SNS APPをベンチマーキングし、日常を共有する事ができるSNSサイトを作りました。<br>
 また、会員なら趣味や関心事が同じである他の人々と一緒に集まりを作ることができるよう小集まり掲示板も構成しています。<br>
 2) 開発人員 : 3人<br>
 3) 開発期間 : 2020.02.12 ~ 2020.03.15 (1ヶ月) <br>


<h2>3. 開発環境</h2>
 1) OS : Windows 10 Home <br>
 2) WAS : Tomcat 8.5 <br>
 3) Java :　jdk1.8.0_231 <br>
 4) DB : Oracle Database 11g Express Edition <br>
 5) Tool : Eclipse, SqlDeveloper, Visual Studio Code <br>
 6) 使用言語 : Java ,  JSP , Servlet & MVC , JSTL , HTML5, CSS , Bootstrap, JavaScript, jQuery, Ajax <br>
 
 
 <h2>4. UseCaseと核心技術</h2>
  1) UseCase<br>
<img src = "https://user-images.githubusercontent.com/50767972/85623531-82e21300-b6a3-11ea-946a-0e09b3f7a65b.PNG" width = "90%"></img>    
  
  2) 核心技術<br>
     JFrame UIを実現<br>
     データベース設計<br>
     JDBCを利用したDatabase連動<br>

<h2>5. データベースの構造</h2>
<img src = "" width = "90%"></img>
<img src = "" width = "90%"></img>


<h2>6. スクリーンショット</h2>
<h4>1) ログインの画面</h4>
- 既存登録社員のみ入場可能となっています。 ＩＤ（社番）や暗証番号を入力せずにログインを押すと、警告ウィンドウが表示されます。ＩＤ（社番）や暗証番号が一致しない場合、警告のメッセージが表示されます。 登録されたID(社番)でない場合、警告のメッセージが表示されます。 ID(社番)とパスワードが一致した場合、ログインボタンを押すとお知らせ画面に移動します。<br>
<img src = "" width = "90%"></img>
<br>
<h4>2) 公知事項の画面</h4>
- 左側のお知らせをクリックすると、会社内の全体のお知らせが確認できる画面に変わります。
キーワードを入力して検索ボタンを押すと、キーワードが含まれたお知らせを検索できます。
部署が人事部の社員のみお知らせを登録することができます。
下段の書き込みボタンを押すと、新しいお知らせが書ける画面に切り替わります。<br>
<img src = "" width = "90%"></img>
<br>
<h4>3) 簡単な掲示板の画面</h4>
- 社員たちが作成した文やコメントを確認することができます。
画面上段の作成者の横の空欄をクリックすると、社番を入力するポップアップ ウィンドウが表示されます。 
掲示文を作成し、登録ボタンを押すと、文が登録されます。
既存の登録しない社番とか、内容が空欄であれば登録されません。
掲示文をクリックすると、該当文のすべてのコメントを確認することができます。
下段の削除およびコメントボタンを押すと、文を削除するか、コメントを入力することができます。
下段の右側の検索ボタンで文番号、作成者、内容別に掲示文を検索することができます。<br>
<img src = "" width = "90%"></img>
<br>
<h4>4) 管理者モードの画面</h4>
- 会社内のすべての社員の情報を確認することができます。
下段の追加ボタンを押すと、新しい社員の情報を追加することができます。
全社員リストのいずれかをクリックし、下段の変更、削除ボタンを押すと、各機能を実行する画面に切り替わります。変更ボタンを押すと、既存に保存されている情報が入力されており、既存に入力された内容を確認することができます。<br>
<img src = "" width = "90%"></img>
<br>
- 管理者モードの修正の画面
<img src = "" width = "90%"></img>
<br>
- 管理者モードの追加の画面
<img src = "" width = "90%"></img>
<br>
<h4>5) メッセージの画面</h4>
- メイン画面の上段にメッセージをクリックすると、メッセージウィンドウが表示されます。
受け取ったメッセージと送ったメッセージを確認できるように、Tabで区切られています。
下段のメッセージ送信ボタンを押すと、新しいメッセージを送信することができる画面に移動しながら、部署別、社員名、社員番号で社員を検索できるウィンドウが表示されます。
受信メッセージと送信メッセージのうち、1つをクリックし、下段の内容を見るボタンを押すと、そのメッセージの詳細が確認できる画面に移動します。
該当メッセージをクリックし、下段の削除ボタンを押すと、削除できます。<br>
<img src = "" width = "90%"></img>
