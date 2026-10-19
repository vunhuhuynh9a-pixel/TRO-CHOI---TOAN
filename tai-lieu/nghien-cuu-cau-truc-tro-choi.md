# Nghiên cứu cấu trúc trò chơi cho bài giảng Toán 7

Mục tiêu: mượn **cơ chế** (luật chơi, vòng lặp, cảm giác) của các trò chơi học sinh THCS đã quen,
rồi thay "nguyên liệu" bằng kiến thức trong SGK Toán 7 – Kết nối tri thức. Học sinh không phải học luật mới,
chỉ cần học toán. Không dùng hình ảnh, tên gọi, nhân vật có bản quyền của các trò chơi gốc —
chỉ lấy ý tưởng cơ chế, tự vẽ lại toàn bộ.

## Tiêu chí chọn cơ chế

1. **Quyết định toán học là hành động chính** — mỗi lượt chơi buộc học sinh phải phân loại, so sánh, tính toán.
   Nếu bỏ phần toán đi mà vẫn thắng được thì cơ chế đó không phù hợp.
2. **Sai thì thấy ngay hậu quả** — phản hồi tức thì, kèm lời giải thích ngắn bằng ngôn ngữ của sách.
3. **Chơi được trên máy chiếu** — chữ to, điều khiển bằng chuột/chạm, có nút tạm dừng để giáo viên giảng.
4. **Một ván 3–6 phút** — vừa một hoạt động khởi động hoặc củng cố trong tiết 45 phút.
5. **Chạy ngay trên trình duyệt** — một file HTML, không cần cài đặt, không cần mạng sau khi tải.

## Bảng các cơ chế quen thuộc

| Trò chơi gốc (cơ chế) | Vòng lặp chơi | Kĩ năng toán phù hợp | Bài phù hợp trong SGK |
|---|---|---|---|
| **Plants vs. Zombies** — thủ thành theo làn | Quan sát đối tượng đang tiến tới → chọn "công cụ" đúng loại → đặt vào làn | **Phân loại** nhanh, nhiều lần, có áp lực thời gian | B7 Tập hợp số thực (ℚ / 𝕀), B17 phân loại dữ liệu |
| **Fruit Ninja** — chém vật bay lên | Nhiều vật bay lên cùng lúc → chỉ chém vật thoả điều kiện, tránh "bom" | Nhận diện theo điều kiện (∈ / ∉) | B1 nhận biết ℚ, B5 thập phân hữu hạn / vô hạn tuần hoàn |
| **Subway Surfers / Temple Run** — chạy 3 làn | Cổng đáp án hiện ở 3 làn → đổi làn vào cổng đúng | Tính nhẩm, so sánh nhanh | B2 phép tính ℚ, B3 luỹ thừa, B12 tổng ba góc |
| **Flappy Bird** — bay qua khe | Mỗi cột có khe ghi số → bay qua khe lớn hơn / nhỏ hơn | So sánh, sắp thứ tự | B1, B7 so sánh số thực |
| **Rắn săn mồi (Snake)** | Ăn số theo thứ tự tăng dần, ăn sai thì rắn ngắn lại | Sắp thứ tự trên trục số | B1, B7 trục số |
| **2048 / Candy Crush** — ghép khối | Ghép hai ô có giá trị bằng nhau | Nhận ra các cách viết khác nhau của cùng một số | B1 phân số bằng nhau, B3 xᵐ·xⁿ, B5 0,(1) = 1/9 |
| **Tetris** | Khối rơi mang biểu thức → xếp vào cột có kết quả đúng | Tính giá trị biểu thức | B4 thứ tự thực hiện phép tính |
| **Angry Birds** — bắn theo góc | Chọn số đo góc để bắn trúng mục tiêu | Góc kề bù, đối đỉnh, so le trong, đồng vị | Chương III |
| **Among Us** — tìm kẻ mạo danh | Trong một nhóm có một "kẻ mạo danh" sai tính chất → bỏ phiếu loại | Phản ví dụ, phát hiện lời giải sai | B11 định lí, Chương IV tam giác bằng nhau |
| **Ai là triệu phú / Kahoot / Rung chuông vàng** | Câu hỏi trắc nghiệm, quyền trợ giúp, thang điểm | Ôn tập tổng hợp | Ôn tập chương, giữa kì |
| **Đập chuột (Whack-a-mole)** | Đập con chuột mang đáp án đúng trước khi nó lặn | Phản xạ nhận diện | B6 căn bậc hai, B16 tam giác cân |
| **Minecraft** — xây dựng | Thu thập "khối" đúng để xây công trình | Tổng hợp nhiều bước | Dự án cuối chương |

