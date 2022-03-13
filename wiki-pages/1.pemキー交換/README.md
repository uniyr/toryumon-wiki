## GOAL

 - 新しい Pem キー 「Ytoryu-key」 で本番サーバーにログイン**できる**ようになっていることを確認
 - 古い Pem キー 「newToryumon.pem」 でログイン**できない**ようになっていることを確認


## [検証]手順詳細

### 1. 本番日次スナップショット （AMI） から検証用インスタンスを起動
WIP

### 2. 既存pemキー「newToryumon.pem」でログインできることを確認
WIP

### 3. `~/.ssh/authorized_keys` フォルダの内容を書き換える
WIP

▼ Before
```
```

▼ After（登竜門検証用サーバーの `~/.ssh/authorized_keys` と同じ）
```
```


### 4. 新しい Pem キー 「Ytoryu-key」 でログイン**できる**ようになっていることを確認
WIP

### 5. 古い Pem キー 「newToryumon.pem」 でログイン**できない**ようになっていることを確認
WIP

### ❏ 参考情報
[【SSH】公開鍵認証とEC2について - Qiita](https://qiita.com/aiandrox/items/98ad9b7551481d890916)

[EC2のキーペア(SSHキー)を交換する方法とは？ | Tech Dive](https://tech-dive.xyz/2020/07/13/ec2%E3%81%AE%E3%82%AD%E3%83%BC%E3%83%9A%E3%82%A2ssh%E3%82%AD%E3%83%BC%E3%82%92%E4%BA%A4%E6%8F%9B%E3%81%99%E3%82%8B%E6%96%B9%E6%B3%95%E3%81%A8%E3%81%AF%EF%BC%9F/#toc2)