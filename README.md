# mycobra

Download cobra:
```bash
go get -u github.com/spf13/cobra/cobra
```

start new cobra project:
```bash
cobra init --pkg-name github.com/ShubhamTatvamasi/mycobra
go mod init github.com/ShubhamTatvamasi/mycobra
# update all dependencies
go get
```

add new command:
```bash
cobra add random
```

