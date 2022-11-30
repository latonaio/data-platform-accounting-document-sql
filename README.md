# data-platform-accounting-document-sql 
data-platform-accounting-document-sql は、データ連携基盤において、会計伝票データを維持管理するSQLテーブルを作成するためのレポジトリです。

## 前提条件  
data-platform-accounting-document-sql は、データ連携にあたり、API を利用し、本レポジトリ の sql 設定ファイルの内容は、下記 URL の API 仕様を前提としています。  
https://api.xxx.com/api/API_XXXXX_XXX/overview    

## sqlの設定ファイル
data-platform-accounting-document-sql には、sqlの設定ファイルとして、以下のファイルが含まれています。  

* data-platform-accounting-document-sql-accounting-document-item-data.sql（データ連携基盤 会計伝票 - 会計伝票明細データ）

## MySQLのセットアップ / Kubernetesの設定 / SQLテーブルの作成方法
MySQLのセットアップ / Kubernetesの設定 / 具体的なSQLテーブルの作成方法、については、[mysql-kube](https://github.com/latonaio/mysql-kube)を参照ください。
