sizeof并不是一个函数，当它要查看一个数据类型的大小，比如说int类型，需要加括号

如sizeof(int), 一般返回的值是4 bytes

但是当它要查看一个**变量**值的大小，可以不加括号，如

int dogs = 1234;

cout << sizeof dogs;



单个字符用单引号表示，如 char ch = 'M';

而如果是一个字符串的话，用双引号来表示“”



------

