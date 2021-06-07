---
title: bind-view
---
//[stream-chat-android-ui-components](../../index.md)/[io.getstream.chat.android.ui.message.list.header.viewmodel](index.md)/[bindView](bindView.md)



# bindView  
[androidJvm]  
Content  
@[JvmName](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-name/index.html)(name = bind)  
  
fun [MessageListHeaderViewModel](MessageListHeaderViewModel/index.md).[bindView](bindView.md)(view: [MessageListHeaderView](../io.getstream.chat.android.ui.message.list.header/MessageListHeaderView/index.md), lifecycle: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html))  
More info  


Binds [MessageListHeaderView](../io.getstream.chat.android.ui.message.list.header/MessageListHeaderView/index.md) with [MessageListHeaderViewModel](MessageListHeaderViewModel/index.md), updating the view's state based on data provided by the ViewModel.



This function sets listeners on the view and ViewModel. Call this method before setting any additional listeners on these objects yourself.

  


