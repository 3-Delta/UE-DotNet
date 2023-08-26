# UE-DotNet

1. step1: 使用mono的解释器模式执行il
2. step2: ue借助step1,然后封装一套Unity的GetComponent系列接口，方便上层逻辑整合迁移

参考：
1. https://github.com/loongly/PureScript 一个支持Unity3D的C#热更框架，基于Mono的MONO_AOT_MODE_INTERP模式
2. https://mono-ue.github.io/ 
3. 参考unity4.6.3源码中用mono处理c#的过程
