---
title: index
sidebar_position: 1
---
//[stream-chat-android-client](../../../index.md)/[io.getstream.chat.android.client.models](../index.md)/[Message](index.md)



# Message  
 [androidJvm] data class [Message](index.md)(**id**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **cid**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **text**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **html**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **parentId**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **command**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **attachments**: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Attachment](../Attachment/index.md)&gt;, **mentionedUsersIds**: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, **mentionedUsers**: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[User](../User/index.md)&gt;, **replyCount**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **reactionCounts**: [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;, **reactionScores**: [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;, **syncStatus**: [SyncStatus](../../io.getstream.chat.android.client.utils/SyncStatus/index.md), **attachmentsSyncStatus**: [SyncStatus](../../io.getstream.chat.android.client.utils/SyncStatus/index.md), **type**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **latestReactions**: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Reaction](../Reaction/index.md)&gt;, **ownReactions**: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Reaction](../Reaction/index.md)&gt;, **createdAt**: [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)?, **updatedAt**: [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)?, **deletedAt**: [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)?, **updatedLocallyAt**: [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)?, **createdLocallyAt**: [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)?, **user**: [User](../User/index.md), **extraData**: [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt;, **silent**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **shadowed**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **i18n**: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, **showInChannel**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **channelInfo**: [ChannelInfo](../ChannelInfo/index.md)?, **replyTo**: [Message](index.md)?, **replyMessageId**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **pinned**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **pinnedAt**: [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)?, **pinExpires**: [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)?, **pinnedBy**: [User](../User/index.md)?, **threadParticipants**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[User](../User/index.md)&gt;) : [CustomObject](../CustomObject/index.md)   


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="io.getstream.chat.android.client.models/Message/attachments/#/PointingToDeclaration/"></a>[attachments](attachments.md)| <a name="io.getstream.chat.android.client.models/Message/attachments/#/PointingToDeclaration/"></a> [androidJvm] var [attachments](attachments.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Attachment](../Attachment/index.md)&gt;   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/attachmentsSyncStatus/#/PointingToDeclaration/"></a>[attachmentsSyncStatus](attachmentsSyncStatus.md)| <a name="io.getstream.chat.android.client.models/Message/attachmentsSyncStatus/#/PointingToDeclaration/"></a> [androidJvm] var [attachmentsSyncStatus](attachmentsSyncStatus.md): [SyncStatus](../../io.getstream.chat.android.client.utils/SyncStatus/index.md)if all the message's attachments has been uploaded to the servers   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/channelInfo/#/PointingToDeclaration/"></a>[channelInfo](channelInfo.md)| <a name="io.getstream.chat.android.client.models/Message/channelInfo/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = channel)  <br/>  <br/>var [channelInfo](channelInfo.md): [ChannelInfo](../ChannelInfo/index.md)? = null   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/cid/#/PointingToDeclaration/"></a>[cid](cid.md)| <a name="io.getstream.chat.android.client.models/Message/cid/#/PointingToDeclaration/"></a> [androidJvm] var [cid](cid.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/command/#/PointingToDeclaration/"></a>[command](command.md)| <a name="io.getstream.chat.android.client.models/Message/command/#/PointingToDeclaration/"></a> [androidJvm] var [command](command.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/createdAt/#/PointingToDeclaration/"></a>[createdAt](createdAt.md)| <a name="io.getstream.chat.android.client.models/Message/createdAt/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = created_at)  <br/>  <br/>var [createdAt](createdAt.md): [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)? = null   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/createdLocallyAt/#/PointingToDeclaration/"></a>[createdLocallyAt](createdLocallyAt.md)| <a name="io.getstream.chat.android.client.models/Message/createdLocallyAt/#/PointingToDeclaration/"></a> [androidJvm] var [createdLocallyAt](createdLocallyAt.md): [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)? = null   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/deletedAt/#/PointingToDeclaration/"></a>[deletedAt](deletedAt.md)| <a name="io.getstream.chat.android.client.models/Message/deletedAt/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = deleted_at)  <br/>  <br/>var [deletedAt](deletedAt.md): [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)? = null   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/extraData/#/PointingToDeclaration/"></a>[extraData](extraData.md)| <a name="io.getstream.chat.android.client.models/Message/extraData/#/PointingToDeclaration/"></a> [androidJvm] open override var [extraData](extraData.md): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt;   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/html/#/PointingToDeclaration/"></a>[html](html.md)| <a name="io.getstream.chat.android.client.models/Message/html/#/PointingToDeclaration/"></a> [androidJvm] val [html](html.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/i18n/#/PointingToDeclaration/"></a>[i18n](i18n.md)| <a name="io.getstream.chat.android.client.models/Message/i18n/#/PointingToDeclaration/"></a> [androidJvm] val [i18n](i18n.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/id/#/PointingToDeclaration/"></a>[id](id.md)| <a name="io.getstream.chat.android.client.models/Message/id/#/PointingToDeclaration/"></a> [androidJvm] var [id](id.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/latestReactions/#/PointingToDeclaration/"></a>[latestReactions](latestReactions.md)| <a name="io.getstream.chat.android.client.models/Message/latestReactions/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = latest_reactions)  <br/>  <br/>var [latestReactions](latestReactions.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Reaction](../Reaction/index.md)&gt;   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/mentionedUsers/#/PointingToDeclaration/"></a>[mentionedUsers](mentionedUsers.md)| <a name="io.getstream.chat.android.client.models/Message/mentionedUsers/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = mentioned_users)  <br/>  <br/>var [mentionedUsers](mentionedUsers.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[User](../User/index.md)&gt;   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/mentionedUsersIds/#/PointingToDeclaration/"></a>[mentionedUsersIds](mentionedUsersIds.md)| <a name="io.getstream.chat.android.client.models/Message/mentionedUsersIds/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = mentioned_users)  <br/>  <br/>var [mentionedUsersIds](mentionedUsersIds.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/ownReactions/#/PointingToDeclaration/"></a>[ownReactions](ownReactions.md)| <a name="io.getstream.chat.android.client.models/Message/ownReactions/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = own_reactions)  <br/>  <br/>var [ownReactions](ownReactions.md): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Reaction](../Reaction/index.md)&gt;   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/parentId/#/PointingToDeclaration/"></a>[parentId](parentId.md)| <a name="io.getstream.chat.android.client.models/Message/parentId/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = parent_id)  <br/>  <br/>var [parentId](parentId.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/pinExpires/#/PointingToDeclaration/"></a>[pinExpires](pinExpires.md)| <a name="io.getstream.chat.android.client.models/Message/pinExpires/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = pin_expires)  <br/>  <br/>var [pinExpires](pinExpires.md): [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)? = null   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/pinned/#/PointingToDeclaration/"></a>[pinned](pinned.md)| <a name="io.getstream.chat.android.client.models/Message/pinned/#/PointingToDeclaration/"></a> [androidJvm] var [pinned](pinned.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/pinnedAt/#/PointingToDeclaration/"></a>[pinnedAt](pinnedAt.md)| <a name="io.getstream.chat.android.client.models/Message/pinnedAt/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = pinned_at)  <br/>  <br/>var [pinnedAt](pinnedAt.md): [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)? = null   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/pinnedBy/#/PointingToDeclaration/"></a>[pinnedBy](pinnedBy.md)| <a name="io.getstream.chat.android.client.models/Message/pinnedBy/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = pinned_by)  <br/>  <br/>var [pinnedBy](pinnedBy.md): [User](../User/index.md)? = null   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/reactionCounts/#/PointingToDeclaration/"></a>[reactionCounts](reactionCounts.md)| <a name="io.getstream.chat.android.client.models/Message/reactionCounts/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = reaction_counts)  <br/>  <br/>var [reactionCounts](reactionCounts.md): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/reactionScores/#/PointingToDeclaration/"></a>[reactionScores](reactionScores.md)| <a name="io.getstream.chat.android.client.models/Message/reactionScores/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = reaction_scores)  <br/>  <br/>var [reactionScores](reactionScores.md): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/replyCount/#/PointingToDeclaration/"></a>[replyCount](replyCount.md)| <a name="io.getstream.chat.android.client.models/Message/replyCount/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = reply_count)  <br/>  <br/>var [replyCount](replyCount.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/replyMessageId/#/PointingToDeclaration/"></a>[replyMessageId](replyMessageId.md)| <a name="io.getstream.chat.android.client.models/Message/replyMessageId/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = quoted_message_id)  <br/>  <br/>var [replyMessageId](replyMessageId.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/replyTo/#/PointingToDeclaration/"></a>[replyTo](replyTo.md)| <a name="io.getstream.chat.android.client.models/Message/replyTo/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = quoted_message)  <br/>  <br/>var [replyTo](replyTo.md): [Message](index.md)? = null   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/shadowed/#/PointingToDeclaration/"></a>[shadowed](shadowed.md)| <a name="io.getstream.chat.android.client.models/Message/shadowed/#/PointingToDeclaration/"></a> [androidJvm] var [shadowed](shadowed.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/showInChannel/#/PointingToDeclaration/"></a>[showInChannel](showInChannel.md)| <a name="io.getstream.chat.android.client.models/Message/showInChannel/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = show_in_channel)  <br/>  <br/>var [showInChannel](showInChannel.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/silent/#/PointingToDeclaration/"></a>[silent](silent.md)| <a name="io.getstream.chat.android.client.models/Message/silent/#/PointingToDeclaration/"></a> [androidJvm] var [silent](silent.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/syncStatus/#/PointingToDeclaration/"></a>[syncStatus](syncStatus.md)| <a name="io.getstream.chat.android.client.models/Message/syncStatus/#/PointingToDeclaration/"></a> [androidJvm] var [syncStatus](syncStatus.md): [SyncStatus](../../io.getstream.chat.android.client.utils/SyncStatus/index.md)if the message has been synced to the servers   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/text/#/PointingToDeclaration/"></a>[text](text.md)| <a name="io.getstream.chat.android.client.models/Message/text/#/PointingToDeclaration/"></a> [androidJvm] var [text](text.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/threadParticipants/#/PointingToDeclaration/"></a>[threadParticipants](threadParticipants.md)| <a name="io.getstream.chat.android.client.models/Message/threadParticipants/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = thread_participants)  <br/>  <br/>var [threadParticipants](threadParticipants.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[User](../User/index.md)&gt;   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/type/#/PointingToDeclaration/"></a>[type](type.md)| <a name="io.getstream.chat.android.client.models/Message/type/#/PointingToDeclaration/"></a> [androidJvm] var [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/updatedAt/#/PointingToDeclaration/"></a>[updatedAt](updatedAt.md)| <a name="io.getstream.chat.android.client.models/Message/updatedAt/#/PointingToDeclaration/"></a> [androidJvm] @SerializedName(value = updated_at)  <br/>  <br/>var [updatedAt](updatedAt.md): [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)? = null   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/updatedLocallyAt/#/PointingToDeclaration/"></a>[updatedLocallyAt](updatedLocallyAt.md)| <a name="io.getstream.chat.android.client.models/Message/updatedLocallyAt/#/PointingToDeclaration/"></a> [androidJvm] var [updatedLocallyAt](updatedLocallyAt.md): [Date](https://developer.android.com/reference/kotlin/java/util/Date.html)? = null   <br/>|
| <a name="io.getstream.chat.android.client.models/Message/user/#/PointingToDeclaration/"></a>[user](user.md)| <a name="io.getstream.chat.android.client.models/Message/user/#/PointingToDeclaration/"></a> [androidJvm] var [user](user.md): [User](../User/index.md)   <br/>|


