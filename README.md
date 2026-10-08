# 谁是卧底 · 角色抽取

**教学定位：COE 章 → HRBP 章的过渡环节**（COE 讲完、进入第4章 HRBP 之前的开场热身/钩子游戏）。
用「谁是卧底」引出核心议题：**少数派 HRBP 如何在 COE 群体中找出彼此、HRBP 与 COE 的区别与关系**。

- 承载课程：人力资源管理前沿（第4章 HRBP）
- 词语设定：6 人 COE（平民）+ 2 人 HRBP（卧底），对应"少数 HRBP 混在 COE 群中"
- 线上地址：https://mingyuecressy.github.io/wodi-game/

## 用法
- **老师端**：部署网址后加 `?host=1` 生成牌局，复制学生链接并生成二维码
- **学生端**：扫码 → 点击自己抽到的座位号 → 私密显示「座位号 + 词语 + 平民/卧底」

## 一码一局
学生链接形如 `index.html#deck=1:civ,2:spy,...`，牌局编码在 URL 里，8 台手机读同一副牌，避免各抽各的导致卧底数量出错。其中 `civ`=平民（COE，6 人），`spy`=卧底（HRBP，2 人）。

## 改词
编辑 `index.html` 顶部 `CONFIG.words`：`civilian` 平民词(COE) / `spy` 卧底词(HRBP)。
