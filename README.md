# Note163Checkin

特别鸣谢：https://github.com/SoYoungxSoWhat/smzdm

## 三、运行

**`Actions`->`Run`->`Run workflow`**：
![run-workflow](https://img.guoqianfan.com/note/2020/08/run-workflow.png)

**注意**：本项目**不会**自动运行，需要自行在`.github/workflows/main.yml`添加定时任务。

## 四、查看运行结果

**`Actions`->`Run`->`build`**，能看到下图，表示运行成功
![查看action运行记录](https://img.guoqianfan.com/note/2020/08/查看action运行记录.png)

## 注意事项

24小时内频繁登录可能会触发验证，程序就会登录失败。此时需要在网页上手动登录一次（需要输入验证码），登录成功后再次运行本程序即可。

## 参考

参考了以下项目：
- [ydao](https://github.com/yygtboy/ydao/)
- [node-script](https://github.com/SunSeekerX/node-script)
- [youdaoyun](https://github.com/hezhizheng/youdaoyun)