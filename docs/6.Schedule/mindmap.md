# Mindmap - Quản lý lịch trình dự án (Project Schedule Management)

```
Quản lý lịch trình dự án (Project Schedule Management)
├── Quy trình quản lý lịch trình (Schedule Management Processes)
│   ├── Lập kế hoạch quản lý lịch trình (Plan Schedule Management)
│   │   ├── Xác định phương pháp lập lịch (Define scheduling methodology)
│   │   ├── Định nghĩa đơn vị đo (Define units of measure)
│   │   ├── Thiết lập ngưỡng kiểm soát (Establish control thresholds)
│   │   └── Định dạng báo cáo (Report formats)
│   │
│   ├── Xác định hoạt động (Define Activities)
│   │   ├── Phân rã từ WBS (Decomposition from WBS)
│   │   ├── Danh sách hoạt động (Activity list)
│   │   ├── Thuộc tính hoạt động (Activity attributes)
│   │   └── Danh sách mũ neo (Milestone list)
│   │
│   ├── Sắp xếp các hoạt động (Sequence Activities)
│   │   ├── Phương pháp tiền nhiệm (PDM) (Precedence Diagramming Method)
│   │   ├── Quan hệ logic (Logical relationships)
│   │   │   ├── Kết thúc-Bắt đầu (FS) (Finish-to-Start)
│   │   │   ├── Bắt đầu-Bắt đầu (SS) (Start-to-Start)
│   │   │   ├── Kết thúc-Kết thúc (FF) (Finish-to-Finish)
│   │   │   └── Bắt đầu-Kết thúc (SF) (Start-to-Finish)
│   │   │
│   │   ├── Lead và Lag (Lead and Lag)
│   │   └── Biểu đồ mạng (Network diagram)
│   │
│   ├── Ước tính thời gian hoạt động (Estimate Activity Durations)
│   │   ├── Ước tính điểm (Point estimation)
│   │   ├── Ước tính tham số (Parametric estimation)
│   │   ├── Ước tính ba điểm (PERT) (Three-point estimates)
│   │   │   ├── Lạc quan (O) (Optimistic)
│   │   │   ├── Khả năng nhất (M) (Most likely)
│   │   │   ├── Bi quan (P) (Pessimistic)
│   │   │   └── Trung bình (Average): (O+4M+P)/6
│   │   │
│   │   └── Dự trữ thời gian (Schedule reserves)
│   │
│   ├── Phát triển lịch trình (Develop Schedule)
│   │   ├── Phân tích mạng (Network analysis)
│   │   ├── Phương pháp đường găng (CPM) (Critical Path Method)
│   │   ├── Tối ưu hóa nguồn lực (Resource optimization)
│   │   ├── Nén lịch trình (Schedule compression)
│   │   │   ├── Fast tracking
│   │   │   └── Crashing
│   │   │
│   │   ├── Biểu đồ Gantt (Gantt chart)
│   │   └── Đường cơ sở lịch trình (Schedule baseline)
│   │
│   └── Kiểm soát lịch trình (Control Schedule)
│       ├── Đo lường tiến độ (Progress measurement)
│       ├── Phân tích sai lệch (Variance analysis)
│       ├── Báo cáo tiến độ (Progress reporting)
│       └── Yêu cầu thay đổi (Change requests)
│
├── Kỹ thuật lập lịch trình (Scheduling Techniques)
│   ├── Phương pháp đường găng (CPM) (Critical Path Method)
│   │   ├── Xác định chuỗi hoạt động dài nhất (Identify longest sequence of activities)
│   │   ├── Thời gian sớm nhất bắt đầu (ES) (Early Start)
│   │   ├── Thời gian sớm nhất kết thúc (EF) (Early Finish)
│   │   ├── Thời gian trễ nhất bắt đầu (LS) (Late Start)
│   │   ├── Thời gian trễ nhất kết thúc (LF) (Late Finish)
│   │   └── Thời gian nổi (Float) (Float time)
│   │
│   ├── PERT (Program Evaluation and Review Technique)
│   │   ├── Ước tính ba điểm (Three-point estimation)
│   │   ├── Phân tích xác suất (Probability analysis)
│   │   └── Biểu đồ PERT (PERT chart)
│   │
│   ├── Phương pháp chuỗi tới hạn (CCM) (Critical Chain Method)
│   │   ├── Đệm hoạt động (Activity buffer)
│   │   ├── Đệm dự án (Project buffer)
│   │   └── Đệm nguồn lực (Resource buffer)
│   │
│   └── Phương pháp Agile (Agile Methods)
│       ├── Sprint/Iteration
│       ├── Burndown chart
│       └── Velocity
│
├── Tối ưu hóa lịch trình (Schedule Optimization)
│   ├── Nén lịch trình (Schedule Compression)
│   │   ├── Fast tracking
│   │   │   ├── Thực hiện song song/chồng chéo (Perform in parallel/overlap)
│   │   │   └── Tăng rủi ro (Increases risk)
│   │   │
│   │   └── Crashing
│   │       ├── Thêm nguồn lực (Add resources)
│   │       ├── Tăng chi phí (Increases cost)
│   │       └── So sánh chi phí-lợi ích (Cost-benefit analysis)
│   │
│   ├── Điều chỉnh nguồn lực (Resource Adjustment)
│   │   ├── Cân bằng nguồn lực (Resource leveling)
│   │   ├── Làm phẳng nguồn lực (Resource smoothing)
│   │   └── Phân bổ lại nguồn lực (Resource reallocation)
│   │
│   └── Phân tích kịch bản (Scenario Analysis)
│       ├── What-if (What-if analysis)
│       └── Mô phỏng Monte Carlo (Monte Carlo simulation)
│
├── Khái niệm quan trọng (Key Concepts)
│   ├── Đường găng (Critical Path)
│   │   ├── Hoạt động găng (Critical activities)
│   │   ├── Không có thời gian nổi (Zero float)
│   │   └── Xác định thời gian dự án (Determines project duration)
│   │
│   ├── Thời gian nổi (Float Time)
│   │   ├── Thời gian nổi tổng thể (Total Float)
│   │   ├── Thời gian nổi tự do (Free Float)
│   │   └── Thời gian nổi dự án (Project Float)
│   │
│   ├── Ràng buộc lịch trình (Schedule Constraints)
│   │   ├── Bắt buộc (Mandatory) (Mandatory constraints)
│   │   ├── Tùy ý (Discretionary) (Discretionary constraints)
│   │   ├── Bên ngoài (External) (External constraints)
│   │   └── Bên trong (Internal) (Internal constraints)
│   │
│   └── Mũ neo (Milestone)
│       ├── Điểm kiểm tra (Checkpoint)
│       ├── Sự kiện quan trọng (Significant event)
│       └── Không có thời lượng (Zero duration)
│
├── Công cụ trực quan hóa (Visualization Tools)
│   ├── Biểu đồ Gantt (Gantt Chart)
│   │   ├── Thanh ngang thể hiện thời gian (Horizontal bars representing duration)
│   │   ├── Dễ hiểu, phổ biến (Easy to understand, popular)
│   │   └── Thể hiện quan hệ phụ thuộc (Shows dependencies)
│   │
│   ├── Biểu đồ mạng (Network Diagram)
│   │   ├── AON (Activity-on-Node)
│   │   ├── AOA (Activity-on-Arrow)
│   │   └── Thể hiện mối quan hệ logic (Shows logical relationships)
│   │
│   └── S-Curve
│       ├── Thể hiện tiến độ tích lũy (Shows cumulative progress)
│       ├── So sánh kế hoạch vs thực tế (Compares planned vs. actual)
│       └── Dự báo xu hướng (Forecasts trends)
│
└── Mẹo thi PMP (PMP Exam Tips)
    ├── Trình tự quy trình (Process Sequence)
    │   ├── Hiểu thứ tự của 6 quy trình (Understand sequence of 6 processes)
    │   └── Biết nhóm quy trình tương ứng (Know corresponding process groups)
    │
    ├── Tính toán (Calculations)
    │   ├── Công thức PERT (PERT formula)
    │   ├── Tính thời gian nổi (Calculate float)
    │   └── Xác định đường găng (Identify critical path)
    │
    ├── Kỹ thuật nén lịch trình (Schedule Compression)
    │   ├── Fast tracking trước crashing (Fast tracking before crashing)
    │   └── Hiểu ưu/nhược điểm (Understand pros/cons)
    │
    └── Xung đột nguồn lực (Resource Conflicts)
        ├── Giải quyết xung đột (Resolve conflicts)
        └── Thứ tự ưu tiên (Prioritization)
```

