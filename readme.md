# Nodepay Network Bot

## Contact me:
```
   Telegram: https://t.me/null671
   Join Grass: https://app.getgrass.io/register/?referralCode=ssMIrLbjhT-OJAZ
   Proxy + tool: 50 Proxies for only $10
```

## Description
This script automates network or node operations for Nodepay Network.

## Features
- **Automated node interaction**
- **Mutil-account session**
- **Proxy and non-proxy support**

## Prerequisites
- [Python](https://www.python.org/) (version 3.7 or higher)

## Usage
1. Register nodepay account first, if you dont have you can register [here](https://app.nodepay.ai/register?ref=WKAjFjvHncz5BGb), I recomended to download extension and activate your account first before running the script.
2. Set and Modify `user.txt` before running the script. Below how to setup this file, put your np_token in the text file, example below:
	```
	eyJhbGcixxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
	eyJ23wixxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
	```
	To get your token, follow this step:
	- Login to your grass account in https://app.nodepay.ai/dashboard, make sure you is in this link before go to next step
	- Go to inspect element, press F12 or right-click then pick inspect element in your browser
	- Go to application tab - look for Local Storage in storage list -> click `https://app.nodepay.ai` and you will see your np_token.
	- or you can go Console tab and paste this 
	```bash
	localStorage.getItem('np_token')
	```
3. If you want to use proxy, edit the `proxy.txt` with your proxy.
	```
 	ip:port
	username:password@ip:port
	http://ip:port
	http://username:password@ip:port
	socks5://ip:port
	socks5://username:password@ip:port
 	```
4. Run the script:
	```
	main.exe
	```
5. When running the script, select the menu if you want to use proxy or not and if you want to show the error in console or not with arrow keys, it will look like this
	```
 	? Do you want to use or run with proxy? (Use arrow keys)
	❯ Use Proxy
	  Without Proxy/Local network
 	```
	```
	? Do you want to show error in console?
	❯ Show Errors
	  Hide Errors
	```
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Note
This script only for testing purpose, using this script might violates ToS and may get your account permanently banned.





## Nodepay Network Bot

## Mô tả
Bot này tự động hóa việc vận hành mạng hoặc node (nút mạng) trên hệ thống Nodepay Network. Đây là một công cụ giúp bạn tối ưu hóa hoạt động tài khoản để tăng cơ hội nhận airdrop.

## Tính năng
- **Tự động tương tác với node: Gửi tín hiệu ping liên tục để duy trì hoạt động của tài khoản.**
- **Hỗ trợ đa tài khoản: Bạn có thể vận hành nhiều tài khoản cùng lúc bằng cách sử dụng danh sách token.**
- **Hỗ trợ proxy: Tăng cường bảo mật và hạn chế bị chặn IP bằng proxy.**

## Yêu cầu
- Python (phiên bản 3.7 hoặc cao hơn): Công cụ lập trình cần thiết để chạy bot.

## Tài khoản Nodepay: Cần đăng ký tài khoản và kích hoạt node trước khi sử dụng bot.
- Hướng dẫn cài đặt
- Tải mã nguồn về máy tính:
- Thêm đầy đủ data vào file user.txt và proxy.txt
- Mở file main.exe để bắt đầu chạy

## Hướng dẫn sử dụng
1. Lấy token (np_token) của bạn:
- Trước tiên, hãy đăng ký tài khoản nodepay, nếu bạn chưa có, bạn có thể đăng ký [tại đây] (https://app.nodepay.ai/register?ref=WKAjFjvHncz5BGb). Tôi khuyên bạn nên tải tiện ích mở rộng và kích hoạt tài khoản trước khi chạy tập lệnh.
- Đăng nhập vào tài khoản trên trang Nodepay: Nodepay Dashboard(https://app.nodepay.ai/dashboard).
- Sử dụng công cụ Inspect Element (F12) trong trình duyệt để truy cập Local Storage:
	+ Tìm mục np_token ở phần Local Storage và sao chép nó.
	+ Hoặc sử dụng tab Console và chạy lệnh sau:
[javascript]
	localStorage.getItem('np_token')

2. Cấu hình file user.txt:
- Thêm token của bạn vào file user.txt.
Ví dụ:
	```
	eyJhbGcixxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
	eyJ23wixxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
	```

3. (Tùy chọn) Thêm proxy vào file proxy.txt:
- Định dạng proxy có thể sử dụng:
Ví dụ:
	```
 	ip:port
	username:password@ip:port
	http://ip:port
	http://username:password@ip:port
	socks5://ip:port
	socks5://username:password@ip:port
 	```

## Chạy bot:
- Chạy chương trình:
- Khởi chạy file main.exe từ tool đã tải
- Lựa chọn cài đặt khi được hỏi:
	+ Sử dụng proxy không?
		❯ Có sử dụng Proxy
  		  Không sử dụng Proxy/Mạng cục bộ
	+ Hiển thị lỗi trong console?
		❯ Hiển thị lỗi
  		  Ẩn lỗi

## Lưu ý:
- Chương trình thử nghiệm: Việc sử dụng bot có thể vi phạm điều khoản sử dụng của Nodepay, dẫn đến tài khoản bị khóa.
- Bảo mật thông tin: Hãy giữ token và proxy an toàn, tránh để lộ ra bên ngoài.
- Nếu cần thêm chi tiết hoặc hỗ trợ, bạn có thể cung cấp thêm thông tin! Telegram: @null671
