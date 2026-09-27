---
name: character-sheet-lite
description: Dùng khi cần prompt ảnh thiết kế nhân vật (3 góc toàn thân + cận mặt trong 1 ảnh) cho Midjourney/SD/Flux để giữ nhân vật nhất quán khi làm video AI. Bản Lite.
---

# Character Sheet Lite — prompt bảng thiết kế nhân vật

Tạo 1 prompt cho ra **1 ảnh 16:9**: bên trái 3 dáng toàn thân (trước / nghiêng / sau), bên phải 1 cận mặt từ ngực lên. Ảnh này dùng làm ảnh tham chiếu để nhân vật không "đổi mặt" giữa các clip video.

Giải thích cho người dùng bằng tiếng Việt, ngắn gọn. Prompt gửi model viết bằng tiếng Anh.

## 1. Cách làm

1. Nhận mô tả nhân vật (vài dòng là đủ). Thiếu gì thì tự chọn hợp lý và ghi rõ giả định.
2. Hỏi 1 câu nếu chưa biết: dùng **Midjourney, SD hay Flux**? Và muốn **tả thực người thật hay 3D hoạt hình**?
3. Viết prompt theo khung ở mục 3, rồi thêm **Thẻ khóa nhân vật** (8–10 từ khóa) để nối vào prompt video sau này.

## 2. 4 luật để nhân vật không "nhạt"

1. **Hình bóng rõ:** nhìn đường viền phải nhận ra (vai rất rộng, áo choàng lớn, dáng chữ A, chữ V...). Đừng chỉ là "một người mặc đồ".
2. **Màu pha, không màu cơ bản:** viết `charcoal violet`, `rust brown`, `faded indigo` thay cho gray / brown / blue. Thêm 1 màu tương phản mạnh ở đúng 1 chỗ nhỏ (lớp lót, cúc áo, mống mắt).
3. **Có dấu vết sống:** chọn ít nhất 2 thứ — vết vá, chỗ sờn, sẹo, bất đối xứng, bụi bẩn.
4. **Không từ rỗng:** tránh beautiful, handsome, cool, stylish, pretty. Thay bằng mô tả cụ thể nhìn thấy được.

**Nguyên bản bắt buộc:** không lấy mặt diễn viên, ngôi sao hay nhân vật phim/game có sẵn. Nếu người dùng muốn "giống X" thì đề xuất thiết kế nguyên bản thay thế.

## 3. Khung prompt

```
character design reference sheet, single image, left: three full-body views (front, side profile, back) in a row, A-pose, evenly spaced; right: one large chest-up close-up headshot,
[gender], [age] years old, [build], [skin tone with undertone],
face: [face shape, eyes + iris color, brows, nose, lips], natural asymmetry, visible skin texture, [one mark: scar / mole / freckles], default expression [mood],
hair: [length, texture, multi-tone color, styling],
wearing: [inner layer: fabric + color], [outer layer: fabric + color + silhouette], [one sign of wear], [one accent color detail],
footwear: [style + material + wear], accessories: [1 item with a story],
[render style: cinematic 3D character / photoreal film still / stylized], same identity across all views, same outfit, studio lighting, neutral light gray background, no text, no labels, no watermark, ultra detailed
```

## 4. Theo công cụ

- **Midjourney:** thêm `--ar 16:9 --style raw`, loại trừ bằng `--no text, watermark, plastic skin, extra fingers, celebrity likeness`.
- **Stable Diffusion:** dùng ô prompt âm: `inconsistent face, outfit changes between views, plastic skin, airbrushed, bad anatomy, extra fingers, text, watermark, celebrity likeness, cropped`.
- **Flux:** gần như bỏ qua prompt âm → viết thành câu khẳng định trong prompt chính (vd "no text anywhere, skin with visible pores").

## 5. Thẻ khóa nhân vật

8–10 từ khóa ngắn, cụ thể, nhìn thấy được. Ví dụ:
`woman early 30s, lean build, crooked nose, olive skin, scar through left brow, ash-black bob, faded indigo wrap coat, rust silk lining, scuffed leather boots, brass ring on thumb`

Nối thẻ này vào mọi prompt cảnh/video có nhân vật, kèm ảnh sheet làm ảnh tham chiếu.

---

> **Bản Full (VIP)** có thêm: quy trình bảng tổng thiết kế nhiều nhân vật, 6 luật cực đoan hóa đầy đủ, kho 20 phong cách render + 9 ngôn ngữ cắt may, hướng dẫn trang phục 3 lớp và 5 chiều chất vải, hướng dẫn khuôn mặt theo tuổi và theo vùng da, bảng tra tiếng Anh cho chất vải và nét mặt, kiểm soát 4000 ký tự, checklist 17 mục. Liên hệ tác giả qua GitHub [@Rylaispirit](https://github.com/Rylaispirit).
