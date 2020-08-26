---
title: "Zennのマークダウン・エディターの使い方"
emoji: "👩‍💻"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["マークダウン", "zenn"]
published: false
---
このページではZennのマークダウンエディターの使い方を解説します。 

# 🖥 ショートカット
Zennのエディターでは以下のショートカットを使うことができます。`Ctrl`と記載している部分はMacでは`⌘(Command)`キーを使用してください。

## プレビュー
```
Ctrl + P
```
マークダウンがどのように表示されるかをチェックできます。もう一度ショートカットを実行すると、エディターに戻ります。

## 内容の保存
```
Ctrl + S
```

## 埋め込み
```
Ctrl + I
```
👇このようなモーダルが開きます。
![](https://storage.googleapis.com/zenn-user-upload/3eczstjiajdxbqujkloer616mj6r =400x)
ツイートやYouTube、CodePen、SpeakerDeckなどを挿入できます。

## その他のショートカット
- `Ctrl + B`：選択部分を**太字**に
- `Ctrl + Z`：1つ戻る
- `Ctrl + K`：テキストリンクの挿入
- `Ctrl + alt + C`：コードブロックの挿入
- `Ctrl + L`：リストの挿入
- `Ctrl + alt + L`：番号付きリストの挿入

👆Macでは`alt`の代わりに`option`キーを使います。


# 📝 マークダウンの基本

## コードブロック
> \```
> 
> \```

言語を指定するとシンタックスハイライトが適用されます。

> \```js
> 
> \```

```js
const var = () => {
  console.log("hello")
}
```

## 数式
`math`を指定されたコードブロックでは、TeX記法を使用できます。

> \```math
> 
> \```


```math
x = {-b \pm \sqrt{b^2-4ac} \over 2a}.
```

また、`$$`で数式を挟むことでも、数式ブロックを作ることもできます。

### インラインで数式を書く
`$a\ne0$`というよう`$`で挟むことで、文中に数式を含めることができます。
たとえば$a\ne0$のようなイメージです。


## 見出し
```
# 見出し1
## 見出し2
### 見出し3
#### 見出し4
```

## リスト
```
- Hello!
- Hola!
  - Bonjour!
  * Hi!
```
- Hello!
- Hola!
  - Bonjour!
  * Hi!

リストのアイテムには`*`もしくは`-`を使います。

## 番号付きリスト
```
1. First
2. Second
```
1. First
2. Second


## インラインスタイル
```
*イタリック*
**太字**
~~打ち消し線~~
インラインで`code`を挿入する
```
*イタリック*
**太字**
~~打ち消し線~~
インラインで`code`を挿入する


## リンクテキスト
```
[アンカーテキスト](リンクのURL)
```
[アンカーテキスト](https://zenn.dev)
`Ctrl + K`のショートカットでも挿入できます。


## 画像の挿入
```
![altテキスト](https://画像のURL)
```
![altテキスト](https://storage.googleapis.com/zenn-user-upload/gxnwu3br83nsbqs873uibiy6fd43)

### 画像の横幅を指定する
```
![altテキスト](https://画像のURL =250x)
```
![altテキスト](https://storage.googleapis.com/zenn-user-upload/gxnwu3br83nsbqs873uibiy6fd43 =250x)
画像の表示が大きすぎる場合は、URLの後に半角スペースを空けて`=○○x`と記述すると、画像の幅を指定できます。


## テーブル
```
| Head | Head | Head |
| ---- | ---- | ---- |
| Text | Text | Text |
| Text | Text | Text |
```
| Head | Head | Head |
| ---- | ---- | ---- |
| Text | Text | Text |
| Text | Text | Text |


## 引用
```
> 引用文
> 引用文
```
> 引用文
> 引用文

## 区切り線
```
-----
```
-----
