### typeorm-model-generator

```
Options:
  --help                       显示帮助信息                               [布尔]
  --version                    显示版本号                                 [布尔]
  -h, --host                   IP address/Hostname for database server
                                                  [字符串] [默认值: "127.0.0.1"]
  -d, --database               Database name(or path for sqlite). You can pass
                               multiple values separated by comma.
                                                    [字符串] [必需] [默认值: ""]
  -u, --user                   Username for database server[字符串] [默认值: ""]
  -x, --pass                   Password for database server[字符串] [默认值: ""]
  -p, --port                   Port number for database server[数字] [默认值: 0]
  -e, --engine                 Database engine
    [必需] [可选值: "mssql", "postgres", "mysql", "mariadb", "oracle", "sqlite"]
  -o, --output                 Where to place generated models
                            [默认值: "C:\Users\luanxingtong\Desktop\orm\output"]
  -s, --schema                 Schema name to create model from. Only for mssql
                               and postgres. You can pass multiple values
                               separated by comma eg. -s scheme1,scheme2,scheme3
                                                           [字符串] [默认值: ""]
  --ssl                                                   [布尔] [默认值: false]
  --noConfig                   Doesn't create tsconfig.json and ormconfig.json
                                                          [布尔] [默认值: false]
  --cf, --case-file            Convert file names to specified case
                 [可选值: "pascal", "param", "camel", "none"] [默认值: "pascal"]
  --ce, --case-entity          Convert class names to specified case
                          [可选值: "pascal", "camel", "none"] [默认值: "pascal"]
  --cp, --case-property        Convert property names to specified case
                           [可选值: "pascal", "camel", "none"] [默认值: "camel"]
  --eol                        Force EOL to be LF or CRLF
                                         [可选值: "LF", "CRLF"] [默认值: "CRLF"]
  --pv, --property-visibility  Defines which visibility should have the
                               generated property
             [可选值: "public", "protected", "private", "none"] [默认值: "none"]
  --lazy                       Generate lazy relations    [布尔] [默认值: false]
  -a, --active-record          Use ActiveRecord syntax for generated models
                                                          [布尔] [默认值: false]
  --namingStrategy             Use custom naming strategy  [字符串] [默认值: ""]
  --relationIds                Generate RelationId fields [布尔] [默认值: false]
  --skipSchema                 Omits schema identifier in generated entities
                                                          [布尔] [默认值: false]
  --generateConstructor        Generate constructor allowing partial
                               initialization             [布尔] [默认值: false]
  --disablePluralization       Disable pluralization of OneToMany, ManyToMany
                               relation names             [布尔] [默认值: false]
  --skipTables                 Skip schema generation for specific tables. You
                               can pass multiple values separated by comma
                                                           [字符串] [默认值: ""]
  --strictMode                 Mark fields as optional(?) or non-null(!)
                                     [可选值: "none", "?", "!"] [默认值: "none"]
  --index                      Generate index file        [布尔] [默认值: false]
  --defaultExport              Generate index file        [布尔] [默认值: false]
```

<https://www.npmjs.com/package/typeorm-model-generator>
