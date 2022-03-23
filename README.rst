Greatwall编程风格指南(V0.1)
================================
.. note:: 

    **声明**

    本指南借鉴于 Google 官方项目，用于统一长城内部编程风格。

    如果你关注的是 Google 官方英文版，请移步 `Google Style Guide <https://github.com/google/styleguide>`_ 。

    请访问<https://greatwall-styleguide.readthedocs.io/zh_CN/latest/google-cpp-styleguide/contents.html> 获取最新的更新。

每个较大的开源项目都有自己的风格指南：关于如何为该项目编写代码的一系列约定（有时候会比较武断）。当所有代码均保持一致的风格，在理解大型代码库时更为轻松。

“风格”的含义涵盖范围广，从“变量使用驼峰格式（camelCase）”到“决不使用全局变量”再到“决不使用异常”，等等诸如此类。

本项目目前为试行版本，目前仅对“7.命名约定”做强制要求，其余项目前仅做建议。