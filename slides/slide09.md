### アクセストークンの漏洩

* 通常、`App A` の管理者はアプリにアクセスしてきたあなたのアクセストークンを知ることはありません
* でも、`App A` の管理者が悪意を持っていれば、アクセストークンが取得できる形にアプリを作ることができます
* `App A` の管理者はあなたになりすまして SNS にアクセスできます


これは脆弱性ではなく、仕様です! <!-- .element: class="fragment" data-fragment-index="1" -->

アプリの管理者に認可した API を呼びだされる可能性がありますので、信頼できないアプリを使わないことが大切です <!-- .element: class="fragment" data-fragment-index="1" -->
