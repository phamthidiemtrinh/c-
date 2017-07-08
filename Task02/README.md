##  1. Comment 

- Các comment chú thích để diễn giải làm cho dòng code dễ hiểu hơn.
- có 2 cách comment:
  + diễn giải trên một dòng : sử dụng dấu \\
  + diễn giải trên nhiều dòng (đoạn) : /* abcxyz */
- khi biên dịch chương trình tự động bỏ qua phần comment này.

## 2. Data type

````````````````

|  Kiểu dữ liệu       |      	Từ khóa      |
|_____________________|______________________|
|    Boolean	      |       bool           |
|_____________________|______________________|
|    Ký tự            |     	char         |
|_____________________|_____________________ |
|    Số nguyên	      |        int           |
|_____________________|____________________  |
|    Số thực	      |       float          |
|_____________________|____________________  |
| Số thực dạng Double |       double         |
|_____________________|____________________  |
|Kiểu không có giá trị|      	void         |
|_____________________|____________________  |
| Kiểu Wide character |       wchar_t        |

````````````````````````

- một số dạng nâng cấp hơn : signed, unsigned, short,long
- giới hạn của các kiều dữ liệu: 
![](https://nguyenvanquan7826.com/wp-content/uploads/2014/12/kieu.png)
-kích cỡ của các biến thuộc các kiều dữ liệu trên bị phụ thuộc vào trình biên dịch và máy tính.
- Khai báo một kiểu mới trong C++ : 'Typedef kieu ten;'
- khai báo kiểu liệt kê: `enum tên{list tên} list_biến;`


