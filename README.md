文件夹 evawyf.com.resume 链接到 GitLab 作为base：
1. 每次修改在该目录下修改，然后首先整体 $ git push 到 GitLab 更新base；
2. 然后在该目录下运行 $ ./deploy.sh 这个文件会首先build 也就是运行 $ hugo 生成 public 文件，并把 public 文件夹git到远程 GitHub pages 目录下，然后删除 public 文件，结束。