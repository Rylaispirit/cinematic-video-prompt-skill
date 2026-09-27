---
name: oriental-scene-lite
description: Dùng khi viết prompt ảnh/video cảnh tiên hiệp, cổ phong, mỹ học phương Đông (thiên cung, biển mây, cung điện, kiếm khách) cho Midjourney/SD/Flux/Veo. Bản Lite.
---

# Oriental Scene Lite — prompt cảnh mỹ học phương Đông

Viết prompt cảnh quốc phong / tiên hiệp đẹp như poster phim. Giải thích bằng tiếng Việt ngắn gọn; prompt gửi model viết bằng tiếng Anh, kèm 1 dòng tiếng Việt tóm ý để người dùng dễ sửa.

## 1. Công thức 6 lớp (theo thứ tự)

1. **Góc máy:** epic wide shot · overhead shot · low angle wide-angle · symmetrical composition · long corridor depth shot
2. **Kiến trúc:** ancient Chinese palace, multi-layered upturned eaves, white jade columns carved with dragons, moon gate arch, wooden lattice windows
3. **Một điểm nhấn (chỉ chọn 1):** giant phoenix · bronze cauldron · stone dragon head with waterfall · ancient pine on cliff · floating scrolls
4. **Nhân vật nhỏ, quay lưng:** back view, figure in flowing hanfu / white-robed swordsman, silk fluttering in wind
5. **Môi trường + ánh sáng:** endless sea of clouds · mirror lake · golden dawn light · Tyndall light beams · soft morning haze · warm dusk backlight
6. **Chất lượng:** delicate texture, volumetric light, depth of field, cinematic, 8K, Unreal Engine 5 rendering

Mẹo: nhân vật nhỏ + quay lưng làm cảnh hùng vĩ hơn và tránh lỗi mặt. Mỗi cảnh chỉ 1 điểm nhấn để không rối.

## 2. Khuôn mẫu vạn năng

```
Chinese xianxia concept art, [camera angle], [architecture], [one focal element], [small figure, back view, outfit], [environment], [lighting], volumetric light, atmospheric haze, delicate texture, depth of field, cinematic, 8K
```

## 3. Ví dụ

**Hành lang trên mây (sáng sớm, thanh tịnh):**
```
Chinese xianxia concept art, low angle long corridor depth shot, white jade colonnade carved with dragons and clouds, glossy stone floor reflecting the sky, a giant moon gate arch opening onto a sea of clouds, tiny figure in a crimson hanfu standing at the far end, back view, soft cool morning light, pale blue sky, atmospheric haze, clean architectural lines, depth of field, cinematic, 8K
```

**Kiếm khách bên hồ gương (rạng đông, mơ màng):**
```
Chinese xianxia concept art, symmetrical composition, floating palace mirrored in a still lake that merges with the clouds, lone white-robed swordsman standing on the water's edge holding a long sword, back view, hair tied and flowing, pale dawn sky, soft dreamy light, gentle ripples, ultra-wide lens, volumetric light, cinematic, 8K
```

## 4. Theo công cụ

- **Midjourney:** thêm `--ar 16:9` (hoặc `--ar 21:9` cho khổ rộng), `--style raw`, `--no text, watermark, modern buildings`.
- **SD / Flux:** SD dùng ô prompt âm `text, watermark, modern elements, blurry, deformed architecture`; Flux viết loại trừ thành câu khẳng định.
- **Video (Veo, Kling...):** thêm đúng 1 chuyển động máy (`slow push-in` / `crane up revealing the palace`) và 1 chuyển động môi trường (`clouds drifting`, `silk fluttering`). Tra thêm chuyển động camera trong skill `cinematic-video-prompt`.

---

> **Bản Full (VIP)** có thêm: công thức 8 lớp với kho từ khóa đầy đủ, 9 cảnh mẫu hoàn chỉnh (thiên cung phượng hoàng, Lăng Tiêu, thác đầu rồng, tiên các, cổ quyển sa mạc...) kèm bản tiếng Việt, thông số SD chi tiết, hướng dẫn chuyển ảnh thành video, kết nối với skill tạo nhân vật để giữ mặt nhất quán. Liên hệ tác giả qua GitHub [@Rylaispirit](https://github.com/Rylaispirit).
