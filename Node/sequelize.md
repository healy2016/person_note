### sequelize
>* 使用sequelize：  Ram query 原始执行语句可执行混合查询
>* 使用sequelize.transaction 事务控制多个表的增删改
>* 增加属性的配置： operatorsAliases: false   去掉别名
>* sequelize-auto 的使用可以自动生成Model
>* 必须全局安装 sequelize-auto  pg@6 和 pg-hstore

### sequelize 生成Model示例

>* sequelize-auto -h 60.205.138.237 -d gtyserver -u postgres -x postgres -p 5432  --dialect postgres  -o "./model" -t gty_role -C
>* sequelize-auto -o "./models" -d sequelize_auto_test -h localhost -u my_username -p 5432 -x my_password -e postgres

