# ardour
오픈소스 사운드 편집툴 https://ardour.org 에 관련된 정보를 표기하는 리포지터리입니다.

### Convert audio file using ffmpeng

#### wav to mp3
```
$ ffmpeg -i web_bgm.wav -codec:a libmp3lame -qscale:a 2 web_bgm.mp3
```

#### wav to ogg
```
$ ffmpeg -i web_bgm.wav -c:a libvorbis -qscale:a 3 web_bgm.ogg
```

### Market
- https://www.premiumbeat.com
- 비용 : 비상업용 6만원선, 상업용 20만원선
