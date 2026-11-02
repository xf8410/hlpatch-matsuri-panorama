# hlpatch-matsuri-panorama

11-01/02 五个新仓库的全景整理页（单 main 分支）：hlpatch 工具线 + 骏大祭数据链 + 剧本15 反汇编档案。

- **入口**：GitHub Pages 上的 `index.html`（响应式，手机/电脑同一页自适应）
- **内容**：五仓总览 → 逐仓详情 → **汇编专区**（4 个地址的"文字/代码/效果"三段式 + capstone 5.0.9 独立复核结论）→ 反汇编批次 01-07 → 复验路径
- **汇编复核结果**：核心断言全部通过；发现 2 处文档内伤（README 旧手解值未同步、GET-GAIN 文档错拿 ctor 段），详见页面第 3 节
- **纪律**：no-ai-coauthor 剥名闸已接入；原五仓未做任何改动

| 原仓库 | 说明 |
|---|---|
| xf8410/uma-single-mode-disasm | 剧本15 反汇编与运行时实测档案（17 提交） |
| xf8410/hlpatch-readall-spec | hlpatch 全格式可读改造规格书 + disasm 批次 01-07（12 提交） |
| xf8410/hlpatch-reasoning-log | 推理过程存档（2 提交） |
| xf8410/ura-replay | hlpatch SO + 落盘回放（10 提交） |
| xf8410/matsuri-capture | 骏大祭真机数据接收端（6 提交） |
