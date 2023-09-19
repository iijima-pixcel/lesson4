# 第四回課題
1. 新規vpc  
![vpc](./img/lesson4-vpc.png) 
2. 新規EC2  
![EC2](./img/lesson4-instance.png)  
3. 新規RDS  
![RDS](./img/rds-database.png)   
4. EC2からRDSへの接続確認  
![EC2-RDS](./img/ec2-mysql.png)  
5. EC2のセキュリティグループ  
![EC2-inbound](./img/ec2-inbound.png)  
このインスタンスに接続できるのは、自分のipだけにした。(セキュリティ的観点から)　
6. RDSのセキュリティグループ  
![rds-inbound](./img/rds-inbound.png)  
RDSインスタンスに接続できるのは、5で設定したwebサーバーだけにした。(セキュリティ的観点から) 
