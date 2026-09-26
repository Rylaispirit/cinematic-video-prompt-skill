---
name: cinematic-video-prompt
description: Dùng khi viết hoặc sửa prompt tạo video/ảnh AI (Veo 3, Google Flow, Kling, Runway, Sora, Midjourney, Hailuo, Luma): từ vựng chuẩn về góc máy, chuyển động camera, ánh sáng, bố cục, phong cách, màu, cảm xúc công thức ghép prompt, và bài học thực chiến về lỗi model AI hay gặp. Use when writing or fixing AI video/image prompts — cinematic camera angles, camera movement, lighting, composition, style, color grading, mood, a prompt formula, and real-world lessons on common AI video model failures.
---

# Cinematic Video Prompt — skill bổ trợ tạo video/ảnh AI

Skill này là "từ điển kỹ thuật quay phim" để AI hiểu đúng ý về ánh sáng, góc máy, chuyển động. Dùng kèm với skill/pipeline tạo video khác (video truyện, video sản phẩm, video đào tạo...). Prompt cuối cùng luôn viết bằng **tiếng Anh**, thuật ngữ giữ nguyên như bảng dưới.

Cần tra sâu hơn (700+ thuật ngữ có giải thích): xem thư mục `references/`.

## 1. Cách làm việc

1. Hỏi (hoặc suy ra từ ngữ cảnh) 3 thứ: **cảnh gì** (chủ thể + hành động), **cảm xúc muốn có**, **dùng cho tool nào** (video hay ảnh tĩnh).
2. Ghép prompt theo công thức mục 2. Mỗi khối chọn **1–2 từ khóa**, không nhồi.
3. Kiểm tra bằng checklist mục 6 rồi mới đưa prompt.
4. Nếu người dùng chỉ đưa ý tưởng mơ hồ ("cảnh buồn buồn", "cho ngầu hơn"), tra mục 5 (cảm xúc → combo) để đề xuất.
5. Trước khi viết prompt phức tạp (nhiều nhịp, loài vật lạ, sự kiện, cảm xúc dồn), đọc lại mục 8 — những điều model AI hay làm sai.

## 2. Công thức ghép prompt

**Video (5–10 giây/clip):**
```
[Shot size + Angle], [Chủ thể + ngoại hình], [Hành động cụ thể], [Bối cảnh + thời tiết], [Ánh sáng], [Camera movement], [Style + màu], [Mood], [Kỹ thuật]
```
Ví dụ: `Medium close-up, low angle, a young woman in a red áo dài walks slowly through a rainy Saigon alley at night, neon signs reflecting on wet asphalt, rim lighting from city lights, slow dolly in, cinematic, teal and orange grading, melancholic mood, shallow depth of field, 35mm film grain`

**Ảnh tĩnh:** bỏ khối Camera movement, thêm Composition và Lens.

Nguyên tắc:
- Mỗi clip video chỉ **1 chuyển động camera** và **1 hành động chính**. Muốn nhiều hơn → tách clip.
- Chủ thể + hành động đứng trước; thuật ngữ kỹ thuật đứng sau.
- Thời tiết/ánh sáng phải khớp nhau (không "golden hour" + "heavy downpour").
- Với video truyện: tả nhân vật nhất quán ở mọi clip (tuổi, tóc, trang phục, màu chủ đạo) rồi mới đổi hành động.

## 3. Bảng từ khóa rút gọn

### 3.1 Shot size & góc máy (Angles)
| Từ khóa | Dùng khi |
|---|---|
| Extreme wide shot / Establishing shot | Mở cảnh, giới thiệu bối cảnh, chủ thể rất nhỏ |
| Wide shot / Full body shot | Thấy toàn thân + môi trường |
| Medium shot | Từ thắt lưng lên, đối thoại thường |
| Medium close-up (MCU) | Từ vai lên, biểu cảm |
| Close-up / Reaction shot | Gương mặt, cảm xúc mạnh |
| Extreme close-up / Macro | Mắt, tay, chi tiết kết cấu |
| Eye-level | Trung lập, tự nhiên |
| Low angle / Hero shot | Chủ thể mạnh mẽ, quyền lực |
| High angle | Chủ thể nhỏ bé, yếu thế |
| Worm's-eye view | Từ sát đất hất lên, hùng vĩ |
| Bird's-eye / Top-down / Overhead flat lay | Nhìn thẳng từ trên xuống; flat lay cho ẩm thực, sản phẩm |
| Dutch tilt / Canted angle | Bất ổn, căng thẳng |
| Over-the-shoulder | Đối thoại, góc nhìn theo nhân vật |
| POV shot | Góc nhìn thứ nhất |
| Three-quarter view | Chân dung nịnh mắt nhất |
| Side profile | Nhìn nghiêng 90°, bí ẩn/trang trọng |

