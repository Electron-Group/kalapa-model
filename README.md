# kalapa-model

code chính thức ở file: second challenge.iypnb
- Mình đã tách mỗi bộ dataset thành hai biến: categoric và numeric
- Sau đó mình đã Fill_missing data bằng cách:
  + Với biến numeric: mình đã dùng giá trị mean cho mỗi ô NaN
  + Với biến categoric: mình đã dùng giá trị mode cho mỗi ô Nan
- Tiếp theo là mình đã clean bớt cột giống nhau trong cả hai bộ dataset
- Sau đó mình dùng thư viện Autoviz và thư viện Sweetviz để biểu diễn cho mỗi biến
- Tiếp đó mình đi tìm cộ nào có ảnh hưởng đến giá trị label nhiều nhất.
