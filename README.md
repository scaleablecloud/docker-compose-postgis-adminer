```docker stack deploy -c stack.yml postgres```

or 

```docker-compose -f stack.yml up -d ```


visit 

http://localhost:84

psql -h localhost -U testuser -d testdb

PostgreSQL 11.2