# Myapp-Tasks
  Railsプロジェクトの起動方法について説明します

# 使用技術
- Ruby 3.2.2  
- Ruby on Rails 7.0.6  
- Postgresql 12
- Docker / Docker-compose

# 環境構築方法
1. クローンを作成したいフォルダに移動して、`git clone https://github.com/Nov-Is/rails-docker.git`を実行します  
2. `docker-compose up -d`を実行してコンテナやボリューム、ネットワークを作成します 
3. `docker-compose run web rails db:create`を実行してデータベースを作成します  
4. `docker-compose run web rails db:migrate`を実行してデータベースの構造を設定します  
5. ブラウザにて http://localhost:3000 にアクセスしてアプリを動かすことができます
