# Quản lý lịch trình dự án | Project Schedule Management

## Định nghĩa và tầm quan trọng | Definition and Importance
- **Quản lý lịch trình | Schedule Management**: Quá trình lập kế hoạch, phát triển, quản lý, thực hiện và kiểm soát lịch trình dự án | The process of planning, developing, managing, executing, and controlling the project schedule
- **Lịch trình dự án | Project Schedule**: Xác định thời gian bắt đầu, thời gian kết thúc và thời gian thực hiện các hoạt động dự án | Determines the start time, end time, and duration of project activities
- **Tầm quan trọng | Importance**: Quản lý lịch trình hiệu quả giúp dự án hoàn thành đúng thời hạn, tối ưu hóa nguồn lực và kiểm soát chi phí | Effective schedule management helps complete projects on time, optimize resources, and control costs

## Các quy trình quản lý lịch trình | Schedule Management Processes

### 1. Lập kế hoạch quản lý lịch trình | Plan Schedule Management
Thiết lập chính sách, thủ tục và tài liệu để lập kế hoạch, phát triển, quản lý, thực hiện và kiểm soát lịch trình dự án | Establishing policies, procedures, and documentation for planning, developing, managing, executing, and controlling the project schedule

### 2. Xác định hoạt động | Define Activities
Xác định và tài liệu hóa các hành động cụ thể cần thực hiện để tạo ra kết quả bàn giao dự án | Identifying and documenting the specific actions to be performed to produce project deliverables

### 3. Sắp xếp các hoạt động | Sequence Activities
Xác định và ghi lại mối quan hệ giữa các hoạt động dự án | Identifying and documenting relationships among project activities

### 4. Ước tính thời gian hoạt động | Estimate Activity Durations
Ước tính số kỳ làm việc cần thiết để hoàn thành từng hoạt động với các nguồn lực dự kiến | Estimating the number of work periods needed to complete individual activities with estimated resources

### 5. Phát triển lịch trình | Develop Schedule
Phân tích trình tự hoạt động, thời lượng, yêu cầu nguồn lực và ràng buộc lịch trình để tạo mô hình lịch trình dự án | Analyzing activity sequences, durations, resource requirements, and schedule constraints to create the project schedule model

### 6. Kiểm soát lịch trình | Control Schedule
Giám sát trạng thái dự án để cập nhật tiến độ và quản lý thay đổi đối với đường cơ sở lịch trình | Monitoring project status to update project progress and manage changes to the schedule baseline

## Công cụ và kỹ thuật lập lịch trình | Schedule Tools and Techniques
### Phương pháp xác định mối quan hệ giữa các hoạt động | Activity Relationship Methods
- **Phương pháp tiền nhiệm (PDM) | Precedence Diagramming Method (PDM)**: Sử dụng các mối quan hệ logic giữa các hoạt động | Using logical relationships between activities
  - **Kết thúc-Bắt đầu (FS) | Finish-to-Start (FS)**: Hoạt động trước phải kết thúc trước khi hoạt động sau có thể bắt đầu | Predecessor must finish before successor can start
  - **Bắt đầu-Bắt đầu (SS) | Start-to-Start (SS)**: Hoạt động trước phải bắt đầu trước khi hoạt động sau có thể bắt đầu | Predecessor must start before successor can start
  - **Kết thúc-Kết thúc (FF) | Finish-to-Finish (FF)**: Hoạt động trước phải kết thúc trước khi hoạt động sau có thể kết thúc | Predecessor must finish before successor can finish
  - **Bắt đầu-Kết thúc (SF) | Start-to-Finish (SF)**: Hoạt động trước phải bắt đầu trước khi hoạt động sau có thể kết thúc | Predecessor must start before successor can finish
- **Thời gian Lead và Lag | Lead and Lag Time**
  - **Lead time | Lead time**: Đẩy nhanh hoạt động kế tiếp | Accelerates the successor activity
  - **Lag time | Lag time**: Trì hoãn hoạt động kế tiếp | Delays the successor activity

### Ước tính | Estimation
- **Ước tính điểm | Point Estimation**: Ước tính đơn giá trị dựa trên trực giác hoặc kinh nghiệm | Single-value estimate based on intuition or experience
- **Ước tính tham số | Parametric Estimation**: Sử dụng mối quan hệ thống kê giữa dữ liệu lịch sử và các biến số khác | Using statistical relationships between historical data and other variables
- **Ước tính ba điểm (PERT) | Three-Point Estimates (PERT)**
  - **Thời gian lạc quan (O) | Optimistic Time (O)**: Kịch bản tốt nhất | Best-case scenario
  - **Thời gian bi quan (P) | Pessimistic Time (P)**: Kịch bản xấu nhất | Worst-case scenario
  - **Thời gian khả năng nhất (M) | Most Likely Time (M)**: Kịch bản có khả năng xảy ra nhất | Most probable scenario
  - **Ước tính trung bình | Average Estimate**: (O + 4M + P) / 6 | (O + 4M + P) / 6

