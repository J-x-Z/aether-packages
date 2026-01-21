# AetherLang Package Registry

Official package repository for the **jxz** package manager.

## 使用方法

```bash
# 安装包
jxz install <package> <version>

# 例如
jxz install hello 1.0.0
```

## 可用包

| 包名 | 版本 | 描述 |
|------|------|------|
| hello | 1.0.0 | Hello World 示例包 |

## 发布包

1. 创建 `Jxz.toml` 配置文件
2. 打包为 `.tar.gz`
3. 创建 GitHub Release 并上传

## 包格式

```
package-name/
├── Jxz.toml      # 包元数据
├── src/          # 源代码
│   └── main.aeth
└── bin/          # 编译后的二进制文件
```
