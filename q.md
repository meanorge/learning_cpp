На вход дается натуральное число N. Выведите следующее за ним четное число.

<details>
  <summary>Показать решение (C++)</summary>

  ```cpp
  #include <iostream>
  using namespace std;

  int main() {
      int q;
      cin >> q;
      cout << (q + (2 - q % 2));
      return 0;
  }
