# Phân tích giá trị thu được (EVM) | Earned Value Management (EVM)

## Định nghĩa và tầm quan trọng | Definition and Importance

**Phân tích giá trị thu được (EVM)** là một kỹ thuật quản lý dự án để đo lường khách quan hiệu suất dự án về phạm vi, lịch trình và chi phí. | **Earned Value Management (EVM)** is a project management technique for objectively measuring project performance against scope, schedule, and cost.

### Tầm quan trọng của EVM | Importance of EVM
- Cung cấp cái nhìn tích hợp về tiến độ dự án | Provides an integrated view of project progress
- Cho phép dự báo chính xác về chi phí và thời gian hoàn thành | Allows accurate forecasting of completion costs and times
- Phát hiện sớm các vấn đề và xu hướng | Early detection of problems and trends
- Cung cấp dữ liệu khách quan cho việc ra quyết định | Provides objective data for decision-making

## Các khái niệm cơ bản | Basic Concepts

### 1. Giá trị kế hoạch (PV - Planned Value)
- **Định nghĩa**: Chi phí ngân sách của công việc theo kế hoạch | **Definition**: Budgeted cost of work scheduled
- **Cách tính**: PV = % công việc theo kế hoạch × Ngân sách tổng | **Calculation**: PV = % work planned × Total budget

### 2. Giá trị thu được (EV - Earned Value)
- **Định nghĩa**: Chi phí ngân sách của công việc đã thực hiện | **Definition**: Budgeted cost of work performed
- **Cách tính**: EV = % công việc hoàn thành × Ngân sách tổng | **Calculation**: EV = % work completed × Total budget

### 3. Chi phí thực tế (AC - Actual Cost)
- **Định nghĩa**: Chi phí thực tế phát sinh cho công việc đã thực hiện | **Definition**: Actual cost incurred for work performed
- **Cách tính**: Tổng chi phí thực tế đã chi | **Calculation**: Sum of actual costs spent

### 4. Ngân sách khi hoàn thành (BAC - Budget At Completion)
- **Định nghĩa**: Tổng ngân sách dự án | **Definition**: Total project budget
- **Cách tính**: Tổng chi phí kế hoạch cho toàn bộ dự án | **Calculation**: Total planned cost for entire project

## Chỉ số hiệu suất | Performance Indices

### 1. Chênh lệch lịch trình (SV - Schedule Variance)
- **Định nghĩa**: Chênh lệch giữa công việc đã hoàn thành so với kế hoạch | **Definition**: Difference between work completed and planned
- **Công thức**: SV = EV - PV | **Formula**: SV = EV - PV
- **Diễn giải**: | **Interpretation**:
  - SV > 0: Trước tiến độ | Ahead of schedule
  - SV = 0: Đúng tiến độ | On schedule
  - SV < 0: Chậm tiến độ | Behind schedule

### 2. Chênh lệch chi phí (CV - Cost Variance)
- **Định nghĩa**: Chênh lệch giữa giá trị thu được và chi phí thực tế | **Definition**: Difference between earned value and actual cost
- **Công thức**: CV = EV - AC | **Formula**: CV = EV - AC
- **Diễn giải**: | **Interpretation**:
  - CV > 0: Dưới ngân sách | Under budget
  - CV = 0: Đúng ngân sách | On budget
  - CV < 0: Vượt ngân sách | Over budget

### 3. Chỉ số hiệu suất lịch trình (SPI - Schedule Performance Index)
- **Định nghĩa**: Tỷ lệ giữa công việc hoàn thành và công việc theo kế hoạch | **Definition**: Ratio of work completed to work planned
- **Công thức**: SPI = EV / PV | **Formula**: SPI = EV / PV
- **Diễn giải**: | **Interpretation**:
  - SPI > 1: Nhanh hơn kế hoạch | Faster than planned
  - SPI = 1: Đúng tiến độ | On schedule
  - SPI < 1: Chậm hơn kế hoạch | Slower than planned

### 4. Chỉ số hiệu suất chi phí (CPI - Cost Performance Index)
- **Định nghĩa**: Tỷ lệ giữa giá trị thu được và chi phí thực tế | **Definition**: Ratio of earned value to actual cost
- **Công thức**: CPI = EV / AC | **Formula**: CPI = EV / AC
- **Diễn giải**: | **Interpretation**:
  - CPI > 1: Hiệu quả về chi phí, tiết kiệm | Cost efficient, saving money
  - CPI = 1: Chi phí chính xác như kế hoạch | Costs exactly as planned
  - CPI < 1: Không hiệu quả về chi phí, tốn kém | Cost inefficient, wasting money

## Dự báo | Forecasting

