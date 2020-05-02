# Pretty ResultSet

give it a result set, it will print it like a table.

for example:

```java
ResultSet rs = statement.executeQuery("select * from person where name='Lily'");
ResultSetPrinter.printResultSet(rs);
```

then it will output:

```
+----+----+---+
|  id|name|age|
+----+----+---+
|1000|Lily| 18|
+----+----+---+
```