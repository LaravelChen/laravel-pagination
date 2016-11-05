##Laravel5无刷新分页的使用

###查看效果
![enter image description here](http://picture.laravelchen.cn/my.gif)


### 1.Clone本地的package

```
git clone https://github.com/LaravelChen/laravel-pagination.git

cd laravel-pagination

composer install

```

### 2.修改你的数据库配置

修改 .env 文件并且设置数据库配置

### 3.数据库迁移

在你的项目根目录 (`laravel-vue-pagination/`):

```
php artisan migrate

php artisan tinker
```
然后
```
factory(App\Post::class,35)->create()
```

### 4.查看demo
运行服务器然后查看demo :
```
php artisan serve
```
