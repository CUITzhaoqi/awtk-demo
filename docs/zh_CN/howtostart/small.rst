小
===

AWTK的小并非真的小，而是它可以很小。这主要得益于：

1. 灵活的架构
  
  通常鱼和熊掌不兼得，功能强大和代码体积相互矛盾，AWTK要在嵌入式的低端，中端和高端平台上运行，要在Android/iOS上运行，要在PC甚至Web上运行，光靠小是不行的，灵活的架构才能 让它可小可大。
2. 高效的数据格式
  
  AWTK的主题数据和界面描述数据，在开 发时使用XML格式，运行时则编译成二进制的常量，故无需解析和内存分配。图片和字体也可以预先解码并编译成常量，运行时直接从FLASH读取，无需解码和内存分配。所以AWTK在内存很小的平台仍然可以正常运行
3. 保守的设计
  
  由俭到奢易，由奢到俭难。在设计控件时尽量保守，降低对底层硬件的要求。

AWTK可以在低端嵌入式平台上运行。 这些平台典型的配置是32K RAM，512K Flash 和低于100M主频的CPU。

