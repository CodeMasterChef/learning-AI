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

# numpy.zeros(number)

Khởi tạo một mảng có number các số 0. Hàm này thường được dùng để khởi tạo vector 0 với number chiều.
Ví dụ: 
```
import numpy as  np
np.zeros(3)
```
Kết quả: ```array([0., 0., 0.])```


Chúng ta cũng có thể tạo vector 0 nhiều chiều, ví dụ: tạo vector 0 có 3 dòng 2 cột:

```
import numpy as  np
np.zeros((3,2))

```
Kết quả: 
``` 
array([[0., 0.],
       [0., 0.],
       [0., 0.]])

```
# numpy.ones(number) 
Khởi tạo một mảng có number các phần tử 1.

```
import numpy as  np
np.ones(3)

```
Kết quả: ```array([1., 1., 1.])```

# numby.linspace(start, stop, number)

Khởi tạo một mảng có number phần tử từ start đến stop.

Ví dụ: 

```
import numpy as np
np.linspace(1,10,3)
```
Kết quả : ```array([ 1. , 5.5, 10. ])```

# numpy.eye(rowNumber , columnNumber)

Trả về ma trận chéo có rowNumber d và columnNumber cột: đường chéo là 1, chỗ khác thì 0. 

Ví vụ:
```
import numby as np
np.eye(3,2)
```
Kết quả: 

```
array([[1., 0.],
       [0., 1.],
       [0., 0.]])
```


# numpy.random.rand(d1, d2,...)

Trả về một mảng chứa các phần tử sinh tự do từ 0 đến 1. 

Ví dụ: 

```
import numpy as  np
np.random.rand(3,2)
```
Kết quả trả về: 

```
array([[0.46322199, 0.38592549],
       [0.54504234, 0.07416177],
       [0.07517889, 0.21519514]])
```


# numby.random.randn(d1,d2,...)

Trả về một mảnh có d1,d2,... chiều, trong đó các phần tử được sinh tự do theo phân phối chuẩn (phân phối Gauss).

Ví dụ:

```
import numpy as  np
np.random.randn(4)
```

Kết quả: 

```
array([-0.32572334, -2.47828912, -0.0445359 ,  0.29938883])
```