## Những điểm quan trọng cần nhớ (Key Points to Remember)

### 1. Phương pháp đường găng (Critical Path Method)

- **Đường găng** xác định thời gian tối thiểu để hoàn thành dự án
- **Hoạt động găng** là những hoạt động không có thời gian nổi (Float = 0)
- Trễ bất kỳ hoạt động găng nào sẽ làm trễ toàn bộ dự án
- Để rút ngắn thời gian dự án, phải rút ngắn đường găng
- Tính toán đường găng bằng cách xác định **ES, EF, LS, LF** cho mỗi hoạt động

### 2. Kỹ thuật nén lịch trình (Schedule Compression)

- **Fast tracking**: Thực hiện các hoạt động song song/chồng chéo thay vì tuần tự
  - Không tốn thêm chi phí nhưng tăng rủi ro
  - Chỉ có thể áp dụng cho các hoạt động có thể chồng chéo
- **Crashing**: Thêm nguồn lực để rút ngắn thời gian
  - Tăng chi phí dự án
  - Chọn hoạt động có tỷ lệ chi phí-thời gian tốt nhất
- Trong kỳ thi, nên cân nhắc **fast tracking trước, sau đó mới crashing**

### 3. Các loại quan hệ logic (Logical Relationships)

- **Kết thúc-Bắt đầu (FS)**: Quan hệ phổ biến nhất - B chỉ có thể bắt đầu sau khi A kết thúc
- **Bắt đầu-Bắt đầu (SS)**: B có thể bắt đầu sau khi A bắt đầu
- **Kết thúc-Kết thúc (FF)**: B chỉ có thể kết thúc sau khi A kết thúc
- **Bắt đầu-Kết thúc (SF)**: Hiếm gặp - B chỉ có thể kết thúc sau khi A bắt đầu
- **Lead**: Thời gian đẩy nhanh hoạt động kế tiếp (số âm)
- **Lag**: Thời gian trì hoãn giữa các hoạt động (số dương)

### 4. Điều chỉnh nguồn lực (Resource Adjustment)

- **Cân bằng nguồn lực (Resource leveling)**: Điều chỉnh lịch trình khi nguồn lực bị hạn chế
  - Có thể làm thay đổi đường găng
  - Thường kéo dài thời gian dự án
- **Làm phẳng nguồn lực (Resource smoothing)**: Điều chỉnh trong giới hạn thời gian nổi
  - Không thay đổi ngày kết thúc dự án
  - Tận dụng thời gian nổi của các hoạt động không găng

### 5. Mẹo làm bài thi PMP (PMP Exam Tips)

- Biết công thức PERT: **(O + 4M + P) / 6**
- Hiểu rõ sự khác biệt giữa **thời gian nổi tổng thể và thời gian nổi tự do**
- Biết cách xác định đường găng và tính toán thời gian dự án
- Nhận biết các ràng buộc lịch trình và tác động của chúng
- Trong câu hỏi về nén lịch trình, ưu tiên fast tracking nếu không đề cập đến chi phí 