# English Practice

Education Hub 的英语互动练习模块：词汇、核心语法和造句输出。

在线入口：`/education_hub/apps/english/`

## 模块边界

- `index.html`：练习入口与每日学习顺序。
- `vocabulary.html`：2000 核心词汇的复习与掌握标记。
- `grammar.html`：12 个核心语法点与章节进度。
- `sentence_practice.html`：60 个造句练习、朗读和录音。
- `optional/anki_vocabulary.csv`：可选的 Anki 词表。
- `source/`：从原 `lemon_english` 保存的 Markdown 源材料，仅作内容参考。

浏览器数据使用 `education-hub:english:*` 键名保存，避免与其他 Education Hub 模块冲突；首次访问会兼容迁移旧 `lemon_english` 的主题和章节进度。
