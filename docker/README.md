# docker

## 打包

在代码根目录执行

```bash
docker build -f  "docker/Dockerfile" -t myexpress:latest .
```

## 运行

在代码根目录执行

```bash
docker run -d -p 3000:3000 myexpress:latest
```