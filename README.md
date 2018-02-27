# Android知识点整理

> 以下知识点基于已经了解常规使用方法的情况，列出了一些细节点

### Activity

- 常规启动Activity及通信
- 各种情况下的生命周期
- 保存/恢复状态
- 四种启动方式及标志位
- 任务栈

### Fragment

- Fragment的加载
- 各种情况下的生命周期、和Activity生命周期的联系
- Fragment的保存/恢复状态及和Activity的关系
- Fragment的startActivityForResult和onActivityResult，及和Activity中触发onActivityResult的关系

### Service

- 生命周期
- 启动服务和绑定服务
- 绑定本地服务、远程服务
- IntentService

### ContentProvider

- ContentResolver 访问数据
- ContentProvider 提供数据
- UriMatcher、ContentUris、ContentObserver

[Carson_Ho - 关于ContentProvider的知识都在这里了！](https://www.jianshu.com/p/ea8bc4aaf057)

> 介绍了 ContentProvider 和 ContentReslover 的使用和配合SQLite的数据查询

### BroadcastReceiver

### 动画

### View绘制

### View事件分发

### 消息机制

### AsyncTask

### 基本布局

### View控件

- ViewPager
- Toolbar

### 蓝牙

### NDK

### Binder AIDL

### 数据存储

- SharePerference
- SQLite

### Okhttp3

- 基础使用
- 基础架构分析、设计模式分析
- 各个拦截器作用

[被代码淹没的小伙子 - okhttp源码分析](https://www.jianshu.com/p/37e26f4ea57b)

### 多线程

- volatile、synchronized
- wait、sleep、interupt、notify等
- 线程池
- ThreadLocal
- BlockingQueue

[ghsau - Java线程专栏](http://blog.csdn.net/column/details/java-thread.html)
