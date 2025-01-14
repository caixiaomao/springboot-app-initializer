# springboot app initializer

## 模块说明

- initializer-generator: 生成项目模块
- initializer-page: 前端页面
- initializer-start: 启动、打包入口模块

## springboot 版本兼容信息

- https://start.spring.io/actuator/info

## 编译打包

```shell
yarn run build
```

访问：http://127.0.0.1:7001/index.html

## 常见问题
1. 高版本 nodejs 编译报错，参考 [Error message "error:0308010C:digital envelope routines::unsupported"](https://stackoverflow.com/questions/69692842/error-message-error0308010cdigital-envelope-routinesunsupported)，设置环境变量

```shell
# CMD
set NODE_OPTIONS=--openssl-legacy-provider
# PowerShell
$env:NODE_OPTIONS = "--openssl-legacy-provider"
```

## 感谢

- [cloud-native-app-initializer](https://github.com/alibaba/cloud-native-app-initializer)
