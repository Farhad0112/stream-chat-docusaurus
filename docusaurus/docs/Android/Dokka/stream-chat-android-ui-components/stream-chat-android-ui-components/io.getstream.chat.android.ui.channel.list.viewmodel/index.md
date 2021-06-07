---
title: index
sidebar_position: 1
---
//[stream-chat-android-ui-components](../../index.md)/[io.getstream.chat.android.ui.channel.list.viewmodel](index.md)



# Package io.getstream.chat.android.ui.channel.list.viewmodel  


## Types  
  
|  Name |  Summary | 
|---|---|
| <a name="io.getstream.chat.android.ui.channel.list.viewmodel/ChannelListViewModel///PointingToDeclaration/"></a>[ChannelListViewModel](ChannelListViewModel/index.md)| <a name="io.getstream.chat.android.ui.channel.list.viewmodel/ChannelListViewModel///PointingToDeclaration/"></a>[androidJvm]  <br/>Content  <br/>class [ChannelListViewModel](ChannelListViewModel/index.md)(**chatDomain**: ChatDomain, **filter**: FilterObject, **sort**: QuerySort&lt;Channel&gt;, **limit**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **messageLimit**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [ViewModel](https://developer.android.com/reference/kotlin/androidx/lifecycle/ViewModel.html)  <br/>More info  <br/>ViewModel class for [io.getstream.chat.android.ui.channel.list.ChannelListView](../io.getstream.chat.android.ui.channel.list/ChannelListView/index.md).  <br/><br/><br/>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="io.getstream.chat.android.ui.channel.list.viewmodel//bindView/io.getstream.chat.android.ui.channel.list.viewmodel.ChannelListViewModel#io.getstream.chat.android.ui.channel.list.ChannelListView#androidx.lifecycle.LifecycleOwner/PointingToDeclaration/"></a>[bindView](bindView.md)| <a name="io.getstream.chat.android.ui.channel.list.viewmodel//bindView/io.getstream.chat.android.ui.channel.list.viewmodel.ChannelListViewModel#io.getstream.chat.android.ui.channel.list.ChannelListView#androidx.lifecycle.LifecycleOwner/PointingToDeclaration/"></a>[androidJvm]  <br/>Content  <br/>@[JvmName](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-name/index.html)(name = bind)  <br/>  <br/>fun [ChannelListViewModel](ChannelListViewModel/index.md).[bindView](bindView.md)(view: [ChannelListView](../io.getstream.chat.android.ui.channel.list/ChannelListView/index.md), lifecycleOwner: [LifecycleOwner](https://developer.android.com/reference/kotlin/androidx/lifecycle/LifecycleOwner.html))  <br/>More info  <br/>Binds [ChannelListView](../io.getstream.chat.android.ui.channel.list/ChannelListView/index.md) with [ChannelListViewModel](ChannelListViewModel/index.md), updating the view's state based on data provided by the ViewModel, and propagating view events to the ViewModel as needed.  <br/><br/><br/>|
