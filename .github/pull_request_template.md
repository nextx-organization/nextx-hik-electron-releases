<!--
  4 dòng dưới đây là BẮT BUỘC. Guard CI sẽ chặn PR nếu thiếu.
  Mất 10 giây điền, nhưng đây là thứ duy nhất tách được "lỗi yêu cầu" khỏi "lỗi code".
  Không dùng để chấm lương — dùng để biết công sức đang chảy đi đâu.
-->
Khách:
Nguồn:
Loại:
Sự cố:

<!--
  Khách:  tên nhà/khách hàng (GON, Việt Nhân, Thái Anh, An Phát, VIFIT...)
          hoặc "nội bộ" nếu không phục vụ khách cụ thể
          hoặc "toàn hệ" nếu ảnh hưởng mọi khách

  Nguồn:  khách báo | nội bộ phát hiện | theo kế hoạch | hồi quy

  Loại:   lỗi-yêu-cầu     — code chạy đúng như đã tả, nhưng tả sai/thiếu
          lỗi-code        — code chạy sai so với điều đã tả
          hạ-tầng         — server, mạng, CI, cấu hình, không phải logic
          tính-năng-mới   — làm mới, không sửa cái đang có

  Sự cố:  ngày sự cố (dd/mm/yyyy) nếu đây là vá sự cố; để trống nếu không phải
-->

## Nội dung

<!-- Mô tả cái gì thay đổi và TẠI SAO. Viết như đang giải thích cho người 3 tháng sau. -->

## Cách kiểm chứng

<!--
  Đã chạy gì để biết là nó chạy được? Nêu ĐỐI CHỨNG:
  ca nào phải đỏ trước khi vá, và giờ đã xanh.
  "build xanh" và "test pass" KHÔNG phải bằng chứng — guard có thể tự vô hiệu.
-->

## Rủi ro / đường lùi

<!-- Có chạm migration, DI, topology, gateway, nginx không? Lùi bằng cách nào? -->
