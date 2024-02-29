SSH

删除ssh目录：
    rm -r .ssh/
生成ssh目录：
    ssh-keygen -t rsa -C [Email地址]    一定注意C大写，用默认值确认，会生成id_rsa和id_rsa.pub两个文件
进入.ssh目录，打开 id_rsa.pub 文件，复制全部内容
进入远程库的个人界面，点击“SSH and GPG keys”,再点击"New SSK",填写标题和粘贴复制内容。

在本地端 git remote add [别名] [SSH地址]