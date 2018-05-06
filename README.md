
Aria2GUI
===========

![UI](http://i.imgur.com/MEZqP9z.png)

## Features:

- 集成aria2c
- 多线程下载
- 未完成任务退出自动保存
- 支持网盘的aria2导出（需要浏览器插件支持）
- 支持PT/BT
- 在Badge显示整体下载速度（暂不能关闭）
- 任务完成通知（可关闭）

## Usage:

- 解压后拖到应用里面运行即可

## Tips:

- 使用Chrome浏览器可配合[YAAW-for-Chrome](https://github.com/acgotaku/YAAW-for-Chrome)插件接管浏览器的所有下载到aria2
- 使用Safari浏览器可配合[safari2aria](https://github.com/miniers/safari2aria)插件接管浏览器的所有下载到aria2
- 导出插件：[百度网盘](https://github.com/acgotaku/BaiduExporter)，[115网盘](https://github.com/acgotaku/115)，[迅雷离线](https://github.com/binux/ThunderLixianExporter)
- 网盘插件里面的User-Agent优先级高于客户端，所以修改客户端里面User-Agent不会影响导出下载的速度，默认伪装成Transmission/2.77是为了支持BT/PT
- 把同一服务器连接数的上限从16提高到了256，默认值256，单个任务最大线程数默认值相应改为256，新加入"max-tries" "retry-wait"两个启动项，为了下载某盘资源是获得更理想的下载速度。

## Download:

  [Releases](https://github.com/yangshun1029/aria2gui/releases)

## With special thanks to:  

- [Aria2](https://aria2.github.io)
- [YAAW](https://github.com/binux/yaaw)
- [MacGap](https://github.com/MacGapProject)
- [fakeThunder](https://github.com/MartianZ/fakeThunder)

## Contributors:  

  [Nick](https://github.com/yangshun1029)

## License

Aria2GUI is licensed under [MIT License](http://choosealicense.com/licenses/mit/) 
