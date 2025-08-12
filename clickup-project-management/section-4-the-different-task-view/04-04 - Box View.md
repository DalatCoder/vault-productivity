## Chế độ xem Hộp trong ClickUp (Box View)

### Giới thiệu về Box View

- Được đánh giá là **chế độ xem tốt nhất** (best view) trong ClickUp
- Chức năng chính: **Quản lý nguồn lực** (Resource Management)
- Cho phép quản lý khối lượng công việc trực quan trên một màn hình


### Cách tạo Box View

```
Thao tác: View → Select Box → Click Add
```


### Quản lý Khối lượng Công việc (Workload Management)

#### Hiển thị Workload

- Bên trái: Hiển thị khối lượng công việc (workload) của từng người dùng
- Có thể dựa trên nhiều tiêu chí khác nhau


#### Các tiêu chí đo lường Workload

##### 1. Số lượng Nhiệm vụ (Number of Tasks)

- Mặc định: Dựa trên số lượng task được giao
- Dễ sử dụng, không cần thiết lập bổ sung


##### 2. Thời gian Ước tính (Time Estimate)

- Dựa trên thời gian dự kiến hoàn thành mỗi task
- **Yêu cầu**: Tất cả task phải có estimate time
- Nếu không có estimate → Hiện thông báo lỗi


##### 3. Điểm Sprint (Sprint Points)

- Dựa trên sprint points được gán cho từng task
- Sẽ được đề cập chi tiết trong bài học sau
- Yêu cầu: Task phải có sprint points


##### 4. Trường Tùy chỉnh (Custom Field)

- Có thể tạo tiêu chí đo lường riêng
- Linh hoạt theo nhu cầu dự án cụ thể


### Theo dõi Tiến độ (Progress Tracking)

#### Hiển thị Progress

- Khi đánh dấu task hoàn thành → Xuất hiện **thanh xanh** (green bar)
- Thanh xanh thể hiện tỷ lệ % công việc đã hoàn thành
- Ví dụ: Hoàn thành 1/4 task → Hiển thị 25% complete


#### Cách thức hoạt động

```
Ví dụ thực tế:
1. Peter có nhiều task nhất trong team
2. Chưa có task nào hoàn thành
3. Đánh dấu 1 task complete → Hiển thị 25% progress
4. Workload bar cập nhật ngay lập tức
```


### Tổng quan Workspace

#### Mở rộng phạm vi

- Mặc định: Chỉ hiển thị project hiện tại
- Có thể mở rộng để bao gồm **toàn bộ workspace**
- Hiển thị tất cả người dùng và project trong workspace


#### Ứng dụng cho Team lớn

```
Ví dụ: Team 20 người
- Xem tổng quan workload của tất cả thành viên
- So sánh khối lượng công việc giữa các cá nhân
- Phát hiện ai bị quá tải (overload)
- Thảo luận và cân bằng lại công việc
```


### Quản lý Cá nhân với Item Lineup

#### Truy cập Item Lineup

- Nhấn vào tên một người cụ thể (ví dụ: Peter)
- Mở ra giao diện **Item Lineup**


#### Chức năng Item Lineup

- **Mục đích**: Sắp xếp ưu tiên (prioritization) công việc cá nhân
- **Cách thức**: Kéo thả các task theo thứ tự ưu tiên
    - Task 1: Quan trọng nhất, làm trước tiên
    - Task 2: Quan trọng thứ hai
    - Tiếp tục theo thứ tự...


#### Inbox cho theo dõi Task

Hiển thị các thông tin quan trọng:

- **Tasks completed**: Nhiệm vụ đã hoàn thành
- **Tasks delegated**: Nhiệm vụ đã ủy quyền
- **Tasks due today**: Nhiệm vụ hết hạn hôm nay
- **Overdue tasks**: Nhiệm vụ quá hạn
- **Tasks due next**: Nhiệm vụ sẽ hết hạn tiếp theo và thời gian


### Tính năng Lọc và Cân bằng

#### Bộ lọc (Filter)

- Tương tự các view khác trong ClickUp
- Lọc theo người được giao (assignee)
- Lọc theo độ ưu tiên (priority)
- Các tiêu chí lọc khác tùy theo dự án


#### Cân bằng Workload (Balancing)

- **Phát hiện**: Thành viên nào có quá nhiều task
- **Hành động**: Kéo thả task từ người này sang người khác
- **Ví dụ**: Di chuyển "Assigned Development Team" từ bucket của một người sang bucket của Sarah
- **Cập nhật**: Tự động refresh và hiển thị workload mới


### Ứng dụng Thực tế

#### Cho Team Leader

- Quản lý hiệu quả khối lượng công việc của team
- Phát hiện và giải quyết tình trạng quá tải
- Cân bằng công việc giữa các thành viên


#### Cho Project Manager

- Dù không quản lý trực tiếp team, vẫn có thể:
    - Xem tổng quan phân bổ công việc
    - Thảo luận về ưu tiên công việc với team
    - Sử dụng Item Lineup để sắp xếp priorities


#### Ưu điểm nổi bật

- **Trực quan**: Dễ dàng nhận diện workload imbalance
- **Tương tác**: Có thể điều chỉnh trực tiếp bằng drag \& drop
- **Toàn diện**: Từ overview team đến chi tiết cá nhân
- **Thực tế**: Được sử dụng thường xuyên trong quản lý dự án


### Ghi chú thêm

- Box View đặc biệt hữu ích cho **quản lý nguồn lực** trong dự án lớn
- **Item Lineup** là tính năng quan trọng cho việc sắp xếp ưu tiên công việc
- Phù hợp nhất cho các team có nhiều thành viên và cần cân bằng workload
- Chế độ xem tiếp theo sẽ tìm hiểu: **Biểu đồ Gantt (Gantt View)**


### Liên kết nội bộ

Các thuật ngữ và khái niệm quan trọng: [[ClickUp Views]], [[Box View]], [[Resource Management]], [[Workload]], [[Time Estimate]], [[Sprint Points]], [[Custom Field]], [[Progress Tracking]], [[Item Lineup]], [[Prioritization]], [[Inbox]], [[Filter]], [[Workload Balancing]], [[Team Management]], [[Gantt View]]

