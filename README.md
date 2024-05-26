# A-payment-code-exclusively-for-the-elderly
给家人设计用来收款的app

## 原因
最近家里出去卖东西，家人不太会用智能手机，只能收现金，或者作者跟着一起去，不太方便索性就花了几分钟写了这个东西，方便家里人来用

## 使用方法
将支付宝收款码和微信收款码放到static目录下，分别命名为zfb.jpg和vx.jpg
如果不想重命名也可以，将支付宝收款码和微信收款码放到static目录下，然后修改pages/index/index.vue文件
将第四行和第七行的中的src="/static/你的文件名.jpg"修改成这个样子
**注意：文件名不能出现中文，防止打包失败**

static中的已有的图片可以删除

## 使用环境
```
uni-app
vue3
```

## 演示

微信![微信图片_20240526172333](D:\核酸\A-payment-code-exclusively-for-the-elderly\README.assets\微信图片_20240526172333.jpg)

支付宝

![微信图片_20240526172308](D:\核酸\A-payment-code-exclusively-for-the-elderly\README.assets\微信图片_20240526172308.jpg)

## 存在bug

1.可能点击按钮没有反应，多点击几次即可

2.当手机安装某些手机会出现以下情况，忽略即可，不会影响使用

![微信图片_20240526172337.jpg](D:\核酸\A-payment-code-exclusively-for-the-elderly\README.assets\微信图片_20240526172337.jpg)
