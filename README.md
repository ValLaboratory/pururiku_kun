プルリク君
==========

いま出ているプルリクリストをSlack通知してくれます。
通知内容はタイトル、URL、プルリクを出した人、付いているリアクションです。

使い方
----

```sh
$ mv ./config.yaml.sample ./config.yaml
$ vim ./config.yaml
$ chmod u+x ./pururiku_kun
$ ./pururiku_kun ./config.yaml
```

定期実行機能は付いてません。Jenkins、cronなど、環境にあったやり方で仕込んでください。

