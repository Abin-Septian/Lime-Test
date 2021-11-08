## Tentang Module Lime

**Module Lime** adalah module `magento 2` versi `2.3.1` yang berisikan module 
- addTopMenu
- HelloWorld

## Development
untuk menambahkan module ke dalam platform magento lakukan langkah berikut :

1. clone / download module dan copy ke dalam `dir` : `app/code`
2. aktifkan module ke dalam sistem dengan command
```
php bin/magento module:enable [module_name]
```
3. update depedency platform
```
php bin/magento setup:upgrade
```
4. menghasilkan file tampilan statis 
```
php bin/magento setup:static-content:deploy -f
```
5. membersihkan cache
```
php bin/magento cache:clean
```

### Akses HelloWorld
Page HelloWorld dapat di akses dengan `url` `[root:domain]/helloworld` atau `[root:domain]/helloworld/index/index`

#### Github Link
https://github.com/Abin-Septian/Lime-Test