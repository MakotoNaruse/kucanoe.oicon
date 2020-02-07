# readme

jsでxssをしているためローカル環境ではfile:/の開き方では駅等が正しく表示されない

サーバーをたてて、http://localhost:8080/oicon.html などで開く

各開発環境にApacheなどがあるならそれでOK

## phpのみで簡易サーバを立てる
`cd 作業ディレクトリ` 

`php -S localhost:8080`

## Node.jsを用いてliveサーバを立てる
`npm install -g live-server` 

`cd 作業ディレクトリ` 

`live-server --port=8080`
