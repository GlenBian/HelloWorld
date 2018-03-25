# HelloWorld

### 在github上如何进行新建仓库和操作请参考教程：https://guides.github.com/activities/hello-world/

```
youibot@youibot-laptop:~$ ssh-keygen -t rsa -C "bianxu@youibot.com" 
```

* 后边的邮箱为你的私有账号的注册邮箱，执行之后会在~/.ssh目录下生成id_rsa  id_rsa.pub两个文件，打开id_rsa.pub，复制里边的key：

```
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDL0RGMnb0qQYK9k6WVDrE7mvi4XPk/DqA6TZnvTh1L4cHiExuJkYu8VfLq2VcJOOtBBPGMcP/YT4eD6X1Bi4RE8+yKZIN8D143ftVtJQ61M41kiyQ6a9QMg4bvNPFrvea4/ORdFdxDxx/wCCkX0P7tjmYBRdezRdh67j30g8e2fE0cUm02qHTIdtETwjftNOFOm/qq8ZKdwL1ESEPKbJ8B0f7h9FBXRuSJ41h0lSMxpg+01nLwr4NQ6QlvOaZZJMOMyMWFHIwpG9kqEywa+47Bas90mTW3nVD5hXcUNSYeFsh+5BbGiJQbnjnav+XG31GKU8/V0ekuKaxL+c+5rqsX bianxu@youibot.com
```

* 回到github网站，打开setting，点击SSH and GPG keys选项卡，点击绿色的New SSH key，将之前复制的key拷贝进来，生成新的key，Fingerprint: 2f:fd:b3:c0:69:c6:4c:7b:ba:08:2c:3d:1c:30:dd:40；

* ssh -T git@github.com ， 终端显示Hi GlenBian! You've successfully authenticated, but GitHub does not provide shell access.好了，现在你可以使用代码fork你的代码了，注意：当你换电脑时要重复上述步骤重新add一个新的SSH key；

### github简明教程   https://rogerdudler.github.io/git-guide/index.zh.html
