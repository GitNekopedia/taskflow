# taskflow-java

## 初始化 initialize mysql

```bash
#
# 初始化 mysql initialize mysql
docker compose up -d
# 检查 db 是否初始化成功 check whether db successfully initilized
docker exec -it async-flow-db /usr/bin/mysql -uroot -p1234 -D asyncflow -e "show tables;"
```

## 启动  flowsvr start flowsvr

## 创建任务 create tasks

## 启动 worker start worker
