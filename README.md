# MaiThy_lithuyet_controdong_level08
# Con Trỏ Động
## 1. Khái niệm
### -*Biến động*: là biến tạo ra lúc chạy chương trình, dung lượng tùy nhu cầu
*dùng các biến có săn trong thư viện stdlib.h*:
- Tạo biến động : malloc()
- thu hồi: free() 
VD1:

int *p; /* Khai báo biến con trỏ p*/

p= (int *) malloc(100);/* Tạo biến động*/

### *Cú pháp*
 
 `void *malloc(kiểu _dl size).`
### *Cấp phát bộ nhớ động bằng hàm calloc*


Cú pháp


`(datatype *) calloc(n, sizeof(object));`
### *Cấp phát bộ nhớ động bằng hàm relloc*


Cú pháp


`(datatype *) realloc(buf _p, newsize);`
