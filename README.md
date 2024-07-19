## 目的
- 搭建ELK环境使用kibana来查询odoo日志

## 流程
- odoo的日志存储至本地```logfile=/home/logs/odoo.log```
- filebeat监听日志文件将文件写入elasticsearch
- kibana提供可视化界面查询elasticsearch中的日志

## 注意事项
- 注意修改docker-compose.yml中的kibana密码
