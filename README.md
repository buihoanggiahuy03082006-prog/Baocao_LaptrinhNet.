# 🏢 XÂY DỰNG WEBSITE BÁN HÀNG CÔNG NGHỆ FPT SHOP

---

## 📖 1. GIỚI THIỆU ĐỀ TÀI

* **Học phần:** Lập trình .NET
* **Đề tài:** Xây dựng hệ thống website mua sắm và quản lý cửa hàng đồ điện tử FPT Shop.

Hệ thống được xây dựng nhằm phục vụ nhu cầu mua sắm trực tuyến của khách hàng đồng thời hỗ trợ quản trị viên (Admin) quản lý kho hàng, danh mục, sản phẩm, duyệt đơn hàng, theo dõi bảo hành và thống kê doanh thu hiệu quả.

Hệ thống bao gồm các chức năng chính:

* **Đăng ký, Đăng nhập & Phân quyền:** Phân chia 2 vai trò cơ bản là Khách hàng (mua sắm) và Admin (vào trang quản trị).
* **Quản lý Danh mục (CRUD):** Thêm, sửa, xóa các nhóm hàng hiển thị trên menu như Điện thoại, Laptop, Máy tính bảng, Phụ kiện.
* **Quản lý Sản phẩm (CRUD):** Thêm, sửa, xóa sản phẩm (tên máy, giá bán, hình ảnh, số lượng tồn kho, số tháng bảo hành và thông số tóm tắt).
* **Trang chủ & Xem chi tiết sản phẩm:** Hiển thị danh sách sản phẩm nổi bật theo từng danh mục và trang xem chi tiết cấu hình, giá bán của từng máy.
* **Tìm kiếm & Lọc sản phẩm:** Thanh tìm kiếm theo tên thiết bị kết hợp bộ lọc cơ bản theo danh mục hoặc khoảng giá.
* **Giỏ hàng & Đặt hàng (Checkout):** Thêm máy vào giỏ, cập nhật số lượng, xóa khỏi giỏ, nhập thông tin người nhận (Tên, SĐT, Địa chỉ) và bấm đặt hàng.
* **Quản lý & Duyệt đơn hàng:** Admin xem danh sách đơn khách vừa đặt, chuyển trạng thái (`Chờ duyệt` ➔ `Đang giao` ➔ `Hoàn thành`) và tự động trừ số lượng tồn kho khi duyệt đơn.
* **Tra cứu Đơn hàng & Bảo hành:** Khách hàng nhập Số điện thoại hoặc Mã đơn hàng để theo dõi tình trạng giao hàng và xem ngày hết hạn bảo hành của thiết bị đã mua.
* **Thống kê Doanh thu:** Chọn khoảng thời gian (`Từ ngày` – `Đến ngày`) để liệt kê các đơn đã hoàn thành và tính tổng doanh thu bán hàng.

---

## 👥 2. THÀNH VIÊN NHÓM THỰC HIỆN

<table>
  <thead>
    <tr>
      <th align="center">STT</th>
      <th align="center">Họ và Tên</th>
      <th align="center">Vai trò chính</th>
      <th align="center">Phân công nhiệm vụ cụ thể</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">1</td>
      <td align="center"><b>Bùi Hoàng Gia Huy</b></td>
      <td align="center">Nhóm trưởng</td>
      <td>
        <b>Hệ thống & Quản lý Kho hàng (Phía Admin):</b><br>
        • Đăng ký, Đăng nhập & Phân quyền: Phân chia 2 vai trò cơ bản là Khách hàng (mua sắm) và Admin (vào trang quản trị).<br>
        • Quản lý Danh mục (CRUD): Thêm, sửa, xóa các nhóm hàng hiển thị trên menu như Điện thoại, Laptop, Máy tính bảng, Phụ kiện.<br>
        • Quản lý Sản phẩm (CRUD): Thêm, sửa, xóa sản phẩm (tên máy, giá bán, hình ảnh, số lượng tồn kho, số tháng bảo hành và thông số tóm tắt).<br>
        • Điều phối tiến độ và quản lý mã nguồn GitHub.
      </td>
    </tr>
    <tr>
      <td align="center">2</td>
      <td align="center"><b>Đinh Xuân Trường</b></td>
      <td align="center">Thành viên</td>
      <td>
        <b>Giao diện Mua sắm (Phía Khách hàng - giống FPT Shop):</b><br>
        • Trang chủ & Xem chi tiết sản phẩm: Hiển thị danh sách sản phẩm nổi bật theo từng danh mục và trang xem chi tiết cấu hình, giá bán của từng máy.<br>
        • Tìm kiếm & Lọc sản phẩm: Thanh tìm kiếm theo tên thiết bị kết hợp bộ lọc cơ bản theo danh mục hoặc khoảng giá.<br>
        • Giỏ hàng & Đặt hàng (Checkout): Thêm máy vào giỏ, cập nhật số lượng, xóa khỏi giỏ, nhập thông tin người nhận (Tên, SĐT, Địa chỉ) và bấm đặt hàng.
      </td>
    </tr>
    <tr>
      <td align="center">3</td>
      <td align="center"><b>Nguyễn Quang Huy</b></td>
      <td align="center">Thành viên</td>
      <td>
        <b>Xử lý Đơn hàng, Bảo hành & Thống kê:</b><br>
        • Quản lý & Duyệt đơn hàng: Admin xem danh sách đơn khách vừa đặt, chuyển trạng thái (<code>Chờ duyệt</code> ➔ <code>Đang giao</code> ➔ <code>Hoàn thành</code>) và tự động trừ số lượng tồn kho khi duyệt đơn.<br>
        • Tra cứu Đơn hàng & Bảo hành: Khách hàng nhập Số điện thoại hoặc Mã đơn hàng để theo dõi tình trạng giao hàng và xem ngày hết hạn bảo hành của thiết bị đã mua.<br>
        • Thống kê Doanh thu: Chọn khoảng thời gian (<code>Từ ngày</code> – <code>Đến ngày</code>) để liệt kê các đơn đã hoàn thành và tính tổng doanh thu bán hàng.
      </td>
    </tr>
  </tbody>
</table>
