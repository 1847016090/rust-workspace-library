# ISSUE

1. 根目录执行`git add .`失败
   原因： `cargo new`生成的包默认包含`.git`文件夹，我们应该删除后，再进行提交操作

   ```shell
    #check for .git files using this command
    ls -la
    #if .git files present
    rm -rf .git
   ```
