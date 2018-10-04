### マークダウンに関しては以下も参照
https://daringfireball.net/projects/markdown/syntax

<!-- 見出し -->
# H1
## H2
### H3

<!-- 水平線 -->

---

<!-- リスト -->
* リスト1
    - リスト2
        + リスト3

<!-- 番号付きリスト -->

1.リスト1
2.リスト2


```ruby:qiita.rb
puts 'The best way to log and share programmers knowledge.'
```

```ruby:qiita&nbsp;motto.rb　(2)
puts 'The best way to log and share programmers knowledge.'
```

` puts 'Qiita'` はプログラマのための技術情報共有サービスです。

`` `バッククオート` `` や ``` ``2連続バッククオート`` ``` も記述できます。


`#ffce44`
`rgb(255,0,0)`
`rgba(0,255,0,0.4)`
`hsl(100, 10%, 10%)`
`hsla(100, 24%, 40%, 0.5)`

_ か * で囲むとHTMLのemタグになります。Qiitaでは*イタリック体*になります。
__ か ** で囲むとHTMLのstrongタグになります。Qiitaでは**太字**になります。


打ち消し線を使うには ~~ で囲みます。 ~~打ち消し~~



追加情報としたい内容を、detailsタグで囲みます。そして、要約として表示したい文章をsummaryタグで記載します。

Qiitaとは

<details><summary>Qiita(キータ)は、プログラマのための技術情報共有サービスです。</summary>プログラミングに関することをどんどん投稿して、知識を記録、共有しましょう。
Qiitaに投稿すると、自分のコードやノウハウを見やすい形で残すことができます。
技術情報はテキストファイルへのメモではなく、タグを付けた文章、シンタックスハイライトされたコードで保存することで初めて再利用可能な知識になる、そうQiitaでは考えています。</details>

<details><summary>サンプルコード</summary><div>

\```rb
puts 'Hello, World'
\```
</div></details>

<dl>
  <dt>リンゴ</dt>
  <dd>赤いフルーツ</dd>
  <dt>オレンジ</dt>
  <dd>橙色のフルーツ</dd>
</dl>

<dl>
  <dt>リンゴ</dt>
  <dd> とても **赤い** フルーツ </dd>
</dl>

<dl>
  <dt>リンゴ</dt>
  <dd> とても<strong>赤い</strong>フルーツ </dd>
</dl>

- [ ] タスク1
- [x] タスク2

* * *
***
*****
- - -
---------------------------------------

[Qiita](http://qiita.com "Qiita")


[Qiita](http://qiita.com)

![Qiita](https://qiita-image-store.s3.amazonaws.com/0/45617/015bd058-7ea0-e6a5-b9cb-36a4fb38e59c.png "Qiita")


| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       | This        | This         |
| column     | column      | column       |
| will       | will        | will         |
| be         | be          | be           |
| left       | right       | center       |
| aligned    | aligned     | aligned      |

```math
\left( \sum_{k=1}^n a_k b_k \right)^{!!2} \leq
\left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```


