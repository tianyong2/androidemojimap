#Unicode Emoji to Emoji Cheat Sheet Android converter

This Android library will convert Strings containing unicode Emoji characters to their [Emoji Cheat Sheet](http://www.emoji-cheat-sheet.com/) equiavelent and vice-versa. 

While this library will work with all versions of Android, displaying unicode emojis in Android Widgets is unavailable before API 17.

##Usage

    String cheatSheetString = EmojiMapUtil.replaceUnicodeEmojis("☃")
    // cheatSheet = ":snowman:"
    String emojiString = EmojiMapUtil.replaceUnicodeEmojis(":snowman:")
    // emojiString = "☃"
  

##License

This project is licensed under [Apache Commons 2.0](http://www.apache.org/licenses/LICENSE-2.0) as well.

Made by the folks at [Hall.com](https://hall.com)


这是输入法自带表情 的转义
