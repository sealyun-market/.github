## sealyun-market 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://guides.github.com/features/mastering-markdown/)
-->
### 🧙最近重要事务🧙

1. app模块 （引入kyverno）
2. cloud模块 - 对接aliyun/huaweiyun
3. 多集群开源

#### 组织背景🌈

> 这个组织主要是围绕[sealyun](www.sealyun.com)来工作，主要包括后端、前端、以及CI相关的核心项目。

#### 使用规范👩‍💻

1. **所有的bug和问题都填写到[issue](https://github.com/sealyun-market/issues/issues)中方便追踪**
2. **客户问题记录 [QA	](https://github.com/sealyun-market/QA/issues)**
3. **工作内容记录 [doc](https://github.com/sealyun-market/sealyun-market/issues)**
4. apiserver为后端
5. front-home为前端
6. webhook主要用来做CI
7. upgrade主要项目升级
8. containerd是编译arm的containerd
9. marketctl主要针对sealyun的openApi做操作的

#### 其他信息🍿


1. 测试环境 https://market.cuisongliu.com  数据库 mysql 
2. 生产环境 https://www.sealyun.com
3. 之后要上线的功能
	1. 账号密码登录
	2. 订阅服务模块（服务创建、绑定产品，管理员功能）
  > 目前有个隐患： 用户下完订单之后修改VIP时间会影响订单状态，这个需要调整数据库，看进度，可延后处理。
4. 等后期需要修改登录接口要支持其他登录方式  

#### 人员信息

- cuisongliu 主要开发和负责人
- geekFeier 前端
- aaronlyc 后端开发
- oldthreefeng OP运维
