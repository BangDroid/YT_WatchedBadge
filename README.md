 # YT_WatchedBadge
Adds a "Watched" cover and configurable progress bar to thumbnails, making it easier to see what videos have been watched.
The Watched Cover will appear on any video watched by any amount. This may become configurable in the future.
The progress bar can be configured in the Userstyle options menu.
Compatible with YouTube's own light and dark themes, no guaranteed compatibility for other userstyle custom themes.

The intent of YouTube's progress bar is to help users easily see video completion, but their implementation only tracks watched duration, regardless of a viewer's completion.
A huge number of videos are considered watched by the vast majority of viewers but never attain 100% watched progress due to things like Patreon credits or long outros.
This leaves the page scattered with red bars which makes it harder for users to assess at a glance. This Userstyle helps to reduce visual noise on the page.

[![alt tag](https://img.shields.io/badge/Install%20directly%20with-Stylus-%233daee9?style=for-the-badge)](https://github.com/BangDroid/YT_WatchedBadge/raw/main/YT_WatchedBadge.user.css)

## Preview
![Preview image](/img/preview.png)

## Userstyle Options
![options image](/img/options.jpg)

- **Watched Threshold:** Sets how much progress is considered watched. As described in [this issue.](https://github.com/BangDroid/YT_WatchedBadge/issues/2)
- **Hide All Progress Bars:** Hides all progress bars completely, only showing the Watched cover. This is the original behaviour of this Userstyle.
- **Hide Bars on Watched:** Hides progress bars over the threshold.
- **Obscure Bars on Watched:** Makes progress bars over the threshold less obvious.

[![alt tag](https://img.shields.io/badge/Install%20directly%20with-Stylus-%233daee9?style=for-the-badge)](https://github.com/BangDroid/YT_WatchedBadge/raw/main/YT_WatchedBadge.user.css)

## Known issues
- **YouTubes own progress tracking.** Occasionally a video will be attributed 100% watch progress when only a small amount has actually been watched, and even instances where the progress bar is full on videos that are not watched at all and don't even exist in the history. Subsequently, the Watched Cover is missappropriately applied. It's an issue on YouTube's end, there's nothing we can do about it.
- **Hover hide.** The intent is to have the Watched cover hide when hovered to see the thumbnail and previews clearer, this is not working on some thumbnails on some pages. Debugging is difficult and it's low priority for now.
