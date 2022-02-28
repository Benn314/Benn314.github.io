**这是guide界面**

- - `git push -u origin main`
    上面命令表示，将当前分支推送到origin主机的对应分支。
    加了参数-u后，以后即可直接用git push 代替git push origin main
    origin指 指定被推送到的默认主机，这个origin在`remote add`命令里指定 。
- 最坑的是，你发现整个过程都没让你输入密码，但是在你push的时候，返回
  `fatal: unable to access 'https://github.com/Huxiehang/xrdDrawer.git' : Failed to connect to github.com port 443: Timed out`
  原因就是你没有输入密码，解决方法就是多push几次，会弹出让你输密码的页面。然后再push就成功了。
