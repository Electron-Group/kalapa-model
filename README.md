# kalapa-model

* <h1>Ở bộ: second challenge.iypnb</h1>
- Mình đã tách mỗi bộ dataset thành hai biến: categoric và numeric
- Sau đó mình đã Fill_missing data bằng cách:
  + Với biến numeric: mình đã dùng giá trị mean cho mỗi ô NaN
  + Với biến categoric: mình đã dùng giá trị mode cho mỗi ô Nan
- Tiếp theo là mình đã clean bớt cột giống nhau trong cả hai bộ dataset
- Sau đó mình dùng thư viện Autoviz và thư viện Sweetviz để biểu diễn cho mỗi biến
- Tiếp đó mình đi tìm cộ nào có ảnh hưởng đến giá trị label nhiều nhất.
* <h1>Ở tệp: Third challenge.iynb</h1>
- Đồng bộ hai bộ train và test
- Sau đó, mình đã chia bộ train thành 5 loại:
  + I: Date/ DateTime/ x_startDate, x_endDate: đây là những feature có dữ liệu là ngày tháng năm
  + II: xLocationId, xcountry, xstate,...: những feature có nhiều số 0, thay nó bằng giá trị Nan
  + III: diaChi, maCv: chưa xử lí được(vì chưa có thời gian nhiều cho nó)
  + IV: gioiTinh, info_social_sex: mình đã gộp hai feature này lại để giảm bớt truongf hợp thiếu
  + V: còn lại là những cột khác, cần phải xử lí nó, đồng thời drop những cột không cần thiết.
 - Cuối cùng là gộp nó thành một bộ dataset riêng, sau đó sẽ fill_missing data bằng những cách hợp lí
