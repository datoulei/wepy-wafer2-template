# A WePY-Wafer2 project

WePY默认模板 + Wafer2服务端Demo

## 体验步骤
### 1. 安装 wepy
本项目基于wepy开发，[参考这里](https://github.com/wepyjs/wepy)
```bash
npm install wepy-cli -g
```

### 2. 下载源代码
```bash
git clone https://github.com/datoulei/wepy-wafer2-template.git
```

### 3. 安装开发依赖
```bash
npm install
```

### 4. 编译源代码
```bash
wepy build --watch
```

### 6.修改配置

* 修改`project.config.json`中的`appid`为你的appID
* 修改`server/config.js`中的`appId`、`appSecret`、`mysql.pass`为你对应的配置
* 修改`src/config.js`中的`host`为你值腾讯云对应的域名

### 6.导入至开发者工具

编译完成后会生成`client`目录，开发者工具本地开发目录指向`client`目录。