## Inherited functions  
  
|  Name |  Summary | 
|---|---|
| <a name="io.getstream.chat.android.client.models/CustomObject/getExtraValue/#kotlin.String#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/"></a>[getExtraValue](../CustomObject/getExtraValue.md)| <a name="io.getstream.chat.android.client.models/CustomObject/getExtraValue/#kotlin.String#TypeParam(bounds=[kotlin.Any?])/PointingToDeclaration/"></a>[androidJvm]  <br/>Content  <br/>open fun &lt;[T](../CustomObject/getExtraValue.md)&gt; [getExtraValue](../CustomObject/getExtraValue.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), default: [T](../CustomObject/getExtraValue.md)): [T](../CustomObject/getExtraValue.md)  <br/><br/><br/>|
| <a name="io.getstream.chat.android.client.models/CustomObject/putExtraValue/#kotlin.String#kotlin.Any/PointingToDeclaration/"></a>[putExtraValue](../CustomObject/putExtraValue.md)| <a name="io.getstream.chat.android.client.models/CustomObject/putExtraValue/#kotlin.String#kotlin.Any/PointingToDeclaration/"></a>[androidJvm]  <br/>Content  <br/>open fun [putExtraValue](../CustomObject/putExtraValue.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html))  <br/><br/><br/>|


