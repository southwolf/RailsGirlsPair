## Rails Girls Making a Pair App

This app is built for rails girls to making a pair between female participants and tutors.

### Main Functions

1. Registration  注册
2. Rails Girls event installation guides for Chinese  安装文档本土化
3. Admin tool  管理员可以在profile添加问题
4. User profile 用户的资料，主要用来做背景调查
5. Making a pair  两个功能，一个是签到，一个是配对。

	* 活动签到：需要设置一个密码，上午到门口的时候，我们就把密码发给girls 和 tutors，自己登入后用注册邮箱地址签到。
	* 自动配对：然后我们根据用户的role（user字段）不同， 自动匹配。后台可以设置匹配人数，例如 8个girls+4个tutors  一组。然后把结果输出来

