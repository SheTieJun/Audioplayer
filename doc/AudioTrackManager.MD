# AudioTrackManager :PCM文件播放
暂时不支持进度显示

```java
 //必须初始化 
AudioTrackManager.getInstance().setContext(getActivity(), getPathname()); //初始化
AudioTrackManager.getInstance().isStartPlay() //是否正在播放
AudioTrackManager.getInstance().startThread(); //开始播放
AudioTrackManager.getInstance().stopThread(); // 停止播放
              
```



