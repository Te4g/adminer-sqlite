## What is this ?
This is an adminer docker image ready to use with sqlite

## How to use
Run:
```bash
docker run -d --rm -p 7777:8080 -v $(pwd):/app ghcr.io/te4g/adminer-sqlite
```
1. Go to http://localhost:7777
2. Select `sqlite3` as the database type
3. Use `admin:admin:` as the credentials
4. If you have a sqlite database in your current directory it will be mounted in `/app`