### 3.2 Chuyển động camera (video)
| Từ khóa | Cảm giác / dùng khi |
|---|---|
| Static shot / Locked-off | Tĩnh, trang trọng, talking head |
| Slow dolly in | Tiến gần: tập trung, nhận ra điều gì, thân mật |
| Slow dolly out / pull back to reveal | Lùi ra: cô đơn, kết cảnh, lộ bối cảnh |
| Slow pan left/right | Quét phong cảnh, dõi theo ánh mắt |
| Tilt up / Tilt down | Ngước lên: tôn vinh, to lớn; cúi xuống: yếu thế |
| Tracking shot / Side tracking | Đi song song chủ thể đang di chuyển |
| Following shot / Leading shot | Theo sau lưng / đi lùi trước mặt |
| Arc shot / 360 orbit | Xoay quanh chủ thể: hero moment, thời trang, lãng mạn |
| Crane shot up / Jib up | Nâng từ thấp lên cao, hùng vĩ, kết cảnh |
| Slow zoom in/out | Ống kính zoom, không gian phẳng hơn dolly |
| Crash zoom / Snap zoom | Zoom cực nhanh: hài, sốc, hành động |
| Dolly zoom / Vertigo effect | Choáng váng, nhận thức đột ngột |
| Whip pan | Chuyển cảnh nhanh, hỗn loạn |
| Handheld, slight shake | Chân thực, tài liệu, cãi vã |
| Shaky cam | Hỗn loạn, cháy nổ |
| Steadicam / Gimbal smooth | Mượt như bay: MV, thời trang, mơ |
| FPV drone / Aerial flyover | Bay tốc độ cao, du lịch, mạo hiểm |
| Drone dive / Nosedive | Lao từ trời xuống, chuyển toàn → cận |
| Fly-through gap | Bay xuyên qua cửa sổ, khe hẹp |
| Top-down tracking | Nhìn thẳng từ trên, theo nhân vật |
| Hyperlapse | Tua nhanh thời gian + di chuyển |
| Bullet time | Thời gian ngưng, camera xoay quanh |
| Underwater drift / Floating camera | Bồng bềnh, mộng mơ |
| Reveal shot, sliding past foreground object | Lướt qua vật tiền cảnh để lộ cảnh chính |
| Continuous long take | Một cú máy liền mạch |

### 3.3 Ánh sáng (Lighting)
| Từ khóa | Cảm giác |
|---|---|
| Golden hour / Magic hour | Ấm, thơ mộng |
| Blue hour | Xanh huyền ảo, chạng vạng |
| Soft light / Window light / Softbox | Mềm, tình cảm, chân dung |
| Hard light / Direct midday sun | Gắt, bóng sắc, kịch tính |
| Rim lighting / Edge lighting | Viền sáng tách chủ thể khỏi nền |
| Backlighting + lens flare | Ngược sáng, điện ảnh |
| Volumetric lighting / God rays / Crepuscular rays | Tia sáng thấy rõ trong không khí |
| Rembrandt lighting | Chân dung cổ điển, tam giác sáng dưới mắt |
| Chiaroscuro / Low-key lighting | Tương phản cực mạnh, u tối |
| High-key lighting | Sáng, sạch, tươi |
| Neon glow / Neon lights | Cyberpunk, đêm phố |
| Practical lighting (lamp, candle, screen) | Nguồn sáng trong cảnh, chân thực |
| Light from a single candle | Cổ kính, bí ẩn, tương phản tối đa |
| Dappled light | Nắng lốm đốm qua tán lá |
| Silhouette | Bóng đen trên nền sáng |
| Under-lighting | Rùng rợn, ma quái |
| Gobo lighting / Window shadow pattern | Bóng hoa văn đổ lên tường |
| Street lamp glare / Light halos | Đêm đô thị, quầng sáng |
| Overcast / Flat light | Không bóng đổ, màu trung thực |
| Tungsten (2700K) / Daylight (6500K) | Ấm vàng / trắng trung tính |
| Teal key with warm fill | Phối lạnh-ấm kiểu điện ảnh |
| Screen light on face | Bối cảnh công nghệ, đêm khuya |

