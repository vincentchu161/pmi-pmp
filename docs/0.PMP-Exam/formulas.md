# Công thức quan trọng cho kỳ thi PMP (Important Formulas for PMP Exam)

## 1. Ước tính thời gian (Duration Estimation)

### PERT (Program Evaluation and Review Technique)
```
E = (O + 4M + P) / 6
```

**English:**
- E: Expected duration
- O: Optimistic time
- M: Most likely time
- P: Pessimistic time

**Standard Deviation**: σ = (P - O) / 6  
**Variance**: σ² = [(P - O) / 6]²

**Application**: Used for estimating activity durations with high uncertainty.

**Tiếng Việt:**
- E: Ước tính thời gian dự kiến
- O: Thời gian lạc quan
- M: Thời gian khả năng nhất
- P: Thời gian bi quan

**Độ lệch chuẩn**: σ = (P - O) / 6  
**Phương sai**: σ² = [(P - O) / 6]²

**Cách áp dụng**: Sử dụng khi cần ước tính thời gian hoạt động có độ không chắc chắn cao.

## 2. Quản lý giá trị thu được (Earned Value Management - EVM)

### Basic Indices (Các chỉ số cơ bản)

**English:**
- **PV (Planned Value)**: Planned cost at reporting time
- **EV (Earned Value)**: % complete × BAC
- **AC (Actual Cost)**: Actual costs incurred at reporting time
- **BAC (Budget At Completion)**: Total project budget

**Tiếng Việt:**
- **PV (Planned Value - Giá trị kế hoạch)**: Chi phí theo kế hoạch tại thời điểm báo cáo
- **EV (Earned Value - Giá trị thu được)**: % hoàn thành × BAC
- **AC (Actual Cost - Chi phí thực tế)**: Chi phí thực tế đã chi tại thời điểm báo cáo
- **BAC (Budget At Completion - Tổng ngân sách dự án)**: Tổng ngân sách dự án

### Variance Indices (Chỉ số sai lệch)

**English:**
- **CV (Cost Variance)** = EV - AC
  - CV > 0: Under budget (good)
  - CV < 0: Over budget (bad)
- **SV (Schedule Variance)** = EV - PV
  - SV > 0: Ahead of schedule (good)
  - SV < 0: Behind schedule (bad)

**Tiếng Việt:**
- **CV (Cost Variance - Chênh lệch chi phí)** = EV - AC
  - CV > 0: Dưới ngân sách (tốt)
  - CV < 0: Vượt ngân sách (xấu)
- **SV (Schedule Variance - Chênh lệch tiến độ)** = EV - PV
  - SV > 0: Trước tiến độ (tốt)
  - SV < 0: Chậm tiến độ (xấu)

### Performance Indices (Chỉ số hiệu suất)

**English:**
- **CPI (Cost Performance Index)** = EV / AC
  - CPI > 1: Cost efficient (good)
  - CPI < 1: Cost inefficient (bad)
- **SPI (Schedule Performance Index)** = EV / PV
  - SPI > 1: Ahead of schedule (good)
  - SPI < 1: Behind schedule (bad)

**Tiếng Việt:**
- **CPI (Cost Performance Index - Chỉ số hiệu suất chi phí)** = EV / AC
  - CPI > 1: Hiệu quả chi phí (tốt)
  - CPI < 1: Kém hiệu quả chi phí (xấu)
- **SPI (Schedule Performance Index - Chỉ số hiệu suất tiến độ)** = EV / PV
  - SPI > 1: Tiến độ tốt (tốt)
  - SPI < 1: Tiến độ chậm (xấu)

### Forecasting (Dự báo)

**English:**
- **EAC (Estimate at Completion)** - Estimated total cost at project completion
  - For atypical cost variances: EAC = AC + (BAC - EV)
  - For typical cost variances: EAC = BAC / CPI
  - When both schedule and cost affect remaining work: EAC = AC + [(BAC - EV) / (CPI × SPI)]
- **ETC (Estimate to Complete)** = EAC - AC
- **VAC (Variance at Completion)** = BAC - EAC
- **TCPI (To-Complete Performance Index)** = (BAC - EV) / (BAC - AC)
  - Cost performance required for remaining work

**Tiếng Việt:**
- **EAC (Estimate at Completion - Ước tính tổng chi phí khi hoàn thành)** - Ước tính tổng chi phí dự án khi hoàn thành
  - Khi biến động chi phí không điển hình: EAC = AC + (BAC - EV)
  - Khi biến động chi phí điển hình: EAC = BAC / CPI
  - Khi cả tiến độ và chi phí ảnh hưởng: EAC = AC + [(BAC - EV) / (CPI × SPI)]
- **ETC (Estimate to Complete - Ước tính chi phí để hoàn thành)** = EAC - AC
- **VAC (Variance at Completion - Chênh lệch khi hoàn thành)** = BAC - EAC
- **TCPI (To-Complete Performance Index - Chỉ số hiệu suất để hoàn thành)** = (BAC - EV) / (BAC - AC)
  - Chỉ số hiệu suất chi phí cần đạt được cho phần công việc còn lại

