# code_utils
my code utils



## 注意

编译  `code_utils` 的时候，可能会报错：

```bash
code_utils-master/src/sumpixel_test.cpp:2:10: fatal error: backward.hpp: No such file or directory
 #include "backward.hpp"
```

解决方法：

在`code_utils`下面找到  src/sumpixel_test.cpp，修改 `#include "backward.hpp" `为  ` #include "code_utils/backward.hpp"  `，再编译。