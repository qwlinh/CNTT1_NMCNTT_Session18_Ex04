# Bài 4 : Sự cố xung đột phiên đăng nhập trên trình duyệt

## So sánh sự khác biệt về lưu trữ trạng thái giữa Incognito Mode (tạm thời trên RAM) và Dedicated Profile (lâu dài trên ổ cứng).

- Incognito Mode : Lưu tạm vào RAM trong phần làm việc và khi đóng cửa sổ ẩn dang thì sẻ biến mất và không lưu lại lịch sử 

- Dedicated Profile : Lưu trữ lâu dài và tộn tải vĩnh viễn cho đến khi chủ động xóa và lưu giữ đầy đủ cookie, mật khẩu, lịch sử web

## Mô tả quy trình tạo và đồng bộ hóa Cloud Sync để bảo vệ Bookmark khi đổi máy tính.

**1** Thiết lập Profile độc lập:

    Bước 1: Mở chrome
    
    Bước 2: Nhấn vào biểu tượng avata 

    Bước 3: Chọn và add để tạo 3 Profile riêng biệt

**2** Đồng bộ hóa Cloud Sync

Bước 1: Đăng nhập tài khoản Google tương ứng vào từng Profile.

Bước 2: Bật tính năng Turn on sync (chọn đồng bộ Bookmarks và Passwords).

**3** Quy tắc sử dụng Guest Profile trên máy công cộng

- Sử dụng Guest Profile:

Khi làm việc trên máy tính công cộng, nhấp vào Avatar và chọn Guest (Khách) thay vì dùng ẩn danh trên profile chính để đảm bảo sự cô lập tuyệt đối.

- Quy tắc kết thúc:

Chỉ cần đóng cửa sổ Guest, toàn bộ lịch sử, cookie và phiên đăng nhập sẽ tự động bị xóa sạch, không để lộ thông tin cho người dùng sau.


## Giả định làm việc trên máy tính công cộng, hãy đề xuất quy tắc sử dụng Guest Profile để bảo mật.

1: Sử dụng chế độ Khách (Guest Profile):

- Mở trình duyệt, chọn Avatar tài khoản và nhấp chọn Guest (Khách) thay vì dùng chế độ ẩn danh (Incognito) trên profile chính của người khác.

- Lợi ích: Tạo ra một phiên làm việc độc lập hoàn toàn, không cho phép truy cập hay lưu trữ bất kỳ thông tin nào liên quan đến các profile cá nhân khác trên máy.

2; Quy tắc khi kết thúc phiên làm việc:

- Ngay sau khi hoàn thành công việc, chỉ cần đóng cửa sổ Guest.

- Trình duyệt sẽ tự động xóa sạch toàn bộ lịch sử duyệt web, cookie, tệp đã tải xuống và thông tin đăng nhập, đảm bảo không để lại bất kỳ dấu vết hay tài khoản nào cho người sử dụng tiếp theo.
