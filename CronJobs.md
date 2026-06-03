# Cron Jobs

## Edit Cron

```bash
crontab -e
```

## List Cron Jobs

```bash
crontab -l
```

## Remove Cron Jobs

```bash
crontab -r
```

## Examples

Run every 5 minutes:

```bash
*/5 * * * * /root/script.sh
```

Run every day at 12 AM:

```bash
0 0 * * * /root/backup.sh
```
