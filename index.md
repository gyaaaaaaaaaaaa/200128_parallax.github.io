14

<div class="testdayo">
  <img src="pokemon-sword-shield-20bp-serialcode-aikotoba-series2-2.jpg">
</div>

↑これだ！これでmdファイルでclassを付与しながら画像を表示できる！  
この次に普通に`<script></script>`でコード書けば普通に動くだろう！  

<script>
  function testdayo(){
  console.log("test");
  }
</script>

よし動いた！  

CSSはどこに書けばいいのか？  
`_sass/jekyll-theme-midnight.scss`か？　違った。  
`_layouts/default.html`か？　違った。  
`_sass/normalize.scss`か？　違った。  
class名をかぶんないやつにしてみるか。  
`_layouts/default.html`か？　違った。  
`_sass/jekyll-theme-midnight.scss`か？　違った。  
`_sass/normalize.scss`か？　違った。  
`_sass/rouge-base16-dark.scss`か？違った。  
`assets/css/style.scss`か？違った。全然パララックスせんやん。  
`assets/css/ie.scss`でもない。えええ？？？  
このmdファイルに直接`<style>`タグで書いてもだめ。やばすぎる。オンクリックの動きはできたけど、パララックスができない。
新規cssファイルを作って、`_layouts/default.html`で呼び出してもだめ。

<img src="attach:pokemon-sword-shield-20bp-serialcode-aikotoba-series2-2.jpg" width="200">

![alt](/assets/images/pokemon-sword-shield-20bp-serialcode-aikotoba-series2-2.jpg)

![代替文字列](/assets/images/pokemon-sword-shield-20bp-serialcode-aikotoba-series2-2.jpg "タイトル")

<img src="/assets/images/pokemon-sword-shield-20bp-serialcode-aikotoba-series2-2.jpg" alt="attach:cat" width="200">

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
