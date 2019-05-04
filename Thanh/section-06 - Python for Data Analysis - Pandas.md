# Section 5 - Python for Data Analysis - DataFrame
## Part 1 Tao DataFrame 
- ```import pandas as pd```
- ```pd.Series(data=my_data, index = labels)```: my_data and labels is array. => return series, co the cong 2 series voi nhau, truy xuat giong nhu array trong js
- import randn: ```from numpy.random import randn```
- the same random number: ```np.random.seed(101)```
- create data frame: ```pd.DataFrame(randn(5,4), ['a','b','c','d','e'], ['w','x','y','z'])``` 5 dong, 4 cot nhu sau

    -	          w	     x	           y	           z
    -     a	-1.467514	-0.494095	-0.162535	0.485809
    -     b	0.392489	0.221491	-0.855196	1.541990
    -     c	0.666319	-0.538235	-0.568581	1.407338
    -     d	0.641806	-0.905100	-0.391157	1.028293
    -     e	-1.972605	-0.866885	0.720788	-1.223082

- Truy xuat cot: ```df['w']``` or ```df.w``` or ```df[['w','z']]```: tra ve cot kieu series.
- Them cot moi: ```df['new'] = df['w'] + df['y']```
- Xoa cot: ```df1 = df.drop('new', axis=1, inplace=True)```, asix = 0 la dong, = 1 la cot. inplace=True la thay doi df, = False la khong thay doi bien df.
- Xem tuple cua DataFrame: ```df.shape```
- Lay dong a: ```df.loc['a']```
- Lay dong by index: ```df.iloc[2]```
- Lay dong b cot y: ```df.loc['b','y']```. Lay nhieu dong, nhieu cot: ```df.loc[['a','b'] ,['w','y']]```.
## Part 2
- Tra ve ma tran (new co 'w' thi tra ve cot w True/False) True/False: ```df[df['w'] > 0]```
- Phan tu nao false thi tra ve NaN: ```df[df>0]```
- ```df[df['w'] > 0]```: Tra ve nhung dong nao co gia tri cot 'w' > 0
- ```df[df['w'] > 0][['x', 'y']]```: Tra ve (2 cot x, y) nhung dong nao co gia tri cot 'w' > 0
- ```df[(df['w']>0) & (df['x'] < 0)]```: dieu kien 'and'. Neu dung ```and``` thi chi so sanh dc 1 phan tu, ko so sanh dc series, vd: True and False => False
- ```df.reset_index()```: thay cot dau tien thanh so thu tu, chen them cot ke tiep cot dau voi title 'index' mang gia tri 'a b c d e'.
- ```df.set_index('w')```: chuyen cot w thanh cot index dau tien thay the cho 'a b c d e'.