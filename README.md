# 设计思路
* 指定了用面向对象的方式构建且指定了三个类
1. Crypto类
  a. 加密   就是改变字符的ASCII码
  b. 解密   同理
2. FileHandler类
  a. 读取文本   用ifstream
  b. 保存文本   用ofstream
3. Menu类
  a. 菜单显示   cout
  b. 整合前面两个函数实现功能
4. 主函数


# 运行编译（cmake）
* 采用 **源码外构建** ，把可执行文件都放在build里面
* 其余的就是cmake的基础写法（设置cmake版本，定义项目名称，生成可执行文件）
* make  编译文件
* ./kaisa 运行文件