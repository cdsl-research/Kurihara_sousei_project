# worker_connectionsの変更必要性を調べるアプリケーション
リバースプロキシサーバをNginxで構築する．その際，worker_connectionsを変更せずにユーザからのリクエスト処理を正常におこなえるかを負荷試験する．

k3sをインストールする．→helmをインストールする．→helmを使用してNginxをインストールする→configmapでNginxの設定を変更しpodを立てる．
## 手順
1. リバースプロキシサーバとして使用したいサーバにファイルをダウンロードする．
2. シェルスプリクトファイルを実行する．
3. エラーが発生したのか，結果が返ってくる．
