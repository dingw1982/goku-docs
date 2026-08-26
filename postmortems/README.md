# postmortems —— 内容不在这里

**复盘记录的唯一权威位置是 `goku-core` 仓库里的：**

```
goku-core/docs/复盘记录/
```

先读那里的 `README.md`（索引、编号约定、写法）。

---

## 为什么这个目录是空的

`goku-core/CLAUDE.md` 开头那条硬性要求（改 migration / seed / workspace
相关代码前必须先读复盘）曾经指向这个目录，但内容一直写在 core 仓库里。

**两个位置各自演进，结果是 6 份被 CLAUDE.md 和 `admin/system.py` 引用的
复盘全部丢失** —— 规则的结论还在 CLAUDE.md 正文里，原因和现场没了。

2026-08-26 已把 CLAUDE.md 的指向改到 core 仓库，并在那边的 README 里
记录了丢失清单与编号冲突。

**不要在这里新建复盘。** 写到 `goku-core/docs/复盘记录/`，从 0013 起编号。

---

## 如果复盘涉及多个仓库

仍然写在 `goku-core/docs/复盘记录/`，在标题和关键词里注明涉及的服务
（goku-router / goku-studio / goku-sdk）。一个位置、一套编号，
比"放对地方"重要得多 —— 这次丢记录就是分家分出来的。
