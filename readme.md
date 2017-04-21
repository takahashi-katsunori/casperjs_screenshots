# casperjsで複数URLをスクショ

## phantomjsとcasperjsのインストール
```
$ npm install -g phantomjs casperjs
```

## list.csvを作成
1列目にURL、2列目にファイル名

## コマンドラインを叩いてスクショ
### PCでベーシック認証通してスクショ
```
$ casperjs capture.js pc --id=cyberss --pass=ss1126gpo
```

### SPでベーシック認証通してスクショ
```
$ casperjs capture.js iphone6 --id=cyberss --pass=ss1126gpo
```

※デバイスはdevice.csvを確認