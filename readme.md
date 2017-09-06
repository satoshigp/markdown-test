# 箇条書き
- item1
- item2
- item3
- [Ctrl]+[Shift]+[M]キー

もうひとつの大見出し
===

中見出し
---

## h2タグのタイトル

### h3小見出し

###### h6まで使える

改行だけでは改行にならない。  
改行前に半角スペース2つ以上入れると改行

hello.  
hello. hello. hello. hello. hello. hello.
hello. hello. hello. hello. hello. hello. hello.

hello. hello. hello. hello. hello. hello. hello.
hello. hello. hello. hello. hello. hello. hello.

hello. hello. hello. hello. hello. hello. hello.
hello. hello. hello. hello. hello. hello. hello.

# 引用
>  quote. quote. quote. quote. quote. quote. quote.
quote. quote. quote. quote. quote. quote. quote. quote.

## 引用とは
ほかの著作物の一部を抜粋して、それについて述べたりすること。
本文と明確に異なる書式にする

# 区切り線
---

***
___

- - -

上に行があるとh2になってしまう

---

# 強調表現
普通 *強調* 普通

nomal *kyoutyou* nomal

nomal _kyoutyou_ nomal

強調　**強調2**　普通

nomal **kyoutyou2** nomal

nomal __kyoutyou2__ nomal

# 箇条書き

  - item1
  - item2

    段下げした状態で文を記載できる。
    前後に空行を入れて、4つ半角スペースを入れる。

  - item3

# 連番リスト

1. 数字、ドット、スペース
2. 数字は何でもよい
1.
3. これでも3になる
1. よくやるのは、**すべて1.** にする　

#リンク
<http://dotinstall.com>

http://dotinstall.com

[リンク文字](http://dotinstall.com)

[ホバー](http://dotinstall.com "ドットインストール")

利用したアセットへのリンクなどで活用するとよい

# コードを見やすく

function x(){
  return x;
}

//Shift+@キー
```javascript
function x(){
  return x;
}
```
文章内でコードをあらわす場合
、`function`などと書く

バッククオート3つの後ろに言語を現すつづりを書くと、その言語用のハイライトが
行われる、C#ならCs、htmlならhtml、C言語ならC

```c
void main(){
  return0;
}
```

### 箇条書きのインデント
 - 箇条書き
  - スペース2つで箇条書きの段下げ
    - スペース4つで更に下げる
  - 一段戻す

 1. 連番も同様
  1. 下げる
  1. 下げる
 1. 戻す

# 画像

![ALT属性](http://dotinstall.com/img/logo_200x200.png)

ALT属性とは画像が取得できなかったり非表示のときに、
代わりに表示される文字列
![ALT属性](http://dotinstall.com/img/logo_200x200.png  "ドットインストール")

## 画像にリンク
[![ALT属性](http://dotinstall.com/img/logo_200x200.png  "ドットインストール")](http://dotinstall.com)

リンクと画像を組み組合わせたもの、[]内に画像のマークダウンを書いて、()にリンク先のurlを書く

## マークダウンファイルと同じ場所の画像へリンク
- [いらすとや](http://irasutoya.com/)
- いらすとやで画像を選んで保存

![おすもう](./sumo_yumitorishiki .png)
