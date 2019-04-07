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

Để in một giá trị, chỉ cần dùng lệnh: print. Ví dụ:

```
print(myVar)

```
# String format: 
Có thể sử dụng string format để tạo một chuỗi được chèn giá trị của các biến. Ví dụ:

```
name = 'Ninh'
age = 25
'Helo, I am {} and I am {} year old.'.format(name,age)
```
Kết quả: 'Helo, I am Ninh and I am 25 year old.'

Nếu lo ngại không truyền đúng thứ tự thì có thể dùng như sau: 


```
name = 'Ninh'
age = 25
'Helo, I am {one} and I am {two} year old.'.format(one = name, two = age)
```

# Kí tự trong 1 chuỗi: 

Một chuỗi trong Python có thể xem là một mảng. Ví dụ: 
```
s = 'hello'
s[0]
```
Kết quả: 'h'

Ngoài ra, ta dùng kí tự : để lấy phần tử từ bao nhiêu đến bao nhiêu. Ví dụ: 

Lấy từ phần tử thứ 1 đến hết:

```
s = 'abcdefghijk'
s[1:]
```
Kết quả thu được: 'bcdefghijk'

Lấy từ vị trí bắt đầu cho đến vị trí thứ 3 (không bao gồm vị trí thứ 3): 

```
s = 'abcdefghijk'
s[:3]

```
Lết quả thu được: 'abc'



Lấy kết quả từ thứ tự 3 đến 6, không bao gồm kí tự thứ 6:

```
s = 'abcdefghijk'
s[3:6]

```
Lết quả thu được: 'def'

# Mảng: 

Tạo mảng tương tự như trong Javascript, dùng dấu []. Ví dụ:

```
myList = [1, 2, 3]
```

Chèn thêm phần tự vào phía sau bằng các dùng phàm append. Ví dụ:

```
myList = [1, 2, 3]
myList.append(4)
print(myList)
```
Kết quả thu được: [0, 1, 2, 3, 4]

Chúng ta cũng mảng nhiều chiều: 

```
myList = [ 1, 2, 3, ['a' , 'b']] 
print(myList[3][1])
```
Kết quả: 'b'







