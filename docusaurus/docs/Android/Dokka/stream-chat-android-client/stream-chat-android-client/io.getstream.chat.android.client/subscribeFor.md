---
title: subscribe-for
---
//[stream-chat-android-client](../../index.md)/[io.getstream.chat.android.client](index.md)/[subscribeFor](subscribeFor.md)



# subscribeFor  
[androidJvm]  
Content  
inline fun &lt;[T](subscribeFor.md) : [ChatEvent](../io.getstream.chat.android.client.events/ChatEvent/index.md)&gt; [ChatClient](ChatClient/index.md).[subscribeFor](subscribeFor.md)(listener: [ChatEventListener](ChatEventListener/index.md)&lt;[T](subscribeFor.md)&gt;): [Disposable](../io.getstream.chat.android.client.utils.observable/Disposable/index.md)  
More info  


Subscribes to client events of type [T](subscribeFor.md).

  


[androidJvm]  
Content  
inline fun &lt;[T](subscribeFor.md) : [ChatEvent](../io.getstream.chat.android.client.events/ChatEvent/index.md)&gt; [ChatClient](ChatClient/index.md).[subscribeFor](subscribeFor.md)(lifecycleOwner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html), listener: [ChatEventListener](ChatEventListener/index.md)&lt;[T](subscribeFor.md)&gt;): [Disposable](../io.getstream.chat.android.client.utils.observable/Disposable/index.md)  
More info  


Subscribes to client events of type [T](subscribeFor.md), in the lifecycle of [lifecycleOwner](subscribeFor.md).



Only receives events when the lifecycle is in a STARTED state, otherwise events are dropped.

  


[androidJvm]  
Content  
fun [ChatClient](ChatClient/index.md).[subscribeFor](subscribeFor.md)(vararg eventTypes: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)&lt;out [ChatEvent](../io.getstream.chat.android.client.events/ChatEvent/index.md)&gt;, listener: [ChatEventListener](ChatEventListener/index.md)&lt;[ChatEvent](../io.getstream.chat.android.client.events/ChatEvent/index.md)&gt;): [Disposable](../io.getstream.chat.android.client.utils.observable/Disposable/index.md)  
More info  


Subscribes to the specific [eventTypes](subscribeFor.md) of the client.

  


[androidJvm]  
Content  
fun [ChatClient](ChatClient/index.md).[subscribeFor](subscribeFor.md)(lifecycleOwner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html), vararg eventTypes: [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)&lt;out [ChatEvent](../io.getstream.chat.android.client.events/ChatEvent/index.md)&gt;, listener: [ChatEventListener](ChatEventListener/index.md)&lt;[ChatEvent](../io.getstream.chat.android.client.events/ChatEvent/index.md)&gt;): [Disposable](../io.getstream.chat.android.client.utils.observable/Disposable/index.md)  
More info  


Subscribes to the specific [eventTypes](subscribeFor.md) of the client, in the lifecycle of [lifecycleOwner](subscribeFor.md).



Only receives events when the lifecycle is in a STARTED state, otherwise events are dropped.

  