### 1. Ước tính khi hoàn thành (EAC - Estimate At Completion)
- **Định nghĩa**: Tổng chi phí dự kiến khi dự án hoàn thành | **Definition**: Total expected cost when project is complete
- **Công thức phổ biến**: | **Common formulas**:
  - EAC = AC + (BAC - EV) [khi sai số không lặp lại] | EAC = AC + (BAC - EV) [when variance is not typical]
  - EAC = AC + (BAC - EV) / CPI [khi sai số điển hình] | EAC = AC + (BAC - EV) / CPI [when variance is typical]
  - EAC = BAC / CPI [khi giả định CPI không thay đổi] | EAC = BAC / CPI [when assuming CPI remains constant]

### 2. Ước tính để hoàn thành (ETC - Estimate To Complete)
- **Định nghĩa**: Chi phí dự kiến cần thiết để hoàn thành công việc còn lại | **Definition**: Expected cost needed to complete remaining work
- **Công thức**: ETC = EAC - AC | **Formula**: ETC = EAC - AC

### 3. Chỉ số hiệu suất để hoàn thành (TCPI - To-Complete Performance Index)
- **Định nghĩa**: Hiệu quả chi phí cần thiết để đạt mục tiêu | **Definition**: Cost efficiency needed to achieve goal
- **Công thức**: | **Formula**:
  - TCPI = (BAC - EV) / (BAC - AC) [để đạt BAC] | TCPI = (BAC - EV) / (BAC - AC) [to achieve BAC]
  - TCPI = (BAC - EV) / (EAC - AC) [để đạt EAC] | TCPI = (BAC - EV) / (EAC - AC) [to achieve EAC]

## Ví dụ thực tế | Practical Example

### Ví dụ: Dự án phát triển phần mềm | Example: Software development project

**Dữ liệu đầu vào** | **Input data**:
- Ngân sách dự án (BAC): $500,000 | Project budget (BAC): $500,000
- % Công việc theo kế hoạch: 40% | % Work planned: 40%
- % Công việc thực tế hoàn thành: 30% | % Work actually completed: 30%
- Chi phí thực tế đã chi: $180,000 | Actual cost spent: $180,000

**Tính toán cơ bản** | **Basic calculations**:
- PV = 40% × $500,000 = $200,000
- EV = 30% × $500,000 = $150,000
- AC = $180,000

**Phân tích hiệu suất** | **Performance analysis**:
- SV = EV - PV = $150,000 - $200,000 = -$50,000
- CV = EV - AC = $150,000 - $180,000 = -$30,000
- SPI = EV / PV = $150,000 / $200,000 = 0.75
- CPI = EV / AC = $150,000 / $180,000 = 0.83

**Diễn giải** | **Interpretation**:
- Dự án chậm tiến độ (SV âm, SPI < 1) | Project is behind schedule (negative SV, SPI < 1)
- Dự án vượt ngân sách (CV âm, CPI < 1) | Project is over budget (negative CV, CPI < 1)
- Đã hoàn thành 75% công việc dự kiến (SPI = 0.75) | Completed 75% of planned work (SPI = 0.75)
- Mỗi $1 chi tiêu mang lại giá trị $0.83 (CPI = 0.83) | Each $1 spent yields $0.83 in value (CPI = 0.83)

**Dự báo** | **Forecasts**:
- EAC (giả định CPI không thay đổi) = BAC / CPI = $500,000 / 0.83 = $602,410
- ETC = EAC - AC = $602,410 - $180,000 = $422,410
- TCPI (để đạt BAC) = (BAC - EV) / (BAC - AC) = ($500,000 - $150,000) / ($500,000 - $180,000) = $350,000 / $320,000 = 1.09

**Kết luận** | **Conclusion**:
- Dự án dự kiến vượt ngân sách $102,410 | Project forecasted to exceed budget by $102,410
- Để đạt được ngân sách ban đầu, hiệu suất chi phí phải tăng 9% | To meet original budget, cost performance must improve by 9%
- Cần phải đánh giá lại kế hoạch dự án | Project plan needs to be reevaluated

## EVM trong môi trường Agile | EVM in Agile Environments

Trong dự án Agile, EVM được điều chỉnh như sau | In Agile projects, EVM is adapted as follows:

### AgileEVM | AgileEVM
- **Story Point**: Đơn vị đo lường công việc thay vì giờ công | **Story Point**: Unit of work measurement instead of labor hours
- **Release**: Tương đương với dự án/giai đoạn | **Release**: Equivalent to project/phase
- **Sprint**: Đơn vị thời gian để đo lường tiến độ | **Sprint**: Time unit for measuring progress

### Các metric AgileEVM | AgileEVM metrics
- **Planned Value**: Story points theo kế hoạch trong sprint | **Planned Value**: Planned story points in a sprint
- **Earned Value**: Story points hoàn thành | **Earned Value**: Completed story points
- **Actual Cost**: Chi phí thực tế phát sinh | **Actual Cost**: Actual cost incurred

