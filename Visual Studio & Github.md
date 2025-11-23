# 💻 CHUYÊN ĐỀ TIN HỌC: Làm quen với Visual Studio Code & Github

---

## A. TỔNG QUAN

* [cite_start]**VS Code (Visual Studio Code):** là trình soạn thảo mã nguồn miễn phí do Microsoft phát triển [cite: 4][cite_start], hỗ trợ rất nhiều ngôn ngữ lập trình như C++, Python, Java, JavaScript… [cite: 4][cite_start]; sở hữu hệ thống extension phong phú[cite: 5].
* [cite_start]**Github:** là nền tảng lưu trữ và chia sẻ mã nguồn trực tuyến, dựa trên Git[cite: 6]. [cite_start]Nó cho phép quản lý phiên bản, làm việc nhóm, và tham gia vào các dự án mã nguồn mở[cite: 7].
* [cite_start]**Git:** Git là hệ thống quản lý phiên bản (Version Control System) giúp theo dõi lịch sử thay đổi mã nguồn, tạo nhánh, hợp nhất và làm việc nhóm hiệu quả [cite: 8][cite_start], do Linus Torvalds tạo ra[cite: 8].
* [cite_start]**Github Desktop:** GitHub Desktop là ứng dụng giao diện (GUI) giúp bạn sử dụng Git và GitHub dễ dàng hơn mà không cần dùng lệnh[cite: 9].

---

## B. CÀI ĐẶT & THIẾT LẬP

### I. CÀI ĐẶT

#### 1. VS Code

