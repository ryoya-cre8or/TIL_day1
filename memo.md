# GitHubでTIL

## 1.投稿する流れ
リポジトリを作り、コンテンツを書く。
[参考記事](https://www.asobou.co.jp/blog/web/github-til)

## 2.Markdown記法
[Markdown](https://wa3.i-3-i.info/word18982.html)ファイルで記述。  
詳しい記述方法は[これ](https://gist.github.com/mignonstyle/083c9e1651d7734f84c99b8cf49d57fa)と[これ](https://qiita.com/do7be/items/d21405a3d243dde37f92)。

よく使うもの以下にまとめる。
***
### 見出し
* 表記  

```
# 見出し1
## 見出し2
### 見出し3
```

* プレビュー  

![見出しの画像](https://github.com/ryoya-cre8tor/TIL_day1/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202021-06-28%2017.52.23.png)
***
### 太字

* 表記

```
みなさん**こんにちは**。
```

* プレビュー

みなさん**こんにちは**。
***
### 文章の改行  
* 表記

```
こんにちは(空白2つ)
元気です
```

* プレビュー

こんにちは  
元気です  
***
### 空行
*　表記

```
こんにちは
(空行)
いい天気
```

*　プレビュー

こんにちは

いい天気
***
### URL添付
* 表記

```
https://wa3.i-3-i.info/word18982.html
```

* プレビュー

https://wa3.i-3-i.info/word18982.html
***
### クリックでリンク先
* 表記

```
[リンク先はこちら](https://wa3.i-3-i.info/word18982.html)
```

* プレビュー

[リンク先はこちら](https://wa3.i-3-i.info/word18982.html)
***
### 箇条書き
* 表記

```
* これ
* それ
* あれ
```

* プレビュー
* これ  
* それ  
* あれ  
***
### コード
* 表記

バッククオート3つ  
(コード)  
バッククオート3つ

* プレビュー

```
Scaffold(
      appBar: AppBar(
        backgroundColor: Colors.red,
        title: Text('Demo'),
      ),
      body: Center(
          child: RawMaterialButton(
            fillColor: Colors.red,
            shape: RoundedRectangleBorder(
              borderRadius: BorderRadius.circular(50.0),
            ),
            constraints: BoxConstraints.tightFor(height: 50, width: 100),
          ),
      ),
    );
```
***
### 記号の直接表示(インラインコード)
* 表記

```
ここが`# 文字`です。
```
* プレビュー

ここが`# 文字`です。
***
### URLありの画像

*　表記
```
![見出しの画像](https://cdn-ssl-devio-img.classmethod.jp/wp-content/uploads/2018/08/flutter-logo-400x400.png)
```

*　プレビュー

![見出しの画像](https://cdn-ssl-devio-img.classmethod.jp/wp-content/uploads/2018/08/flutter-logo-400x400.png)
***
### URLなしの画像、gif等

* 表記
```
![見出しの画像](https://github.com/ryoya-cre8tor/TIL_day1/blob/main/gif%E3%83%86%E3%82%B9%E3%83%88.gif)
```
↑↑↑

(リポジトリに画像を追加するしかない？)

* プレビュー

![見出しの画像](https://github.com/ryoya-cre8tor/TIL_day1/blob/main/gif%E3%83%86%E3%82%B9%E3%83%88.gif)

※gifは5秒間30フレームで作成


