## Arc browser's bookmarks export

Arc 浏览器没有书签（Pined Tab）导出的地方和能力，因此想要导出数据切换到其他浏览器比较麻烦。于是写了点脚本进行转换。相关的背景可以查看[博客]()。

### 使用方法

1. 找到 Arc 的数据文件 `/Users/{你的用户名}/Library/Application Support/Arc/StorableSidebar.json`
2. 打开并复制里面的文本内容
3. 粘贴到脚本网页中
4. 点击导出按钮
5. 复制结果或者下载文件到本地
6. 在 chrome / edge 浏览器中导入书签。