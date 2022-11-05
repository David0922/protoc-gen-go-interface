install

```bash
cd REPO_PATH
go install .

# or

go install github.com/David0922/protoc-gen-go-interface
```

usage

```
protoc --go-interface_out=. --go-interface_opt=paths=source_relative ./*.proto
```

todo

- enum
