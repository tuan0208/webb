<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Image Preview</title>
  <style>
    #image {
      background-image: url("");
      background-size: cover;
      height: 300px;
      width: 500px;
      border: 2px solid #ccc;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 18px;
      color: #333;
    }
    .preview {
      width: 100px;
      margin: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <div id="image">
    Di chuột qua một hình ảnh bên dưới để hiển thị ở đây.
  </div>

  <img class="preview" alt="Ảnh 1" src="https://hoanghamobile.com/tin-tuc/wp-content/uploads/2024/04/anh-cuoi-34.jpg" 
       onmouseover="update(this)" onmouseout="unDo()">
  <img class="preview" alt="Ảnh 2" src="https://image.dienthoaivui.com.vn/x,webp,q90/https://dashboard.dienthoaivui.com.vn/uploads/dashboard/editor_upload/anh-meme-7.jpg"
       onmouseover="update(this)" onmouseout="unDo()">
  <img class="preview" alt="Ảnh 3" src="https://jbagy.me/wp-content/uploads/2025/04/Hinh-meme-meo-cuoi-deu-1.jpg" 
       onmouseover="update(this)" onmouseout="unDo()">

  <script src="script.js"></script>
</body>
</html>
