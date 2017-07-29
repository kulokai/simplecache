### Usage
```php
//init the tool
SimpleCache::init('.../path/to/cache');
```

```php
//set cache
$isSuccess = SimpleCache::set('key','hello world');
  
//set cache and set expire time
$isSuccess = SimpleCache::set('key','hello world',600);
```

```php
//get cache
$value = SimpleCache::get('key');
  
//get cache and set default value 
$value = SimpleCache::get('key','default value');
```