## Lọc và Sắp Xếp Trong ClickUp

### Sử Dụng Bộ Lọc (Filtering)

#### Truy Cập Bộ Lọc

- **Vị trí**: Nút Filter ở phần đầu kế hoạch
- **Chức năng**: Lọc theo mọi trường (field) có sẵn trong dự án


#### Lọc Theo Độ Ưu Tiên (Priority)

- **Cách thực hiện**: Click Filter → chọn Priority → chọn mức độ (ví dụ: High)
- **Kết quả**: Chỉ hiển thị các nhiệm vụ có độ ưu tiên cao
- **Hiển thị**: Bộ lọc được áp dụng ngay lập tức


#### Sử Dụng Nhiều Bộ Lọc (Multiple Filters)

**Ví dụ kết hợp lọc**:

- **Filter 1**: Priority = High
- **Filter 2**: Due date trong 7 ngày tới
- **Kết quả**: Hiển thị nhiệm vụ vừa có độ ưu tiên cao vừa đến hạn trong tuần


### Lưu Bộ Lọc Làm Mẫu (Filter Templates)

#### Hai Loại Template

1. **My Filters** (bộ lọc cá nhân): Chỉ bản thân sử dụng
2. **Workspace Filters** (bộ lọc workspace): Toàn bộ team có thể sử dụng

#### Cách Lưu Template

- **Bước 1**: Tạo các bộ lọc mong muốn
- **Bước 2**: Nhấp "Save as template"
- **Bước 3**: Chọn loại (My Filters hoặc Workspace Filters)
- **Bước 4**: Đặt tên (ví dụ: "High Importance Next 7 Days")


#### Sử Dụng Template Đã Lưu

- **Xóa bộ lọc hiện tại**: Để hiển thị toàn bộ dự án
- **Áp dụng template**: Chọn từ danh sách template đã lưu
- **Kết quả**: Bộ lọc được áp dụng ngay lập tức


### Các Tùy Chọn Lọc Theo Thời Gian

#### Lọc Theo Due Date

**Tùy chọn thời gian có sẵn**:

- This year (năm nay)
- Last quarter (quý trước)
- This quarter (quý này)
- Next year (năm sau)
- Within next 7 days (trong 7 ngày tới)
- Custom date ranges (khoảng thời gian tùy chỉnh)


#### Lọc Theo Người Được Giao (Assignee)

- **Chức năng**: Xem nhiệm vụ của thành viên cụ thể
- **Ví dụ**: Lọc tất cả nhiệm vụ của John
- **Ứng dụng**: Hữu ích khi làm việc nhóm, muốn theo dõi workload cá nhân


### Sắp Xếp (Sorting)

#### Sắp Xếp Theo Tiến Độ (Progress)

- **Cách thực hiện**: Click Sort → chọn Progress
- **Kết quả**: Sắp xếp theo phần trăm hoàn thành
- **Lưu ý quan trọng**: Chỉ áp dụng cho parent tasks (nhiệm vụ chính), không tính subtasks


#### Sắp Xếp Nhiều Tiêu Chí (Multiple Sorting)

**Ví dụ sắp xếp kết hợp**:

- **Sort 1**: Priority (độ ưu tiên)
- **Sort 2**: Budget (ngân sách)


#### Thứ Tự Ưu Tiên Sắp Xếp

- **Hiển thị**: Biểu tượng số thứ tự (1, 2, 3, 4...)
- **Sort 1**: Tiêu chí chính (ưu tiên cao nhất)
- **Sort 2, 3, 4**: Tiêu chí phụ (áp dụng khi Sort 1 có giá trị giống nhau)


#### Thay Đổi Thứ Tự Sắp Xếp

- **Cách thực hiện**: Kéo thả trong danh sách sorting
- **Ví dụ**: Di chuyển Budget lên làm Sort 1 thay vì Priority
- **Kết quả**: Danh sách được sắp xếp lại theo thứ tự mới


### Nguyên Tắc Hoạt Động

#### Logic Sắp Xếp Nhiều Tiêu Chí

- **Ví dụ thực tế**:
    - Nếu có nhiều nhiệm vụ Priority = Low
    - Sort 2 (Budget) sẽ quyết định thứ tự giữa các nhiệm vụ Low priority này
    - Nhiệm vụ Low priority + Budget cao sẽ đứng trước Low priority + Budget thấp


#### Parent Tasks vs Subtasks

- **Quy tắc**: Sorting chỉ áp dụng cho parent tasks (nhiệm vụ chính)
- **Subtasks**: Không ảnh hưởng đến thứ tự sắp xếp tổng thể
- **Hiển thị**: Subtasks luôn hiển thị bên dưới parent task của chúng


### Các Tùy Chọn Lọc Khác

#### Đa Dạng Tiêu Chí

- **Status** (trạng thái): Lọc theo giai đoạn dự án
- **Custom Fields** (trường tùy chỉnh): Lọc theo các trường đã tạo
- **Date Created** (ngày tạo): Lọc theo thời gian tạo nhiệm vụ
- **Budget** (ngân sách): Lọc theo khoảng ngân sách
- **Time Tracked** (thời gian theo dõi): Lọc theo thời gian làm việc


#### Tính Linh Hoạt

- **Dễ sử dụng**: Giao diện trực quan, không cần hướng dẫn phức tạp
- **Tìm kiếm nhanh**: Tìm bất kỳ tiêu chí nào cần thiết
- **Kết hợp linh hoạt**: Có thể áp dụng nhiều bộ lọc đồng thời


### Thực Hành Khuyến Nghị

#### Workflow Hiệu Quả

1. **Xác định nhu cầu**: Thông tin nào cần xem thường xuyên?
2. **Tạo template**: Lưu các bộ lọc thường dùng
3. **Đặt tên rõ ràng**: Template dễ nhận biết và sử dụng
4. **Chia sẻ team**: Sử dụng Workspace Filters cho nhóm

#### Các Template Hữu Ích

- **"My Tasks This Week"**: Assignee = Me + Due date trong 7 ngày
- **"High Priority Overdue"**: Priority = High + Due date trong quá khứ
- **"Budget Over 5K"**: Budget > \$5,000
- **"Team John Tasks"**: Assignee = John


### Ghi Chú Thêm

- Bộ lọc và sắp xếp là công cụ mạnh mẽ để quản lý dự án phức tạp
- Nên dành thời gian thực hành để làm quen với các tùy chọn
- Template filters giúp tiết kiệm thời gian và chuẩn hóa cách xem dữ liệu
- Kết hợp filtering và sorting để có cái nhìn tối ưu về tiến độ dự án

**Liên kết**: [[ClickUp]], [[Filtering]], [[Sorting]], [[Filter Templates]], [[Multiple Filters]], [[Priority]], [[Due Date]], [[Assignee]], [[Progress]], [[Budget]], [[Parent Tasks]], [[Subtasks]], [[Workspace Filters]], [[Custom Fields]]

