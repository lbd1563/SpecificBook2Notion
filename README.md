# SpecificBook2Notion
将微信读书中指定书籍的划线和笔记记录导入notion中。参考了@malinkang 老师的代码，感谢。

## 使用

1.需要安装指定的库；

2.必须使用本Notion模板：[ https://www.notion.so/75aa71cbf5f0455288f714d2dc9d8e3c ] ：打开后点击右上角的“复制”图标duplicate；

3.需要获取以下3个变量的值，并填入代码中：

    WEREAD_COOKIE ：电脑登录微信读书网页版，登录后F12开发者模式找到cookie值，具体请查阅其它教程；
    NOTION_TOKEN ：保存notion模板之后创建并添加connection，创建网址：https://www.notion.so/my-integrations，创建成功后View，复制Secrets；
    NOTION_PAGE ：保存notion模板后打开模板，.notion.so/到?之间的就是需要的值。例如：https://www.notion.so/6c70916e728555509613d2459044c4de?pvs=4中的6c70916e728555509613d2459044c4de
  
4.使用时须在终端中输入与微信读书书架中一致的书名，多个书名之间以“，”（中文逗号）分隔；

5.数据库中的字段：书籍名称、作者、状态、阅读已用时长、书籍字数、进度、评分、本条目创建时间及修改时间等。




## 捐赠

如果你觉得这个项目对你有帮助，欢迎请我喝咖啡~
<p align="left">
  <img src="https://github.com/lbd1563/SpecificBook2Notion/assets/34161959/9df88671-4326-4d53-a431-144cedf38d96' alt="logo" width="200" height="200">
</p>


## 联系

如果你有任何问题或建议，请通过以下方式联系我：

- 电子邮件：hiljx1002@163.com
