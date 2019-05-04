# Section 5 - Python for Data Analysis - NumPy
## Tao ma tran
- ```import numpy as np```
- Tao ma tran 1:  ```np.ones(1, 2)```
- Khoang cach giua 0 va 5 lay 8 item:  ```np.linspace(0, 5, 8)```
- Lay 100 so int random giua 1 va 100: ```np.random.randint(1, 100, 10)```
- Lay array  tu 0=>24: ```np.arange(25)```
- Sap xep lai arr sang ma tran theo dong va cot: ```arr.reshape(5, 5)```
- Lay index cua item lon nhat trong array: ```ranarr.argmax()```
- Import ham randint: ```from numpy.random import randint```
- Create array 5x5 random number pos/negative: ```np.random.randn(25)```
## Indexing
- Copy array ref: ```arr_copy = arr.copy()```. ```arr_copy[:] = 100``` arr_copy se khong reference toi arr.
- Copy array ko ref: ```arr_copy = arr[:]```
- Cat mang 2 chieu: ```arr_2d[:2,1:]```
- Tao mang bool theo dk mang arr: ```bool_arr = arr > 5```
- Lay nhung phan tu thoa dieu kien theo mang arr: ```arr[bool_arr]```
  