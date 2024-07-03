自分用のキーボードリマップ設定です。Windowsの[のどか](https://appletllc.com/)用と、Linuxの[keyd](https://github.com/rvaiya/keyd)用があります。
キーボードは[Mistel Barocco MD600（英語配列）](https://archisite.co.jp/products/mistel/eol/barocco-md600-en/)です。

<kbd>CapsLock</kbd>キーをレイヤーキーとして、<kbd>CapsLock</kbd>+各キーでemacs風のカーソル移動ほか、色々押せるようにしてあります。
<kbd>CapsLock</kbd>を短押しするとIME切り替えとなっています。

# ✍メモ

## keyd

### 設定ファイルの保存先
`/etc/keyd/default.conf`

### コマンド

#### キーの識別子を確認する
```
keyd list-keys
```

#### 設定を再読込する
```
sudo keyd reload
```

#### キーの設定状況を確認する
```
sudo keyd monitor
```

-----
2024 Romly
