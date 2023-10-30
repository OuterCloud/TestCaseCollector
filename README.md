# TestCaseCollector

```sh
# 打 tag 并上传到 github
git tag -a 0.0.1 -m "init"
git push origin .0.0.1

# 创建 podspec 文件
pod spec create TestCaseCollector

# 设置代理(解决无法访问 github 问题): 点击小猫头->复制终端代理命令->终端执行

# 检查 podspec 文件合法性
pod spec lint TestCaseCollector.podspec

# 邮箱验证
pod trunk register runcheck1@163.com "tianyou.lan"

# 上传到 cocoapods
pod trunk push TestCaseCollector.podspec
```
