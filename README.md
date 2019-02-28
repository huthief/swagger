## Docker-compose for swagger

### 一、Docker使用的版本

* swaggerapi/swagger-ui:latest

* swaggerapi/swagger-editor:latest


### 二、設定說明

#### swagger-ui 預設載入的swagger.json

預設載入的swagger.json為本目錄下的swagger.json


#### container啟動後，各服務的連線URL與 Port

- 連線到swagger-ui
localhost:9088
此時會預設載入本目錄下的swagger.json

-  連線到swagger-editor
localhost:9090

### 三、Docker啟動使用說明

#### 1. 安裝與啟動

開啟終端機，切換到本目錄，執行以下指令以啟動Docker container

```bash
$ docker-compose up -d
```

#### 2. 停止並刪除container

開啟終端機，切換到本目錄，執行以下指令以停止並刪除container

```bash
$ docker-compose down
```