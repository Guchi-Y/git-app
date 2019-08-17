# README
<img width="326" alt="yacho" src="https://user-images.githubusercontent.com/51224937/62510876-d3623f00-b84b-11e9-8e83-52ce1bae3ed5.png">

# YACHO!
<img width="500" alt="yacho2" src="https://user-images.githubusercontent.com/51224937/62512037-40c49e80-b851-11e9-8699-d029564b9cc3.png">

* アプリ詳細<br>
 野鳥情報共有アプリです。<br>
 野鳥ごとに、マップで目撃地点の閲覧・登録、<br>
 チャットでのコミュニケーションが出来ます。<br>

* 開発環境<br>
 Ruby version 2.5.1<br>
 Rails version 5.2.3<br>
 Mysql version 5.6.43<br>
 
* ローカル環境で使用する場合<br>
git clone をした後、以下のコマンドを実行して下さい<br>  
$ bundle install<br>
$ bundle exec rake db:create<br>
$ bundle exec rake db:migrate<br>
$ rails c<br>
pry(main)> Scraping.get_bird_name<br>

* 
