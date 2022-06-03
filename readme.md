# @hanhan9449/dotfiles-cli

## 功能

用于同步管理不同设备上的dotfiles文件。

## todo-list

- [ ] 文件本地备份
- [ ] 文件本地恢复
- [ ] 文件远程同步上传
- [ ] 文件远程同步下载
- [ ] 文件下载冲突解决（不重要+容易解决）

## 使用用法

1. init
2. backup
3. restore
4. delete
5. sync

### init 

初始化本地git仓库，关联远程git仓库地址。

### backup

将单个本地文件同步到备份仓库中。

### restore

将备份仓库中的文件恢复到本地文件中。

### delete

删除备份仓库中的单个文件。

### sync 

将本地仓库和远程仓库进行同步。
