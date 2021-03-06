# opencmdb
OpenCMDB，一个打破现有市场格局的开源项目。敬请期待！

## 系统组件和引用说明

- 前端框架：Vue.js https://cn.vuejs.org/
- 前端UI组件库：iView  http://v1.iviewui.com/
- 数据可视化：Echarts http://echarts.baidu.com/
- 后端：Flask + Flask Restful + Mongodb
- API文档：Swagger UI https://swagger.io/download-swagger-ui/
- API测试：pyresttest https://github.com/svanoort/pyresttest
- RESTful API设计指南： http://www.ruanyifeng.com/blog/2014/05/restful_api.html

## 主要模块

- 模型管理（自定义CI模型、模型编辑、模型关系等）
- 仓库管理（基于Excel数据导入导出、资产编辑、资产搜索、Web SSH等）
- 视图管理（内置架构视图、业务视图等）
- 容量管理（多维度Dashboard展示）
- 系统设置（API Token、验证方式、）
- 用户中心（权限管理、SSH Key管理）

## 细节杂谈

- 拒绝图数据库，优点：关系描述完备，符合真实关系。缺点：谁用谁知道。
- 内置多种视图，支持全文检索，例如你搜索一个IP地址，将显示和该IP相关的整个链路。
- 完备的自动化，例如所有HTTP API的配置项会自动添加接口拨测，所有具有过期时间属性的对象，均会自动添加到期提醒。
- 支持直接和Zabbix对接，进行资产比对和监控的自动化添加。
- 支持自动化从OpenStack中获取资产信息。
- 公有云支持敬请期待。