### Phân tích mạng lịch trình | Schedule Network Analysis
- **Phương pháp đường găng (CPM) | Critical Path Method (CPM)**: Xác định chuỗi hoạt động dài nhất để tính toán thời gian sớm nhất và trễ nhất | Identifying the longest sequence of activities to calculate early and late times
- **Phương pháp chuỗi tới hạn (CCM) | Critical Chain Method (CCM)**: Tập trung vào quản lý và tối ưu hóa nguồn lực của chuỗi tới hạn | Focusing on managing and optimizing resources of the critical chain
- **Kỹ thuật đánh giá và xem xét chương trình (PERT) | Program Evaluation and Review Technique (PERT)**: Phân tích thống kê thời gian hoạt động với ước tính ba điểm | Statistical analysis of activity times with three-point estimates
- **Phân tích kịch bản what-if | What-If Scenario Analysis**: Đánh giá tác động của các kịch bản khác nhau đến lịch trình dự án | Evaluating the impact of different scenarios on the project schedule

## Phân tích đường găng (Critical Path Method - CPM) | Critical Path Method (CPM) Analysis

### Định nghĩa | Definition
- **Biểu đồ găng (CPM)** là kỹ thuật lập lịch trình xác định chuỗi các hoạt động dài nhất (đường găng) và tính toán thời gian hoàn thành sớm nhất của dự án.
- **Critical Path Method (CPM)** is a scheduling technique that identifies the longest sequence of dependent activities (the critical path) and calculates the earliest project completion time.

### Mục đích và tầm quan trọng | Purpose and Importance
- Xác định các hoạt động then chốt quyết định thời gian hoàn thành dự án | Identifies key activities that determine the project's duration
- Giúp quản lý tiến độ, phân bổ nguồn lực hiệu quả | Helps manage schedule and allocate resources efficiently
- Phát hiện các hoạt động có thể bị trì hoãn mà không ảnh hưởng đến tổng tiến độ | Identifies activities that can be delayed without affecting the overall schedule (float/slack)
- Là công cụ quan trọng trong kiểm soát tiến độ và ra quyết định | Essential tool for schedule control and decision-making

### Các bước thực hiện CPM | Steps in CPM
1. **Liệt kê các hoạt động dự án | List Project Activities**
   - Xác định tất cả các công việc cần thiết để hoàn thành dự án | Identify all tasks required to complete the project
2. **Xác định mối quan hệ phụ thuộc | Define Dependencies**
   - Xác định thứ tự thực hiện và các mối quan hệ giữa các hoạt động (FS, SS, FF, SF) | Define the sequence and dependencies (Finish-to-Start, Start-to-Start, etc.)
3. **Ước tính thời lượng từng hoạt động | Estimate Activity Durations**
   - Ước tính thời gian cần thiết cho mỗi hoạt động | Estimate the duration for each activity
4. **Vẽ sơ đồ mạng lưới | Draw the Network Diagram**
   - Biểu diễn các hoạt động và mối quan hệ bằng sơ đồ mạng (Network Diagram) | Represent activities and dependencies in a network diagram
5. **Xác định đường găng | Identify the Critical Path**
   - Tính toán thời gian sớm nhất (Early Start/Finish) và trễ nhất (Late Start/Finish) cho từng hoạt động | Calculate Early Start (ES), Early Finish (EF), Late Start (LS), Late Finish (LF) for each activity
   - Đường găng là chuỗi hoạt động có tổng thời gian dài nhất, không có thời gian nổi (Total Float = 0) | The critical path is the longest path through the network, with zero total float
6. **Tính toán thời gian nổi (Float/Slack) | Calculate Float/Slack**
   - **Total Float**: Thời gian một hoạt động có thể bị trì hoãn mà không làm trễ dự án | Time an activity can be delayed without delaying the project
   - **Free Float**: Thời gian một hoạt động có thể bị trì hoãn mà không làm trễ hoạt động tiếp theo | Time an activity can be delayed without delaying the next activity

