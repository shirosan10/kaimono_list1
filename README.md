# README

# Kaimono_List



# アプリケーション概要
--------------------------------------------------------------
キッチリ家計簿をつけつのは面倒臭い、でもなんとなく自分がどれくらい使ってる
のかを把握はしておきたい人向けに、買い物リストを作成したついでに簡易的な家
計簿を作成できるアプリケーションです。



# URL(未実装)



# テストアカウント(未実装)



# 利用方法
--------------------------------------------------------------







# 要件

| 機能              | 目的         | 詳細        | ストーリー      |
| :---------------- | :---------- | :---------- | :------------ |
| 



# 実装機能(未実装)



# 実装予定機能



# ER図





# ローカル環境での動作方法





# テーブル設計

## users テーブル 

| Column               |    Type    | Options                         |
| -------------------- | ---------- | ------------------------------- |
| nickname             |   string   | null: false                     |
| email                |   string   | null: false                     |
| phone_number         |   string   | null: false                     |
| password             |   string   | null: false                     |

### Association

- 


## category テーブル

| Column               |    Type    | Options                         |
| -------------------- | ---------- | ------------------------------- |
| name                 |   string   | null: false                     |

### Association

- has_many :reservations
- has_many :shop_genre
- has_many :shops, through: shop_genre



