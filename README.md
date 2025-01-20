<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Xuân Ất Tỵ</title>
    <style>
        /* Định dạng cho dòng chữ chạy */
        @keyframes runText {
            from {
                transform: translateX(100%);
            }
            to {
                transform: translateX(-100%);
            }
        }

        .running-text {
            font-size: 40px;
            font-weight: bold;
            color: red;
            animation: runText 10s linear infinite;
            white-space: nowrap;
            overflow: hidden;
            position: fixed;
            top: 10px;
            right: 0;
        }

        /* Định dạng chung */
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f7f1e3;
            text-align: right; /* Canh lề phải */
        }

        h1 {
            color: #e84118;
            text-align: center;
        }

        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px auto;
        }

        /* Định dạng cho các đoạn văn */
        p {
            font-size: 16px;
            line-height: 1.5;
            color: #2f3542;
        }

        /* Định dạng cho P1 */
        .important-p1 {
            font-weight: bold;
            color: #f39c12; /* Màu vàng */
        }

        /* Định dạng cho P2 và P3 */
        .important-p2,
        .important-p3 {
            font-style: italic;
            color: #2980b9; /* Màu xanh dương */
        }
    </style>
</head>
<body>
    <!-- Dòng chữ chạy -->
    <div class="running-text">XUÂN ẤT TỴ-2025!</div>

    <h1>Chào mừng đến với trang web Tết cổ truyền</h1>

    <!-- Hình ảnh ngày Tết -->
    <img src="tet2025.jpg" alt="Hình ảnh Tết cổ truyền">

    <!-- Nội dung -->
    <p>Đây là nội dung giới thiệu về ngày Tết cổ truyền của Việt Nam. Tết là dịp để mọi người sum họp, quây quần bên nhau.</p>
    <p class="important-p1">P1: Tết Nguyên Đán không chỉ là dịp lễ truyền thống mà còn là thời gian để tri ân tổ tiên và đón chào năm mới.</p>
    <p class="important-p2">P2: Tục lệ lì xì đầu năm mang ý nghĩa chúc may mắn và tài lộc cho cả năm.</p>
    <p class="important-p3">P3: Mâm cỗ Tết Việt bao gồm bánh chưng, dưa hành, thịt kho tàu, và nhiều món ăn đặc trưng khác.</p>
    <p>Các hoạt động vui chơi trong dịp Tết như múa lân, bắn pháo hoa, và đi lễ chùa là những nét đẹp văn hóa truyền thống.</p>
</body>
</html>
