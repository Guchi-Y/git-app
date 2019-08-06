# README
<img width="326" alt="スクリーンショット 2019-08-06 13 09 07" src="https://user-images.githubusercontent.com/51224937/62510876-d3623f00-b84b-11e9-8e83-52ce1bae3ed5.png">

# YACHO!


Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
## membersテーブル

|Column|Type|Options|
|------|----|-------|
|user_id|integer|null: false, foreign_key: true|
|group_id|integer|null: false, foreign_key: true|

### Association
- belongs_to :group
- belongs_to :user