### 3.4 Bố cục (Composition) — chủ yếu cho ảnh tĩnh & khung đầu clip
rule of thirds · centered composition · symmetry (hoặc broken symmetry) · leading lines · S-curve · diagonal lines · negative space · framing within a frame · foreground interest · depth layers (foreground/midground/background) · rule of odds · fill the frame · isolation of subject · look space / lead room · low horizon (nhấn trời) / high horizon (nhấn đất) · vanishing point · repoussoir (vật tối tiền cảnh đẩy sâu) · juxtaposition (đối lập ý tưởng).

### 3.5 Ống kính & kỹ thuật (Lens & Technical)
| Nhóm | Từ khóa hay dùng |
|---|---|
| Tiêu cự | 24mm (rộng, méo nhẹ), 35mm (đường phố, kể chuyện), 50mm (tự nhiên), 85mm (chân dung), telephoto compression (nén không gian) |
| Xóa phông | shallow depth of field, f/1.4, bokeh, anamorphic oval bokeh |
| Sâu nét | deep focus, hyperfocal, f/11 |
| Chuyển động | motion blur, long exposure light trails, shutter angle 180°, 1/8000s freeze action |
| Flare | lens flare, anamorphic lens flare (vệt ngang xanh), sun star effect |
| Chất phim | 35mm film grain, Kodak Portra 400, CineStill 800T, Super 8, VHS look, black and white high contrast |
| Filter | Black Pro Mist (mềm, quầng sáng), polarizer, halation |
| Máy | Shot on Arri Alexa / RED, Sony A7, iPhone mobile photography style |
| Chất lượng | 8K, hyperdetailed, photorealistic, Unreal Engine 5 render, IMAX quality |
| Khung hình | 2.35:1 cinemascope, 16:9, 9:16 vertical (TikTok/Reels), 1:1 |
| Hiệu ứng | tilt-shift miniature, double exposure, fisheye, rack focus, split diopter, dolly zoom |

### 3.6 Phong cách nghệ thuật (Style)
**Ảnh thật:** cinematic · hyperrealistic · photorealistic · street photography · documentary · food photography · film noir · authentic mobile phone photography.
**Vẽ/hoạt hình:** anime style · Ghibli style · watercolor · ink wash painting (thủy mặc) · concept art · cel shading · line art · pencil sketch · pixel art · vector art · claymation · stop-motion · low poly · book illustration.
**Trường phái:** fantasy art · surrealism · minimalism · pop art · art deco · art nouveau · baroque · renaissance painting · ukiyo-e · expressionism · bauhaus.
**Thẩm mỹ:** cyberpunk · steampunk · synthwave · vaporwave · neon noir · glitch art · isometric · infographic · blueprint · cross-section / exploded view (kỹ thuật, giải thích).

### 3.7 Màu sắc (Color)
| Từ khóa | Cảm giác |
|---|---|
| Teal and orange grading | Điện ảnh Hollywood |
| Warm palette / Cool palette | Ấm áp, năng lượng / tĩnh, buồn, bí ẩn |
| Muted / Desaturated | Trầm, hoài cổ, nghiêm túc |
| Vibrant / Hyper-saturated | Rực rỡ, vui, quảng cáo |
| Pastel colors | Nhẹ nhàng, ngọt, thuần khiết |
| Monochromatic | Một màu nhiều sắc độ, nghệ thuật |
| Monochrome with spot color | Đen trắng + 1 màu nổi bật |
| Earth tones | Mộc mạc, tự nhiên |
| Jewel tones | Sang trọng, đậm đà |
| Neon palette (pink/cyan) | Cyberpunk, đêm |
| Sepia / Faded film colors | Ảnh cũ, ký ức |
| Golden hues | Sang trọng, cổ điển, linh thiêng |
| Lifted blacks | Vùng tối bị nâng, cảm giác phim mờ |
| Duotone | Đồ họa, poster |
| Complementary / Analogous colors | Tương phản mạnh / hài hòa êm |

### 3.8 Cảm xúc (Mood) — mỗi prompt 1–2 từ
serene · peaceful · melancholic · nostalgic · joyful · energetic · mysterious · ominous · eerie · tense · suspenseful · dramatic · intense · hopeful · triumphant · majestic · awe · intimate · romantic · cozy · lonely / isolation · dreamy · surreal · whimsical · solemn · gloomy · menacing · contemplative · playful · ethereal · haunting · urgent · liberating · claustrophobic · spiritual.

