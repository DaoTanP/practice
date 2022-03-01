<!DOCTYPE html>
<html lang="vi">

<head>
    <meta charset="UTF-8">
    <title>Đăng kí khách hàng</title>
    <link rel="stylesheet" href="DangKiKhachHang.css">
</head>

<body>
    <form action="#" method="post">
        <h1>Đăng kí khách hàng</h1>
        <div class="info">
            <p>Thông tin đăng nhập</p>
            <table>
                <tr>
                    <td><span class="text">Tên đăng nhập</span></td>
                    <td><input type="text" required></td>
                </tr>
                <tr>
                    <td><span class="text">Mật khẩu</span></td>
                    <td><input type="password" required></td>
                </tr>
                <tr>
                    <td><span class="text">Nhập lại mật khẩu</span></td>
                    <td><input type="password" required></td>
                </tr>
            </table>
        </div>
        <div class="info">
            <p>Thông tin chi tiết cá nhân</p>
            <table>
                <tr>
                    <td><span class="text">Họ tên khách hàng</span></td>
                    <td><input type="text" required></td>
                </tr>
                <tr>
                    <td><span class="text">Ngày sinh</span></td>
                    <td><input type="date" required></td>
                </tr>
                <tr>
                    <td><span class="text">Giới tính</span></td>
                    <td>
                        <input type="radio" name="gioi_tinh" value="Nam">
                        <label for="gioi_tinh">Nam</label>
                        <input type="radio" name="gioi_tinh" value="Nữ">
                        <label for="gioi_tinh">Nữ</label>
                    </td>
                </tr>
                <tr>
                    <td><span class="text">Địa chỉ Email</span></td>
                    <td><input type="email"></td>
                </tr>
                <tr>
                    <td><span class="text">Thu nhập</span></td>
                    <td><input type="number"></td>
                </tr>
            </table>
        </div>
        <input type="submit" value="Đăng kí">
    </form>
</body>

</html>
