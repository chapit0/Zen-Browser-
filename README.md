# Zen-Browser-
CSS code to modify the look of the Zen Browser

<div align="center">

# --- URL BAR ---

</div>

**Hides the container info in url-bar.**
```css
/* Hides the container info in url-bar */
#userContext-label,
#userContext-indicator,
#userContext-icons {
  display: none !important;
}
```
---
**Hides the shield button from the url-bar.**
```css
/* Removes Shield button */
#tracking-protection-icon-container {
  display: none !important;
}
```
---
**Hides the bookmarks button from the url-bar.**
```css
/* Removes Bookmarks button */
#star-button-box {
  display: none !important;
}
```
---
**Hides the permission button from the url-bar.**
```css
/* Removes Permission button */
#identity-permission-box{
  display: none !important;
}
```
---
**Hides the shield identity from the url-bar.**
```css
/* Removes Identity button */
#identity-box{
  display: none !important;
}
```
---
**Hides the zoom button from the url-bar.**
```css
/* Removes the Zoom button in the url */
#urlbar-zoom-button{
  display: none !important;
}
```
---
**Centers the text on the url-bar.**
```css
/* Centers the url text */
#urlbar-input{
  text-align: center !important;
}
```
---
<div align="center">

# --- BOOKMARKS MENU ---

</div>

**Simpler bookmarks menu.**

![bookmarks](https://github.com/chapit0/Zen-Browser-/blob/6bab99f6a1216710002389401db4c708dec7eda8/bookmarks.png)
```css
#BMB_bookmarksToolbar {
  display: none !important;
}

/* Removes the Search bookmarks from the Bookmarks menu */
#BMB_searchBookmarks {
  display: none !important;
}

/* Removes the Manage bookmarks on the top from the Bookmarks menu */
#BMB_bookmarksShowAllTop, menuseparator {
  display: none !important;
}

/* Removes the Manage bookmarks on the bottom from the Bookmarks menu */
#BMB_bookmarksShowAll, menuseparator {
  display:none !important;
}

/* Removes the View bookmarks sidebar from the Bookmarks menu */
#BMB_viewBookmarksSidebar {
  display: none !important;
}
```
---

<div align="center">

# --- OTHERS ---

</div>

**Remove the plugins button.**
```css
/* Hides plugins button */
#unified-extensions-button {
  display: none !important;
}
#unified-extensions-button,
#unified-extensions-area {
  display: none !important;
}
```
----
**Hides the Status bar**
```css
/* Hides status bar */
#statuspanel{
    display: none !important;
}
```
---
**Removes the split view controls.**

![splitView](https://github.com/chapit0/Zen-Browser-/blob/5f0ec9e6897ac8f71020eb1a07c917dcbf2a543f/splitView.png)
```css
/* Removes the split view controls */
.zen-view-splitter-header-container {
  display: none !important;
}
```
---
