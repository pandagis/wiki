<p align="center">
  <img height="100px" src="./logo.svg" />
</p>

# [Wiki.js](https://github.com/Requarks/wiki)

Wiki.js 是一个基于 Node.js 构建的，现代的、轻量级的、功能强大的 wiki 应用。

## 部署


本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&tdl_anchor=github&tdl_site=0&appUrl=https://github.com/TencentCloudBase-Marketplace/wiki)

### 配置

- DB_HOST：数据库 Host
- DB_PORT： 数据库端口
- DB_USER： 数据库用户
- DB_PASS： 数据库密码
- DB_NAME： 数据库名称，默认为 wiki

### 依赖

- CynosDB：使用 CynosDB 数据库存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
2. Wiki.js 支持使用 PostgreSQL 数据库
