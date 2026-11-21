# Phiếu QC 1 — Road v1.0

Lô được kiểm (học viên): nguyensontung        Người kiểm (học viên): Trần Đức Hải
Ngày: 21/11/2026                         Phiên bản guideline: Road v1.0  
File được kiểm (tên + `revision` trong manifest): `nguyensontung` + `1`
Số ảnh kiểm: 20 / 20 ảnh bắt buộc (+ 8 ảnh thêm)   Số nhãn đã kiểm (shape + tag): 277

## Tổng hợp theo mã

| Mã | Loại lỗi | Số mục kiểm | Số lỗi | Mức |
| --- | --- | ---: | ---: | --- |
| QC1-01 tag camera | sai thuộc tính / bỏ sót | 80 | 0 | nặng |
| QC1-02 đủ L1, R1 | bỏ sót | 21 | 3 | nặng |
| QC1-03 position | sai thuộc tính / thừa | 38 | 0 | nặng |
| QC1-04 tâm vạch, chiều, điểm dừng | sai phạm vi / bỏ sót | 38 | 6 | chính |
| QC1-05 vạch đứt, che | sai phạm vi / sai thuộc tính | 38 | 0 | chính |
| QC1-06 style, color, kind | sai thuộc tính | 38 | 1 | chính |
| QC1-07 vùng lái | sai phạm vi / bỏ sót / thừa | 59 | 6 | chính |
| QC1-08 đèn, màu | bỏ sót / sai phạm vi / sai thuộc tính | 51 | 2 | nặng / chính |
| QC1-09 facing, type, group, biển phụ | sai thuộc tính | 100 | 0 | chính |
| QC1-10 hình in, đủ biển | bỏ sót / sai phạm vi | 49 | 6 | chính |
| QC1-11 fisheye | sai phạm vi / sai thuộc tính | 55 | 0 | chính |
| QC1-12 file | lỗi file | 277 | 0 | nhẹ / nặng |

## Danh sách lỗi (mỗi lỗi một dòng)

| # | Mã | Ảnh | Nhãn (label, id) | Mức | Mô tả ngắn |
| --- | --- | --- | --- | --- | --- |
| 1 | QC1-06 | A01 | lane#6@(1280,706) | chính | sai color=white→yellow |
| 2 | QC1-07 | A01 | road_curb | chính | thiếu road_curb |
| 3 | QC1-07 | A02 | road_curb | chính | thiếu road_curb |
| 4 | QC1-10 | A03 | traffic_sign | chính | thiếu biển |
| 5 | QC1-10 | A04 | traffic_sign | chính | thiếu biển |
| 6 | QC1-02 | A06 | lane | nặng | thiếu vạch L1 |
| 7 | QC1-10 | A06 | traffic_sign | chính | thiếu biển |
| 8 | QC1-02 | A08 | lane | nặng | thiếu vạch L1 |
| 9 | QC1-10 | A08 | traffic_sign | chính | thiếu biển |
| 10 | QC1-08 | A09 | traffic_light | chính | thiếu đèn |
| 11 | QC1-02 | A10 | lane | nặng | thiếu vạch R1 |
| 12 | QC1-10 | A10 | traffic_sign | chính | thiếu biển |
| 13 | QC1-08 | A11 | traffic_light | chính | thiếu đèn |
| 14 | QC1-04 | A12 | lane | chính | thiếu vạch position=R2 |
| 15 | QC1-04 | A12 | lane | chính | thiếu vạch position=L2 |
| 16 | QC1-10 | A12 | traffic_sign | chính | thiếu biển |
| 17 | QC1-07 | B01 | road_curb | chính | thiếu road_curb |
| 18 | QC1-07 | B03 | road_curb | chính | thiếu road_curb |
| 19 | QC1-04 | B05 | lane | chính | thiếu vạch position=other |
| 20 | QC1-07 | B05 | road_curb | chính | thiếu road_curb |
| 21 | QC1-04 | B06 | lane | chính | thiếu vạch position=other |
| 22 | QC1-04 | B07 | lane | chính | thiếu vạch position=other |
| 23 | QC1-07 | B07 | road_curb | chính | thiếu road_curb |
| 24 | QC1-04 | B08 | lane#1@(91,730) | chính | vẽ ngược chiều |

## Ca mơ hồ

| Ảnh | Câu hỏi cho lead | Lời đáp (nếu có) |
| --- | --- | --- |
| - | - | - |

## Quyết định

Lỗi nặng: 3    Lỗi chính: 21 / 277 nhãn = 7.6%    Lỗi nhẹ: 0    Ca chờ lead: 0 (chưa có xác nhận thủ công)

Quyết định (Release / Hold / Rework): **Rework** (đề xuất từ so sánh tự động)

Lý do (theo luật của phiếu): có lỗi nặng → Rework.
