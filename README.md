# MySQL-Smart-Queries:

### Delete last 360 days records with MySQL TimeStamp fields:
```sql
DELETE FROM activity_log WHERE created_at > (NOW() - INTERVAL 360 DAY);
```
