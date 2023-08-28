# Cài đặt Docker
Tải về và cài đặt
```
https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe?utm_source=docker&utm_medium=webreferral&utm_campaign=dd-smartbutton&utm_location=module&_gl=1*xi55t8*_ga*Mzg3NDU4MjguMTY5MjY5OTgxMg..*_ga_XJWPQMJYHQ*MTY5MzI1NDg2NC4zLjAuMTY5MzI1NDg2NC42MC4wLjA
```
# Subspace Guide cài đặt (dành cho docker desktop trên Windows)
1/ Tải về thư mục Subspace
```
https://github.com/pnpn1212/Subspace-monitor-windows/archive/refs/heads/main.zip
```
2/ Giải nén thư mục và sửa đổi tên Node, địa chỉ ví, đường dẫn lưu file, đường dẫn plot, dung lượng cần plot
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
4/
Truy cập Grafana
```
localhost:3000
```

Thông tin đăng nhập Grafana
```
user: admin
pass: MFL123123
```

MFLow - MFL VNBnodes
