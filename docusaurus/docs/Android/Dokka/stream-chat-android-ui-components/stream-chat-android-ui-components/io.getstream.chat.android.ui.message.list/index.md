---
title: index
sidebar_position: 1
---
//[stream-chat-android-ui-components](../../index.md)/[io.getstream.chat.android.ui.message.list](index.md)



# Package io.getstream.chat.android.ui.message.list  


## Types  
  
|  Name |  Summary | 
|---|---|
| <a name="io.getstream.chat.android.ui.message.list/MessageListItemStyle///PointingToDeclaration/"></a>[MessageListItemStyle](MessageListItemStyle/index.md)| <a name="io.getstream.chat.android.ui.message.list/MessageListItemStyle///PointingToDeclaration/"></a>[androidJvm]  <br/>Content  <br/>data class [MessageListItemStyle](MessageListItemStyle/index.md)(@[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**messageBackgroundColorMine**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**messageBackgroundColorTheirs**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**messageTextColorMine**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**messageTextColorTheirs**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**messageLinkTextColorMine**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**messageLinkTextColorTheirs**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**messageLinkBackgroundColorMine**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**messageLinkBackgroundColorTheirs**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **reactionsEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **threadsEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **linkDescriptionMaxLines**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **textStyleMine**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md), **textStyleTheirs**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md), **textStyleUserName**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md), **textStyleMessageDate**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md), **textStyleThreadCounter**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md), **textStyleLinkTitle**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md), **textStyleLinkDescription**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**dateSeparatorBackgroundColor**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **textStyleDateSeparator**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md), **reactionsViewStyle**: [ViewReactionsViewStyle](../io.getstream.chat.android.ui.message.list.reactions.view/ViewReactionsViewStyle/index.md), **editReactionsViewStyle**: [EditReactionsViewStyle](../io.getstream.chat.android.ui.message.list.reactions.edit/EditReactionsViewStyle/index.md), **iconIndicatorSent**: [Drawable](https://developer.android.com/reference/kotlin/android/graphics/drawable/Drawable.html), **iconIndicatorRead**: [Drawable](https://developer.android.com/reference/kotlin/android/graphics/drawable/Drawable.html), **iconIndicatorPendingSync**: [Drawable](https://developer.android.com/reference/kotlin/android/graphics/drawable/Drawable.html), **textStyleMessageDeleted**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**messageDeletedBackground**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**messageStrokeColorMine**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), @[Px](https://developer.android.com/reference/kotlin/androidx/annotation/Px.html)()**messageStrokeWidthMine**: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**messageStrokeColorTheirs**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), @[Px](https://developer.android.com/reference/kotlin/androidx/annotation/Px.html)()**messageStrokeWidthTheirs**: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html), **textStyleSystemMessage**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md), **textStyleErrorMessage**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md))  <br/>More info  <br/>Style for view holders used inside [MessageListView](MessageListView/index.md).  <br/><br/><br/>|
| <a name="io.getstream.chat.android.ui.message.list/MessageListView///PointingToDeclaration/"></a>[MessageListView](MessageListView/index.md)| <a name="io.getstream.chat.android.ui.message.list/MessageListView///PointingToDeclaration/"></a>[androidJvm]  <br/>Content  <br/>class [MessageListView](MessageListView/index.md) : ConstraintLayout  <br/>More info  <br/>MessageListView renders a list of messages and extends the [RecyclerView](https://developer.android.com/reference/kotlin/androidx/recyclerview/widget/RecyclerView.html) The most common customizations are<ul><li>Disabling Reactions</li><li>Disabling Threads</li><li>Customizing the click and longCLick (via the adapter)</li><li>The list_item_message template to use (perhaps, multiple ones...?)</li></ul>  <br/><br/><br/>|
| <a name="io.getstream.chat.android.ui.message.list/MessageListViewStyle///PointingToDeclaration/"></a>[MessageListViewStyle](MessageListViewStyle/index.md)| <a name="io.getstream.chat.android.ui.message.list/MessageListViewStyle///PointingToDeclaration/"></a>[androidJvm]  <br/>Content  <br/>data class [MessageListViewStyle](MessageListViewStyle/index.md)(**scrollButtonViewStyle**: [ScrollButtonViewStyle](ScrollButtonViewStyle/index.md), **itemStyle**: [MessageListItemStyle](MessageListItemStyle/index.md), **reactionsEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**backgroundColor**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**iconsTint**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **replyIcon**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **replyEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **threadReplyIcon**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **threadsEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **retryIcon**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **copyIcon**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **editMessageEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **editIcon**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **flagIcon**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **flagEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **muteIcon**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **unmuteIcon**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **muteEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **blockIcon**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **blockEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **deleteIcon**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **deleteMessageEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **copyTextEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **deleteConfirmationEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **flagMessageConfirmationEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**warningActionsTintColor**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **messageOptionsText**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**messageOptionsBackgroundColor**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**userReactionsBackgroundColor**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **userReactionsTitleText**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**optionsOverlayDimColor**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))  <br/>More info  <br/>Style for [MessageListView](MessageListView/index.md).  <br/><br/><br/>|
| <a name="io.getstream.chat.android.ui.message.list/ScrollButtonViewStyle///PointingToDeclaration/"></a>[ScrollButtonViewStyle](ScrollButtonViewStyle/index.md)| <a name="io.getstream.chat.android.ui.message.list/ScrollButtonViewStyle///PointingToDeclaration/"></a>[androidJvm]  <br/>Content  <br/>data class [ScrollButtonViewStyle](ScrollButtonViewStyle/index.md)(**scrollButtonEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **scrollButtonUnreadEnabled**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**scrollButtonColor**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**scrollButtonRippleColor**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), @[ColorInt](https://developer.android.com/reference/kotlin/androidx/annotation/ColorInt.html)()**scrollButtonBadgeColor**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **scrollButtonIcon**: [Drawable](https://developer.android.com/reference/kotlin/android/graphics/drawable/Drawable.html)?, **scrollButtonBadgeTextStyle**: [TextStyle](../io.getstream.chat.android.ui.common.style/TextStyle/index.md))  <br/>More info  <br/>Style for ScrollButtonView  <br/><br/><br/>|
