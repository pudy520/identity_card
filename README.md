

身份证验证
## 运行环境

- php >= 7.0
- composer

## 安装

```Shell
$ composer require vvv/identity_card
```
## 使用
```
 $num = '33071919610920021X';
 if (IdentityCard::isValid($num)) {
     echo '身份证格式正确';
 } else {
     echo '身份证格式不正确';
 }

```

## License

MIT
