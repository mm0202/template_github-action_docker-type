![.github/workflows/main.yml](https://github.com/mm0202/template_github-action_docker-type/workflows/.github/workflows/main.yml/badge.svg)

# template_github-action_docker-type
 DockerタイプのGitHubアクションのひな型

## trace from [Docker コンテナのアクションを作成する](https://help.github.com/ja/actions/building-actions/creating-a-docker-container-action)

### Hello world docker action

このアクションは"Hello World"もしくは"Hello" + ログに挨拶する人物名を出力します。

### 入力

#### `who-to-greet`

**必須** 挨拶する相手の名前。 デフォルトは `"World"`。

### 出力

#### `time`

挨拶した時間。

### 使用例
```yaml
uses: mm0202/template_github-action_docker-type@0.0.1
with:
  who-to-greet: 'Mona the Octocat'
```
`uses`フィールドのリポジトリ名は作成したリポジトリに書き換えて使用