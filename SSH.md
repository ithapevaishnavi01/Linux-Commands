# SSH Commands

## Connect Remote Server

```bash
ssh user@server-ip
```

## Copy File to Remote Server

```bash
scp file.txt user@server:/tmp
```

## Copy File from Server

```bash
scp user@server:/tmp/file.txt .
```

## Generate SSH Key

```bash
ssh-keygen
```

## Copy Public Key

```bash
ssh-copy-id user@server
```

## Sync Files

```bash
rsync -avz source/ destination/
```
