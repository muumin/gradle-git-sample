# Gradle Git サンプル

GradleからGitを操作するサンプル

maven release plugin（っぽい事）をしたかったので以下の動作

* masterにreleaseブランチをマージ
* gradle.propertiesのマイナーバージョンをインクリメントしてタグ付け
    * インクリメントするので最初は1.0.-1から開始すると1.0.0になる
* gradle.propertiesを更新してpush


# 参考サイト

* [裏紙](http://backpaper0.github.io/2015/06/29/grgit.html)
* [grgit](https://github.com/ajoberstar/grgit)
