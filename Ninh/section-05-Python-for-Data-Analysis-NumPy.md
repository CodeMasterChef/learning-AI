# Numpy:
Numpy là một package chủ yếu cho việc tính toán khoa học trên Python.

Numpy hỗ trợ mạnh mẽ việc tính toán với matrix, vector và các các hàm đại số tuyến tính cơ bản.

# Cài đặt:

Nếu sử dụng Anaconda để code Python thì nên dùng lệnh sau cài thư viện:
```
conda install numpy

```
Nếu code python thuần thì dùng lệnh sau: 

```
pip3 install numpy
```

# Sử dụng: 

Ví dụ:

```
import numpy as  np
x = [1, 2, 3]
np.array(x)

```
# numpy.arange(start, end, step)

Khởi tạo 1 mảng từ start đến end với bước nhảy là step.

Ví dụ:

```
import numpy as  np
np.arange(0,10,2)
```
Kết quả:  ```array([0, 2, 4, 6, 8])```

# numby.zeros(number)

Khởi tạo một mảng có number các số 0. Hàm này thường được dùng để khởi tạo vector 0 với number chiều.
Ví dụ: 
```
import numpy as  np
np.zeros(3)
```
Kết quả: ```array([0., 0., 0.])```





