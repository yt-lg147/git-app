# memo
Fatty liver

![readme](readme.png "readme")

## usersテーブル
|Column|Type|Options|
|-------|----|-------|
user_id|integer|primary key, index
name|varchar|null: false, unique: true
email|varchar|null: false, unique: true
password|varchar|null: false

### Association
- has_many: user_groups
