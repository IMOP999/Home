**1.创建和运行项目**

- vue create app
- npm run serve

**2.初始化配置：**

- 浏览器自动打开

  ```json
  package.json
  
  "scripts":{
    "serve":"vue-cli-service serve --open",
    "build":"vue-cli-service build",
    "lint":"vue-cli-service lint"
  }
  ```

- 关闭 eslint 校验工具

- ```js
  vue.config.js
  
  modele.exports = {
    lintOnSave:false
  }
  ```

- Src 文件夹别名设置

  ```json
  {
    "compilerOptions":{
      "baseUrl":"./",
      "paths":{
        "@/":[
          "src/"
        ]
      }
    },
    "exclude":[
      "node_modules",
      "dist"
    ]
  }
  ```

------

**3.上传项目至 GIT 仓库**