## 3. Quản lý rủi ro (Risk Management)

### EMV (Expected Monetary Value)
```
EMV = Probability × Impact
```

**English:**
**Application**: 
- Used in decision analysis and decision trees to estimate weighted average outcome of risk scenarios
- Project's total EMV = Sum of opportunity EMVs + Sum of threat EMVs
- Positive EMV: opportunity, Negative EMV: threat

**Tiếng Việt:**
```
EMV = Xác suất × Tác động
```

**Áp dụng**: 
- Sử dụng trong phân tích quyết định, cây quyết định để ước tính giá trị trung bình có trọng số của các kịch bản rủi ro
- Tổng EMV của dự án = Tổng EMV các cơ hội + Tổng EMV các mối đe dọa
- EMV dương: cơ hội, EMV âm: mối đe dọa

## 4. Đường găng (Critical Path)

### Time Calculation (Tính toán các thời điểm)

**English:**
- **ES (Early Start)** - Earliest time an activity can start
- **EF (Early Finish)** = ES + Duration
- **LS (Late Start)** = LF - Duration
- **LF (Late Finish)** - Latest time an activity can finish without delaying project

**Tiếng Việt:**
- **ES (Early Start - Thời điểm sớm nhất bắt đầu)** - Thời điểm sớm nhất có thể bắt đầu hoạt động
- **EF (Early Finish - Thời điểm sớm nhất kết thúc)** = ES + Thời gian thực hiện
- **LS (Late Start - Thời điểm trễ nhất bắt đầu)** = LF - Thời gian thực hiện
- **LF (Late Finish - Thời điểm trễ nhất kết thúc)** - Thời điểm trễ nhất có thể kết thúc hoạt động

### Float Time (Thời gian nổi)

**English:**
- **Total Float** = LS - ES = LF - EF
- **Free Float** = ES(next activity) - EF(current activity)

**Critical Path**: Sequence of activities with Total Float = 0, determines minimum project duration.

**Tiếng Việt:**
- **Total Float (Thời gian nổi tổng thể)** = LS - ES = LF - EF
- **Free Float (Thời gian nổi tự do)** = ES(hoạt động kế tiếp) - EF(hoạt động hiện tại)

**Đường găng**: Chuỗi hoạt động với Total Float = 0, xác định thời gian tối thiểu để hoàn thành dự án.

## 5. Truyền thông (Communication)

### Communication Channels (Số kênh truyền thông)
```
N = n(n-1)/2
```

**English:**
- N: Number of communication channels
- n: Number of stakeholders

**Significance**: This formula helps calculate the potential communication channels in a project. When the number of people increases, the number of communication channels increases exponentially.

**Tiếng Việt:**
```
N = n(n-1)/2
```
- N: Số kênh truyền thông
- n: Số người tham gia

**Ý nghĩa**: Công thức này giúp tính toán số lượng kênh giao tiếp tiềm năng trong dự án. Khi số người tham gia tăng lên, số kênh giao tiếp tăng theo cấp số nhân.

## 6. Chi phí chất lượng (Cost of Quality - COQ)

**English:**
### COQ = Cost of Conformance + Cost of Non-Conformance
- **Cost of Conformance** = Prevention Cost + Appraisal Cost
  - Prevention Cost: training, documentation, equipment
  - Appraisal Cost: inspection, testing, quality assessments
- **Cost of Non-Conformance** = Internal Failure Cost + External Failure Cost
  - Internal Failure Cost: rework, scrap (before delivery)
  - External Failure Cost: warranty, liability, reputation loss (after delivery)

**Tiếng Việt:**
### COQ = Chi phí tuân thủ + Chi phí không tuân thủ
- **Chi phí tuân thủ** = Chi phí phòng ngừa + Chi phí đánh giá
  - Chi phí phòng ngừa: đào tạo, tài liệu quy trình, thiết bị
  - Chi phí đánh giá: kiểm tra, thử nghiệm, đánh giá
- **Chi phí không tuân thủ** = Chi phí thất bại nội bộ + Chi phí thất bại bên ngoài
  - Chi phí thất bại nội bộ: làm lại, loại bỏ sản phẩm lỗi (trước khi bàn giao)
  - Chi phí thất bại bên ngoài: bảo hành, trách nhiệm pháp lý, mất uy tín (sau khi bàn giao)

## 7. Nén lịch trình (Schedule Compression)

### Fast Tracking

**English:**
- Perform activities in parallel or overlap them instead of sequentially
- Does not increase cost but increases risk
- Only applicable to activities that can be overlapped

**Tiếng Việt:**
- Thực hiện các hoạt động song song/chồng chéo thay vì tuần tự
- Không tăng chi phí nhưng tăng rủi ro
- Chỉ áp dụng cho các hoạt động có thể chồng chéo

### Crashing

