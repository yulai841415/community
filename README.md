# community
社区管理工具－基于laravel5.5 + vue + elementUi

### 项目构建流程

1、初始composer
```
composer install
```
2、安装package依赖（我在构建的时候node 版本为8.7.0,尽量用这个，有问题好定位）
```
npm install
```
3、 赋予目录操作权限
```
chmod -R 777 bootstrap
chmod -R 777 storage
chmod -R 777 vendor
```
4、在项目根目录，找到.env.local.example，复制一份，修改名称为.env
```
cp .env.local.example .env
```
5、生成安全机制 即.env 文件中的 APP_KEY
```
php artisan key:generate
```

至此，基本构建配置已完成。。。
