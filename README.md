### vieclamit - bot tìm việc làm IT
- Yêu cầu 1 tin tuyển dụng (recruitment) hợp lệ phải đủ các trường sau:
```
{
    "title" : "Sales Manager (IT Outsourcing) - Up To 2500$",
    "company" : "Công ty CP Savvycom",
    "location" : "Hà Nội",
    "salary" : "Tới 2,500 USD",
    "url_job" : "https://www.topcv.vn/brand/savvycomsoftware/tuyen-dung/sales-manager-it-outsourcing-up-to-2500-j595803.html",
    "url_company" : "https://savvycomsoftware.com/",
    "job_deadline" : "15/03/2022"
} 
```

- Tiêu chí:
* [x]  Thu thập hết dữ liệu từ nguồn
* [x]  Dữ liệu thu thập không bị trùng lặp
* [x]  Lập lịch tự động thu thập dữ liệu
* [x]  Lập lịch tự động xóa các tin tuyển dụng quá hạn

- Chức năng:
    - Tìm kiếm tin tuyển dụng theo từ khóa không phân biệt chữ hoa/thường, phải đủ dấu:
        * [x]  Từ khóa: skill (golang, python, php,...)
        * [x]  Từ khóa: location (Hà nội, Hồ chí minh, đà nẵng,...)
        * [x]  Từ khóa: company (vccorp, FPT, vng,...)
    - Xem chi tiết nội dung tin tuyển dụng dưới dạng ảnh chụp màn hình
    [link](https://www.topcv.vn/brand/smartosc/tuyen-dung/it-comtor-j592057.html)
    ![alt text](https://github.com/dactoankmapydev/vieclamit/blob/master/screenshot_descript_brand.png)

- Cài đặt:
    - [golang-install](https://go.dev/doc/install)
    - [mongodb-on-ubuntu-20-04](https://www.digitalocean.com/community/tutorials/how-to-install-mongodb-on-ubuntu-20-04)
- Sử dụng:
```
$ go run main.go
```
    Hoặc:
```
$ go build
$ ./vieclamit
```
