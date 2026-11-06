# YoYo 小人正文配图 Skill

> 把中文文章里的判断、流程、状态和隐喻，变成 YoYo 小人参与的白底手绘正文配图。
>
> 16:9 横版 | YoYo IP | 膝盖长度黄裙子 | 红棕短发 | 少量红橙蓝批注

视觉风格继承 [Ian Xiaohei Illustrations](https://github.com/helloianneo/ian-xiaohei-illustrations)，IP 角色替换为 TeacherYo 的 YoYo 小人。

这是独立 skill 仓库：`SKILL.md` 在仓库根目录，skills.sh 和会克隆仓库的 agent 可以直接读到。

Gemini 这类聊天产品打不开 GitHub 仓库页面。给它们看这一页，规范和角色图都在页面正文里：

https://qiuyue-lab.github.io/yoyo-illustrations/

## 安装

```bash
npx skills add qiuyue-lab/yoyo-illustrations
```

或链到本机 Cursor skills：

```bash
git clone https://github.com/qiuyue-lab/yoyo-illustrations.git
mkdir -p ~/.cursor/skills
ln -s "$PWD/yoyo-illustrations" ~/.cursor/skills/yoyo-illustrations
```

## 使用

让 Cursor Agent 读取 `SKILL.md`，或直接说：

```
用 yoyo-illustrations skill，为这篇公众号文章设计并生成 4 张 YoYo 小人正文配图。
```

更多示例见 [examples/prompts.md](examples/prompts.md)。

## 定稿角色样例

`assets/examples/yoyo-character-calibration-v5.png`

## 目录结构

```
yoyo-illustrations/
├── SKILL.md
├── README.md
├── references/
│   ├── style-dna.md
│   ├── yoyo-ip.md
│   ├── prompt-template.md
│   ├── composition-patterns.md
│   └── qa-checklist.md
├── examples/
│   └── prompts.md
└── assets/
    ├── reference-photo.png
    └── examples/
        └── yoyo-character-calibration-v5.png
```
