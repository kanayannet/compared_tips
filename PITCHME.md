# Compared Tips

<span style="font-size:35pt">Gunma.web #28</span><br>
@kanayannet

---

# 自己紹介

- 氏名: 金澤 宏昭
- twitter: @kanayannet
- facebook: HiroakiKanazawa

![](img/cNat7zMn.jpg)

---

## What's Compare

- 比較という意味
- 比較対象
    - Vue と Angular

+++

## What's Tips

- 豆知識、ヒントなどを集めたもの
    - Vue と Angular 比較して役立ちそうなものを集める

+++

## なぜ話すのか?

- Vue と Angular よく解ってない
- 比較できるほど詳しくない
    - 他の人の記事を参考にしながら..
    - Tips にできればいいなぁ。

+++

## どの程度解ってないのか?

- チュートリアルをそれぞれやった程度

+++

## チュートリアル?

- Vue.js
    - https://jp.vuejs.org/v2/guide/
- Angular
    - https://angular.io/tutorial

---

# 1st

- いくつかの Vue の構文は AngularJS と非常に良く似ているように見える
    - ソース元
        - https://jp.vuejs.org/v2/guide/comparison.html

+++

## 1st

- 例 : v-if と ng-if

+++

## 1st

- API と設計の両方の観点から、Vue は AngularJS と比較してとても単純です。
- 重要なアプリケーションを構築するために十分学ぶのには大抵 1 日もかからないでしょう。

+++

## 1st

- 「大抵 1 日もかからないでしょう。」

+++

# 本当か?

+++

## 1st

- 本当か?
    - 試しにチュートリアルをやり始める

+++

## 1st

- 4-5時間経過
    - 終わらないよ汗
- 翌日
    - あと少しで終わりそう...

+++

# よく見る

+++

# よく見る

- 「大抵1日」

+++

## 1st

- よく見ると..
    - 「大抵」１日
        - 俺が未熟者なのかな〜汗

---

# 2nd

- React、Angularになじめなかった僕に手を差し伸べてくれたVue.js
- ソース元
    - http://qiita.com/samuraikun/items/bb2939296bbead341293

+++

## 2nd

- 「イケてるフロントエンド開発をちょっと試したいと思っても、BabelやWebpackの設定など環境構築でつまづき...」

+++

## 2nd

- 試しにチュートリアルの初めで比較

+++

## 2nd

- Angular
    - git clone https://github.com/angular/quickstart.git quickstart
    - cd quickstart
    - npm install
    - npm start    

+++

## 2nd

- ああ、なるほど。
- node(npm) 当たり前の世界になってるのね。

+++

## 2nd

- ちなみに vue はこう

```html
<script src="https://unpkg.com/vue"></script>
<div id="app">
  {{ message }}
</div>
<script>
var app = new Vue({
  el: '#app',
  data: {
    message: 'Hello Vue!'
  }
})
</script>
```

---

# 3rd

- 最も勢いのある成長があったフレームワークはvue.jsである。
- Angular 4のリリースがある。技術的には大きな変化があるが、それはバージョン1から2ほどの劇的な変化ではない。
    - ソース元
        - https://www.infoq.com/jp/news/2017/01/javascript-2017-frameworks

+++

## 3rd

- 成長のあったフレームワーク
    - 何をもって?

+++

## 3rd
    
- 試しにググった結果
    - Vuejs
        - 654,000
    - AngularJS
        - 15,800,000

+++

## 3rd

???

+++

## 3rd

- github の更新履歴
    - 2017
        - Vuejs
            - 546
        - Angular
            - 2114

+++

## 3rd

結局なぜか解らず...

---

# まとめ...

- どっちがどうなのか?はちょっと触ったくらいじゃ解らない。
- 「こっちがいい」的な記事はあるけど、具体的に「どこを比較して」なのか解りづらい汗
- エディタ戦争的なカオスな流れか?
- ついでに...

+++

# 反省点

- 記事を色々追って Tips にするつもりが...
    - 何を根拠に言っているのかさっぱり解らない
        - 裏をとる作業がメインになってしまった。
- こんなんばっかなの?

+++

# 俺だけか?

- 実際どうなんだろ?
    - 根拠があって使っている方、発表お願いします。

---

# ...

+++

# これで終わり?

- 5分もかかってないだろう? <- ツッコミ

+++

## もう少し話すよ

---

# 雑感

- ※ あくまで @kanayannet 個人の感想
- Vue.js の方が入りやすいかな?
    - 理由
        - npm なしでもいけそう
        - チュートリアル : 日本語
        - この二つだけでも学習強度が低い

+++

# 使いどころ

- SPA
    - DOMの書き換えが多いページ
- 双方向データバインディング
    - UIの変更があればデータの更新を自動的に行う機能
- コンポーネント指向
    - UIコンポーネント（部品）を組み合わせてアプリケーションを作る
    - Web Components を意識?

+++

## おっと

- 上記のワードでググったら比較的良記事が出てきた
    - https://app.codegrid.net/entry/vue-1
- 学習コスト
    - 制約がなく、シンプルで学習コストが低いのは、Vue.jsの大きな利点
- 制約がないということ
    - 制約がないことから、各個人によって書き方に相違が出やすいことも意識しておいてほしいことです。

---

# 関係ないけど

全く関係ない

+++

# 関係ないけど

- このスライド
    - gitpitch で書いてるよ
    - https://gitpitch.com/
        
+++

# 関係ないけど

- reveal.js みたい
    - ソース見ると...
- syntax ハイライトもできる
- 動画も流せる
    - youtube も簡易的に...

+++

# 動画

![Video](https://www.youtube.com/embed/mkiDkkdGGAQ)

---

# ご清聴<br>ありがとうございました。

+++

# 質疑応答

- GitPitch 以外なら受け付けます。
    - GitPitch は懇談会でw
