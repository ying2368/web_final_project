# Web Final Project

## 必要設定

**請自行在 `module/` 資料夾內新增一個 `config.php` 檔案。**

`config.php` 檔案範例如下：

```php
<?php
// 設定資料庫連線
define('DB_HOST', '');
define('DB_USER', '');
define('DB_PASS', '');
define('DB_NAME', '');

$conn = new mysqli(DB_HOST, DB_USER, DB_PASS, DB_NAME);

if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
?>
```
將 DB_HOST、DB_USER、DB_PASS、DB_NAME 替換成你自己的資料庫連線資訊。
