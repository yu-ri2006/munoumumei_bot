# 令和最新版無能無名bot
とある鯖のために開発したbot  
[discord 招待リンク](https://discord.com/api/oauth2/authorize?client_id=970687646772887622&permissions=8&scope=bot%20applications.commands)  
  
## 機能  
| コマンド | 機能 | 詳細 | 
----|----|----|
| - | 読み上げ | テキストチャンネルに送信されたメッセージをVCで読み上げ |
| - | VC参加通知 | サーバー内のメンバーがボイスチャンネルに参加すると同一カテゴリー内に存在する優先テキストチャンネルに通知を送信 |
| - | VC退出通知 | サーバー内のメンバーがボイスチャンネルに退出すると同一カテゴリー内に存在する優先テキストチャンネルに通知を送信 |
| `/join` | 参加 | ユーザーが参加中のVCにbotを参加させる  |
| `/exit` | 退出 | botが参加中のVCからbotを退出させる |
| `/team` | チーム分け | 実行したユーザーと同一ボイスチャンネル参加者をチーム分けする |
  
## コマンド  
`/join` 参加中のVCにbotを参加させる  
`/exit` botが参加中のVCから退出させる  
`/team チーム数[int]` 指定したチーム数分のチームをVC参加中のメンバーから割り振り・作成を行う  
