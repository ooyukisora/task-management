# README

This README would normally document whatever steps are necessary to get the
application up and running.

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


## usersテーブル
|Column|Type|Options|
|------|----|-------|
|email|integer|null: false, unique: true|
|password|integer|null false|
|nickname|string|null: false|

### Association



## users_tasksテーブル
|Column|Type|Options|
|------|----|-------|
|user_id|integer|null: false, foreign_key: true|
|mtasks_id|integer|null: false, foreign_key: true|


### Association


## tasksテーブル
Column|Type|Options|
|------|----|-------|
|name|string|null: false|
|management_id|

### Association




