# LISCOM v66.12 ZYZ Split + Slim 主站包（无音频）

本包基于 v66.11 继续优化：

- 做题流程仍然只在首页展示一次。
- 每张卡仍然是一道小题。
- 每张卡先展示题目和至少一句完整证据原文/听力原文，用户填写后再显示答案解析。
- 为方便 GitHub 上传，`cards_zyz_reading.json` 已改为两个小文件：
  - `assets/data/cards_zyz_reading_part1.json`
  - `assets/data/cards_zyz_reading_part2.json`
- 同时删除题卡 JSON 里页面不使用的历史冗余字段，减小主站包体积。

上传 GitHub Pages 时，保持目录结构不变即可。音频仍使用 v66.9 的分散音频包，解压到仓库根目录。
