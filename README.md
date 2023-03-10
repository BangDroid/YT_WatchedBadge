 # YT_WatchedBadge
Replaces the red progress bar on thumbnails with a "Watched" cover that disappears on hover.

Compatible with YouTube's own light and dark themes, no guaranteed compatibility for other userstyle custom themes. But provided they leave the progress bar alone (&lt;ytd-thumbnail-overlay-resume-playback-renderer&gt; and children, it shouldn't be an issue.)
The userstyle includes a baked in image as encoded base64 string so it's quite large but removes external dependencies on other hosts. The progress bar amount is also ignored, regardless of how much is watched of a video the "Watched" cover will be displayed. Disabling the style will show progress once again. (I use a hotkey with Stylus to do this).

[![alt tag](https://img.shields.io/badge/Install%20directly%20with-Stylus-%233daee9?style=for-the-badge)](https://github.com/BangDroid/YT_WatchedBadge/raw/main/YT_WatchedBadge.user.css)

## Preview
![Preview image](https://github.com/BangDroid/YT_WatchedBadge/raw/main/watchedBadgePreview.png)
