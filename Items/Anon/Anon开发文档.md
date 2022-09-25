# Anon开发文档

## 数据库设计

### 用户数据表

- 用户注册  字段--字段类型
  1. id--int
  2. phone--number
  3. password--char(64)
  4. confirm--char(64)
  5. message--手机验证码
  6. code--任务识别验证码

- 用户登录  字段--字段类型
  1. id--int
  2. phone--number / email--char(64)
  3. password--char(64)

### 商品数据表



## 数据表设计

### 用户表设计

1. id
2. phone
3. password
4. is_admin
5. email
6. username
7. headicon





## 接口设计

### 用户注册

接口注册
```
POST  /api/user/register
```

请求参数
```
phone、password、confirm、(email)
```

需要返回的数据格式

```

```

成功响应

```

```


### 用户登录

接口注册
```
POST  /api/user/login
```

请求参数
```
phone、password、
```

成功响应
```

```

### 忘记密码
接口注册
```

```
请求参数
```

```
成功响应
```

```




## 
