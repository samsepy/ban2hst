# banhst (for Mac )

## インターネットを封印してライバルに差をつけろ

まだ、SNSに消耗しているの？リアルを楽しもうぜ

## Initialize

```
git clone https://github.com/samsepy/ban2hst.git ~/.ban2hst
echo 'export PATH="$PATH:$HOME/.ban2hst"' >> ~/.zshrc
exec $SHELL -l
```

## How to use

- `config` ファイルにアクセス制限したいホストを記述
- `ban2hst -e` でアクセス制限実行
- `ban2hst -d` でアクセス制限解除
