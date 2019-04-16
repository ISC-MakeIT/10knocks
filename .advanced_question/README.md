# 10nocksが割と早く終わってしまった人へ

```
※ このAdvance問題には直接的なヒントはありません、問題文、'必要な構文の項目'より意図を読み取り、実際にプログラムを組みながら挑戦してみてください
```

## 問題

### 1. 以下のような挙動をするプログラムを書いてみてください。

```
1 ~ 100の数値を順番に列挙し、
列挙している数値が３で割り切れる場合は'fizz'を
5で割り切れる場合は'buzz'を表示してみてください。
```

  * 必要な知識
    - 1 ~ 100を表示するための繰り返し構文: for, while
    - 各数字を判断するための条件式(構文): if, 三項演算子
    - 数字が割り切れるかどうかの判断をする: 四則演算

<details><summary>挙動</summary>
1
2
fizz
4
buzz
fizz
7
8
fizz
buzz
11
fizz
13
14
buzz
</details><br/>

#### 1.a
  - 列挙した項目のうち15の倍数になるものは'fizzbuzz'となるように変更をしましょう

<details><summary>挙動</summary>
1
2
fizz
4
buzz
fizz
7
8
fizz
buzz
11
fizz
13
14
fizzbuzz
</details><br/>

この問題は。[`fizzbuzz問題`](https://ja.wikipedia.org/wiki/Fizz_Buzz)と呼ばれるプログラマなら一度は書いたことがある(はず)な有名な問題です。自分で書くことができたらインターネットで調べてみてください

*Check point*

  + for, whileによる繰り返し処理が理解できた。
  + if, 三項演算子による条件判断がりかいできた。
  + JavaScriptにおける四則演算の書き方を理解できた。
