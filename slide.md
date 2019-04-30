#### プログラミングLT 2019
- - -

## Ruby にコミットしよう

---


#### 自己紹介
- - -

* なまえ  : おしょー
* Twitter : [@pink_bangbi](https://twitter.com/pink_bangbi)
* github  : [osyo-manga](https://github.com/osyo-manga)
* ブログ  : [Secret Garden(Instrumental)](http://secret-garden.hatenablog.com)
* Rails 歴 1年の初心者                          <!-- .element: class="fragment" -->
* 趣味で Ruby にパッチ投げたりしている                          <!-- .element: class="fragment" -->
  * 機能提案などが多い
  * 15パッチ中7つ取り込まれた
* エディタは Vim                        <!-- .element: class="fragment" -->
  * わしの vimrc は 5000行以上あるぞ                        <!-- .element: class="fragment" -->

---

## Ruby にコミットしよう
- - -
実例を交えて Ruby の開発プロセスについて解説

---


#### 3行でわかる Ruby
- - -

* まつもとゆきひろ氏（通称 Matz）によって開発された言語                        <!-- .element: class="fragment" -->
  * 日本人のコミッタが多い
  * Ruby に機能を追加する最終的な決定権は Matz が持っています
* Web アプリケーション開発で利用されている                        <!-- .element: class="fragment" -->
  * Ruby on Rails
* Ruby は死んだ？                        <!-- .element: class="fragment" -->
  * まだ生きてる                        <!-- .element: class="fragment" -->

---


#### Ruby にコミットされるまでの流れ
- - -

1. 機能提案のチケットを登録する                        <!-- .element: class="fragment" -->
1. 開発者会議の議題で取り上げる                        <!-- .element: class="fragment" -->
1. 問題がなければマージされる                         <!-- .element: class="fragment" -->


 <br>
# 超簡単！                          <!-- .element: class="fragment" -->

---


#### 機能提案のチケットを登録する
- - -

* bugs.ruby でチケット管理している                       <!-- .element: class="fragment" -->
  * 機能提案やバグがあればここに登録する                       <!-- .element: class="fragment" -->
  * 基本的に英語だけど日本語でも OK                       <!-- .element: class="fragment" -->
  * github のミラーはあるが議論などでは使われてない         <!-- .element: class="fragment" -->
* 実際に登録した内容                       <!-- .element: class="fragment" -->
  * https://bugs.ruby-lang.org/issues/15653


---

#### 開発者会議
- - -

* 毎月コミッタが集まって会議をしている             <!-- .element: class="fragment" -->
  * ここで bugs.ruby に提案された機能を入れるかどうかの議論が行われてい <!-- .element: class="fragment" -->
  * つまり年に12回しかチャンスがない <!-- .element: class="fragment" -->
* 登録した提案はここで議論してもらえるように議題に追加する必要がある(超重要)             <!-- .element: class="fragment" -->
  * https://bugs.ruby-lang.org/issues/15614
* この会議で問題ないと判断すればマージされる             <!-- .element: class="fragment" -->
  * ダメならリジェクトされる


---

#### 機能提案する上で気をつけている事
- - -

* コミッタを説得出来るだけのユースケースを考える             <!-- .element: class="fragment" -->
  * より具体的に実際に困ってるケースなど提示     <!-- .element: class="fragment" -->
  * Matz の気持ちを考える               <!-- .element: class="fragment" -->
* 言語デザインとして一貫性がある             <!-- .element: class="fragment" -->
  * 他の機能と比べて整合性が取れているか
* 本当に Ruby 本体に必要なのか             <!-- .element: class="fragment" -->
  * 外部ライブラリではダメなのか


---

#### まとめ
- - -

* Ruby の開発プロセスについて簡単に説明した           <!-- .element: class="fragment" -->
* 自分が使用している言語・ツールがどのように開発されているのか知っておく事は大事           <!-- .element: class="fragment" -->
* 貢献すると中の人が喜ぶので積極的に関わっていこう           <!-- .element: class="fragment" -->
  * Ruby に関して言えばそこまでハードルが高くはない
  * 奥せずになんでもチャレンジ!
* ほしいものは自分でつくる!!!           <!-- .element: class="fragment" -->
  * ほしい!!というモチベーション

---

### おまけ : Ruby をハックしたいなら
- - -

* メーリングリストに登録する
  * bugs.ruby の情報が流れてくるので最近の動向がわかる
* [Ruby Hack Challenge](https://rhc.connpass.com/event/125655/) に参加する
  * Ruby の開発を行うもくもく会
  * 次は 5月11日に開催
  * RubyKaigi 反省会が行われる予定
  * https://github.com/ko1/rubyhackchallenge

---


## ご清聴
## ありがとうございました

