FunPay个人收款支付系统
--------


> 代码作为样例已集成在[Funboot](https://github.com/funson86/)开发平台中。直接clone Funboot项目即可。

### 在线体验

在线体验网址： https://funpay.mayicun.com/

### 快速安装

代码作为样例已集成在[Funboot](https://github.com/funson86/)开发平台中。直接clone Funboot项目即可。请参考 Funboot安装文档 https://github.com/funson86/funboot/blob/master/docs/guide-zh-CN/start-installation.md


### 基本配置

在common/config/param.php中配置接收邮件

```php
    'funPay' => [
        'adminEmail' => '3375074@qq.com',
    ],
```

在common/config/param-local.php文件中配置邮件相关信息

```php
return [
    'smtp_host' => 'smtp.163.com',
    'smtp_username' => 'funson86@163.com',
    'smtp_password' => '',
    'smtp_port' => '587',
    'smtp_encryption' => 'tls',
];
```

这样才能在支付订单时，给管理员邮箱发邮件

