# 音频上传说明（GitHub Pages）

主站包不包含 MP3，只包含听力题卡 JSON。听力题卡已经在：

```text
assets/data/cards_cambridge_listening.json
assets/data/cards_highfreq_listening.json
```

## Cambridge 16-20 音频上传位置

把每个 Cambridge 音频小包解压到仓库根目录，不要改目录层级。最终必须是：

```text
assets/audio/cambridge/book16/test1/section1.mp3
assets/audio/cambridge/book16/test1/section2.mp3
assets/audio/cambridge/book16/test1/section3.mp3
assets/audio/cambridge/book16/test1/section4.mp3
...
assets/audio/cambridge/book20/test4/section1.mp3
assets/audio/cambridge/book20/test4/section2.mp3
assets/audio/cambridge/book20/test4/section3.mp3
assets/audio/cambridge/book20/test4/section4.mp3
```

例如 Book 18 Test 3 Part 2：

```text
assets/audio/cambridge/book18/test3/section2.mp3
```

## 高频听力音频上传位置

按题卡里的 `audioSrcV6614` 路径放。常见形式：

```text
assets/audio/highfreq/P1/某个听力标题/audio.mp3
assets/audio/highfreq/P2/某个听力标题/audio.mp3
assets/audio/highfreq/P3/某个听力标题/audio.mp3
assets/audio/highfreq/P4/某个听力标题/audio.mp3
```

不要把 MP3 放进 `assets/data/`，那里只放 JSON。

## GitHub 网页上传操作

1. 打开 GitHub 仓库。
2. 进入或新建 `assets/audio/`。
3. Cambridge 音频按 `cambridge/bookXX/testX/sectionX.mp3` 上传。
4. 高频音频按 `highfreq/P1/.../audio.mp3` 上传。
5. 上传后进入任意听力卡，播放器下方显示的“路径”能在仓库中找到同名文件，就能播放。

## 本地检查

```bash
python3 -m http.server 8000
```

然后打开：

```text
http://localhost:8000
```