### 3.9 Thời tiết & không khí (Weather & Atmosphere)
foggy / misty · ground fog · heavy downpour · drizzle · rainy night, wet asphalt reflections, puddles · snowing · blizzard · overcast · stormy sky, lightning · sun-drenched · heat haze · dust storm · morning dew · sea mist · starry night · moonlit night · aurora · smoke-filled air · God rays through dusty air · cloud inversion · calm before the storm · monsoon rain · red sunset dust.

### 3.10 Chất liệu & bề mặt (Materials) — khi cần tả sản phẩm/chi tiết
matte · glossy · brushed metal · chrome · polished wood · aged wood grain · worn leather · velvet · silk (flowing fabric) · frosted glass · translucent · iridescent · holographic · polished marble · rusted iron · cracked earth · wet slick surface · subsurface scattering (da, sáp) · PBR materials · condensation droplets · carbon fiber · hammered metal · mother of pearl.

### 3.11 Tư thế (Pose) — cho nhân vật
**Tĩnh/cảm xúc:** contemplative pose · looking away pensive · looking over shoulder · leaning against wall · hands in pockets · sitting on floor · hugging self · head resting on hand · looking down at hands · arms crossed · hands clasped (lo lắng) · cowering (sợ).
**Mạnh/động:** power pose · hands on hips · action pose · mid-action · striding · running towards camera · jumping suspended · arms outstretched · reaching out · defiant pose · leaning into wind.
**Chân dung/thời trang:** S-curve pose · weight shift · three-quarter turn · direct gaze · candid pose · walking away · silhouette pose · tucking hair behind ear · slight smile.

## 4. Combo sẵn theo loại video

| Loại video | Combo gợi ý |
|---|---|
| Video kể truyện (cảm xúc, hồi tưởng) | Medium close-up · soft window light hoặc golden hour · slow dolly in · muted warm palette, lifted blacks · melancholic/nostalgic · 35mm film grain, shallow DOF |
| Truyện kinh dị / huyền bí | Low angle hoặc Dutch tilt · single candle / under-lighting / fog · slow pan hoặc handheld slight shake · cool desaturated, deep shadows · eerie, ominous · ground fog |
| Truyện cổ trang / tu tiên | Wide establishing shot · God rays, dappled light · crane shot up / arc shot · ink wash painting hoặc cinematic fantasy art · majestic, ethereal · mist, mountain clouds |
| Video sản phẩm (e-commerce) | Product on clean surface · softbox / studio lighting, specular highlights · slow 360 orbit hoặc slow dolly in · vibrant, clean, high-key · macro detail shot cho chất liệu |
| Video ẩm thực | Overhead flat lay + close-up · warm window light, steam visible · slow pan hoặc slow push in · warm palette, food photography · cozy, appetizing |
| Video đào tạo / talking head | Medium shot, eye-level · two-point lighting hoặc softbox · static / locked-off, thỉnh thoảng slow zoom in · neutral color, clean · professional, calm · 16:9 |
| Video đường phố / đô thị đêm | Low angle · neon glow, wet reflections, rim light from city lights · side tracking shot · neon noir, teal & magenta · confident, mysterious · rainy night |
| Phong cảnh / du lịch | Extreme wide shot, low horizon · golden hour hoặc blue hour · FPV drone / aerial flyover / hyperlapse · vibrant HDR · awe, majestic |
| Hành động | Wide → close-up cắt nhanh · hard light, high contrast · tracking shot, whip pan, crash zoom · teal & orange · intense · motion blur, shutter angle 180° |
| Reels/TikTok dọc | 9:16 vertical · practical lighting tự nhiên · handheld slight shake · authentic mobile phone photography style · candid |

## 5. Cảm xúc → combo nhanh

