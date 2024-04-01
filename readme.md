# DiscordBotの作成方法（Xのポスト通知）
## 使用ツール
- RSS.app<https://rss.app/ja>
    - Xのポストを取得する際に使用するツール、外部ツールのためサービスが終了可能性あり
- Flows<https://cloud.activepieces.com/sign-in>
    - RSS.appで取得したポストのデータに更新があった際にDiscordのbotを通じてメッセージを送信する等のフローを作成できるツール
- Discord開発者ツール
    - DiscordBotを作成する際に必要になるトークンを発行するために使用
## RSS.app
- まずはログインまたはサインイン
- 右上のNewFeedで新規作成→Twitter RSS Feed→少し下にGenerate RSS Feed of a Twitter User Feedがあるのでそこにポストの通知を呼びたいアカウントのIDを入力し、Generate
![alt text](image.png)
![alt text](image-1.png)