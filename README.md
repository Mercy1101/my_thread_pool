# my_benchmark_template
## 简介
一个简单的线程池的实现，具体例子见thread_pool_example.cc.
注意目前工程只能使用C++17及更早C++标准编译。

## 编译
> mkdir build
>
> cd build
>
> cmake ..
>
> MSBuild.exe my_thread_pool.sln -p:Configuration=Release  -t:Rebuild

## 运行
> cd build\Release
>
> .\ my_thread_pool.exe