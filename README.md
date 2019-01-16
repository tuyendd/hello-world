# Cach su dung package composer cho project php
Tren file composer.json cua project muon include package do can them vao dong
```
   "require": {   
        "tuyendd/hello-world": "dev-master"        
    }
```    
# Dung lenh : composer update de load package vo project
Tren file index cua project con require file autoload
```
require_once __DIR__ . '/vendor/autoload.php';
```
# Khi su dung chung can su dung dung namespace:
```
use tuyendd\SayHello\Sayhello;
$hello = new SayHello();
echo $hello->world();
```
# Ta lieu tham khao:
* https://getcomposer.org/doc/00-intro.md
* https://viblo.asia/thangtd90/posts/jlA7GKWGKZQ2