| Muốn cảm giác | Góc máy | Ánh sáng | Camera | Màu |
|---|---|---|---|---|
| Buồn, cô đơn | high angle, wide, chủ thể nhỏ | overcast, blue hour | slow dolly out | cool, desaturated |
| Mạnh mẽ, quyền lực | low angle, hero shot | rim light, hard light | slow dolly in hoặc arc shot | high contrast |
| Ấm áp, hoài niệm | medium shot | golden hour, dappled light | static hoặc slow pan | warm, faded film |
| Bí ẩn, sợ | Dutch tilt, low angle | low-key, single source, fog | handheld, slow push in | cool, deep shadows |
| Hùng vĩ, kinh ngạc | worm's-eye, extreme wide | God rays, volumetric | crane up, drone flyover | vibrant HDR |
| Thân mật, lãng mạn | close-up, over-the-shoulder | soft light, candle, bokeh | slow dolly in | warm pastel |
| Năng động, vui | eye-level, medium | sun-drenched, high-key | tracking, whip pan | vibrant, saturated |
| Mơ màng, siêu thực | any + soft focus | backlit, haze | floating camera, slow | pastel, dreamy glow |

## 6. Checklist trước khi đưa prompt

- [ ] Có chủ thể + hành động cụ thể (không chỉ toàn thuật ngữ)?
- [ ] Chỉ 1 chuyển động camera và 1 shot size cho mỗi clip?
- [ ] Ánh sáng ↔ thời tiết ↔ thời điểm trong ngày không mâu thuẫn?
- [ ] Style ↔ màu ↔ mood cùng hướng (không "Ghibli" + "hyperrealistic")?
- [ ] Tối đa ~8 từ khóa kỹ thuật; bỏ từ trùng nghĩa?
- [ ] Tỷ lệ khung hình phù hợp nền tảng (9:16 dọc / 16:9 ngang)?
- [ ] Video truyện: mô tả nhân vật giống hệt các clip trước?
- [ ] Clip nhiều nhịp: đã chia khối theo mốc giây và giữ **≤3–5 nhịp**? (mục 8.1, 8.3)
- [ ] Muốn liền mạch → có ghi `single continuous shot, no cuts`? Muốn cắt → có ghi rõ **số shot** + tổng giây? (mục 8.2)
- [ ] Loài vật / vật thể / phong cách lạ: đã **tả từng bộ phận**, không chỉ gọi tên? (mục 8.7)
- [ ] Cảm xúc mạnh: có viết thành **chuỗi nhịp theo thứ tự** + câu cấm để model khỏi diễn quá tay? (mục 8.6)
- [ ] Cần hình sạch: đã ghi `no subtitles, no on-screen text, no watermark`? (mục 8.9)
- [ ] Cần negative prompt (nếu tool hỗ trợ): `blurry, distorted face, extra fingers, text, watermark, low quality`?

## 7. Định dạng trả lời

Khi được nhờ viết prompt, trả về:
1. **Prompt tiếng Anh** trong code block (copy được ngay).
2. Một dòng tiếng Việt giải thích các lựa chọn chính (góc máy, ánh sáng, chuyển động → tạo cảm giác gì).
3. Nếu là chuỗi clip: đánh số từng clip, ghi rõ khối nào giữ nguyên (nhân vật, style, màu) và khối nào đổi (hành động, camera).

## 8. Bài học thực chiến — điều model AI hay làm sai (và cách chống)

Đây là những điều rút ra khi **xem video kết quả** đặt cạnh prompt gốc (đối chiếu ~1100 prompt + 65 video mẫu của các model video AI đời mới: Seedance, Veo, Kling, Sora...). Mức độ khác nhau tùy model, nhưng hầu hết đúng chung. Cứ gen thử 1 clip ngắn để kiểm trước khi làm hàng loạt.

### Cấu trúc prompt

**8.1 — Chia khối theo mốc giây là cách bám kịch bản tốt nhất.** Với clip có nhiều nhịp, viết theo mốc giây, mỗi khối ghi: cỡ cảnh + hành động + biểu cảm (+ âm thanh nếu tool tự sinh tiếng). Model lệch khoảng 1–3 giây, chấp nhận được. Khuôn cho clip 10 giây:
```
{STYLE}. {CHARACTER}.
0-4s: <shot size + angle>, <hành động 1>, <chuyển động nền: gió / cánh hoa / tàn lửa>.
4-10s: <hành động 2 hoặc reveal>, camera <1 chuyển động>.
No subtitles, no on-screen text, no watermark.
```

**8.2 — Muốn mấy shot thì ghi rõ SỐ shot + tổng giây.** `8 hard-cut shots, total 20s` ra đúng 8 shot đúng thứ tự. Ngược lại, muốn một cú máy liền mạch thì phải ghi thẳng `single continuous shot, no cuts` — nếu không, tả kiểu "máy đi qua cửa rồi kéo lên" dễ bị model tự cắt thành nhiều shot.

