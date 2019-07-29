# What is the output of the below function?
```cpp
void f() {
    int endl = 13;
    using namespace std;
    cout << "hello" << endl << "world";
}
```

# What is the value of s?
```cpp
int getval() { return 5;}
namespace std {
    int counter = getval();
};
std::counter = 3;
auto s = 3 + 4 + std::counter;
```

# What is the output of below?
```cpp
namespace std {
    int endl = 5;
};
std::cout << "a" << std::endl << "b";
```

# What is output of below?
```cpp
int n = 2147483647;
n++;
if (n == 2147483647) cout << "match";
else cout << "nomatch"
```

# What is output?
```cpp
int m = 5;
if (m < 10) cout << "aaa";
else if (m == 5) cout << "bbb";
```

# What is output?
```cpp
char ch;
switch (ch) {
    case 'a':
    cout << "hello";
    break

    default:
    break;
}
```

# Will this compile?
```cpp
char xy[2][3] = {
    {'a','b','c'},
    {'d','e','f'},
};
```
# What is prob with below snippet?
```cpp
int r = rand() % 10 + 1;
cout << r;
```

# Will below compile?
```cpp
void f() {
    int n = stoi("13");
}
```
