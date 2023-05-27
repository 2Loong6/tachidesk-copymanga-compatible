# Tachidesk 拷贝漫画兼容项目

本项目为基于tachidesk官方镜像的临时兼容项目，使用时请自负风险。

使用方式如下

```
    $ git clone https://github.com/2Loong6/tachidesk-copymanga-compatible.git
    $ cd tachidesk-copymanga-compatible
    $ docker build  -t tachidesk-copymanga-compatible .
```

### Docker

Docker运行参数请参考 [GitHub - Suwayomi/docker-tachidesk: Run Tachidesk in a docker container](https://github.com/Suwayomi/docker-tachidesk)

```
    $ docker run -p 127.0.0.1:4567:4567 tachidesk-copymanga-compatible
    $ docker run -p 4567:4567 tachidesk-copymanga-compatible
```
