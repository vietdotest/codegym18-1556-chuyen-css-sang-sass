# Chuyen Css Sang Sass

Bài CodeGym 1556.

## Chạy
`npm ci`, `npm run build`, sau đó mở index.html. `npm run build:min` tạo CSS nén; `npm run watch` theo dõi thay đổi. PowerShell có thể dùng npm.cmd.

## Tái cấu trúc
Nguồn CSS được cung cấp trực tiếp trong đề: body, container, button và card. Tách abstracts, base, layout, components; biến quản lý màu/bóng đổ, mixin cho button và shadow. Nesting tại body/container. Giữ nguyên giá trị CSS đã giao.

Dùng @use để gộp partials. CSS đã biên dịch được commit để có thể mở trang ngay.

## Đối chiếu
Mở original.html để xem bản CSS ban đầu. Kết quả biên dịch tại build-validation.json; kiểm tra computed styles và bố cục trước/sau tại validation.json.
