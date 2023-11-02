# Postgres

```
docker compose -f infra/compose.yaml up -d
docker compose up -d --force-recreate   # force container recreate
docker container ps -a
```

# client postgresql-client (psql)

```
sudo apt update
sudo apt install -y postgresql-client
```

# connect to psql

```
psql --host=localhost --username=postgres --port=5432

# Test query
SELECT 1 + 1

\q      # quit
```

# Install pg js module

```
npm install pg@8.11.3
```

# Run tests

```
npm run dev
npm run test:watch
```
