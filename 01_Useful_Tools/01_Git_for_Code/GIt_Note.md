# Git Gitee SSH Tmux

## 1.Git

> 分布式 + 版本控制

- 分布式，每个用户==独享==一个本地库==共享==一个远程库

## 2.版本号

> 版本号：7c090adf2e2d2e5dc3efcb45313b50310c5e27c3
>
> 40位16进制数字构成，通过SHA-1加密算法生成 
>
> 前两位为文件夹 后38位为文件名

```c
git cat-file -p '版本号' //使用Git命名和文件版本号来查看文件  版本号为40位   
```

创建一个ver的仓库用于演示，初始化之后会生成下图所示文件

![image-20241013115550160](https://raw.githubusercontent.com/zhanghjoy/Typora_Note_Photo/main/Photo202410171159968.png)

> 其版本号为：800d2289bdf0d05c6006e9aaac11a655585c8271 
>
> 则在对应的文件夹中使用git 打开此版本号文件

![image-20241013115951012](C:/Users/zhj/AppData/Roaming/Typora/typora-user-images/image-20241013115951012.png)

上图中tree 后有一个版本号 再次打开得到正确的内容

![image-20241013121027862](C:/Users/zhj/AppData/Roaming/Typora/typora-user-images/image-20241013121027862.png)

100 表示普通文件 644 表示权限 blob文件快 此为文件的状态信息

在进行提交时，会将文件的状态信息和文件的提交信息进行关联 对应对应的文件版本号==**总共三个版本号**==

 

