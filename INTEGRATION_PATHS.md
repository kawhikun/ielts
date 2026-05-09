# GitHub 整合路径

## 题卡数据

```text
assets/data/cards_cambridge_reading.json
assets/data/cards_zyz_reading_part1.json
assets/data/cards_zyz_reading_part2.json
assets/data/cards_cambridge_listening.json
assets/data/cards_highfreq_listening.json
assets/data/manifest.json
```

## 听力放哪里

听力题卡已经在主站包里：

```text
assets/data/cards_cambridge_listening.json
assets/data/cards_highfreq_listening.json
```

音频不放在主站包里。把音频小包解压到仓库根目录，保持：

```text
assets/audio/cambridge/book16/test1/section1.mp3
assets/audio/cambridge/book16/test1/section2.mp3
assets/audio/cambridge/book16/test1/section3.mp3
assets/audio/cambridge/book16/test1/section4.mp3
...
assets/audio/cambridge/book20/test4/section4.mp3
assets/audio/highfreq/P1/.../audio.mp3
assets/audio/highfreq/P2/.../audio.mp3
assets/audio/highfreq/P3/.../audio.mp3
assets/audio/highfreq/P4/.../audio.mp3
```

不要把 MP3 放进 `assets/data/`。
