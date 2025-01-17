---
layout: ../../../layouts/wiki/ArticleLayout.astro
title: ダイアログ
description:
tag: word,ui
---

ダイアログとは、ユーザーと文章で対話する:[UI]:の一種。ダイアログは主にユーザーに集中してほしいタスクや情報を表示する。

## 表示の種類

ダイアログは、ユーザーがボタンなどの操作を実行したときに表示する。  
表示のし方として大きく2種類ある。なお:[モーダル]:と:[モードレス]:については別の記事で解説している。

### モーダルダイアログ

ユーザーがダイアログで提示される情報に対応するまで、背後のUIを利用不可能にする表示方式。  
モーダルダイアログが表示されている間、そのダイアログ以外の操作を行うことはできない。これは、ユーザーをタスクに集中させたり、注意すべき情報を伝えるために使われる。

### モードレスダイアログ

ユーザーがダイアログと同時にアプリケーションの他の部分を操作できるようにする表示方式。  
ユーザーが情報を参照しながら他のタスクを行う場合に有用である。

## 用途

ダイアログの用途は大きく分けて以下のような使い方がある。  

- 情報提供: 処理が完了したことやエラーが発生したこと、確認が必要な情報などを伝える。
- ユーザー入力: ユーザーに入力を求める。

なお、SmartHRにおいては、ダイアログを:[オブジェクト]:の生成、または編集をする際に多用している。

## 参考

- [Dialog | コンポーネント | SmartHR Design System](https://smarthr.design/products/components/dialog/)
- [削除ダイアログ | デザインパターン（共通） | SmartHR Design System](https://smarthr.design/products/components/dialog/)
