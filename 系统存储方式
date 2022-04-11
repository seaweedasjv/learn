#判断系统存储方式函数

int check_sys()
{
  int a;
  return *(char*)&a;//大端存储返回1，小端存储返回0.
}

int main()
{
  int a = 0;
  check_sys() ? printf("小端存储模式") : printf("大端存储模式");
  return 0;
}
