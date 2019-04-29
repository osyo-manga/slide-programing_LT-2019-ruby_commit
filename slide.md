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
  * 最終的な決定権は Matz が持っている
* Web アプリケーション開発で利用されている                        <!-- .element: class="fragment" -->
  * Ruby on Rails
* Ruby は死んだ？                        <!-- .element: class="fragment" -->
  * まだ生きてる                        <!-- .element: class="fragment" -->

---


#### Ruby にコミットされるまでの流れ
- - -

1. bugs.ruby にチケットを登録する                        <!-- .element: class="fragment" -->
1. 開発者会議の議題で取り上げる                        <!-- .element: class="fragment" -->
1. 問題がなければマージされる                         <!-- .element: class="fragment" -->

---


#### bugs.ruby に登録する
- - -

* Redmine でチケット管理している                       <!-- .element: class="fragment" -->
  * 機能提案やバグがあればここに issues を登録する
  * 英語が多いが日本語でも登録可
  * 日本人のコミッタが多い利点
  * github は使われてない
* 実際に登録した内容                       <!-- .element: class="fragment" -->
  * https://bugs.ruby-lang.org/issues/15653


---

#### 開発者会議
- - -

* コミッタが集まって毎月会議をしている             <!-- .element: class="fragment" -->
  * bugs.ruby に登録された提案などについて議論している
* この会議で議論してもらえるように議題に追加する必要がある             <!-- .element: class="fragment" -->
  * https://bugs.ruby-lang.org/issues/15614
* この会議で Matz が問題ないと判断すればマージされる             <!-- .element: class="fragment" -->
  * ダメならリジェクトされる


---

#### 機能提案する上で気をつけている事
- - -

* 最終的な決定権は Matz にあるので説得出来るだけのユースケースを考える             <!-- .element: class="fragment" -->
  * より具体的に
* 言語デザインとして一貫性がある             <!-- .element: class="fragment" -->
  * 他の機能と比べて整合性が取れているか
* 本当に Ruby に必要なのか             <!-- .element: class="fragment" -->
  * 外部ライブラリではダメなのか


---

#### まとめ
- - -

* Ruby の開発プロセスについて簡単に説明した           <!-- .element: class="fragment" -->
* 自分が使用している言語・ツールがどのように開発されているのか知っておく事は大事           <!-- .element: class="fragment" -->
* 貢献すると中の人が喜ぶので積極的に関わっていこう           <!-- .element: class="fragment" -->
  * Ruby に関して言えばそこまでハードルが高くはない
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

