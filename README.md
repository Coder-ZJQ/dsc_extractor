### 构建

Xcode 打开项目运行即可在项目 `Products` 目录下生成可执行文件：

<img src="https://gitee.com/coder-zjq/ImageHost/raw/master/jqz3.tech/20210822170803.png" style="zoom: 50%;" />

或者 `dsc_extractor` 目录下执行：

``` bash
clang++ main.cpp -o dsc_extractor
```

<img src="https://gitee.com/coder-zjq/ImageHost/raw/master/jqz3.tech/20210822171219.png" style="zoom:50%;" />

### 使用

``` bash
dsc_extractor <path-to-cache-file> <path-to-device-dir>
```

