<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>So Sánh Ô Tô Xăng và Ô Tô Điện</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f0f0f0;
        }
        h1 {
            color: #2c3e50;
            text-align: center;
        }
        .images {
            display: flex;
            justify-content: space-around;
            margin-bottom: 20px;
        }
        .images img {
            width: 45%;
            height: auto;
            border: 2px solid #ccc;
            border-radius: 8px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            background-color: #fff;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: center;
        }
        th {
            background-color: #3498db;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
    </style>
</head>
<body>

    <h1>So Sánh Ô Tô Chạy Bằng Xăng và Ô Tô Chạy Bằng Điện</h1>

    <div class="images">
        <div>
            <img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/Honda_Civic_Facelift_2020.jpg" alt="Ô tô chạy xăng">
            <p style="text-align:center;">Ô tô chạy bằng xăng</p>
        </div>
        <div>
            <img src="https://upload.wikimedia.org/wikipedia/commons/f/f2/Tesla_Model_3_parked%2C_front_driver_side.jpg" alt="Ô tô chạy điện">
            <p style="text-align:center;">Ô tô chạy bằng điện</p>
        </div>
    </div>

    <table>
        <tr>
            <th>Tiêu chí</th>
            <th>Ô tô chạy xăng</th>
            <th>Ô tô chạy điện</th>
        </tr>
        <tr>
            <td>Nhiên liệu</td>
            <td>Xăng/dầu</td>
            <td>Điện năng</td>
        </tr>
        <tr>
            <td>Chi phí sử dụng</td>
            <td>Cao hơn</td>
            <td>Tiết kiệm hơn</td>
        </tr>
        <tr>
            <td>Khí thải</td>
            <td>CO₂ và khí độc hại</td>
            <td>Không phát thải</td>
        </tr>
        <tr>
            <td>Bảo dưỡng</td>
            <td>Phức tạp hơn</td>
            <td>Đơn giản hơn</td>
        </tr>
        <tr>
            <td>Thời gian tiếp nhiên liệu/sạc</td>
            <td>Nhanh</td>
            <td>Lâu hơn</td>
        </tr>
        <tr>
            <td>Tác động môi trường</td>
            <td>Lớn hơn</td>
            <td>Ít hơn</td>
        </tr>
    </table>

</body>
</html>
