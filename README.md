# banhst (for Mac )

## インターネットを封印してライバルに差をつけろ

まだ、SNSに消耗しているの？リアルを楽しもうぜ

## Initialize

```
git clone https://github.com/samsepy/banhst.git ~/.banhst
echo 'export PATH="$PATH:$HOME/.banhst"' >> ~/.zshrc
exec $SHELL -l
```

## How to use

- `config` ファイルにアクセス制限したいホストを記述
- `banhst -e` でアクセス制限実行
- `banhst -d` でアクセス制限解除
