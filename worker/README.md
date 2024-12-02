# Hono on Cloudflare WorkerからAWS Lambdaを呼び出す

Cloudflare Workerで動作するHonoからAWS Lambdaを呼び出すサンプルコードです。

環境変数として以下の値が必要です。

```bash
AWS_Lambda_Function_URL=https://*********************.lambda-url.ap-northeast-1.on.aws/
AWS_ACCESS_KEY_ID=**************
AWS_SECRET_ACCESS_KEY=*****************************
```

ローカル開発`(npm run dev)`で動作確認できます。その場合は`.dev.vars`に環境変数を設定してください。

```
npm install
npm run dev
```

```
npm run deploy
```