### Ký hiệu và công thức quan trọng | Key Notations and Formulas
- **ES (Early Start)**: Thời điểm sớm nhất có thể bắt đầu | Earliest possible start time
- **EF (Early Finish)**: ES + Duration | ES + Thời lượng
- **LS (Late Start)**: Thời điểm trễ nhất có thể bắt đầu mà không làm trễ dự án | Latest possible start time without delaying the project
- **LF (Late Finish)**: LS + Duration | LS + Thời lượng
- **Total Float** = LS - ES = LF - EF
- **Free Float** = ES của hoạt động kế tiếp - EF của hoạt động hiện tại

### Ví dụ minh họa | Example
**Giả sử có các hoạt động sau:**
| Hoạt động | Thời lượng (ngày) | Tiền nhiệm |
|-----------|-------------------|-----------|
| A         | 2                 | -         |
| B         | 4                 | A         |
| C         | 3                 | A         |
| D         | 2                 | B, C      |

**Sơ đồ mạng:**
- A → B → D
- A → C → D

**Tính đường găng:**
- Đường A-B-D: 2 + 4 + 2 = 8 ngày
- Đường A-C-D: 2 + 3 + 2 = 7 ngày
- **Đường găng là A-B-D (8 ngày)**

### Ứng dụng thực tế và mẹo thi PMP | Practical Use & PMP Exam Tips
- **Hoạt động trên đường găng có Total Float = 0** | Activities on the critical path have zero total float
- **Nếu một hoạt động trên đường găng bị trễ, toàn bộ dự án sẽ bị trễ** | If a critical path activity is delayed, the whole project is delayed
- **Có thể có nhiều hơn một đường găng** | There can be more than one critical path
- **Đường găng có thể thay đổi trong quá trình thực hiện dự án** | The critical path can change as the project progresses
- **PMP Exam:** Câu hỏi thường yêu cầu xác định đường găng, tính float, hoặc tác động của việc thay đổi thời lượng hoạt động | PMP questions often ask to identify the critical path, calculate float, or assess the impact of duration changes

### Công cụ hỗ trợ | Tools
- **Biểu đồ mạng (Network Diagram)**
- **Phần mềm quản lý dự án (MS Project, Primavera, v.v.)**
- **Gantt Chart**: Dùng để trực quan hóa tiến độ, nhưng CPM mới là công cụ phân tích đường găng | Gantt charts visualize schedule, but CPM is used for critical path analysis

**Tóm tắt nhanh | Quick Summary:**
- Đường găng = Chuỗi hoạt động dài nhất, quyết định thời gian dự án
- Hoạt động trên đường găng: Total Float = 0
- Biết cách vẽ sơ đồ mạng, tính ES, EF, LS, LF, Float
- Ứng dụng CPM để kiểm soát tiến độ, tối ưu nguồn lực, và trả lời các câu hỏi PMP về tiến độ

### Tối ưu hóa lịch trình | Schedule Optimization
- **Nén lịch trình | Schedule Compression**
  - **Fast tracking | Fast Tracking**: Thực hiện các hoạt động song song/chồng 
  chéo | Performing activities in parallel/overlapping
  - **Crashing | Crashing**: Thêm nguồn lực để rút ngắn thời gian | Adding 
  resources to shorten duration
- **Cân bằng nguồn lực | Resource Leveling**: Điều chỉnh lịch trình dựa trên nhu 
cầu và giới hạn nguồn lực | Adjusting the schedule based on resource demands and 
constraints
- **Phân tích thời gian chờ đợi | Float Analysis**: Sử dụng thời gian nổi (float/
slack) để tối ưu hóa lịch trình | Using float/slack time to optimize the schedule

## Các khái niệm quan trọng | Key Concepts
- **Đường găng (Critical Path) | Critical Path**: Chuỗi hoạt động dài nhất xác định thời gian hoàn thành dự án | The longest sequence of activities that determines project completion time
- **Thời gian nổi tổng thể (Total Float) | Total Float**: Thời gian hoạt động có thể bị trì hoãn mà không ảnh hưởng đến ngày kết thúc dự án | Time an activity can be delayed without affecting the project end date
- **Thời gian nổi tự do (Free Float) | Free Float**: Thời gian hoạt động có thể bị trì hoãn mà không ảnh hưởng đến hoạt động tiếp theo | Time an activity can be delayed without affecting the next activity
- **Đường cơ sở lịch trình (Schedule Baseline) | Schedule Baseline**: Phiên bản được phê duyệt của mô hình lịch trình dự án | The approved version of the project schedule model
- **Mũ neo (Milestone) | Milestone**: Sự kiện quan trọng trong dự án, thường là hoàn thành các kết quả bàn giao chính | A significant event in a project, typically completion of major deliverables
- **Lịch trình tổng hợp (Master Schedule) | Master Schedule**: Lịch trình tổng thể của dự án bao gồm các mốc và hoạt động chính | Overall project schedule including key milestones and activities