**English:**
- **Crashing Cost Slope** = (Crash cost - Normal cost) / (Normal duration - Crash duration)
- Choose activity with lowest cost slope for crashing
- Add resources to shorten duration, increasing project cost

**Tiếng Việt:**
- **Crashing Cost Slope (Độ dốc chi phí nén)** = (Chi phí crash - Chi phí thường) / (Thời gian thường - Thời gian crash)
- Chọn hoạt động có cost slope thấp nhất để crash
- Thêm nguồn lực để rút ngắn thời gian, tăng chi phí dự án

## 8. Phân tích tài chính (Financial Analysis)

### Return on Investment (ROI)

**English:**
```
ROI = (Benefits - Costs) / Costs
```
- ROI > 0: profitable project
- Higher ROI is better

**Tiếng Việt:**
```
ROI = (Lợi ích - Chi phí) / Chi phí
```
- ROI > 0: dự án có lãi
- ROI càng cao càng tốt

### Net Present Value (NPV)

**English:**
```
NPV = Σ [Ct / (1+r)^t] - C0
```
- Ct: Cash inflow at time t
- r: Discount rate
- C0: Initial investment
- NPV > 0: project should be accepted

**Tiếng Việt:**
```
NPV = Σ [Ct / (1+r)^t] - C0
```
- Ct: Dòng tiền vào tại thời điểm t
- r: Tỷ lệ chiết khấu
- C0: Chi phí ban đầu
- NPV > 0: dự án nên được chấp nhận

### Benefit-Cost Ratio (BCR)

**English:**
```
BCR = PV of Benefits / PV of Costs
```
- BCR > 1: profitable project
- Higher BCR is better

**Tiếng Việt:**
```
BCR = PV of Benefits / PV of Costs
```
- BCR > 1: dự án có lãi
- BCR càng cao càng tốt

### Payback Period

**English:**
```
Payback Period = Initial Investment / Annual Cash Inflow
```
- Time required to recover the initial investment
- Shorter periods are better

**Tiếng Việt:**
```
Payback Period = Chi phí ban đầu / Dòng tiền vào hàng năm
```
- Thời gian cần thiết để thu hồi vốn đầu tư
- Thời gian càng ngắn càng tốt

## 9. Chỉ số hiệu suất khác (Other Performance Indices)

### To-Complete Performance Index (TCPI)

**English:**
- **TCPI (BAC)** = (BAC - EV) / (BAC - AC)
- **TCPI (EAC)** = (BAC - EV) / (EAC - AC)

**Tiếng Việt:**
- **TCPI (BAC) (Chỉ số hiệu suất để hoàn thành theo BAC)** = (BAC - EV) / (BAC - AC)
- **TCPI (EAC) (Chỉ số hiệu suất để hoàn thành theo EAC)** = (BAC - EV) / (EAC - AC)

### Time Estimate at Completion

**English:**
- **EACt (Estimate At Completion time)** = Planned duration × (1/SPI)

**Tiếng Việt:**
- **EACt (Estimate At Completion time - Ước tính thời gian hoàn thành)** = Thời gian dự kiến × (1/SPI)

## Lưu ý khi làm bài thi PMP (PMP Exam Tips)

**English:**
1. **EVM**: Memorize the formulas, especially how to calculate EAC in different scenarios. Remember that CPI, SPI > 1 is good, < 1 is bad.

2. **PERT**: Remember that the weight of M (Most Likely) is 4 times that of O and P.

3. **Critical Path**: The critical path is the sequence of activities with the longest duration and zero float (Float = 0).

4. **EMV**: EMV is a weighted average value based on probability, not the exact result that will be achieved.

5. **Cost of Quality**: Prevention costs are typically much lower than failure costs, especially external failure costs.

6. **Schedule Compression**: In the exam, consider fast tracking before crashing.

7. **Financial Analysis**: Projects with positive NPV, high ROI, and short payback periods are usually preferred.

**Tiếng Việt:**
1. **EVM**: Học thuộc các công thức, đặc biệt cách tính EAC trong các trường hợp khác nhau. Nhớ rằng CPI, SPI > 1 là tốt, < 1 là xấu.

2. **PERT**: Nhớ trọng số của M (Most Likely) gấp 4 lần so với O và P.

3. **Đường găng**: Đường găng là chuỗi hoạt động có tổng thời gian dài nhất và không có thời gian nổi (Float = 0). 

4. **EMV**: EMV là giá trị trung bình có trọng số dựa trên xác suất, không phải kết quả chắc chắn sẽ nhận được.

5. **Chi phí chất lượng**: Chi phí phòng ngừa thường thấp hơn nhiều so với chi phí sửa chữa lỗi, đặc biệt là chi phí thất bại bên ngoài.

6. **Nén lịch trình**: Trong kỳ thi, nên cân nhắc fast tracking trước, sau đó mới crashing.

7. **Phân tích tài chính**: Dự án có NPV dương, ROI cao và thời gian hoàn vốn ngắn thường được ưu tiên. 