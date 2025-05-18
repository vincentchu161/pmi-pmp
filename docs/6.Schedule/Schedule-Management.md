# Quản lý lịch trình dự án (Schedule Management)

## Định nghĩa và tầm quan trọng
- Quản lý lịch trình là quá trình lập kế hoạch, phát triển, quản lý, thực hiện và kiểm soát lịch trình dự án
- Lịch trình dự án xác định thời gian bắt đầu, thời gian kết thúc và thời gian thực hiện các hoạt động dự án
- Quản lý lịch trình hiệu quả giúp dự án hoàn thành đúng thời hạn, tối ưu hóa nguồn lực và kiểm soát chi phí

## Các quy trình quản lý lịch trình
1. **Lập kế hoạch quản lý lịch trình**: Thiết lập chính sách, thủ tục và tài liệu để lập kế hoạch, phát triển, quản lý, thực hiện và kiểm soát lịch trình dự án
2. **Xác định hoạt động**: Xác định và tài liệu hóa các hành động cụ thể cần thực hiện để tạo ra kết quả bàn giao dự án
3. **Sắp xếp các hoạt động**: Xác định và ghi lại mối quan hệ giữa các hoạt động dự án
4. **Ước tính thời gian hoạt động**: Ước tính số kỳ làm việc cần thiết để hoàn thành từng hoạt động với các nguồn lực dự kiến
5. **Phát triển lịch trình**: Phân tích trình tự hoạt động, thời lượng, yêu cầu nguồn lực và ràng buộc lịch trình để tạo mô hình lịch trình dự án
6. **Kiểm soát lịch trình**: Giám sát trạng thái dự án để cập nhật tiến độ và quản lý thay đổi đối với đường cơ sở lịch trình

## Công cụ và kỹ thuật lập lịch trình
### Phương pháp xác định mối quan hệ giữa các hoạt động
- **Phương pháp tiền nhiệm (PDM)**: Sử dụng các mối quan hệ logic giữa các hoạt động
  - Kết thúc-Bắt đầu (FS): Hoạt động trước phải kết thúc trước khi hoạt động sau có thể bắt đầu
  - Bắt đầu-Bắt đầu (SS): Hoạt động trước phải bắt đầu trước khi hoạt động sau có thể bắt đầu
  - Kết thúc-Kết thúc (FF): Hoạt động trước phải kết thúc trước khi hoạt động sau có thể kết thúc
  - Bắt đầu-Kết thúc (SF): Hoạt động trước phải bắt đầu trước khi hoạt động sau có thể kết thúc
- **Thời gian Lead và Lag**
  - Lead time: Đẩy nhanh hoạt động kế tiếp
  - Lag time: Trì hoãn hoạt động kế tiếp

### Ước tính
- **Ước tính điểm**: Ước tính đơn giá trị dựa trên trực giác hoặc kinh nghiệm
- **Ước tính tham số**: Sử dụng mối quan hệ thống kê giữa dữ liệu lịch sử và các biến số khác
- **Ước tính ba điểm (PERT)**
  - Thời gian lạc quan (O): Kịch bản tốt nhất
  - Thời gian bi quan (P): Kịch bản xấu nhất
  - Thời gian khả năng nhất (M): Kịch bản có khả năng xảy ra nhất
  - Ước tính trung bình: (O + 4M + P) / 6

### Phân tích mạng lịch trình
- **Phương pháp đường găng (CPM)**: Xác định chuỗi hoạt động dài nhất để tính toán thời gian sớm nhất và trễ nhất
- **Phương pháp chuỗi tới hạn (CCM)**: Tập trung vào quản lý và tối ưu hóa nguồn lực của chuỗi tới hạn
- **Kỹ thuật đánh giá và xem xét chương trình (PERT)**: Phân tích thống kê thời gian hoạt động với ước tính ba điểm
- **Phân tích kịch bản what-if**: Đánh giá tác động của các kịch bản khác nhau đến lịch trình dự án

### Tối ưu hóa lịch trình
- **Nén lịch trình**
  - Fast tracking: Thực hiện các hoạt động song song/chồng chéo
  - Crashing: Thêm nguồn lực để rút ngắn thời gian
- **Cân bằng nguồn lực**: Điều chỉnh lịch trình dựa trên nhu cầu và giới hạn nguồn lực
- **Phân tích thời gian chờ đợi**: Sử dụng thời gian nổi (float/slack) để tối ưu hóa lịch trình

## Các khái niệm quan trọng
- **Đường găng (Critical Path)**: Chuỗi hoạt động dài nhất xác định thời gian hoàn thành dự án
- **Thời gian nổi tổng thể (Total Float)**: Thời gian hoạt động có thể bị trì hoãn mà không ảnh hưởng đến ngày kết thúc dự án
- **Thời gian nổi tự do (Free Float)**: Thời gian hoạt động có thể bị trì hoãn mà không ảnh hưởng đến hoạt động tiếp theo
- **Đường cơ sở lịch trình (Schedule Baseline)**: Phiên bản được phê duyệt của mô hình lịch trình dự án
- **Mũ neo (Milestone)**: Sự kiện quan trọng trong dự án, thường là hoàn thành các kết quả bàn giao chính
- **Lịch trình tổng hợp (Master Schedule)**: Lịch trình tổng thể của dự án bao gồm các mốc và hoạt động chính

## Công cụ lập lịch trình
- **Biểu đồ Gantt**: Biểu diễn trực quan các hoạt động dự án theo thời gian
- **Biểu đồ mạng (Network Diagram)**: Biểu diễn mối quan hệ logic giữa các hoạt động
- **S-Curve**: Biểu diễn tích lũy chi phí hoặc tiến độ theo thời gian
- **Biểu đồ cột mốc (Milestone Chart)**: Tóm tắt các sự kiện quan trọng trong dự án 