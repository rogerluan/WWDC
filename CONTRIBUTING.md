# How to contribute

I'm really glad you're reading this and are willing to help. Watching all the sessions is pretty time-consuming and help is highly appreciated.

## Recommendations

You should have a look at the [open PR's](https://github.com/Blackjacx/WWDC/pulls) before you start watching a session. There is a chance that a session has already been processed so you can focus on another video.

I watch sessions in 1.5 speed using the awesome player from wwdc.io. This is the only way for me to watch so many sessions. You can try it and if it feels too fast, just reduce the speed to 1.25 which should be fine for most of the people.

Write in a text editor that offers spell check. You'll be surprised by the amount of typos and small mistakes we make by typing while paying attention to the session :)

## Submitting Changes

Please try to follow the following rules to have a consistent look and feel:
- First of all the list is not sorted. If you want to add a new session, please just put it at the bottom.
- Don't forget to add an entry to the `table of contents`.
- Put a link to the session just below its title. Please use the short version of the url: `https://developer.apple.com/wwdc20/<session_number>`.
- Mention the authors below the session link in the format `_Author_1, Author_2_`. The underscores at both ends make the text italic. You'll find the authors at the beginning of each video.
- The video duration is not needed here since you can see it when you click the link.
- For the session please do not add **code samples**, except one-liners and no **images**. I plan to have all session notes skimmable as easy as possible. But you can link to the relevant position in the video by using a short link in like this: [22:32](https://developer.apple.com/wwdc19/245/?time=1337). Just put the seconds at the end where the interesting part starts in the video.
- Writing while watching the session can be challenging and you'll often make typos or innocent grammar mistakes. Please review what you're submitting before opening a PR, as this will make your notes available to others faster, and with higher quality.
- `objc` != `Obj-C` != `objective-C` != `Objective-C`. `IOS` is not an operating system and neither `XCode` is an IDE (`iOS` and `Xcode` would be correct). Please double check your spelling and make sure it's consistent.

When you are finished please send a [GitHub Pull Request](https://github.com/Blackjacx/WWDC/compare) with some notes of what you have done (read more about [pull requests](http://help.github.com/pull-requests/)).

## Commit Messages

### Submit a Session

It will be enough to have a one-line commit message that contains the title of the session, like:

```
Add Session \"Platform State of the Union\"
```

### Submit a Fix

Here it's enough to quickly mention what you did, like:

```
Fixed typo
```

```
Added Description if Feature xyz
```

Thanks so much for your contribution,
Stefan
