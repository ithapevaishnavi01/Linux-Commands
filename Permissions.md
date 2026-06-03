# Linux Permissions

## Permission Values

| Permission | Value |
|------------|--------|
| Read | 4 |
| Write | 2 |
| Execute | 1 |

## Examples

```bash
chmod 777 file
chmod 755 script.sh
chmod 644 file.txt
```

## Change Owner

```bash
chown user file
```

## Change Group

```bash
chgrp devops file
```

## ACL

```bash
getfacl file

setfacl -m u:john:rwx file

setfacl -x u:john file
```
