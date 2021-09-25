## sealyun-market 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://guides.github.com/features/mastering-markdown/)
-->

#### 组织背景🌈

> 这个组织主要是围绕[sealyun](www.sealyun.com)来工作，主要包括后端、前端、以及CI相关的核心项目。

#### 使用规范👩‍💻

1. **所有的bug都填写到issue中方便追踪**
2. sealyun-market仓库主要用来说明整体规划
3. apiserver为后端
4. front-home为前端
5. webhook主要用来做CI
6. upgrade主要项目升级
7. containerd是编译arm的containerd
8. sealyun-test自动化测试
9. marketctl主要针对sealyun的openApi做操作的

#### 其他信息


1. 测试环境 https://market.cuisongliu.com  数据库 mysql 
2. 生产环境 https://www.sealyun.com
3. 预计10.7之后要上线的功能
	1. 用户管理（修改用户角色（普通、管理员、文档管理员））
	2. 管理员管理产品、产品类型、产品版本
	3. 支付模块（用户可自行查看支付状态并同步，管理员查看所有的订单并同步说有的订单状态、可删除无用订单） 支付的稳定性优先开发
	4. VIP套餐模块（VIP创建、绑定产品，管理员功能）
  > 目前有个隐患： 用户下完订单之后修改VIP时间会影响订单状态，这个需要调整数据库，看进度，可延后处理。
4. 等后期需要修改登录接口要支持其他登录方式  
