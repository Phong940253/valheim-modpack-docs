# 🌱 PHẦN 6 — Easy Plant (PlantEasily): Hướng dẫn sử dụng nhanh (v2.1.1)

**PlantEasily** (Advize) là mod QoL làm nông: trồng **hàng loạt** cây thẳng hàng đều đặn không lãng phí hạt, thu hoạch hàng loạt và tự trồng lại. Hỗ trợ cả bụi dâu, hoa, nấm (mod tự định nghĩa pool pickable — **không phụ thuộc PlantEverything**).

### 1. Cách trồng nhanh

- Trang bị **Cultivator** và chọn hạt giống trong build tab.

- Dùng **Right Ctrl + phím mũi tên** để tăng/giảm số hàng và cột (tính theo hướng nhìn).

- **Chuột trái** để trồng cả lô; vị trí không trồng được hiện **màu đỏ** trước khi đặt (biome sai, đất chưa cày, thiếu nắng, quá nóng/lạnh, thiếu tài nguyên...).

- **Snapping tự động**: mod tự phát hiện 1 cây hoặc grid đã có gần nhất để canh hàng (không cần giữ phím nào — đã xác minh DLL: không có config key "hold to snap"); kết hợp phím alternative placement (`B`) để xoay tự do 360° khi snap.

- Khi cây chín: **Left Shift + Use (E)** để **thu hoạch hàng loạt** (áp dụng cho mọi pickable và tổ ong).

### 2. Phím tắt mặc định

| Phím | Chức năng |
| --- | --- |
| **Right Ctrl + mũi tên** | Tăng/giảm số hàng & cột |
| **Left Shift + Use (E)** | Thu hoạch hàng loạt (khi đã bật) |
| **F6** | Bật/tắt tự trồng lại sau thu hoạch |
| **F8** | Bật/tắt toàn bộ tính năng mod |
| **F10** | Bật/tắt grid snapping |
| Snapping khi trồng | Snap tự động vào 1 cây hoặc grid có sẵn (không cần phím giữ; dùng `B` để xoay tự do khi snap) |
| Phím alternative placement (`B`) | Xoay tự do 360° khi snap |

Các phím chỉ hoạt động khi đang cầm Cultivator và đã chọn loại cây. Phím toggle hỗ trợ tổ hợp (vd `Left Ctrl + F8`) và tất cả đều đổi được trong config.

### 3. Tính năng chính

- Trồng 1 cây, 1 hàng, 1 cột hoặc nhiều hàng/cột cùng lúc — điều chỉnh real-time bằng phím tắt.

- Ngăn trồng sai chỗ: vị trí không hợp lệ hiện đỏ; tuỳ chọn chặn hoàn toàn.

- Xoay ngẫu nhiên cho ruộng bớt đều tăm tắp (tuỳ chọn scatter vị trí/xoay).

- Thu hoạch hàng loạt: mọi **pickable** + tổ ong.

- **Tự trồng lại** khi thu hoạch: chọn loại cây trồng thay thế trong cultivator trước khi thu.

- **Grid snapping**: snap theo 1 cây hoặc grid có sẵn.

### 4. Cấu hình

File `BepInEx/config/advize.PlantEasily.cfg` được tạo sau lần chạy game đầu tiên. Sửa bằng text editor hoặc trong game bằng **ConfigurationManager** (phím `F1`).

**Lưu ý:** đây là mod **client-side only** — không cài lên dedicated server. ⚠ Sửa khi audit: mod **không khai báo BepInIncompatibility** với **FarmGrid**/**MassFarming**/**Farming** (DLL không chứa attribute này) — đây chỉ là *khuyến nghị tránh dùng chung* (các mod trồng cây khác có thể đè behavior), không phải ràng buộc cứng.

#backpacks-wiki { page-break-before: always; }
#backpacks-wiki h2 { color: #16213e; border-bottom: 2px solid #e94560; padding-bottom: 5px; margin-top: 25px; page-break-after: avoid; }
#backpacks-wiki h3 { color: #0f3460; margin-top: 20px; page-break-after: avoid; }
#backpacks-wiki table tr { page-break-inside: avoid; }
#backpacks-wiki blockquote { margin: 8px 0; padding: 8px 12px; background: #f4f4f8; border-left: 4px solid #0f3460; color: #555; font-size: 9pt; }
#backpacks-wiki code { background: #eee; padding: 1px 4px; border-radius: 3px; font-size: 8.5pt; }
#backpacks-wiki pre { background: #f4f4f8; padding: 8px; border-radius: 4px; font-size: 8.5pt; overflow: hidden; }
#backpacks-wiki img { vertical-align: middle; }
#backpacks-wiki ul, #backpacks-wiki ol { margin: 6px 0 6px 22px; }
