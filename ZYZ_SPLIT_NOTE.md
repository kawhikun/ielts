# ZYZ Reading 文件拆分说明

原来的：

```text
assets/data/cards_zyz_reading.json
```

现在拆成：

```text
assets/data/cards_zyz_reading_part1.json
assets/data/cards_zyz_reading_part2.json
```

`assets/data/manifest.json` 已经更新，页面会自动加载这两个文件。
用户在页面上仍然只会看到一个筛选按钮：`ZYZ Reading`。

不要把两个 part 改名，也不要移动目录。
