# vue-JDFinance

---

## 说明

仿京东金融 web 端，vue+webpack 开发，css 模块化

### 封装

- 公共组件

  - btn
  - panel
  - slider
  - footer
  - header
  - navbar

- css

  - reset.scss
  - layout.scss
  - element.scss

- js

  - viewport.js // 从 webpack 中 entry 中引入，解决机型适配的问题 参考[hotcss](https://github.com/xueyan1/hotcss)

### 页面

- 首页 home

  - 组件

    - hslider // 轮播图
    - novice // 新手特权
    - borrow // 极速借贷
    - money // 理财精选
    - product // 新品推荐
    - life // 生活服务
    - reward // 赏金任务

- 赚钱 money

  - 组件

    - mslider // 轮播图
    - ada // 广告位
    - adb

- 借钱 borrow

  - islider
  - service
  - welfare

- 存钱 save

  - sslider
  - sign
  - recommend
  - more

## 业务开发流程

- 技术选型
  - 构建工具选择
  - mvvm 框架选择
    - vue
    - react
    - angular
  - 模块化设计
    - css 模块化
    - js 模块化
    - SPA 设计
  - 自适应方案设计
  - 代码维护及复用性设计
- 业务开发
- 测试验证
- 发布上线

![详细图](/img/业务开发流程.png)
