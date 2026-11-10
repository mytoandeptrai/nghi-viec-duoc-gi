# Nghỉ Việc Được Gì

Checker quyền lợi khi nghỉ việc / bị cho thôi việc theo luật Việt Nam 2026. Tiếng Việt, miễn phí, không cần tài khoản, tính ngay trên trình duyệt, không lưu dữ liệu người dùng.

## Dùng thử

Mở `index.html` bằng trình duyệt, hoặc bật GitHub Pages từ branch `main`.

## Tính gì

- **Trợ cấp thôi việc** — Điều 46, Bộ luật Lao động 2019: làm việc thường xuyên đủ 12 tháng trở lên, mỗi năm 1/2 tháng lương.
- **Trợ cấp mất việc** — Điều 47, Bộ luật Lao động 2019: mất việc do thay đổi cơ cấu, công nghệ hoặc vì lý do kinh tế, mỗi năm 1 tháng lương, ít nhất 2 tháng.
- **Bảo hiểm thất nghiệp** — Luật Việc làm 74/2025/QH15 Điều 38–39, Nghị định 374/2025/NĐ-CP (hiệu lực 1/1/2026): 60% bình quân lương đóng BHTN 6 tháng gần nhất, tối đa 5 lần lương tối thiểu vùng.
- **Thời gian báo trước** — Điều 35–36, Bộ luật Lao động 2019: 45 / 30 / 3 ngày làm việc tùy loại hợp đồng.
- **Checklist hồ sơ BHTN** — Mẫu số 10, Nghị định 374/2025/NĐ-CP, nộp trong 3 tháng kể từ ngày chấm dứt.

## Số luật hardcode

Không có API chính thức cho số luật, nên các hằng số được hardcode trong file `index.html` (khối `LUAT_2026`), kèm nguồn + ngày hiệu lực, kiểm chứng ngày 10/11/2026:

- Lương tối thiểu vùng 2026 — Nghị định 293/2025/NĐ-CP: Vùng I 5.310.000, II 4.730.000, III 4.140.000, IV 3.700.000 đồng/tháng.
- Trần BHTN = 5 lần lương tối thiểu vùng: 26.550.000 / 23.650.000 / 20.700.000 / 18.500.000 đồng/tháng.
- Nguồn tra cứu: vbpl.vn, thuvienphapluat.vn, luatvietnam.vn.

Khi luật đổi (thường lương tối thiểu vùng đổi mỗi năm vào 1/1), cập nhật lại các hằng số này.

## Lưu ý

Chỉ tham khảo, không phải tư vấn pháp lý. Trường hợp phức tạp nên hỏi luật sư / công đoàn.