**8.3 — Đừng nhồi.** Danh sách 11 món model chỉ hiện 4–5; 9 cảnh trong 18 giây thì rớt mất cảnh. Clip 10 giây: **tối đa 3–5 nhịp**. Muốn nhiều hơn → tách clip.

**8.4 — Thông số kỹ thuật bằng số thường bị bỏ qua.** Ghi "24 seconds" ra 30 giây; ghi "no slow motion" vẫn có đoạn gần như đứng hình. Đừng tốn chữ vào mấy con số này. **Ngoại lệ có ích:** ghi **giờ cụ thể trong ngày** ("3:40 PM–4:10 PM") giúp giữ ánh sáng đều qua nhiều shot.

### Nhân vật & cảm xúc

**8.5 — Mặt nhân vật hay "trôi" khi đổi bối cảnh hoặc đổi ánh sáng.** Đây là lỗi phổ biến nhất. Cách chống: **mỗi clip một bối cảnh**, nhắc lại khối mô tả ngoại hình trong từng clip, hoặc dùng ảnh tham chiếu (nếu tool hỗ trợ).

**8.6 — Cận mặt diễn cảm xúc là điểm mạnh, nhưng model hay đẩy quá tay.** Viết cảm xúc thành **chuỗi nhịp theo thứ tự** (ngỡ ngàng → ngấn lệ → một giọt rơi → cười nhẹ) thì diễn đúng trình tự. Nhưng ghi "ngấn lệ mà cố không cho rơi" thì model vẫn có thể cho khóc rồi cười toe. Muốn kìm phải ghi **câu cấm cụ thể**: `tears stay in her eyes and never fall, no crying, no clapping, no smiling`.

**8.7 — Chữ không giữ được loài vật, giải phẫu, hay phong cách lạ.** Ghi "gecko" ra như con cóc; "black dragon" ra con trăn. Muốn đúng hình phải **tả từng bộ phận** (rồng: sừng hươu, râu dài, thân rắn có vảy, bốn chân có vuốt) hoặc dùng ảnh tham chiếu. Con ngươi dọc, hoa "có mặt người"... đều phải tả rõ, đừng gọi tên rồi tin.

### Phong cách, chữ, sự kiện

**8.8 — Phong cách khai báo một lần sẽ trôi khi gặp chủ thể lạ.** Cảnh hiện đại chèn vào giữa clip cổ trang dễ bị trôi sang kiểu khác. **Nhắc lại phong cách trong từng khối quan trọng.** Danh sách `NOT... / NO...` viết hoa giúp kéo model ra khỏi kiểu ảnh thật khi muốn phong cách vẽ.

**8.9 — Chữ trên hình gần như không tin được.** Chữ ngắn trong ngoặc kép ("SALE") thì OK, kể cả tiếng Trung; nhưng slogan dài, biển hiệu neon, chữ tiếng Nhật → toàn chữ giả, model tự viết lại. **Tiêu đề, phụ đề, chữ Hán karaoke làm ở hậu kỳ.** Cần hình sạch thì ghi `no subtitles, no captions, no on-screen text`.

**8.10 — Sự kiện (kinh dị, hành động) phải chỉ rõ VỊ TRÍ + THỜI ĐIỂM + KẾT QUẢ nhìn thấy được.** Prompt một câu "cửa tự mở, máy trôi vào bóng tối" ra đúng không khí nhưng cửa gần như không mở. Viết kiểu: `at 4s the second door on the left swings fully open, revealing pitch darkness`. Và luôn viết điều mình **muốn thấy**, thay vì chỉ viết điều cấm ("không thấy dầu" hay bị bỏ qua).

**8.11 — Cú máy dài liền mạch làm rất đẹp nếu tả theo lộ trình.** Từng chặng bằng động từ cụ thể + luật "một chiều, không quay lại". Hợp cho đoạn mở MV sơn thủy, cảnh chuyển. Khuôn flycam:
```
First-person FPV drone, single continuous shot without cuts, always flying forward, never turning back.
Route: <chặng 1 + động từ> → <chặng 2> → <chặng 3, điểm kết>.
<giờ cụ thể trong ngày>. Negative: no cuts, no black frames, no people looking at camera.
```

### Bản quyền
Đừng gọi thẳng tên phim / game / studio / nhân vật có bản quyền trong prompt (dễ bị model trượt về hình giống IP đó, và rủi ro pháp lý). Làm MV fan-made hay phim truyện thì **tả thiết kế của riêng mình**.
