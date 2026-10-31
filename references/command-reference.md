# Command reference

- `@skill-crud -l`: list all records
- `@skill-crud -s [id:...]`: select records
- `@skill-crud -u [id:..., old => new]`: update
- `@skill-crud -d [index:...]`: delete (bulk operations require confirmation)
- `@skill-crud -a [title=..., text=...]`: append
- `@skill-crud -i [2, title=..., text=...]`: insert at index
- `@skill-crud -c [filter]`: count
- `@skill-crud -len()`: total length
- `@skill-crud -n [https://...]`: fetch a URL when network access is available
- `and`, `or`, `not`: boolean filter operators
- `def name(args): ...`: stored safe declarative function; arbitrary code is not executed