### Lợi ích của AgileEVM | Benefits of AgileEVM
- Kết hợp tính linh hoạt của Agile với độ chính xác của EVM | Combines Agile flexibility with EVM accuracy
- Giúp các tổ chức chuyển tiếp từ truyền thống sang Agile | Helps organizations transition from traditional to Agile
- Cung cấp cái nhìn toàn diện về hiệu suất dự án | Provides comprehensive view of project performance

## Thực hành tốt nhất | Best Practices

1. **Thiết lập cơ sở đo lường hiệu suất** | **Establish performance measurement baseline**
   - Xác định WBS chi tiết | Define detailed WBS
   - Phân bổ ngân sách cho mỗi gói công việc | Allocate budget to each work package
   - Lên lịch các hoạt động dự án | Schedule project activities

2. **Thu thập dữ liệu chính xác** | **Collect accurate data**
   - Đo lường công việc đã hoàn thành một cách nhất quán | Measure completed work consistently
   - Theo dõi chi phí thực tế kịp thời | Track actual costs in timely manner
   - Sử dụng nguyên tắc đo lường tiến độ khách quan | Use objective progress measurement rules

3. **Báo cáo và phân tích thường xuyên** | **Regular reporting and analysis**
   - Tính toán các chỉ số EVM ít nhất hàng tháng | Calculate EVM metrics at least monthly
   - Phân tích xu hướng qua thời gian | Analyze trends over time
   - Tập trung vào các vấn đề và nguyên nhân gốc rễ | Focus on issues and root causes

4. **Hành động dựa trên kết quả EVM** | **Act on EVM results**
   - Phát triển kế hoạch khắc phục cho sai lệch | Develop corrective plans for variances
   - Điều chỉnh chiến lược dự án khi cần thiết | Adjust project strategies when necessary
   - Cập nhật kế hoạch dự án khi được phê duyệt | Update project plan when approved

## Những thách thức phổ biến và giải pháp | Common Challenges and Solutions

### 1. Ước tính % hoàn thành không chính xác | Inaccurate % complete estimates
- **Thách thức**: Ước tính chủ quan có thể làm sai lệch EV | **Challenge**: Subjective estimates can distort EV
- **Giải pháp**: Sử dụng quy tắc đo lường khách quan (0/100, 50/50, cột mốc) | **Solution**: Use objective measurement rules (0/100, 50/50, milestones)

### 2. Thu thập dữ liệu chi phí kịp thời | Timely cost data collection
- **Thách thức**: Dữ liệu chi phí thường bị trễ | **Challenge**: Cost data often lags
- **Giải pháp**: Cải thiện quy trình thu thập, sử dụng ước tính | **Solution**: Improve collection processes, use estimates

### 3. Hiểu sai các chỉ số | Misinterpreting indices
- **Thách thức**: CPI/SPI không nói lên toàn bộ câu chuyện | **Challenge**: CPI/SPI don't tell whole story
- **Giải pháp**: Xem xét nhiều chỉ số, phân tích nguyên nhân | **Solution**: Consider multiple indices, analyze causes

### 4. Báo cáo vấn đề | Reporting issues
- **Thách thức**: Miễn cưỡng báo cáo tin xấu | **Challenge**: Reluctance to report bad news
- **Giải pháp**: Tạo văn hóa minh bạch, tập trung vào giải pháp | **Solution**: Create transparency culture, focus on solutions

## Kết luận | Conclusion

Phân tích giá trị thu được (EVM) là công cụ mạnh mẽ để theo dõi và dự báo hiệu suất dự án. Bằng cách kết hợp đo lường phạm vi, lịch trình và chi phí, EVM cung cấp cái nhìn toàn diện về tình trạng dự án. | Earned Value Management (EVM) is a powerful tool for tracking and forecasting project performance. By combining measurements of scope, schedule, and cost, EVM provides a comprehensive view of project status.

Khi áp dụng đúng, EVM cho phép các nhà quản lý dự án: | When properly applied, EVM allows project managers to:
- Phát hiện vấn đề sớm | Detect problems early
- Dự báo kết quả chính xác | Forecast outcomes accurately
- Đưa ra quyết định dựa trên dữ liệu | Make data-driven decisions
- Truyền đạt tình trạng dự án một cách khách quan | Communicate project status objectively

Dù trong môi trường truyền thống hay Agile, các nguyên tắc của EVM vẫn có thể được áp dụng và điều chỉnh để mang lại cái nhìn rõ ràng về hiệu suất dự án. | Whether in traditional or Agile environments, EVM principles can be applied and adapted to provide clear visibility into project performance. 