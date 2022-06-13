# Hack U チーム18

このOrganizationは、チーム18の各種リポジトリを管理するものです。

## 基本的な運用

mainブランチでは作業せず、issue番号に対応した作業用ブランチで作業をお願いします。

例)  
機能Aの追加を行いたい場合

1. `機能Aの追加`という名前のissueを建てる。  
この時、以下の内容も行う  
    - コメントに詳細な情報を記載
    - Assigneesに作業者を追加
    - 適切なLabelを追加
1. issue番号を確認する。(今回は`機能Aの追加#3`という例で進む)
1. `識別可能な名前 + issue番号`(`add_A#3`のような形)でブランチを作成し、 **作業を行う。** 適宜、commit・pushをする。  
可能であれば、Draft Pull Requestを作成する。  
参考：https://github.blog/jp/2019-02-19-introducing-draft-pull-requests/
1. Pull Requestを作成する。  
この時、以下の内容も行う  
    - 名前に大まかな作業内容を記載
    - コメントにより詳細な作業内容を記載  
    このPull Request内で作業が終了したissueは、コメントに`Close #3`のように`Close`+`#番号`という形で記載(これによってPull RequestがCloseされた際に同時にissueもCloseされる。)
    - Assigneesに作業者を追加
    - 適切なLabelを追加
1. 相互にレビューをし、`main`ブランチにマージする。

## タスク管理

[OrganizationのProjects](https://github.com/orgs/YHU-team18/projects/1)にすべてのタスクを登録する。  
IssueタブからIssueを作成するとテンプレートが使用でき、1分ほどでProjectsへ反映されるため、ここではIssue化しないものを記入する。
