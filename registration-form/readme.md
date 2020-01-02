# 第1章 登録フォーム

## 参考リンク

### プレースホルダーはユーザーにヒントを与えるという意味では良いとは言えない

- [Don’t Put Hints Inside Text Boxes in Web Forms :: UXmatters](https://www.uxmatters.com/mt/archives/2010/03/dont-put-hints-inside-text-boxes-in-web-forms.php)

・labelタグの代わりにプレースホルダーを使うのは良くない。

理由：プレースホルダーは、値を入力するときには消えてしまう

そもそも、なぜinput要素にプレースホルダーを入れるようになったか

→WCAG（Web Content Accessibility Guidelines） v1.0 10.4に記述がある（下記URL参照）

[10.4.1 INPUT、TEXTAREA、SELECT要素でデフォルトの値があるか](http://barrierfree.nict.go.jp/accessibility/helper/logic/10_4_1.html)

「ユーザーエージェントが、空のテキストフィールドを正しく扱えるようになるまでは、デフォルトの文字を入れておくようにする。たとえばHTMLの場合は、TEXTAREA要素とINPUT要素にデフォルトの文字を入れるようにする。」

WCAG v2.0ではプレースホルダーへの言及は無くなったためもう必要ではない

・プレースホルダーがあると、ユーザーはその項目が入力済みだと思ってしまう

実験をした↓（画像を貼りたい）

「ご職業」に入力する内容の"ヒント"として『ITエンジニア』をプレースホルダーに設定した

ユーザーは以下のどちらの選択をするか

- ヒントとして認識するか
- 入力済み項目だと認識して次の項目へ行くか

60％のユーザーは入力済み項目と認識し、次の項目へ進んでいることが判明
（232の内、139）

### 白地にグレーのテキストはコントラストが低く、たいてい読みにくい

- [How the Web Became Unreadable - Backchannel - Medium](https://medium.com/backchannel/how-the-web-became-unreadable-a781ddc711b6)