start a php server in the background with stdout redirected

```
cd ~/webroot
php -S localhost:8000 2> /dev/null &
```
