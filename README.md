### 存储引擎
- 存储引擎是数据库底层的软件组织，数据库管理系统通过存储引擎进行增删查改。存储引擎主要有InnoDB、MyISam、Memory、Archive等。
- mysql5.5之前默认使用MyISam为默认存储引擎，5.7开始采用InnoDB为默认存储引擎。  
查看mysql提供的所有存储引擎：  
`mysql> show engines;`

