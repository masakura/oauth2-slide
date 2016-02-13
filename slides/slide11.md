### 認証のための仕組みではありません

* アプリの作成時に対策をしましょう
  - `Implicit Grant Flow` ではなく、`Authorization Code Flow` を利用する
  - アクセストークンの妥当性検査を行う
  - OpenID Connect を使う

セキュリティの専門家ではないので、これで正しいかは分かりません...
