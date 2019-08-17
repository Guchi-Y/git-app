# README
<img width="326" alt="yacho" src="https://user-images.githubusercontent.com/51224937/62510876-d3623f00-b84b-11e9-8e83-52ce1bae3ed5.png">

# YACHO!
<img width="500" alt="yacho2" src="https://user-images.githubusercontent.com/51224937/62512037-40c49e80-b851-11e9-8699-d029564b9cc3.png">

* アプリ詳細
 野鳥情報共有アプリです。
 野鳥ごとに、マップで目撃地点の閲覧・登録、
 チャットでのコミュニケーションが出来ます。

* 開発環境
 Ruby version 2.5.1
 Rails version 5.2.3
 Mysql version 5.6.43
 
* ローカル環境で使用する場合
git clone をした後、以下のコマンドを実行して下さい
$ bundle install
$ bundle exec rake db:create
$ bundle exec rake db:migrate
$ rails c
pry(main)> Scraping.get_bird_name

* 
