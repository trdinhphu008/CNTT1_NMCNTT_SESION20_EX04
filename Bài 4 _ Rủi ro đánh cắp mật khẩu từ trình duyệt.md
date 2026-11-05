### 1. Bảng so sánh Google Chrome và Bitwarden
|tiêu chí|google chrome|bitwarden|
|:---:|:---:|:---:|
|Chống Infostealer|Có nguy cơ bị mã độc trích xuất dữ liệu từ file Login Data khi máy tính bị nhiễm mã độc|Có thêm lớp bảo vệ bằng Master Password và kho dữ liệu mã hóa. Tuy nhiên, nếu máy đã bị nhiễm mã độc khi Vault đang mở khóa thì vẫn có nguy cơ bị đánh cắp dữ liệu|
|Zero-Knowledge Architecture|Không phải kiến trúc Zero-Knowledge chuyên dụng như Bitwarden|Có kiến trúc Zero-Knowledge, dữ liệu được mã hóa trước khi đồng bộ lên máy chủ|
|Đồng bộ chéo nền tảng|Đồng bộ thuận tiện qua tài khoản Google và Chrome|Đồng bộ trên Windows, macOS, Linux, điện thoại và trình duyệt|

### 2. Tại sao Bitwarden có lợi thế về bảo mật?

-   Bảo vệ bằng Master Password: Người dùng cần Master Password để mở khóa kho mật khẩu, tạo thêm lớp bảo vệ.
    
-   Mã hóa AES-256: Dữ liệu mật khẩu được mã hóa trước khi đồng bộ, giúp người khác khó đọc được thông tin nếu lấy được dữ liệu.
    
-   Zero-Knowledge Architecture: Nhà cung cấp không nắm giữ khóa giải mã để đọc nội dung kho mật khẩu của người dùng.
    
-   Giảm nguy cơ lộ mật khẩu: Bitwarden quản lý mật khẩu riêng biệt, không chỉ dựa vào dữ liệu lưu trong trình duyệt.
    

### 3. Kết luận

Em đề xuất công ty sử dụng Bitwarden thay vì lưu mật khẩu trực tiếp trên Chrome. Dù phải nhập Master Password khi mở khóa, Bitwarden cung cấp thêm lớp mã hóa và bảo vệ dữ liệu tốt hơn. Đây là lựa chọn phù hợp để hạn chế nguy cơ bị mã độc Infostealer đánh cắp mật khẩu.

