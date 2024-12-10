# notekeeper-proto
存储服务的 API 接口


初始化项目的结构如下：
notekeeper/
├── proto/
│   ├── notekeeper/
│   │   ├── notes.proto
│   │   ├── users.proto
│   │   └── ...
│   └── README.md
├── java/
│   ├── src/
│   │   ├── main/
│   │   │   └── java/
│   │   └── ...
│   ├── build.gradle
│   └── ...
├── go/
│   ├── src/
│   │   └── ...
│   ├── go.mod
│   └── ...
├── typescript/
│   ├── src/
│   │   └── ...
│   ├── package.json
│   └── ...
├── scripts/
│   ├── generate_proto_java.sh
│   ├── generate_proto_go.sh
│   ├── generate_proto_ts.sh
│   └── ...
├── docs/
│   └── ...
├── .gitignore
├── README.md
└── LICENSE