## Tự Động Hóa Trong ClickUp (Automations in ClickUp)

### Khái Niệm

- **Tự động hóa (Automations)** giúp giảm thiểu các công việc quản trị hàng ngày
- Tiết kiệm thời gian bằng cách tự động thực hiện các tác vụ lặp đi lặp lại
- Truy cập qua biểu tượng **Automations** ở góc trên bên phải của project plan


### Hai Tự Động Hóa Mặc Định

#### 1. Luôn Gán Nhiệm Vụ Mới (Always Assign New Tasks)

- Tự động gán người thực hiện cho mọi nhiệm vụ mới được tạo
- Cấu hình: chọn người được gán mặc định (ví dụ: "me")


#### 2. Thêm Người Theo Dõi (Add Watcher)

- Tự động thêm **watcher** cho mọi nhiệm vụ mới
- Có thể thêm nhiều người theo dõi (ví dụ: "me" và "John")
- Khi tạo nhiệm vụ mới, hệ thống sẽ tự động gán người thực hiện và người theo dõi


### Giao Diện Quản Lý Tự Động Hóa

#### Cấu Trúc Menu

- **Danh mục bên trái**: Move, Status, Creation, Date, Assigns, Priorities, Other
- **Panel chính**: Tạo automation mới
- **Managed**: Quản lý các automation hiện có
- **Description**: Mô tả automation
- **Usage**: Theo dõi số lượng automation đã sử dụng theo tháng


### Tạo Tự Động Hóa Tùy Chỉnh

#### Ví Dụ 1: Thay Đổi Ưu Tiên Khi Đến Hạn

- **Điều kiện**: Khi due date arrives (đến ngày hạn)
- **Hành động**: Change priority to Urgent (thay đổi ưu tiên thành khẩn cấp)
- **Cấu hình**:
    - Chọn danh mục **Dates**
    - Chọn "When due date arrives, change priority"
    - Đặt priority thành "Urgent"
    - Nhấp **Create**


#### Ví Dụ 2: Thông Báo Khi Hoàn Thành Subtask

- **Điều kiện**: When all subtasks are resolved (khi tất cả subtask hoàn thành)
- **Hành động**: Add comment và tag người cụ thể
- **Cấu hình**:
    - Chọn **Add Custom Automation**
    - Thiết lập điều kiện "all subtasks are resolved"
    - Thêm comment: "Subtasks are done. Please proceed with the next task"
    - Tag người cụ thể (ví dụ: Peter)


### Cách Thức Hoạt Động

#### Automation với Subtasks

- Tạo subtasks trong một nhiệm vụ chính
- Khi tất cả subtasks được đánh dấu hoàn thành
- Hệ thống tự động thêm comment qua **Clickbot**
- Thông báo được gửi đến người được tag


#### Quản Lý Automations

- Xem danh sách automation đang hoạt động
- Bật/tắt automation theo nhu cầu
- Hai automation mặc định không thể tắt hoặc xóa
- Automation tùy chỉnh có thể bật/tắt tự do


### Các Loại Automation Phổ Biến

- **Move tasks** to different lists (chuyển nhiệm vụ sang danh sách khác)
- **Close tasks** automatically (tự động đóng nhiệm vụ)
- **Create new tasks** when one is completed (tạo nhiệm vụ mới khi hoàn thành)
- **Change assigning** when status changes (thay đổi người gán khi trạng thái thay đổi)
- **Update priorities** based on conditions (cập nhật ưu tiên theo điều kiện)


### Lợi Ích và Ứng Dụng

- **Tiết kiệm thời gian**: Giảm công việc quản trị thủ công
- **Tính nhất quán**: Đảm bảo quy trình được thực hiện đồng nhất
- **Giảm sai sót**: Tự động thực hiện các tác vụ quan trọng
- **Tối ưu quy trình**: Cải thiện hiệu quả làm việc nhóm


### Ghi Chú Thêm

- Nên dành thời gian suy nghĩ về các tác vụ có thể tự động hóa khi tạo project plan mới
- Tập trung vào những hành động nhỏ không cần thiết phải thực hiện thủ công
- Tất cả thông báo automation được thực hiện qua **Clickbot**
- Có thể kiểm soát số lượng automation sử dụng qua mục **Usage**

***

**Liên kết**: [[ClickUp]], [[Automation]], [[Subtasks]], [[Priority]], [[Due Date]], [[Project Management]], [[Clickbot]], [[Watcher]], [[Task Assignment]], [[Workflow Optimization]]

