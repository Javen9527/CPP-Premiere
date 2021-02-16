### 1.IO三个独立的头文件：
    //记忆的两条规则：1.先io在file或string再stream(简称输入输出东西流); 2.总有一个类型和头文件相同
    <iostream>:
        istream
        ostream
        iostream      //与头文件相同
    <fstream>:
        ifstream
        ofstream
        fstream       //与头文件相同
    <sstream>:
        istringstream
        ostringstream
        stringstream  //与头文件相同
### 2.IO对象不能拷贝和赋值，读写一个IO对象会改变其状态所以不能是const.
### 3.IO条件状态：
    · badbit
    · failbit
    · eofbit
    · goodbit
### 4.判断IO条件状态
    · s.bad()
    · s.fail()
    · s.eof()
    · s.good()
