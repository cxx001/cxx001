由于gitee个人用户不能上传超过100M文件。
所以本仓库对应的大文件附件移到github/resources这个仓库下。
https://github.com/cxx001/resources

注意通过git lfs 提交到github，免费也只有1G。
使用步骤：
1. 安装git lfs https://github.com/git-lfs/git-lfs

2. 添加待提交大文件路径到.gitattributes文件中并提交
git lfs track "big file path"
git add .gitattributes
git commit -m "xxxxxx"
git push

3. 提交大文件
git add big_file
git commit -m "xxxxx"
git push