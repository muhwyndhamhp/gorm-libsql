# GORM libSQL Driver

![CI](https://github.com/go-gorm/sqlite/workflows/CI/badge.svg)

**Note:** This is an experimental refactored copy of gorm.io/driver/sqlite
to use libsql driver instead of smattn/go-sqlite3. Based on @ekristen repo.

## USAGE

```go
import (
  libsql "github.com/renxzen/gorm-libsql"
  "gorm.io/gorm"
)

// github.com/tursodatabase/libsql-client-go
db, err := gorm.Open(libsql.Open("libsql://..."), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.
