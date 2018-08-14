##### demo测试了4种方式播放m3u8

1. videojs + videojs-contrib-hls.js  文档太少，较难摸索出最佳实践。
2. html5原生video控件 + hls.js  文档太少，较难摸索出最佳实践。
3. chplayer开源网页播放器,体验不错。
4. ckplayer收费的网页播放器。功能丰富。



运行：

1. 运行server 
   + `cd server`
   + `npm run i`
   + `npm run start`
2. 运行例子：
   + videojs + videojs-contrib-hls.js： `http://localhost:12321/my.videojs.html`
   + html5原生video控件 + hls.js： `http://localhost:12321/my.hls.html`
   + chplayer: `http://localhost:12321/chplayer.html` 
   + ckplayer官方例子: `http://localhost:12321/ckplayer.html` 