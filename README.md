# Redmine patch

下記のガントチャート関連の3つのパッチを手修正したものです。

Feature #20481: ガントチャートの表示領域の幅をドラッグでリサイズ 
http://www.redmine.org/issues/20481
Feature #10485: ガントチャートでコンテキストメニューを表示 
http://www.redmine.org/issues/10485#note-10
Feature #26409: ガントチャートに担当者を表示 
http://www.redmine.org/issues/26409#note-2

各ファイルを下記フォルダにコピーしてください。

```
C:\redmine\apps\redmine\htdocs\app\views\gantts\show.html.erb
C:\redmine\apps\redmine\htdocs\app\views\queries\_form.html.erb
C:\redmine\apps\redmine\htdocs\app\models\issue_query.rb
C:\redmine\apps\redmine\htdocs\public\javascripts\gantt.js
C:\redmine\apps\redmine\htdocs\public\stylesheets\application.css
C:\redmine\apps\redmine\htdocs\public\stylesheets\context_menu.css
C:\redmine\apps\redmine\htdocs\public\stylesheets\responsive.css
C:\redmine\apps\redmine\htdocs\lib\redmine\helpers\gantt.rb
C:\redmine\apps\redmine\htdocs\test\functional\queries_controller_test.rb
C:\redmine\apps\redmine\htdocs\test\unit\lib\redmine\helpers\gantt_test.rb
```
