## Entry

Là vị trí bắt đầu để webpack build. Mặc định là `./src/index.js`. `src` viết tắt cho `source` (nguồn)

## Output

Thuộc tính output nói cho webpack biết nơi nào sẽ lưu trữ file bundles và cách đặt tên cho nó. Mặc định là `./dist/main.js` và các file liên quan sẽ được build vào trong folder `./dist`. `dist` viết tắt cho `distribution` (bản phân phối)

## Loaders

Webpack chỉ hiểu JavaScript và JSON. Loaders cho phép webpack có thể thực thi với các loại file khác và convert chúng thành module hợp lệ để app của chúng ta có thể sử dụng được.

Ở mức cao nhất, loader có 2 thuộc tính là webpack config

- Thuộc tính `test` xác định file nào sẽ được biến đổi
- Thuộc tính `use` chỉ ra cái gì sẽ được loader sử dụng để biến đổi

## Plugins

Trong khi loader được sử dụng để biến đổi một file có kiểu cụ thể. Plugins có thể được sử dụng để thực thi nhiều tác vụ hơn, như tối ưu hóa, quản lý tài nguyên hay thêm các biến môi trường

## Mode

Thuộc tính mode nhận một trong các giá trị `development`, `production` hoặc `none`, sử dụng mode để kích hoạt môi trường build. Mặt định, mode nhận giá trị `production`

# Browser compatibility
