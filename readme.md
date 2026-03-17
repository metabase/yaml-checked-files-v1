Exports and database scripts.

Run static metabase checkers on the exports. You can use the resources in the db-schema to connect to a database.

## Usage

```
❯ clj -X:ee metabase-enterprise.checker.checker/cli :export '"/Users/dan/projects/work/yaml-checked-files-v1/exports/sqlite-based"' :output '"/tmp/real.txt"'
```

this will be updated to a normal
