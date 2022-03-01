![Microsoft Cloud Workshop](images/ms-cloud-workshop.png)

PaaS Management Hands-on lab  
March 2022

<br />

**Contents**

- [Exercise 1: Application Gateway の作成と監視](#exercise-1-Application Gateway の作成と監視])

  - [Task 1: Application Gateway の作成](#task-1-Application Gateway の作成)

  - [Task 2: Application Gateway の構成](#task-2-Application Gateway の構成)

<br />

### 使用する環境

<img src="images/hands-on-architecture.png" />

<br />

### アプリケーションの動作確認

  - App Service の **概要** ページの **URL** をクリック

  - 新しいタブでアプリケーションが表示

    <img src="images/sample-app-01.png" />
  
  - **Managed Policy Holders** をクリック

    <img src="images/sample-app-02.png" />

    ※データベースからレコードを取得して表示
  
  - **Details** をクリックし、詳細情報を表示

    <img src="images/sample-app-03.png" />
  
  - **File Path** に表示される PDF ファイルへのリンクをクリック

    <img src="images/sample-app-04.png" />

    ※新しいタブで PDF ファイルが表示
  
  - 画面上部の **File Upload** をクリック

    <img src="images/sample-app-05.png" />

    ※ファイルのアップロードを行う画面が表示

<br />

## Exercise 1: サービス・リソース正常性

<img src="images/exercise-01.png" />

### Task 1: サービス正常性アラートの追加

- Azure ポータルのトップ画面から **検索バー** のテキストボックスに **正常性** と入力

- 表示される候補より **サービス正常性** を選択

  <img src="images/service-health-01.png" />

- **＋ サービス正常性アラートの追加** をクリック

  <img src="images/add-service-health-alert-01.png" />

- **サブスクリプション**、**サービス**、**リージョン** を選択

  <img src="images/add-service-health-alert-02.png" />

- **Service Health の基準** セクションの **イベントの種類** から **サービスの問題**, **計画メンテナンス** を選択

  <img src="images/add-service-health-alert-03.png" />

- **アクション** セクションの **アクション グループの追加** をクリック

  <img src="images/add-service-health-alert-04.png" />
