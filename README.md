


```sql
INSERT INTO mysql_query_rules (rule_id,active,schemaname,match_pattern,replace_pattern,apply) VALUES (1, 1, 'db', '^SELECT \* FROM hodor$','SELECT id FROM hodor', 1);

select * from stats.stats_mysql_query_rules;

load mysql query rules to runtime;
```