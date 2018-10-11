# MusicPlayer

## 开发环境
- 操作系统：Windows
- 编辑器：WinASM
- 汇编器：MASM32

## 模块说明
- 主程序在dialog.asm中，大部分声明在dialog.inc中。
- Music文件夹中存放了三首调试用的音乐 

## 功能（长期目标）

- WAV/MP3 等常用格式的音频文件的解码
- 播放、暂停、上一首、下一首
- 曲目的管理（显示所有歌曲的信息，同时提供增加歌曲、删除歌曲、喜欢、加入自定义歌单的操作）
- 播放模式的选择（单曲循环、随机循环、全部循环）
- 歌词的显示
- 提供关键词搜索功能
-（选做）将关键词搜索从本地的范围扩大到全网

## 待完成（近期目标）
### Task1
- 实现进度选择
- 实现音量选择
- 支持单曲循环和全部循环两种模式

### Task2
- upload函数中将SongMenu的内容存到本地磁盘
- load函数将SongMenu的内容从本地磁盘读取到内存
- 按下导入歌曲按钮后，能够增加歌曲（最好是弹出一个文件选择栏，如果技术实现上存在困难，也可以采用填空的形式）

### 进一步的迭代
## 功能修复
- 在本地文件被删除时，提示用户是否将该歌曲的索引删除
- 增加重复的歌曲时，不会重复增加；并且会提示用户

## 功能增加
- 在目录中进行关键词搜索
- 界面的美化
- 导入歌曲功能的扩展：输入网页链接，然后将歌曲下载到本地。（如果有可能，支持即下即播）
- 支持歌词播放功能