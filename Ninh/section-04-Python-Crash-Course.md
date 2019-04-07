# Số, biến: 
Số nguyên: 1

Số thực: 1.0

Các phép toán như các ngôn ngữ khác: + , - , * , / , % (lấy số dư). 

Phép toán đặc biệt: Lũy thừa: `**`. 
```
Ví dụ: 2**4 = 16
```

Khai báo biến không cần kiểu dữ liệu. Ví dụ: 

```
myVar = 2
```

Kiểu dữ liệu thì có thể dùng '' hoặc "". Ví dụ: 

```
'single quote'
"double quote"
```

Để in một giá trị, chỉ cần dùng lệnh: print

# Dictionary: 
Kiểu dữ liệu tương tự như object trong Javascript, tuy nhiên các tên thuộc tính phải là chuỗi. Ngoài ra, để truy xuất giá trị ta phải dùng dấu `[]`, không thể dùng dấu `.` như Javscript. Ví dụ:

```
student = {'name': 'Ninh' , 'age' : 12}
student['name']
```
Kết quả: 'Ninh'

# Boolean:
Sử dung từ khóa `True` và `False`. 

# Tupple: 

Tupple là dạng danh sách giống như mảng nhưng sử dụng `()` để khởi tạo. Ví dụ: 
```
myTupple = (1,2,3) 
```

Khác với mảng, chúng ta không thể asign giá lại giá trị trong tupple. Ví dụ, đoạn code sau sẽ bị lỗi:
```
myTuple = (1,2,3) 
myTuple[0] = 1

```
```
---------------------------------------------------------------------------
TypeError                                 Traceback (most recent call last)
<ipython-input-26-864eecaf1c6e> in <module>()
      1 myTuple = (1,2,3)
----> 2 myTuple[0] = 1

TypeError: 'tuple' object does not support item assignment
```


# Tập hợp (Set): 

Set là kiểu dữ liệu danh sách khộng trùng lắp. Sử dụng dấu `{}` để khởi tạo tập hợp.

Chúng ta có thể vô tư thêm các phần tử trùng lắp vào tập hợp nhưng kết quả cuối cùng thì tập hợp vẫn không bị trùng lắp. 

Ví dụ: 

```
mySet = {1,1,1,1,1,2,2,2,2,2,3,3,3,3}

```
Kết quả: {1,2,3}

Chúng ta có thể dùng hàm add() để thêm phần tử vào Set. Ví dụ: 

```
s.add(4)
```
Kết quả: {1,2,3,4}

# So sánh: 
 
 Các phép toán so sánh bao gồm: > , < , == , >= , <= , and, or.
 
 Biểu thức điều kiện `if` không được dùng kèm với dấu ngoặc đơn như Javascript mà dùng dấu `:` ở cuối câu. Ví dụ:
 
 ```
 if 1 < 2:
      print('yep!')
 ``
 
 Biểu thứ else cũng tương tự như thế. 
 
 ```
 if 1 == 2:
      print('yep!')
 else:
      print('no')

 ```
 









