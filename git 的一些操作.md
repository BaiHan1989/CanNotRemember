## 打标签

- 添加一个标签

```
git tag -a 标签名称 -m "描述信息"
举例：
git tag -a 3.1.4 -m "Release Version 3.1.4"
```

- 将标签提交到远程服务器上

```
git push origin --tags
```

- 切换到已有的标签

```
git checkout 标签名
举例：
git checkout 3.1.4
```

- 删除标签

```
git tag -d 标签名
举例：
git tag -d 3.1.4
```

- 删除远程服务器的标签

```
git push origin :refs/tags/标签名
举例：
git push origin :refs/tags/3.1.4
```

