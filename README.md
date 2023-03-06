# 本の投稿サイトの作成


## 目次
### 1. modelのそれぞれの役割
### 2. 主なViewファイルのそれぞれの役割
<br>
<br>

### 1. modelのそれぞれの役割

### user
-　本を投稿したユーザーについてのモデル。
### book
-　ユーザーが投稿した本についてのモデル。
### book_comment
-　本に関するコメント機能についてのモデル。
### favorite
-　本のいいね機能に関するモデル。


### 2. 主なViewファイルのそれぞれの役割

### -Book
#### index.html
-  userたちによって投稿された本を一覧化したページ。
#### edit.html
-　ログイン中のユーザーが本の投稿内容を編集するページ。
#### show.html
-　投稿された本の詳細についてのページ。

### -User
#### index.html
-  userたちの情報を一覧化したページ。
#### edit.html
-  ログイン中のuserの情報を編集するページ。
#### show.html
-　ユーザーの詳細についてのページ。

### -device
#### application.html
-  ログイン/サインアップのページ。