1.  [cite_start]Truy cập trang chính thức: [https://code.visualstudio.com](https://code.visualstudio.com)[cite: 13].
2.  [cite_start]Chọn nút **Download** phù hợp với hệ điều hành (Windows, macOS, Linux)[cite: 14].
3.  [cite_start]Mở file cài đặt → nhấn **Next** liên tục → chọn **Install**[cite: 15].
4.  [cite_start]Sau khi cài xong, mở VSCode để kiểm tra[cite: 16].
5.  [cite_start]**(Khuyến nghị)** Cài thêm extension: [cite: 17]
    * [cite_start]**GitLens:** Xem lịch sử commit, tác giả từng dòng[cite: 18].
    * [cite_start]**Prettier:** Định dạng mã nguồn tự động[cite: 19].
    * [cite_start]**GitHub Pull Requests & Issues:** Quản lý PR trực tiếp trong VS Code[cite: 20].

> [cite_start]**Lưu ý:** Chỉnh cấu hình cơ bản (Theme, font, Tiếng Việt,.. nếu cần)[cite: 21].

#### 2. Git

1.  [cite_start]Vào trang chính thức: [https://git-scm.com/downloads](https://git-scm.com/downloads)[cite: 23].
2.  [cite_start]Chọn phiên bản phù hợp với hệ điều hành (Windows/macOS/Linux)[cite: 24].
3.  [cite_start]Mở file cài đặt → nhấn **Next** liên tục → **Install** → **Finish**[cite: 25].
4.  [cite_start]Kiểm tra bằng cách mở Terminal/Command Prompt và gõ: `git --version`[cite: 26].
5.  [cite_start]Nếu hiện số phiên bản là cài thành công[cite: 27].
6.  [cite_start]Cấu hình thông tin lần đầu: [cite: 28]
    * [cite_start]`git config --global user.name "Tên của bạn"` [cite: 29]
    * [cite_start]`git config --global user.email "Email của bạn"` [cite: 30]

> [cite_start]**Lưu ý:** Các cấu hình thông tin sẽ gắn liền với các commit[cite: 31].

#### 3. Github Desktop

1.  [cite_start]Truy cập [https://desktop.github.com](https://desktop.github.com)[cite: 33].
2.  [cite_start]Tải về và cài đặt như phần mềm bình thường[cite: 34].
3.  [cite_start]Đăng nhập bằng tài khoản GitHub[cite: 35].

> [cite_start]**Lưu ý:** [cite: 36]
> [cite_start]* Giao diện chính có các nút: **Clone a repository**, **Create a new repository**, **Add an existing repository**[cite: 37].
> [cite_start]* Có thể mở dự án bằng VSCode trực tiếp từ GitHub Desktop[cite: 38].

### II. THIẾT LẬP

#### 1. Tạo tài khoản Github

1.  [cite_start]Vào [https://github.com](https://github.com)[cite: 41].
2.  [cite_start]Nhấn **Sign up** → nhập email, mật khẩu, username[cite: 42].
3.  [cite_start]Xác nhận email để hoàn tất[cite: 43].

> [cite_start]**Lưu ý:** [cite: 44]
> [cite_start]* Sau khi đăng nhập, bạn có thể tạo repo mới bằng nút **New repository** (Tạo kho chứa mã nguồn mới)[cite: 45].
> [cite_start]* **Chỉnh Public & Private:** [cite: 46]
>     [cite_start]* **Public:** Ai cũng xem được[cite: 47].
>     [cite_start]* **Private:** Chỉ bạn (hoặc nhóm được cấp quyền) xem được[cite: 48].

#### 2. Kết nối VS Code với Github

1.  [cite_start]Mở VSCode → nhấn **Ctrl + Shift + P**[cite: 50].
2.  [cite_start]Gõ: **GitHub: Sign in** → chọn đăng nhập bằng trình duyệt[cite: 51].
3.  [cite_start]Đăng nhập tài khoản GitHub → cấp quyền truy cập[cite: 52].
4.  [cite_start]VSCode sẽ lưu token xác thực → có thể push/pull trực tiếp[cite: 53].
5.  [cite_start]Kiểm tra tab **Source Control** đã hoạt động[cite: 54].

> [cite_start]**Lưu ý:** Tab Source Control là nơi hiển thị mọi thay đổi[cite: 55].

#### 3. Đăng nhập tài khoản Github trên Github Desktop

1.  [cite_start]Mở GitHub Desktop[cite: 57].
2.  [cite_start]Nhấn **File** → **Options** (hoặc biểu tượng bánh răng)[cite: 58].
3.  [cite_start]Chọn **Sign in to GitHub.com**[cite: 59].
4.  [cite_start]Đăng nhập tài khoản → xác nhận[cite: 60].
5.  [cite_start]Sau khi đăng nhập, có thể clone, tạo repo, commit, push dễ dàng[cite: 61].

---

## C. LÀM VIỆC CÙNG GITHUB

### I. QUA VS CODE & GITHUB DESKTOP

#### 1. Lấy dự án từ Github về để chỉnh sửa

##### a. Trực tiếp bằng VS Code

1.  [cite_start]Vào GitHub → chọn repo cần lấy[cite: 66].
2.  [cite_start]Nhấn nút **Code** → copy link **HTTPS**[cite: 67].
3.  [cite_start]Mở VSCode → Terminal → gõ: `git clone <link_repo>`[cite: 68].
4.  [cite_start]Mở thư mục vừa clone → chỉnh sửa, commit, push[cite: 69].

##### b. Thông qua Github Desktop

1.  [cite_start]Mở GitHub Desktop → chọn **Clone a repository** → chọn **URL**[cite: 71].
2.  [cite_start]Dán link repo hoặc chọn repo từ danh sách[cite: 72].
3.  [cite_start]Nhấn **Clone** → mở bằng VSCode để chỉnh sửa[cite: 73].

#### 2. Đưa dự án của bản thân lên Github

##### a. Trực tiếp bằng VS Code

1.  [cite_start]Mở thư mục dự án bằng VSCode[cite: 76].
2.  [cite_start]Mở tab **Source Control** → nhấn **Initialize Repository**[cite: 77].
3.  [cite_start]Gõ nội dung commit → nhấn **Commit**[cite: 78].
4.  [cite_start]Nhấn **Publish to GitHub** → đăng nhập tài khoản[cite: 79].
5.  [cite_start]Chọn tạo repo mới hoặc repo có sẵn[cite: 80].
6.  [cite_start]Sau đó: **Commit** → **Push** mỗi khi cập nhật[cite: 81].

##### b. Thông qua Github Desktop

1.  [cite_start]Mở GitHub Desktop → chọn **Create a new repository**[cite: 83].
2.  [cite_start]Chọn thư mục dự án → đặt tên repo[cite: 84].
3.  [cite_start]Nhấn **Publish repository** để đưa lên GitHub[cite: 85].
4.  [cite_start]Sau khi chỉnh sửa → **Commit** → **Push origin**[cite: 86].
5.  [cite_start]Mở bằng VSCode để tiếp tục làm việc[cite: 87].

### II. TRỰC TIẾP TRÊN GITHUB QUA GITHUB CODESPACE

#### 1. Github CodeSpace là gì?

* [cite_start]Là môi trường lập trình trực tuyến giống Visual Studio Code[cite: 90].
* [cite_start]Chạy trực tiếp trên GitHub, không cần cài đặt phần mềm[cite: 91].
* [cite_start]Tự động tải mã nguồn, cài thư viện, và lưu thay đổi[cite: 92].
* [cite_start]Phù hợp để chỉnh sửa nhanh, làm việc nhóm, hoặc tham gia dự án mã nguồn mở[cite: 93].

#### 2. Cách sử dụng Github CodeSpace

1.  [cite_start]Vào trang GitHub → đăng nhập tài khoản[cite: 95].
2.  [cite_start]Tìm địa chỉ repo bạn muốn chỉnh sửa (có thể là repo của người khác hoặc repo của bạn)[cite: 96].
3.  [cite_start]Dán địa chỉ repo vào thanh tìm kiếm → mở repo[cite: 97].
4.  [cite_start]Nhấn nút **Code** → chọn tab **Codespaces**[cite: 98].
5.  [cite_start]Nhấn **Create with Codespaces** hoặc **New codespace**[cite: 99].
6.  [cite_start]GitHub sẽ mở giao diện VSCode trực tiếp trong trình duyệt[cite: 100].
7.  [cite_start]Bạn có thể chỉnh sửa, commit, push ngay trên web mà không cần tải về[cite: 101].
8.  [cite_start]Nếu muốn đóng góp vào dự án người khác → tạo **Pull Request**[cite: 102].

---

## D. THAM GIA DỰ ÁN MÃ NGUỒN MỞ

### I. MÃ NGUỒN MỞ LÀ GÌ?

* [cite_start]Là các dự án phần mềm có mã nguồn công khai, ai cũng có thể xem, sử dụng, chỉnh sửa và đóng góp[cite: 105].
* [cite_start]Giúp cộng đồng cùng phát triển phần mềm, học hỏi lẫn nhau[cite: 106].
* [cite_start]Các giấy phép phổ biến: **MIT, GPL, Apache**[cite: 107].

### II. CÁCH THAM GIA VÀO DỰ ÁN MÃ NGUỒN MỞ

#### 1. Tìm dự án phù hợp

* [cite_start]Truy cập [https://github.com/explore](https://github.com/explore) hoặc [https://opensource.guide](https://opensource.guide)[cite: 110].
* [cite_start]Tìm dự án theo ngôn ngữ bạn biết (Python, JavaScript, C++, v.v.)[cite: 111].
* [cite_start]Ưu tiên chọn dự án có nhãn **good first issue** hoặc **help wanted**[cite: 112].

#### 2. Quy trình tham gia

1.  [cite_start]**Fork** dự án: tạo bản sao repo về tài khoản của bạn[cite: 114].
2.  [cite_start]**Clone** repo fork về máy để chỉnh sửa: `git clone <link_repo>`[cite: 115].
3.  [cite_start]Tạo nhánh mới để làm việc riêng: `git checkout -b ten-nhanh-moi`[cite: 116].
4.  [cite_start]Chỉnh sửa mã nguồn → **commit** → **push** lên repo fork[cite: 117].
5.  [cite_start]Tạo **Pull Request** để gửi thay đổi cho repo gốc[cite: 118].
6.  [cite_start]Chủ dự án sẽ **review** → nếu đồng ý sẽ **merge** vào dự án chính[cite: 119].

#### 3. Lưu ý khi đóng góp

* [cite_start]Bạn có thể thực hiện tương tự thông qua Github CodeSpace[cite: 121].
* [cite_start]Đọc kỹ file **README.md** và **CONTRIBUTING.md** của dự án[cite: 122].
* [cite_start]Viết **commit** rõ ràng, dễ hiểu[cite: 123].
* [cite_start]Tôn trọng quy tắc cộng đồng, phản hồi lịch sự[cite: 124].
* [cite_start]Có thể bắt đầu bằng việc sửa lỗi nhỏ, cải thiện tài liệu, hoặc thêm tính năng đơn giản[cite: 125].

---

## E. TỔNG KẾT

* [cite_start]**VS Code:** Công cụ viết code mạnh mẽ và phổ biến[cite: 127].
* [cite_start]**Git:** Công cụ quản lý phiên bản không thể thiếu[cite: 128].
* [cite_start]**GitHub:** Nơi lưu trữ, chia sẻ mã nguồn và làm việc nhóm[cite: 129].
* [cite_start]**GitHub Desktop:** Dễ dùng, trực quan cho người mới[cite: 130].

[cite_start]**→ Bộ công cụ giúp học sinh – sinh viên làm việc khoa học, chuyên nghiệp, hiệu quả hơn.** [cite: 131]