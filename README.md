
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chào Mừng Tết Nguyên Đán</title>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
    <style>
        h1 {
            display: none;
            }
        /* Toàn bộ trang */
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(120deg, #ffecd2, #fcb69f);
            color: #333;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        /* Định dạng đoạn văn mặc định */
        p {
            position: relative;
            padding: 20px;
            margin-bottom: 20px;
            background-color: #ffffff;
            border-radius: 10px;
            border: 1px solid #ddd;
            font-size: 1.2rem;
        }

        /* Định dạng cho P1 */
        .p1 {
            background-color: #ffe5e5; /* Nền hồng nhạt */
            color: #c0392b; /* Chữ đỏ đậm */
            border-left: 5px solid #c0392b; /* Viền trái đậm */
            border-right: 3px dashed #e74c3c; /* Viền phải nét đứt */
            border-top: 2px solid #e57373; /* Viền trên mỏng */
            border-bottom: 4px double #d63031; /* Viền dưới nét đôi */
        }

        /* Định dạng cho P2 và P3 */
        .p2, .p3 {
            background-color: #e5f7ff; /* Nền xanh nhạt */
            color: #2980b9; /* Chữ xanh đậm */
            border: 3px solid #3498db; /* Viền đều 4 cạnh */
        }

        /* Hình ảnh bên trái */
        .image-left {
            float: left;
            width: 100px;
            height: 100px;
            margin-right: 15px;
            border-radius: 10px;
            object-fit: cover;
        }

        /* Hình ảnh bên phải */
        .image-right {
            float: right;
            width: 100px;
            height: 100px;
            margin-left: 15px;
            border-radius: 10px;
            object-fit: cover;
        }

        /* Thanh tiêu đề chạy ngang */
        .marquee-container {
            width: 100%;
            background: #e74c3c;
            padding: 15px 0;
            overflow: hidden;
            white-space: nowrap;
            position: relative;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
        }

        .marquee-text {
            display: inline-block;
            font-size: 2.5rem;
            font-weight: bold;
            font-family: 'Dancing Script', cursive;
            color: white;
            text-shadow: 0 0 10px #ffd700, 0 0 20px #ff4500, 0 0 30px #ff8c00;
            animation: marquee 12s linear infinite, glow 2s ease-in-out infinite alternate;
        }

        @keyframes marquee {
            from {
                transform: translateX(100%);
            }
            to {
                transform: translateX(-100%);
            }
        }

        @keyframes glow {
            from {
                text-shadow: 0 0 10px #ffd700, 0 0 20px #ff4500, 0 0 30px #ff8c00;
            }
            to {
                text-shadow: 0 0 20px #ff6347, 0 0 30px #ff4500, 0 0 40px #ff8c00;
            }
        }

        /* Clear float */
        .clearfix {
            clear: both;
        }
    </style>
</head>
<body>

    <!-- Thanh tiêu đề chạy ngang -->
    <div class="marquee-container">
        <div class="marquee-text">✨ Chào Mừng Tết Nguyên Đán 2025 - Chúc Mừng Năm Mới 🎉</div>
    </div>

    <!-- Nội dung trang web -->
    <div class="content">
        <!-- Đoạn văn mặc định -->
        <p>Chúc bạn và gia đình một năm mới tràn đầy hạnh phúc và thành công! 🌟</p>

        <!-- Đoạn văn P1 -->
        <p class="p1 clearfix">
            <img src="https://example.com/hinh-hoa-dao.jpg" alt="Hoa đào" class="image-left">
            <strong>Hoa Đào - Biểu Tượng Của Mùa Xuân:</strong>  
            Tết Nguyên Đán là thời điểm hoa đào khoe sắc, mang lại may mắn và niềm vui cho mọi nhà.
        </p>

        <!-- Đoạn văn P2 -->
        <p class="p2 clearfix">
            <img src="https://example.com/hinh-li-xi.jpg" alt="Lì xì" class="image-right">
            <strong>Tục Lệ Lì Xì - Chúc May Mắn Đầu Năm:</strong>  
            Những phong bao đỏ tượng trưng cho lời chúc phúc, tài lộc và bình an trong năm mới.
        </p>

        <!-- Đoạn văn P3 -->
        <p class="p3 clearfix">
            <img src="IMG_4905.jpeg" alt="Bánh chưng" class="image-left">
            <strong>Bánh Chưng - Hương Vị Của Tết:</strong>  
            Món bánh chưng truyền thống, biểu tượng của sự đoàn viên và văn hóa Việt Nam.
      <div class="audio-player">
        <p>🎶 Nghe nhạc Tết: <strong>Xuân Đã Về</strong></p>
        <audio autoplay loop controls>
            <source src="y2mate.com - Ngày Xuân Long Phụng Xum Vầy Ngô Kiến Huy Khổng Tú Quỳnh Nhiều Ca Si 2013.mp3" type="audio/mpeg">
            Trình duyệt của bạn không hỗ trợ thẻ audio.
        </audio>
    </div>

</body>
</html>
