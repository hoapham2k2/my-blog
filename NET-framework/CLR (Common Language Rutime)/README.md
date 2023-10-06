# Common Language Runtime (CLR) 

## 1. Giới thiệu về Common Language Runtime (CLR)

Common Language Runtime (CLR) là một thành phần của .NET Framework. CLR cung cấp một môi trường thực thi (runtime environment) để chạy các ứng dụng và các thư viện được viết bằng các ngôn ngữ lập trình khác nhau như C#, VB.NET, F#, C++, Python, v.v.

## 2. Các thành phần của Common Language Runtime (CLR)

<img src="https://media.geeksforgeeks.org/wp-content/uploads/Working_CLR.jpg" alt="image clr" style="width: 100%; display: block; margin: auto">

CLR bao gồm các thành phần sau:

- **Common Language Specification (CLS)**: Nó chịu trách nhiệm đảm bảo rằng các ứng dụng và thư viện được viết bằng các ngôn ngữ lập trình khác nhau có thể tương tác với nhau.

- **Common Type System (CTS)**: Mọi ngôn ngữ lập trình đều có hệ thống data type. CTS sẽ chịu trách nhiệm cho việc chuyển đổi các kiểu dữ liệu này thành các kiểu dữ liệu chung (common data type) để các ứng dụng và thư viện có thể tương tác với nhau.
    - Có 2 loại kiểu dữ liệu trong CTS:
        - **Value type**: Kiểu dữ liệu này được lưu trữ trực tiếp trong bộ nhớ stack.
        - **Reference type**: Kiểu dữ liệu này được lưu trữ trong bộ nhớ heap và được trỏ đến bởi một con trỏ (pointer) trong bộ nhớ stack.

- **Garbage Collector (GC)**: Nó chịu trách nhiệm cho việc quản lý bộ nhớ (memory management) trong .NET Framework. GC sẽ tự động thu hồi bộ nhớ không sử dụng (unused memory) để giải phóng bộ nhớ cho các ứng dụng khác.

- **Just-In-Time Compiler (JIT)**: Nó chịu trách nhiệm cho việc biên dịch mã trung gian (intermediate code) thành mã máy (machine code) để máy tính có thể hiểu được.