# vue-docker-sample
vueのdocker起動のサンプル  
以下参照
https://zenn.dev/chida/articles/8f16e42364398c

## 手順
・コンテナ名変更  
Dockerfileのcontainer_nameの名称を変更する  

・コンテナ起動
docker-compose up -d

・コンテナ作業  
docker-compose exec app /bin/bash  
(初期のみ)  
vue create .  
(毎回)
yarn serve
