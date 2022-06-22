# GitHub Pages 维护 markdown 仓库

这是使用GitHub Pages搭建的个人网站。

## 一、Why GitHub Pages

1. 搭建简单且免费
2. 支持静态脚本
3. 可以绑定域名
4. 支持markdown



## 二、搭建日志

1. 注册GitHub账号，我的用户名是"hejingcao"。
2. New repository. 名称需要设置为"hejingcao.github.io"。一般每个用户只有一个域名。
3. 选择新主题，我直接选择了默认第一个主题。
4. 修改文件配置。
5. 上传文件。



## 三、git管理网站

git是一个开源的分布式版本控制系统，可以用它来实现网站的更新和维护。使用git的大致流程如下：

1. 建立本地分支（使用https方式）：

   ```shell
   git clone https://github.com/hejingcao/myLeetcode
   ```

2. 设置本地用户名和邮箱

   ```shell
   git config --global user.name "hejingcao"
   git config --global user.mail "pkuchj2996@gmail.com"
   ```

   如果直接复制，会出现报错"error: key does not contain a section: –global"，需要手动输入该指令。

3. 设置ssh免密push

   ```shell
   cat ~/.ssh/id_rsa.pub
   账号头像->setting->SSH and GPG keys->New SSH key->添加title名字和公玥->Add SSH key
   ssh -T git@github.com
   Hi hejingcao! You’ve successfully authenticated, but GitHub does not provide shell access.
   ```

4. 将提交方式改为ssh：

   ```shell
   git remote -v
   git remote set-url origin git@github.com:hejingcao/hejingcao.github.io.git
   ```

5. 使用git

   ```
   git add .
   git commit -m "fix some errors"
   git push
   ```

   

参考：https://blog.csdn.net/lonyw/article/details/75392410