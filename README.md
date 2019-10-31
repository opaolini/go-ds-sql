# SQL Datastore

An implementation of [the datastore interface](https://github.com/ipfs/go-datastore)
that can be backed by any sql database.

## Usage
```
import (
	"database/sql"
	"github.com/opaolini/go-ds-sql"
)

mydb, _ := sql.Open("yourdb", "yourdbparameters")

ds := sqlds.NewSqlDatastore(mydb)
```

## License
MIT
