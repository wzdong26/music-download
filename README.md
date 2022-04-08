# music-download

## 📙 写在前面：

1. 这是一个可以下载歌曲的听歌webapp
2. 搜索出来的歌曲链接都有期限（1min左右），过期销毁，需要下载的话应该及时下载。
3. 加入歌单里的歌曲链接也会到期销毁，因此存在失效歌曲的情况，需要重新搜索加入歌单覆盖原来的失效歌曲。
4. 源码只有一个[index.html](https://github.com/wzdong26/music-download/blob/main/index.html)文件，追求极简😜，未调用任何第三方库和文件，利用原生h5、js（包含es6）、css实现。**[欢迎广大git友批评指正]**

## 📱 Page

[music-download/appview.png at main · wzdong26/music-download (github.com)](https://github.com/wzdong26/music-download/blob/main/appview.png?raw=true)

## 🔨 Functions

- 音乐搜索
  - 输入歌名+歌手名，如： 春风十里 鹿先森乐队
  - 搜索结果：
    - 点击结果卡片可单曲循环该首歌曲
    - 点击卡片的 **+** 按钮可加入歌单

- 歌单循环播放
  - 点击播放器右侧的 **≡** 按钮可展开歌单
  - 失效歌曲歌名会显示灰色且有 😭 标识
  - 当前播放歌曲歌名显示为红色
  - 失效歌曲在载入播放时会弹出提示并重新搜索该歌，可在搜索结果中重新加入歌单覆盖原来的失效歌曲

## 🙆‍♂️ Contributor

- wzdong
- Email：wzdong.26@qq.com
