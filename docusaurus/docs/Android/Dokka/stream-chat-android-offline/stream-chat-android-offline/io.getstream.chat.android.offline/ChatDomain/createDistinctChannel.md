---
title: create-distinct-channel
---
//[stream-chat-android-offline](../../../index.md)/[io.getstream.chat.android.offline](../index.md)/[ChatDomain](index.md)/[createDistinctChannel](createDistinctChannel.md)



# createDistinctChannel  
[androidJvm]  
Content  
abstract fun [createDistinctChannel](createDistinctChannel.md)(channelType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), members: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, extraData: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt;): Call&lt;Channel&gt;  
More info  


Returns a distinct channel based on its' members. If such channel exists returns existing one, otherwise creates a new.



#### Return  


Call instance with Channel.



## Parameters  
  
androidJvm  
  
| | |
|---|---|
| <a name="io.getstream.chat.android.offline/ChatDomain/createDistinctChannel/#kotlin.String#kotlin.collections.List[kotlin.String]#kotlin.collections.Map[kotlin.String,kotlin.Any]/PointingToDeclaration/"></a>channelType| <a name="io.getstream.chat.android.offline/ChatDomain/createDistinctChannel/#kotlin.String#kotlin.collections.List[kotlin.String]#kotlin.collections.Map[kotlin.String,kotlin.Any]/PointingToDeclaration/"></a><br/><br/>String represents channel type.<br/><br/>|
| <a name="io.getstream.chat.android.offline/ChatDomain/createDistinctChannel/#kotlin.String#kotlin.collections.List[kotlin.String]#kotlin.collections.Map[kotlin.String,kotlin.Any]/PointingToDeclaration/"></a>members| <a name="io.getstream.chat.android.offline/ChatDomain/createDistinctChannel/#kotlin.String#kotlin.collections.List[kotlin.String]#kotlin.collections.Map[kotlin.String,kotlin.Any]/PointingToDeclaration/"></a><br/><br/>List of members' id.<br/><br/>|
| <a name="io.getstream.chat.android.offline/ChatDomain/createDistinctChannel/#kotlin.String#kotlin.collections.List[kotlin.String]#kotlin.collections.Map[kotlin.String,kotlin.Any]/PointingToDeclaration/"></a>extraData| <a name="io.getstream.chat.android.offline/ChatDomain/createDistinctChannel/#kotlin.String#kotlin.collections.List[kotlin.String]#kotlin.collections.Map[kotlin.String,kotlin.Any]/PointingToDeclaration/"></a><br/><br/>Map object with custom fields and additional data.<br/><br/>|
  
  


