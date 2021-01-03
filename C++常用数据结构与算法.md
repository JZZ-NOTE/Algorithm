## bitset

```c++
#include <bitset>
```

## algorithm

### reverse 翻转

```c++
#include <algorithm>
#include <iostream>
#include <string>
using namespace std;

int main()
{
    string str{"jzz"};
    reverse(str.begin(),str.end());
    cout<<str<<endl;
    return 0;
}
```