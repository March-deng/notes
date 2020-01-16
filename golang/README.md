# golang
- 如果一个调用的处理始终是在一个goroutine中处理，那么函数的参数和返回值就应该使用值而不是指针
  * As a conclusion, when we create a function, our default behavior should be to use values instead of pointers. A pointer should only be used if we want to share a variable.
