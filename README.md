## Authentication

```php
### Password in authentication
# config/auth.php
'passwords' => [
    'users' => [
        'provider' => 'users',
        'table' => 'password_resets',
        'expire' => 60,// time token reset life : default 60p
        'throttle' => 60,  // Allows a user to request 1 token per 60s seconds
    ],
],
```


