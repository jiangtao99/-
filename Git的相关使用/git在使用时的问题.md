git在使用时的问题

1、

```
$ git push origin
To https://github.com/jiangtao99/tools_configuration.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/jiangtao99/tools_configuration.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

```

![image-20230529032614001](C:/Users/江涛/AppData/Roaming/Typora/typora-user-images/image-20230529032614001.png)

https://blog.csdn.net/qq_30152625/article/details/90404727





2、

![image-20230529033034719](C:/Users/江涛/AppData/Roaming/Typora/typora-user-images/image-20230529033034719.png)

```
$ git pull --rebase origin master
error: RPC failed; curl 28 Recv failure: Connection was reset
fatal: expected flush after ref listing

```

