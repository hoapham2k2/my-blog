# So sánh về Compiler và Interpreter

## 1. Compiler

Compiler là một chương trình dịch ngược từ ngôn ngữ lập trình cao cấp (high-level language) sang ngôn ngữ máy (machine language) mà máy tính có thể hiểu được. Compiler thường được sử dụng để biên dịch các ngôn ngữ lập trình như C, C++, C#, Java, Python, PHP, Ruby, Perl, Pascal, v.v.

Compiler có thể được chia thành 4 phần chính:

- **Preprocessor**: Thực hiện các thao tác như xử lý các câu lệnh `#include`, `#define`, `#ifdef`, `#ifndef`, `#endif`, v.v. và thay thế các macro bằng các giá trị tương ứng.

- **Compiler**: Biên dịch mã nguồn thành mã trung gian (intermediate code) hoặc mã máy (machine code).

- **Assembler**: Chuyển mã trung gian thành mã máy.

- **Linker**: Liên kết các file object và các thư viện thành file thực thi (executable file).

## 2. Interpreter

Interpreter là một chương trình dịch ngược từ ngôn ngữ lập trình cao cấp (high-level language) sang ngôn ngữ máy (machine language) mà máy tính có thể hiểu được. Interpreter thường được sử dụng để biên dịch các ngôn ngữ lập trình như Python, PHP, Ruby, Perl, v.v.

Interpreter có thể được chia thành 2 phần chính:

- **Interpreter**: Biên dịch mã nguồn thành mã trung gian (intermediate code) hoặc mã máy (machine code).

- **Virtual Machine**: Thực thi mã trung gian.

## 3. So sánh

| Compiler | Interpreter |
| --- | --- |
| Biên dịch toàn bộ chương trình trước khi thực thi | Biên dịch từng dòng lệnh một |
| Tốc độ thực thi nhanh hơn | Tốc độ thực thi chậm hơn |
| Dễ dàng phát hiện lỗi | Khó phát hiện lỗi |
| Cần thời gian để biên dịch | Không cần thời gian để biên dịch |
| Cần ít bộ nhớ hơn | Cần nhiều bộ nhớ hơn |
| Cần ít tài nguyên hơn | Cần nhiều tài nguyên hơn |
| Cần ít thời gian để thực thi | Cần nhiều thời gian để thực thi |

