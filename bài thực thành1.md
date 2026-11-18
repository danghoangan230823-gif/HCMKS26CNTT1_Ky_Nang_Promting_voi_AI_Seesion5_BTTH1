
# **BÀI THỰC HÀNH 1: LẬP KẾ HOẠCH TÀI CHÍNH CÁ NHÂN BẰNG CHAIN-OF-THOUGHT**

## **1. Mục tiêu**

Sử dụng kỹ thuật Chain-of-Thought để giúp AI lập kế hoạch tài chính cá nhân, tính toán thu nhập, chi phí, trả nợ và tiết kiệm.

Đảm bảo các phép tính chính xác, ngân sách hợp lý và tổng tỷ lệ phân bổ bằng 100%.

## **2. Prompt thiết kế**

**Prompt sử dụng:**

Bạn là chuyên gia tư vấn tài chính cá nhân.

Hãy lập kế hoạch tài chính hàng tháng dựa trên dữ liệu sau:

- Thu nhập hàng tháng: 15.000.000 VNĐ.
- Thuế và khoản khấu trừ: 1.000.000 VNĐ.
- Chi phí cố định: 4.000.000 VNĐ.
- Khoản nợ cần trả: 2.000.000 VNĐ.
- Mục tiêu tiết kiệm: tối thiểu 20% thu nhập sau thuế.

**Yêu cầu xử lý bằng Chain-of-Thought:**

Hãy suy nghĩ từng bước một và tính toán chi tiết trước khi đưa ra quyết định.

Bước 1: Tính thu nhập sau thuế và trừ chi phí cố định.

Bước 2: Phân bổ tiền trả nợ.

Bước 3: Trích lập tiết kiệm tối thiểu 20% thu nhập sau thuế.

Bước 4: Chia số tiền còn lại theo quy tắc 50/30/20 cải tiến:

- 50% cho nhu cầu thiết yếu.
- 30% cho mong muốn cá nhân.
- 20% cho quỹ dự phòng.

**Ràng buộc:**

- Không tự ý thay đổi dữ liệu.
- Không bỏ qua khoản nợ.
- Không phân bổ vượt quá thu nhập.
- Kiểm tra lại toàn bộ phép tính.
- Tổng tỷ lệ ngân sách phải bằng chính xác 100%.

**Đầu ra:**

1. Các bước tính toán và số liệu trung gian.
2. Bảng ngân sách Markdown gồm: Hạng mục, Số tiền, Tỷ lệ %, Ghi chú.
3. Kết luận và đề xuất tiết kiệm.

## **3. Kết quả chạy thử**

### **3.1. Phân tích tính toán**

**Bước 1: Tính thu nhập khả dụng**

\- Thu nhập sau thuế:

15.000.000 - 1.000.000 = 14.000.000 VNĐ.

\- Sau khi trừ chi phí cố định:

14.000.000 - 4.000.000 = 10.000.000 VNĐ.

**Bước 2: Trả nợ**

- Khoản nợ cần thanh toán: 2.000.000 VNĐ.
- Tiền còn lại:

10.000.000 - 2.000.000 = 8.000.000 VNĐ.

**Bước 3: Tiết kiệm 20%**

\- Tiền tiết kiệm:

14.000.000 × 20% = 2.800.000 VNĐ.

\- Tiền còn lại:

8.000.000 - 2.800.000 = 5.200.000 VNĐ.

**Bước 4: Phân bổ 50/30/20**

- Nhu cầu thiết yếu: 5.200.000 × 50% = 2.600.000 VNĐ.
- Mong muốn cá nhân: 5.200.000 × 30% = 1.560.000 VNĐ.
- Quỹ dự phòng: 5.200.000 × 20% = 1.040.000 VNĐ.

### **3.2. Bảng phân bổ ngân sách**

| Hạng mục                  | Số tiền (VNĐ)  | Tỷ lệ %  | Ghi chú              |
| ------------------------- | -------------- | -------- | -------------------- |
| Thuế                      | 1.000.000      | 7,14%    | Khấu trừ             |
| Chi phí cố định           | 4.000.000      | 28,57%   | Tiền nhà, điện nước  |
| Trả nợ                    | 2.000.000      | 14,29%   | Thanh toán nợ        |
| Tiết kiệm                 | 2.800.000      | 20%      | Tiết kiệm hàng tháng |
| Nhu cầu thiết yếu bổ sung | 2.600.000      | 18,57%   | Ăn uống, đi lại      |
| Mong muốn cá nhân         | 1.560.000      | 11,14%   | Giải trí, mua sắm    |
| Quỹ dự phòng              | 1.040.000      | 7,43%    | Chi phí bất ngờ      |
| **Tổng cộng**             | **15.000.000** | **100%** |                      |

## **4. Kết luận**

Qua bài thực hành, em đã sử dụng kỹ thuật Chain-of-Thought để chia bài toán tài chính thành các bước nhỏ, giúp AI tính toán và kiểm tra ngân sách có hệ thống.

Kết quả cho thấy:

- Tiết kiệm được 2.800.000 VNĐ/tháng.
- Đảm bảo thanh toán khoản nợ 2.000.000 VNĐ.
- Có ngân sách dành cho chi tiêu và dự phòng.
- Tổng tỷ lệ phân bổ đạt 100%.
# PROMPT LẬP KẾ HOẠCH TÀI CHÍNH CÁ NHÂN THEO CREATE

**C – Context (Bối cảnh):**

Bạn là chuyên gia tư vấn tài chính cá nhân, có kinh nghiệm quản lý ngân sách, tiết kiệm và kiểm soát nợ.

**R – Request (Yêu cầu):**

Hãy lập kế hoạch tài chính hàng tháng dựa trên dữ liệu thu nhập, chi phí cố định, khoản nợ và mục tiêu tiết kiệm. Đưa ra phương án phân bổ ngân sách hợp lý.

**E – Examples (Ví dụ):**

Ví dụ dữ liệu:
- Thu nhập: 15.000.000 VNĐ.
- Thuế: 1.000.000 VNĐ.
- Chi phí cố định: 4.000.000 VNĐ.
- Khoản nợ: 2.000.000 VNĐ.
- Mục tiêu tiết kiệm: 20%.

**A – Audience (Đối tượng):**

Người có thu nhập hàng tháng, muốn quản lý chi tiêu, trả nợ đúng hạn và xây dựng thói quen tiết kiệm.

**T – Tone (Giọng điệu):**

Trình bày chuyên nghiệp, dễ hiểu, ngắn gọn, sử dụng ngôn ngữ phù hợp với sinh viên.

**E – Execution (Cách thực hiện):**

1. Tính thu nhập sau thuế.
2. Trừ chi phí cố định và khoản nợ.
3. Tính khoản tiết kiệm tối thiểu 20% thu nhập sau thuế.
4. Phân bổ phần tiền còn lại theo quy tắc 50/30/20 cải tiến.
5. Kiểm tra tổng số tiền và tỷ lệ phân bổ phải bằng 100%.
6. Nếu dữ liệu thiếu hoặc không hợp lệ, thông báo thay vì tự giả định.

**Định dạng đầu ra:**
- Phân tích các phép tính theo từng bước.
- Bảng Markdown gồm: Hạng mục, Số tiền, Tỷ lệ %, Ghi chú.
- Đưa ra kết luận và đề xuất cải thiện tài chính.
