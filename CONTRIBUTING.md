# Contributing to muse-identities

Thanks for sharing your Muse persona! This guide covers everything you need.

## What we accept

A single Markdown file describing **one** Muse persona, with the identity fields filled in:

- **Name** — what you call your Muse
- **Character** — who it is (an AI? a familiar? something stranger?)
- **Vibe** — how it comes across (sharp, warm, calm, playful…)
- **Emoji** — its signature emoji (optional but fun)
- **Avatar** — an image for the gallery (optional, see below)

Plus one short paragraph: *why does this persona work? What is it good at?*

## Avatars 🖼️

Make your persona stand out in the gallery:

- Add your image as `avatars/<your-persona-name>.svg` (preferred — crisp at any size) or `.png`.
- Square works best; it displays at 72×72 in the gallery.
- List it in your identity file: `- **Avatar:** \`avatars/<your-persona-name>.svg\``
- Keep it tasteful: no copyrighted characters, no photos of real people.
- No image? No problem — your emoji represents you.

## How to submit

### Option A — Pull Request (recommended)

1. Fork this repo.
2. Copy `identities/_template.md` to `identities/<your-persona-name>.md`
   (use lowercase, hyphens instead of spaces, e.g. `midnight-coder.md`).
3. Fill in the fields and the "Why this works" paragraph.
4. *(Optional)* add your avatar to `avatars/` and reference it.
5. Add yourself as the contributor at the bottom.
6. Open a PR — we will merge it quickly.

### Option B — Reply to a promo post

Just drop your fields (name / character / vibe / emoji, plus an avatar image if you have one) in a comment/reply. A maintainer will create the file for you and credit you as the author.

## Ground rules

- **One persona per file.** Got three great Muses? Three files.
- **Describe the AI, not yourself.** No names, emails, or personal data.
- **Keep it real.** Only share personas you actually use and like.
- **Be kind.** No hateful, harassing, or deceptive personas.
- File names: lowercase, hyphens, `.md` extension.

## What makes a great submission?

The best entries have a *distinct point of view* — you can feel the personality in two lines. A sentence or two about *when this persona shines* helps others decide to try it.

---

## 中文版

### 投稿方式

**方式一：提 PR（推荐）**

1. Fork 本仓库
2. 复制 `identities/_template.md` 为 `identities/<你的人设名>.md`（小写、用连字符，如 `midnight-coder.md`）
3. 填好字段 + 一段"为什么这个人设好用"
4. （可选）把头像图片放进 `avatars/` 并在文件中引用
5. 在底部署名，开 PR 即可

**方式二：在宣传帖下回复**

直接回复字段（名字 / 性格 / 风格 / 表情，有头像图也一起发），我们帮你上传并署名。

### 头像规范 🖼️

- 路径：`avatars/<你的人设名>.svg`（推荐，任意尺寸都清晰）或 `.png`
- 正方形最好，画廊里按 72×72 展示
- 不要用有版权的角色、真人照片；没有头像也没关系，表情符号会代表你

### 注意事项

- 一个文件只放一个人设
- 描述的是你的 AI，不是你本人——不要放个人隐私信息
- 只分享你真实在用、觉得好的人设
