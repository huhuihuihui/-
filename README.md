# library

## 项目运行
### 克隆代码
1. 使用git bash运行  
`git clone https://github.com/huhuihuihui/library.git`

### 创建数据库
1. 使用Navicat连接mysql，创建数据库bms
2. 导入sql文件
3. 发现生成四张数据库表

### 修改配置文件
1. 修改config\application.yml
    ```
    url: jdbc:mysql://localhost:3306/bms
    username: "你的用户名"
    password: "你的密码"
    ```

### 运行后端jar包
1. 进入BMS-0.0.1-SNAPSHOT.jar目录，命令行运行
java -jar BMS-0.0.1-SNAPSHOT.jar

### 运行前端代码
1. `npm i`下载依赖
2. `npm run serve`运行
3. 进入地址，可输入“李四，123”登录

### 运行结果
1. 
![](result\login.png)
2. 
![](result\contents.png)
