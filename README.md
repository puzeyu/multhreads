多线程编程
注意:
1.线程间的参数传递使用了malloc. 直接传地址,线程被杀死之后,对应内存也会被释放;
2.cout需先lock来保证只有自己在输出,否则会乱码.(**
