.. _label-lesson2:

====================================
Lesson2: コメント、引用
====================================

   :保存ファイル名: lesson2.rst
   :必要な操作: ファイルの作成、編集

Webブラウザで表示させた状態で以降の行をテキストエディタにコピーの上、
レイアウト等を再現するよう編集してください。

コメントおよび引用について
=====================================

このLesson2ではコメントおよび引用について説明します。

コメント
--------

reSTructured Textでは、".."とのみ記述した行に続けてインデントした文を
記述したものをコメントとすることができます。

".."と記述したインデントの深さに気を付けましょう。

コードブロック
--------------

"::"と記述した行に続けてインデントされた文を記述するとコードブロックと
することが出来ます。同じインデントレベルの文が出るまでが影響の範囲とな
ります。

   ::

      ::

         コードブロックをこのように書くといいです。
         ソースコードの引用、コマンドラインの記述等に
         これを使用することがあります


ラインブロック
--------------

reSTructuredTextでは、パラグラフという概念があり、空行までを一つの文
の塊としてとらえます。そのため、すぐ次の行に改行したテキストを記載する
のに、 ``|`` の後に続ける方法が有効な場合があります。


   | かきくえば
   | かねがなるなり
   | ほうりゅうじ