## Công cụ lập lịch trình | Scheduling Tools
- **Biểu đồ Gantt | Gantt Chart**: Biểu diễn trực quan các hoạt động dự án theo thời gian | Visual representation of project activities over time
- **Biểu đồ mạng (Network Diagram) | Network Diagram**: Biểu diễn mối quan hệ logic giữa các hoạt động | Representation of logical relationships between activities
- **S-Curve | S-Curve**: Biểu diễn tích lũy chi phí hoặc tiến độ theo thời gian | Representation of cumulative cost or progress over time
- **Biểu đồ cột mốc (Milestone Chart) | Milestone Chart**: Tóm tắt các sự kiện quan trọng trong dự án | Summary of significant events in the project

## Mẹo thi PMP về Quản lý Lịch trình | PMP Exam Tips on Schedule Management
- **Ghi nhớ các loại quan hệ phụ thuộc | Remember dependency types**: Bắt buộc, Tùy ý, Bên ngoài, Nội bộ | Mandatory, Discretionary, External, Internal
- **Hiểu rõ đường găng | Understand the critical path**: Chuỗi hoạt động dài nhất quyết định thời gian dự án; hoạt động trên đường găng có thời gian nổi bằng 0 | Longest sequence of activities that determines project duration; activities on critical path have zero float
- **Phân biệt Fast tracking và Crashing | Distinguish between Fast tracking and Crashing**: Fast tracking tăng rủi ro, Crashing tăng chi phí | Fast tracking increases risk, Crashing increases cost
- **Thành thạo ước tính | Master estimation techniques**: Hiểu các ưu điểm và nhược điểm của từng phương pháp | Understand advantages and disadvantages of each method
- **Nắm vững công thức PERT | Know PERT formula**: (O + 4M + P) / 6 cho ước tính trung bình, sqrt[(P-O)/6] cho độ lệch chuẩn | (O + 4M + P) / 6 for average estimate, sqrt[(P-O)/6] for standard deviation
- **Hiểu thời gian nổi | Understand float time**: Thời gian nổi tổng thể ảnh hưởng đến dự án, thời gian nổi tự do ảnh hưởng đến hoạt động tiếp theo | Total float affects project, free float affects next activity

# Quy trình liên quan đến Tiến độ | Schedule-related Processes

## Sơ đồ quy trình tiến độ | Schedule Process Map

```
Planning (Lập kế hoạch)
├── Plan Schedule Management (Lập kế hoạch QL tiến độ)
├── Define Activities (Xác định hoạt động)
├── Sequence Activities (Sắp xếp thứ tự hoạt động)
├── Estimate Activity Durations (Ước lượng thời lượng)
├── Develop Schedule (Lập tiến độ)
Monitoring & Controlling (Giám sát & Kiểm soát)
├── Control Schedule (Kiểm soát tiến độ)
```

| Quy trình | Nhóm quy trình | Mô tả | Đầu vào chính | Đầu ra chính |
|-----------|----------------|-------|---------------|--------------|
| Plan Schedule Management | Planning | Xác định cách lập kế hoạch, phát triển, quản lý tiến độ | Project Charter, Project Management Plan | Schedule Management Plan |
| Define Activities | Planning | Xác định các hoạt động cần thiết để hoàn thành các gói công việc | Scope Baseline, EEFs, OPAs | Activity List, Activity Attributes |
| Sequence Activities | Planning | Sắp xếp thứ tự các hoạt động, xác định mối quan hệ logic | Activity List, Milestone List | Project Schedule Network Diagrams |
| Estimate Activity Durations | Planning | Ước lượng thời lượng cần thiết cho từng hoạt động | Activity List, Resource Calendars | Duration Estimates |
| Develop Schedule | Planning | Phân tích trình tự, thời lượng, nguồn lực để tạo lịch trình dự án | Activity List, Duration Estimates | Project Schedule, Schedule Baseline |
| Control Schedule | Monitoring & Controlling | Theo dõi tiến độ, quản lý thay đổi lịch trình | Project Schedule, Work Performance Data | Schedule Forecasts, Change Requests |

> Xem chi tiết từng quy trình ở các phần bên dưới. 