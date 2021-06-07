---
title: handle-user-lookup
---
//[stream-chat-android-ui-components](../../../../index.md)/[io.getstream.chat.android.ui.message.input](../../index.md)/[MessageInputView](../index.md)/[DefaultUserLookupHandler](index.md)/[handleUserLookup](handleUserLookup.md)



# handleUserLookup  
[androidJvm]  
Content  
open suspend override fun [handleUserLookup](handleUserLookup.md)(query: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;User&gt;  
More info  


Performs users lookup by given [query](handleUserLookup.md) in suspend way. It's executed on background, so it can perform heavy operations.



#### Return  


List of users as result of lookup.



## Parameters  
  
androidJvm  
  
| | |
|---|---|
| <a name="io.getstream.chat.android.ui.message.input/MessageInputView.DefaultUserLookupHandler/handleUserLookup/#kotlin.String/PointingToDeclaration/"></a>query| <a name="io.getstream.chat.android.ui.message.input/MessageInputView.DefaultUserLookupHandler/handleUserLookup/#kotlin.String/PointingToDeclaration/"></a><br/><br/>String as user input for lookup algorithm.<br/><br/>|
  
  


