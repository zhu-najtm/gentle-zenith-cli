# gentle-zenith-cli



学习用的示例项目

## 用法

```bash
cat data.txt | go run main.go
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## 备注

就是给自己省点事，没做太多抽象。

## 安装

```bash
git clone https://github.com/USER/gentle-zenith-cli.git
cd gentle-zenith-cli
go build ./...
```

## License

MIT
