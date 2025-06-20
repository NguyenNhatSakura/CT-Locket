
# 🚀 CT-Locket Tool v1.4 🚀

![Demo](https://img.upanh.tv/2025/05/24/Screenshot-18.png)

> Đây là công cụ giúp bạn tăng bạn bè ảo hoàn loạt bằng cách tạo nhiều tài khoản rác và gửi yêu cầu kết bạn tới Locket được chỉ định.<br>
Đừng nghĩ đây chỉ là tool spam kết bạn và chỉ cần tắt yêu cầu kết bạn hoặc tắt thông báo là xong, vì Locket Widget sử dụng api fetch user liên tục khi vào app, nếu quá nhiều yêu cầu kết bạn sẽ dẫn đến bị <b>Overload</b> cũng có thể bị lỗi mất hiển thị bạn bè cực kì khó chịu.

## 💻 Hướng Dẫn Trên Máy Tính
- [Tải xuống Python 3.12.2 nếu chưa có](https://www.python.org/downloads/release/python-3120/)<br/>
> Tự gắn proxy sài nha ae hỗ trợ loại http/https, không gắn proxy là không sài được đâu :Đ
### ⚙️ Cài Đặt Môi Trường

```bash
pip install -r requirements.txt
```
>Hoặc
```bash
pip install requests tqdm colorama pystyle urllib3
```
### 🏃 Chạy Tool
```bash
python CT-Locket.py
```

- [x] Nhanh Gọn
- [x] Dễ Dùng
- [x] Spam Mượt Và Nhanh
...

### 🏀 Hướng Dẫn Trên Google Shell (Cloud Shell)

Lên **App Store** để tải xuống ứng dụng **Google Cloud** - [Nhấn vào đây để tải xuống](https://apps.apple.com/us/app/google-cloud/id1005120814)<br>
Tôi thấy Google Shell đã tích hợp sẵn các thứ cần thiết nên không cần setup gì nhiều
### 🐍 Cài Đặt PIP
```bash
sudo apt install -y python3-pip
```
### ⬇️ Tải CT-Locket Tool

```bash
git clone https://github.com/NguyenNhatSakura/CT-Locket.git
```
> Lệnh cài môi trường và pip giống lệnh trên máy tính nên không cần hướng dẫn ở đây
### 📂 Đến Thư Mục Tool
```bash
cd CT-Locket
```
### 📂 Lấy Proxy Nếu Chưa Có (Mõi lần chạy tool thì CURL 1 lần nhé)
```bash
curl -o proxy.txt "https://thanhdieu.com/api/list/proxyv3.txt"
```
>Hoặc
```bash
curl -o proxy.txt "https://api.proxyscrape.com/v4/free-proxy-list/get?request=display_proxies&protocol=http&proxy_format=protocolipport&format=text&timeout=20000"
```
### 🏃 Chạy Tool
```bash
python CT-Locket.py
```
Nếu không được hãy thử lệnh `python3 CT-Locket.py`
- [x] Sài Được Trên Điện Thoại
- [x] Dễ Dùng
- [x] Tiện Nghi
...
