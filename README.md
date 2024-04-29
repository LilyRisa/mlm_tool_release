# Release công cụ auto MLM


## cách lấy cookie chuẩn
Sử dụng extension [EditThisCookie](https://chromewebstore.google.com/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg?hl=vi) để lấy cookie

## Crontab là gì và cách sử dụng
Crontab là một cách để tạo và chạy các lệnh theo một chu kỳ xác định. Đây là tiện ích giúp lập lịch trình để chạy những tác vụ. Có thể sử dụng công cụ [crontabguru](https://crontab.guru/)
 Ví dụ về 1 crontab:
 .---------------- Phút (0 - 59)
 |  .------------- Giờ (0 - 23)
 |  |  .---------- Ngày trong tháng (1 - 31)
 |  |  |  .------- Tháng (1 - 12) hoặc jan,feb,mar,apr ...
 |  |  |  |  .---- ngày trong tuần (0 - 6) (Sunday=0 or 7) hoặc sun,mon,tue,wed,thu,fri,sat
 |  |  |  |  |
 *  *  *  *  * 
 Vú dụ về lập lịch chạy tác vụ:
 ``` */2 * * * * ``` Vào phút thứ 2 chạy 1 lần
