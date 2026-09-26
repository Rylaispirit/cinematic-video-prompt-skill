# 🎬 Cinematic Video Prompt Skill

**AI video prompt cheat sheet & Claude Skill for Veo 3, Google Flow, Kling, Sora, Runway, Hailuo, Luma, Midjourney** — camera angles, camera movement, cinematic lighting, composition, color grading, mood, and a ready-to-use prompt formula.

**Bộ từ điển prompt điện ảnh cho AI tạo video/ảnh** — 700+ thuật ngữ về góc máy, chuyển động camera, ánh sáng, bố cục, màu sắc, cảm xúc, có giải thích tiếng Việt và công thức ghép prompt dùng được ngay.

[English](#english) · [Tiếng Việt](#tiếng-việt)

---

## English

### What is this?

A **Claude Skill** (works with Claude Code, Claude Cowork and Claude.ai) that teaches the AI professional cinematography vocabulary so your text-to-video and text-to-image prompts stop being vague ("a nice cinematic scene") and start being precise ("medium close-up, low angle, slow dolly in, rim lighting, teal and orange grading").

It is model-agnostic: the vocabulary works for **Veo 3 / Google Flow, Kling, Sora, Runway Gen-4, Hailuo, Luma Dream Machine, Pika, Midjourney, Stable Diffusion, Flux, Nano Banana**, and any future model that reads English prompts.

### What's inside

| File | Content |
|---|---|
| `SKILL.md` | The skill itself: workflow, **prompt formula**, condensed keyword tables, **ready-made combos by video type**, mood → combo lookup, pre-flight checklist, **real-world lessons** on what AI video models commonly get wrong (section 8) |
| `references/01-camera-angles-and-movement.md` | 70+ camera angles & shot sizes, 60+ camera movements (dolly, arc, crane, FPV drone, dolly zoom, bullet time…) with "when to use" |
| `references/02-lighting.md` | 80+ lighting terms (golden hour, rim light, Rembrandt, chiaroscuro, volumetric, practical, neon…) |
| `references/03-composition.md` | 80+ composition rules (rule of thirds, leading lines, S-curve, negative space, repoussoir…) |
| `references/04-lens-technical-film.md` | Lenses, aperture, shutter, bokeh, flare, filters, film stocks, aspect ratios, color grading tech |
| `references/05-style-color-mood.md` | 100+ art styles, 80+ color palettes/grading, 100+ mood/emotion terms |
| `references/06-materials-weather-pose.md` | Materials & textures, weather & atmosphere, character poses |
| `examples/` | Worked prompt examples for common video types |

### The prompt formula

```
[Shot size + Angle], [Subject + appearance], [Specific action], [Setting + weather],
[Lighting], [Camera movement], [Style + color], [Mood], [Technical]
```

Example:

```
Medium close-up, low angle, a young woman in a red áo dài walks slowly through a rainy
Saigon alley at night, neon signs reflecting on wet asphalt, rim lighting from city lights,
slow dolly in, cinematic, teal and orange grading, melancholic mood, shallow depth of field,
35mm film grain
```

Rules baked into the skill: one camera movement per clip, one main action per clip, lighting must match weather/time of day, style ↔ color ↔ mood must point the same way, max ~8 technical keywords, keep character description identical across clips of the same story.

### Install

**Claude Code**

```bash
git clone https://github.com/Rylaispirit/cinematic-video-prompt-skill.git ~/.claude/skills/cinematic-video-prompt
```

Or per-project: clone into `.claude/skills/cinematic-video-prompt` inside your repo. Then just ask: *"write a Veo 3 prompt for a rainy night street scene"* — the skill loads automatically.

**Claude.ai / Cowork**

Zip the folder (`SKILL.md` must be at the root of the zip) and upload it under *Settings → Capabilities → Skills*.

**Any other AI tool (ChatGPT, Gemini, local LLM)**

Paste `SKILL.md` as a system prompt / custom instruction. The reference files can be pasted on demand when you need deeper vocabulary.

### Usage examples

```
> Write a Kling prompt: a monk meditating on a mountain at dawn, epic feeling
> Make this prompt more cinematic: "a cat sitting on a window"
> Give me 3 clips for a product video of a ceramic mug, consistent style
> Which lighting should I use for a horror scene in an old house?
> Explain what "dolly zoom" does and when to use it
```

The skill answers with an English prompt in a code block, plus a one-line explanation of the choices (in the user's language).

### Why a skill instead of a prompt list?

A raw list of 700 terms is hard to use. The skill adds the layer that matters: **which term to pick for which feeling**, how to **order** them, what **not to combine**, and **ready combos** for storytelling videos, product videos, food, talking-head training videos, night street scenes, travel, action and vertical Reels/TikTok.

### Contributing

PRs welcome — especially new camera-movement "golden prompts" that you have verified work well on a specific model (please name the model).

### License

MIT — free to use, modify, and share.

---

## Tiếng Việt

### Đây là gì?

Một **Claude Skill** (dùng được với Claude Code, Claude Cowork, Claude.ai) giúp AI hiểu đúng ngôn ngữ quay phim chuyên nghiệp. Thay vì prompt mơ hồ kiểu "một cảnh đẹp điện ảnh", bạn sẽ có prompt chính xác kiểu "medium close-up, low angle, slow dolly in, rim lighting, teal and orange grading".

Dùng được cho mọi model tạo video/ảnh đọc prompt tiếng Anh: **Veo 3 / Google Flow, Kling, Sora, Runway, Hailuo, Luma, Pika, Midjourney, Stable Diffusion, Flux, Nano Banana**…

### Có gì bên trong?

- **`SKILL.md`** — phần AI đọc: quy trình làm việc, **công thức ghép prompt**, bảng từ khóa rút gọn theo 11 nhóm, **combo sẵn theo loại video** (video kể truyện, kinh dị, cổ trang/tu tiên, sản phẩm, ẩm thực, đào tạo talking head, đường phố đêm, du lịch, hành động, Reels dọc), bảng **cảm xúc → combo**, checklist trước khi đưa prompt, và **bài học thực chiến** về những lỗi model AI hay mắc (mục 8).
- **`references/`** — bộ tham chiếu đầy đủ 700+ thuật ngữ, mỗi thuật ngữ có giải thích tiếng Việt dễ hiểu và gợi ý khi nào dùng: góc máy & chuyển động camera, ánh sáng, bố cục, ống kính & chất phim, phong cách & màu & cảm xúc, chất liệu & thời tiết & tư thế.
- **`examples/`** — ví dụ prompt hoàn chỉnh cho các loại video hay gặp.

### Cài đặt

**Claude Code** — chạy lệnh:

```bash
git clone https://github.com/Rylaispirit/cinematic-video-prompt-skill.git ~/.claude/skills/cinematic-video-prompt
```

(hoặc clone vào `.claude/skills/cinematic-video-prompt` trong thư mục dự án). Sau đó chỉ cần nói: *"viết prompt Veo 3 cảnh phố đêm mưa"* — skill tự bật.

**Claude.ai / Cowork** — nén thư mục thành file zip (file `SKILL.md` phải nằm ngay gốc zip), vào *Settings → Capabilities → Skills* và tải lên.

**ChatGPT / Gemini / tool khác** — dán nội dung `SKILL.md` vào system prompt hoặc custom instruction. Khi cần tra sâu thì dán thêm file trong `references/`.

### Cách dùng

```
> Viết prompt Kling: nhà sư thiền trên núi lúc bình minh, cảm giác hùng vĩ
> Làm prompt này điện ảnh hơn: "a cat sitting on a window"
> Cho tôi 3 clip video sản phẩm ly gốm, giữ nhất quán style
> Cảnh kinh dị trong nhà cổ nên dùng ánh sáng gì?
> Dolly zoom là gì, dùng khi nào?
```

Skill trả về prompt tiếng Anh trong code block (copy được ngay) kèm một dòng giải thích tiếng Việt vì sao chọn góc máy / ánh sáng / chuyển động đó.

### Vì sao làm thành skill thay vì chỉ để danh sách?

Danh sách 700 thuật ngữ rất khó tra khi đang làm việc. Skill bổ sung phần quan trọng nhất: **chọn từ nào cho cảm giác nào**, **xếp thứ tự** ra sao, **không được ghép gì với gì** (ví dụ "golden hour" + "heavy downpour"), và **combo có sẵn** cho từng loại video để bạn chỉ cần thay chủ thể.

### Đóng góp

Hoan nghênh pull request — đặc biệt là các "golden prompt" chuyển động camera bạn đã thử và thấy chạy tốt trên một model cụ thể (ghi rõ model).

### Giấy phép

MIT — dùng, sửa, chia sẻ tự do.

---

*Keywords: AI video prompt, cinematic prompt, Veo 3 prompt, Kling prompt, Sora prompt, Runway prompt, text to video prompt guide, camera movement prompts, lighting prompts, prompt engineering for video, Claude skill, prompt tạo video AI, prompt Veo 3, prompt Kling, từ điển prompt điện ảnh, hướng dẫn prompt video AI.*
