
## git注意事项

只有src下 APP.vue和componets属于每个分支单独控制
其他东西都属于配置分支,如果要修改其他东西,必须回到配置分支来修改

## 环境搭建

### 前端

#### 饿了么ui

``` 
npm install element-plus --save
npm install @element-plus/icons-vue
```

#### vue-router
```
npm install vue-router@4
```

#### vuex
```
npm install vuex@next
```
#### axios
```
npm install axios
```
#### 前端解决跨域问题
```
npm install http-proxy-middleware --save
```

### 后端

#### 邮箱
```
 pip install django-smtp-ssl
```

#### 验证码转图片

```
pip install captcha
```

#### 后端解决跨域问题
```
pip install django-cors-headers
```



## 前端

### 登录页面

我现在需要你用 vue3 + 饿了么ui  帮我写一个前端登录界面,一定要使用vue3而且要摒弃vue2中的一些被遗弃了的东西,我已经安装好所有的环境了,你只需要告诉我代码就行

首先应该有三个组件,一个是登录组件,一个是注册组件,一个是忘记密码组件, 你需要帮我美化好这三个组件,而且风格也要一样,注释也要详细一点,代码要尽可能简化,而且这些组件应该要展示中文,不需要你帮我写路由文件,你只需要给我这三个组件就行

登录组件中 需要一个邮箱输入框也就是登录账号, 一个密码框,它的后面应该要有一个查看密码的小图标(你可以将其单独变成一个组件,因为后面还需要用到,如果单独变成组件一定要注意保持原先饿了么输入组件的功能), 一个登录按钮, 然后还要包含跳转到注册账号和忘记密码组件的功能

注册组件中  需要一个邮箱输入框,一个密码框, 一个验证密码框,都需要有查看密码小图标,一个验证码输入框,它后面有一个发送按钮, 然后就是一个注册按钮

忘记密码组件中  它和祖册组件差不多 这两个组件也可以共用一下, 只不过一些关键信息不一样,比如标题,或者按钮文字

你现在按照这个步骤一步一步告诉我,每完成一个组件就停下来,我需要看你写的怎么样

### 搜索页面

## 后端

你现在是一个高级Django框架开发工程师
我的Django环境已经全部搭建好了,项目名字叫做searchproject,应用名字是app
我们前面已经完成了前端登录页面,不要忘记哦,我们的前端是用vue3写的,是一个前后端分离项目,接下来我们将一步一步的完成后端的登录逻辑,接下来我将一步步告诉你需要做什么,你先不用写代码,接下来我会像你提要求

我们先简单地设计一个用户模型让他能够注册跟登录,后续再对它的功能增强,它包含用户邮箱(要求唯一),密码,不要使用Django自带的用户模型

还需要一个能够发送邮箱验证码的功能

现在我需要三个接口,一个对应前面创建的用户模型的登录,一个对应密码修改,一个对应注册