## Vì sao chọn "Plants vs. Zombies" cho Bài 7

Bài 7 *Tập hợp các số thực* có trọng tâm là **phân biệt số hữu tỉ và số vô tỉ**, kèm so sánh số thực
và giá trị tuyệt đối. Cơ chế thủ thành theo làn khớp với nội dung này:

| Cơ chế trò chơi | Nội dung toán |
|---|---|
| Zombie mang biển số tiến vào theo làn | Một số thực cần phân loại: 3/4, √2, −√81, 0,(3), π… |
| Cây Đậu ℚ chỉ bắn hạ zombie mang **số hữu tỉ** | Định nghĩa: số viết được dạng a/b, a, b ∈ ℤ, b ≠ 0 (hữu hạn hoặc vô hạn tuần hoàn) |
| Cây Đậu 𝕀 chỉ bắn hạ zombie mang **số vô tỉ** | Định nghĩa: số thập phân vô hạn **không** tuần hoàn |
| Đạn bắn nhầm loại xuyên qua zombie | Phản hồi tức thì khi phân loại sai; được ghi lại thành "số dễ nhầm" |
| Zombie "đội lốt" (√16, −√81, (√3)², √(1+2+1)) | Phải tính rồi mới phân loại: √16 = 4 là số hữu tỉ |
| Zombie Giáo sư có khiên, nhấn vào để trả lời | So sánh số thực, giá trị tuyệt đối, số đối, kí hiệu ∈ |
| Hoa Mặt Trời tạo "nắng" để mua cây; câu đố thưởng nắng | Động lực trả lời câu hỏi để mạnh lên |
| Máy cắt cỏ cứu nguy một lần mỗi làn | Cho phép sai mà không thua ngay, phù hợp học sinh yếu |

Ba màn tăng dần độ khó, bám theo tiến trình bài học:

1. **Màn 1 – Nhận diện:** phân số, số nguyên, thập phân hữu hạn/tuần hoàn đối đầu π, √2, √15, 0,1010010001…
2. **Màn 2 – Đội lốt:** căn bậc hai của số chính phương, giá trị tuyệt đối, (√a)² — phải tính trước khi phân loại.
3. **Màn 3 – Giáo sư Zombie:** trộn tất cả, thêm zombie có khiên mang câu hỏi so sánh và giá trị tuyệt đối.

Toàn bộ số liệu và câu hỏi lấy từ ví dụ, luyện tập và bài tập của Bài 5, 6, 7 (SGK tr. 26–39).

## Ứng viên tiếp theo

- **Fruit Ninja – Bài 5:** chém số thập phân vô hạn tuần hoàn, tránh số hữu hạn; chém đúng thì hiện chu kì.
- **Subway Surfers – Bài 3:** chạy qua cổng luỹ thừa đúng (xᵐ·xⁿ, xᵐ:xⁿ, (xᵐ)ⁿ).
- **Angry Birds – Chương III:** bắn theo số đo góc kề bù / đối đỉnh / so le trong.
- **Among Us – Chương IV:** tìm "kẻ mạo danh" trong các lập luận chứng minh tam giác bằng nhau (c.c.g, g.g.g…).