## Extensions  
  
|  Name |  Summary | 
|---|---|
| <a name="io.getstream.chat.android.client.extensions//enrichWithCid/io.getstream.chat.android.client.models.Message#kotlin.String/PointingToDeclaration/"></a>[enrichWithCid](../../io.getstream.chat.android.client.extensions/enrichWithCid.md)| <a name="io.getstream.chat.android.client.extensions//enrichWithCid/io.getstream.chat.android.client.models.Message#kotlin.String/PointingToDeclaration/"></a>[androidJvm]  <br/>Content  <br/>fun [Message](index.md).[enrichWithCid](../../io.getstream.chat.android.client.extensions/enrichWithCid.md)(cid: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Message](index.md)  <br/><br/><br/>|
| <a name="io.getstream.chat.android.client.models//getTranslation/io.getstream.chat.android.client.models.Message#kotlin.String/PointingToDeclaration/"></a>[getTranslation](../getTranslation.md)| <a name="io.getstream.chat.android.client.models//getTranslation/io.getstream.chat.android.client.models.Message#kotlin.String/PointingToDeclaration/"></a>[androidJvm]  <br/>Content  <br/>fun [Message](index.md).[getTranslation](../getTranslation.md)(language: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br/><br/><br/>|
| <a name="io.getstream.chat.android.client.models//originalLanguage/io.getstream.chat.android.client.models.Message#/PointingToDeclaration/"></a>[originalLanguage](../originalLanguage.md)| <a name="io.getstream.chat.android.client.models//originalLanguage/io.getstream.chat.android.client.models.Message#/PointingToDeclaration/"></a>[androidJvm]  <br/>Content  <br/>val [Message](index.md).[originalLanguage](../originalLanguage.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br/><br/><br/>|
