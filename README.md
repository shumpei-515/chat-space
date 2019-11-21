# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

_はーいここからデータベースの設計ですよ〜〜〜ん！_
# Users テーブル
｜name｜e-mail｜

# Association
** has many messages
** has many groups through groups_users

# groups_usersテーブル

|Column|Type|Options|

# Association
： belongs_to :group
：belongs_to :user

# groups テーブル
|group_name|

# Association
* has many users through groups_users
* belongs_to messages
