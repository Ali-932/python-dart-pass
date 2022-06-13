# python-dart-pass
void main() {
  const hour = DateTime.now().hour;
  print(hour);

//const keyword value must be known at compile time, like 12 or 10, to solve the problem with the code
//i used another key work that dosen't need to know the value at compile time, which is final.
  final hour2 = DateTime.now().hour;
  print(hour2);


}
