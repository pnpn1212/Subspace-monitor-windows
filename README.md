# Cài đặt Docker
Tải về và cài đặt
```
https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe?utm_source=docker&utm_medium=webreferral&utm_campaign=dd-smartbutton&utm_location=module&_gl=1*xi55t8*_ga*Mzg3NDU4MjguMTY5MjY5OTgxMg..*_ga_XJWPQMJYHQ*MTY5MzI1NDg2NC4zLjAuMTY5MzI1NDg2NC42MC4wLjA
```
# Setup (dành cho docker desktop trên Windows)
- Lưu ý: Subspace chạy trên Docker Desktop bắt buộc CPU phải từ 2015 trở về sau mới có thể chạy được

1/ Tải về thư mục Subspace
```
https://github.com/pnpn1212/Subspace-monitor-windows/archive/refs/heads/main.zip
```
2/ Edit file
- Mở docker-compose.yml lên và edit 
- Lưu lại sau khi edit xong

3/ Bắt đầu cài đặt
- Làm theo như hình nhập CMD và enter

![image](https://github.com/pnpn1212/Subspace-monitor-windows/assets/76662222/7c8e766f-4b20-4f5d-bc4d-491fd93c42ce)

```
docker compose up -d
```
Nếu không chạy được thì dùng 
```
docker-compose up -d
```
![image](https://github.com/pnpn1212/Subspace-monitor-windows/assets/76662222/c6f97b18-1fbf-4c89-aeea-bc7b67158a1d)

4/Truy cập Grafana
- Nếu là VPS thì thay localhost bằng địa chỉ IP
```
localhost:3000
```

Thông tin đăng nhập Grafana
```
user: admin
pass: MFL123123
```

Ảnh minh họa

![image](https://github.com/pnpn1212/Subspace-monitor-linux/assets/76662222/cb17be13-2e60-4a98-a978-8d5e631dcd9a)
![image](https://github.com/pnpn1212/Subspace-monitor-linux/assets/76662222/977ef134-b3b5-458e-a4f6-5e7e3ba1a562)
![image](https://github.com/pnpn1212/Subspace-monitor-linux/assets/76662222/ac7b4031-42ec-4e99-9b22-85f8d5a69e5a)

Bản quyền của MFLow - MFL VNBnodes
