# surrealdb-test

[linux install]
curl -sSf https://install.surrealdb.com | sh
export PATH=$PATH:/home/<user>/.surrealdb

[start server]
surreal start --user root --pass root --bind 0.0.0.0:8080 rocksdb:mydatabase.db

open http://localhost:8080



program [python] - https://surrealdb.com/docs/sdk/python/setup

pip install surrealdb


python main.py