## Quản Lý Phân Quyền Trong ClickUp

### Truy Cập Cài Đặt Phân Quyền

#### Cách Truy Cập Permissions

- **Vị trí**: Có thể thiết lập ở cấp độ thư mục (folder) hoặc dự án riêng lẻ
- **Thao tác**:
    - Chọn dự án cụ thể
    - Nhấp chuột phải → **Sharing and Permissions**
- **Hiển thị**: Thể hiện vai trò workspace owner và các tùy chọn phân quyền


### Các Mức Độ Phân Quyền (Permission Levels)

#### Full Access (Quyền truy cập đầy đủ)

**Quyền hạn bao gồm**:

- Tạo tasks và subtasks
- Thêm attachments (tệp đính kèm)
- Xóa tasks
- **Lưu ý quan trọng**: Đây là tùy chọn duy nhất cho guests trên Free Forever workspaces


#### Can Edit (Có thể chỉnh sửa)

**Quyền hạn**:

- Chỉnh sửa tasks hiện có
- Xóa attachments
- Di chuyển, hợp nhất, nhân bản tasks
- **Hạn chế**: Không thể tạo tasks mới


#### Comment (Chỉ bình luận)

**Quyền hạn giới hạn**:

- Bình luận trên tasks
- Đính kèm files
- Hoàn thành checklist items
- **Không thể**: Chỉnh sửa nội dung tasks


#### View Only (Chỉ xem)

**Quyền hạn tối thiểu**:

- Chế độ read-only (chỉ đọc)
- Không thể cập nhật tasks theo bất kỳ cách nào
- Chỉ có thể xem thông tin


### Khuyến Nghị Phân Quyền Thực Tế

#### Cho Team Members (Thành viên nhóm)

- **Cài đặt khuyến nghị**: **Full Access**
- **Lý do**: Cần toàn quyền để làm việc hiệu quả trong team


#### Cho Guests (Khách mời)

- **Điều kiện**: Trên các gói trả phí (paid plans)
- **Cài đặt thường dùng**:
    - **View Only**: Chỉ xem thông tin
    - **Comment**: Xem và bình luận
- **Mục đích**: Giới hạn quyền truy cập cho bên ngoài


### Phân Quyền Theo Cấp Độ

#### Cấp Độ Dự Án (Project Level)

- **Phạm vi**: Áp dụng cho toàn bộ project plan
- **Cách thiết lập**: Sharing and Permissions ở cấp độ dự án
- **Ảnh hưởng**: Quyền mặc định cho tất cả tasks trong dự án


#### Cấp Độ Nhiệm Vụ Riêng Lẻ (Individual Task Level)

- **Tính năng**: Có thể ghi đè (override) quyền dự án cho task cụ thể
- **Ví dụ thực tế**:
    - John có **Full Access** ở cấp độ dự án
    - Nhưng chỉ có **View Only** cho task "Create mockup"
- **Ứng dụng**: Kiểm soát truy cập chi tiết đến thông tin nhạy cảm


### Cách Thiết Lập Phân Quyền Chi Tiết

#### Bước 1: Mở Task Cụ Thể

- Nhấp vào task cần thiết lập quyền riêng
- Truy cập **Sharing and Permissions** của task


#### Bước 2: Thiết Lập Quyền Riêng

- **Ví dụ**: Đặt John là "View Only" cho task "Create mockup"
- **Kết quả**: John vẫn giữ Full Access ở các task khác


#### Bước 3: Kiểm Tra Cài Đặt

- **Cấp độ dự án**: John vẫn hiển thị Full Access
- **Cấp độ task riêng**: John hiển thị View Only cho task cụ thể


### Logic Phân Quyền Phân Cấp

#### Nguyên Tắc Override

- **Quyền dự án**: Thiết lập quyền mặc định
- **Quyền task**: Có thể ghi đè quyền dự án
- **Ưu tiên**: Quyền task luôn được áp dụng trước


#### Ví Dụ Thực Tế

**Tình huống**:

- User A: Full Access ở project level
- Task X: View Only cho User A
- **Kết quả**: User A chỉ có thể xem Task X, nhưng full access các task khác


### Phân Biệt Free vs Paid Plans

#### Free Forever Workspaces

- **Hạn chế**: Guests chỉ có thể có Full Access
- **Không thể**: Thiết lập quyền hạn chế cho guests
- **Lý do**: Giới hạn tính năng của gói miễn phí


#### Paid Plans

- **Linh hoạt**: Đầy đủ các tùy chọn phân quyền cho guests
- **Kiểm soát**: Có thể giới hạn quyền truy cập theo nhu cầu
- **Bảo mật**: Tăng cường kiểm soát thông tin dự án


### Thực Hành Tốt Nhất

#### Nguyên Tắc Phân Quyền

1. **Principle of Least Privilege**: Chỉ cấp quyền tối thiểu cần thiết
2. **Role-based Access**: Phân quyền theo vai trò trong dự án
3. **Regular Review**: Định kỳ xem xét và cập nhật quyền hạn

#### Khuyến Nghị Cụ Thể

**Internal Team**:

- Project Manager: Full Access
- Team Members: Full Access (trên các task được giao)
- Stakeholders: Comment hoặc View Only

**External Parties**:

- Clients: View Only hoặc Comment
- Contractors: Can Edit (chỉ trên task liên quan)
- Auditors: View Only


### Ghi Chú Thêm

- Hệ thống phân quyền của ClickUp rất linh hoạt và chi tiết
- Có thể thiết lập quyền khác nhau cho từng task trong cùng một dự án
- Cần cân bằng giữa tính bảo mật và hiệu quả làm việc
- Phân quyền phù hợp giúp bảo vệ thông tin nhạy cảm trong dự án

**Liên kết**: [[ClickUp]], [[Project Permissions]], [[Sharing and Permissions]], [[Full Access]], [[Can Edit]], [[Comment]], [[View Only]], [[Workspace Owner]], [[Guests]], [[Free Forever]], [[Paid Plans]], [[Task Level Permissions]], [[Project Level Permissions]], [[Role-based Access]], [[Security]]

