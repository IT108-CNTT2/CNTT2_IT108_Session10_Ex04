# Bản Thiết kế Prompt 3 Phần (Prompt Architecture)

```markdown
# 1. Bối cảnh (Context)
Tôi là sinh viên năm nhất ngành Nông nghiệp Công nghệ cao. Tôi đang gặp khó khăn khi học khái niệm **Mô hình IPO (Input - Process - Output)** trong ngữ cảnh **Trang trại Thông minh (Smart Farm)**. Hãy đóng vai một gia sư đại học thân thiện, vui tính và giỏi truyền đạt.

## 2. Nội dung (Content)
Giải thích bản chất của mô hình IPO áp dụng trong quản lý trang trại thông minh. Lấy một ví dụ thực tế đơn giản (ví dụ: hệ thống tưới nước tự động cho nhà kính).

## 3. Yêu cầu (Requirements)
Cần thực hiện các tác vụ sau:
- [ ] Định nghĩa ngắn gọn 3 thành phần: Input (Đầu vào), Process (Xử lý), và Output (Đầu ra).
- [ ] Cho ví dụ minh họa trực quan liên quan đến cây trồng/trang trại.
- [ ] Giới hạn câu trả lời dưới **300 từ**.
- [ ] Dùng tiếng Việt tự nhiên, giải thích rõ các thuật ngữ tiếng Anh nếu bắt buộc phải dùng.

## 4. Ràng buộc & Edge Case (Không cần)
- [ ] **Không cần** giải thích sâu về code, phần cứng phức tạp (như vi điều khiển, mạch điện) hay các giao thức mạng.
- [ ] **Không cần** liệt kê công thức toán học hoặc phương trình hóa học.
- [ ] **Ràng buộc ngôn ngữ/độ khó (Edge Case):** Tuyệt đối không dùng đoạn văn dài toàn thuật ngữ tiếng Anh chưa dịch. Mọi thuật ngữ tiếng Anh phải được mở ngoặc giải thích ngay bằng tiếng Việt đơn giản.
```

---

# Sản phẩm Output: Câu trả lời mẫu từ AI Tutor

# Mô hình IPO trong Trang trại Thông minh là gì?

Chào bạn! Đừng lo lắng, mô hình **IPO** nghe có vẻ "dự án lớn" nhưng thực ra cực kỳ đơn giản và quen thuộc.

**IPO** là viết tắt của 3 bước cơ bản trong mọi hệ thống tự động:
1. **Input (Đầu vào):** Tiếp nhận thông tin từ môi trường.
2. **Process (Xử lý):** Suy nghĩ và đưa ra quyết định dựa trên dữ liệu thu được.
3. **Output (Đầu ra):** Thực hiện hành động cụ thể.

---

## Ví dụ thực tế: Hệ thống Tưới cây Tự động

Hãy tưởng tượng bạn có một nhà kính trồng dâu tây:

* **Input (Đầu vào):** Cảm biến cắm dưới đất đo được độ ẩm hiện tại chỉ là $30\%$ (đất đang rất khô).
* **Process (Xử lý):** Bộ điều khiển trung tâm nhận số liệu $30\%$, so sánh với mức chuẩn (cần $60\%$), và "ra quyết định": *Cần phải tưới nước ngay!*
* **Output (Đầu ra):** Máy bơm tự động bật lên và vòi phun sương tưới nước cho dâu tây cho đến khi đạt đủ độ ẩm.

---

## Tóm tắt nhanh

> **Input** (Thu thập dữ liệu) $\rightarrow$ **Process** (Tính toán/Quyết định) $\rightarrow$ **Output** (Hành động thực tế)

Nhờ mô hình IPO này, trang trại thông minh có thể tự chăm sóc cây trồng $24/7$ mà người nông dân không cần phải tốn công vất vả kiểm tra thủ công mỗi ngày!
