![rhythm-lead](https://s1.ax1x.com/2022/03/20/qepL1H.jpg)

# Rhythm 在线音乐播放器

#### 系统简介

- 音乐播放器就是音频解码器的可视化操作界面，其实质是针对各种音频编码格式的解码器。 例如ape格式通常调用的是Monkey's Audio解码器，flac格式调用的是flac解码器，mp3调用的是lame解码器。
- 大部分音乐播放器都支持多种音乐格式的文件，这是因为这些播放器将不同的音频解码器打包起来，并制作统一的播放界面，从而让使用者能够方便地播放和聆听各种音乐。
- 音乐播放器的人性化界面和扩展性才是各种音乐播放器的特色所在。大部分商业版播放软件往往将界面打造得非常华丽，操作也十分简便，但却缺乏扩展性，支持格式较少。开源播放软件一般能够较好地进行扩展，支持较多的音乐格式。

####  实现功能

我们的音乐播放器希望实现下述功能：

1. 支持基本的本地音乐播放功能，支持常用的mp3，flac，ape,wav等音频文件格式，并支持基本的播放，暂停，调节音量等功能，并从音乐文件中提取歌曲作者。
2. 支持通过lrc文件加载并显示歌词随音乐播放同步滚动显示。
3. 支持一定的乐曲库管理功能，包括将歌曲加入播放列表，或从播放列表中移除歌曲，支持通过歌手（作者）筛选歌曲，支持随机播放，顺序播放，单曲循环等播放顺序；用户可建立多个歌单并将乐曲放入其中以便于分类管理。
4. 支持通过网络播放第三方音乐网站，网络Radio来源的歌曲。（可选）
5. 结合机器学习，人工智能的方法分析音乐风格特征并给予相似风格的歌曲，歌手推荐。（可选）
6. 支持在基本解码播放功能的基础上调整播放音效音质。(可选)



Readme Version 1.1

Fsp&Linton
