# auth-mm (ci_weixin)
基於 CodeIgniter (CI) framework 的微信模組，含：

1. 微信事件響應；
2. 第三方登入授權。

## 安裝
步驟：
- `application/config/constants.php` 增加常量定義：
``` PHP
define('TOKEN', 'yourToken'); // 'yourToken' such as 'QQ83989686'
define('WX_APP_ID', 'yourWeChatAppId'); // 'yourWeChatAppId' such as 'wx36883db1eX0def32'
define('WX_APP_SECRET', 'yourWeChatAppSecret'); // 'yourWeChatAppSecret' such as '2298f3aec9d1c5c96f7c3X96623c5b2e'
```

- 配置相應的資料庫資訊，位於 `application/config/database.php`；
- 將 `src` 中的內容部署至項目中。

## 原作
`sxf02615@163.com`
