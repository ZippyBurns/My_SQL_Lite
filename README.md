## sqlite

## schema-plan
https://drive.google.com/file/d/1bH4a-3Rs9eeqjek0W94MfeFeSb4EZg_q/view?usp=sharing

## to run CLI
    ruby my_sqlite_cli.rb

### SELECT options
- MYSQLite> SELECT lastname FROM db.csv;    [JOIN user_id=id]
- MYSQLite> SELECT lastname, firstname FROM db.csv WHERE lastname=Laura;
- MYSQLite> SELECT lastname, age FROM db.csv ORDER age ASC;
- MYSQLite> SELECT * FROM tb.csv JOIN tb_join.csv ON col=col_join;

### INSERT options
- MYSQLite> INSERT db.csv VALUES lastname=Aaaa firstname=Bbbb age=11 state=AA;

### UPDATE options
- MYSQLite> UPDATE db.csv SET firstname=UPDATED WHERE firstname=Grey;
- MYSQLite> UPDATE db.csv SET firstname=UPDATED; (will update every record in a table)

### DELETE options
- MYSQLite> DELETE FROM db.csv WHERE lastname=Jamie;
- MYSQLite> DELETE FROM db.csv; (will delete every record in a table)

## to quit CLI
MYSQLite> quit