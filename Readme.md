# gihtub 图片
- new,2024-02-27,chenxizhan1995@163.com

## 目录
- [jsdelivrgithub-试试](#jsdelivrgithub-试试)
## jsDelivr+Github, 试试
国内访问不了 JsDeliver，换成 raw.githubusercontent.com 反而能访问，就是慢了点。

两个提交，一个文件 img/foo.png
```
5ef7f66 (HEAD -> main, origin/main) 2024-02-27:更新foo.png
e6979e9 2024-02-27:初始提交
```
- github raw url
	- <https://raw.githubusercontent.com/uwfc/hello/main/img/foo.png>
	- <https://raw.githubusercontent.com/uwfc/hello/5ef7f66/img/foo.png>
- jsdeliver url
	- https://cdn.jsdelivr.net/gh/uwfc/hello/img/foo.png
	- https://cdn.jsdelivr.net/gh/uwfc/hello@e6979e956e382395f57b0626cf77a7d8764f1a42/img/foo.png
	- https://cdn.jsdelivr.net/gh/uwfc/hello@5ef7f666bbfa0e8cdab1a928688194ee2e6fbaff/img/foo.png
	- https://cdn.jsdelivr.net/gh/uwfc/hello@5ef7/img/foo.png

