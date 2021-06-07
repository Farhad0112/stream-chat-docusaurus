---
title: update-channel-partial
---
//[stream-chat-android-client](../../../index.md)/[io.getstream.chat.android.client](../index.md)/[ChatClient](index.md)/[updateChannelPartial](updateChannelPartial.md)



# updateChannelPartial  
[androidJvm]  
Content  
@[CheckResult](https://developer.android.com/reference/kotlin/androidx/annotation/CheckResult.html)()  
  
fun [updateChannelPartial](updateChannelPartial.md)(channelType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), channelId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), set: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt; = emptyMap(), unset: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; = emptyList()): Call&lt;[Channel](../../io.getstream.chat.android.client.models/Channel/index.md)&gt;  
More info  


Updates specific fields of channel data retaining the custom data fields which were set previously.



## Parameters  
  
androidJvm  
  
| | |
|---|---|
| <a name="io.getstream.chat.android.client/ChatClient/updateChannelPartial/#kotlin.String#kotlin.String#kotlin.collections.Map[kotlin.String,kotlin.Any]#kotlin.collections.List[kotlin.String]/PointingToDeclaration/"></a>channelType| <a name="io.getstream.chat.android.client/ChatClient/updateChannelPartial/#kotlin.String#kotlin.String#kotlin.collections.Map[kotlin.String,kotlin.Any]#kotlin.collections.List[kotlin.String]/PointingToDeclaration/"></a><br/><br/>the channel type. ie messaging<br/><br/>|
| <a name="io.getstream.chat.android.client/ChatClient/updateChannelPartial/#kotlin.String#kotlin.String#kotlin.collections.Map[kotlin.String,kotlin.Any]#kotlin.collections.List[kotlin.String]/PointingToDeclaration/"></a>channelId| <a name="io.getstream.chat.android.client/ChatClient/updateChannelPartial/#kotlin.String#kotlin.String#kotlin.collections.Map[kotlin.String,kotlin.Any]#kotlin.collections.List[kotlin.String]/PointingToDeclaration/"></a><br/><br/>the channel id. ie 123<br/><br/>|
| <a name="io.getstream.chat.android.client/ChatClient/updateChannelPartial/#kotlin.String#kotlin.String#kotlin.collections.Map[kotlin.String,kotlin.Any]#kotlin.collections.List[kotlin.String]/PointingToDeclaration/"></a>set| <a name="io.getstream.chat.android.client/ChatClient/updateChannelPartial/#kotlin.String#kotlin.String#kotlin.collections.Map[kotlin.String,kotlin.Any]#kotlin.collections.List[kotlin.String]/PointingToDeclaration/"></a><br/><br/>the key-value data which will be added to the existing channel data object<br/><br/>|
| <a name="io.getstream.chat.android.client/ChatClient/updateChannelPartial/#kotlin.String#kotlin.String#kotlin.collections.Map[kotlin.String,kotlin.Any]#kotlin.collections.List[kotlin.String]/PointingToDeclaration/"></a>unset| <a name="io.getstream.chat.android.client/ChatClient/updateChannelPartial/#kotlin.String#kotlin.String#kotlin.collections.Map[kotlin.String,kotlin.Any]#kotlin.collections.List[kotlin.String]/PointingToDeclaration/"></a><br/><br/>the list of fields which will be removed from the existing channel data object<br/><br/>|
  
  


