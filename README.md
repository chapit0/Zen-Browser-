# Zen-Browser-
CSS code to modify the look of the Zen Browser

<div align="center">

# --- URL BAR ---

</div>

<div align="center">

**Hides the container info in url-bar.**

![Container](https://github.com/chapit0/Zen-Browser-/blob/40edf7a0b95704430f2a46b46c89255f3f1a43a3/container.png)

</div>

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
<div align="center">

**Hides the bookmarks button from the url-bar.**

![bookmarks](https://github.com/chapit0/Zen-Browser-/blob/40edf7a0b95704430f2a46b46c89255f3f1a43a3/bookmarks.png)

</div>

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
<div align="center">
  
**Hides the identity from the url-bar.**

![Identity](https://github.com/chapit0/Zen-Browser-/blob/40edf7a0b95704430f2a46b46c89255f3f1a43a3/identity.png)

</div>

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
<div align="center">
  
**Centers the text on the url-bar.**

![Centertexturl](https://github.com/chapit0/Zen-Browser-/blob/40edf7a0b95704430f2a46b46c89255f3f1a43a3/centerUrlText.png)
</div>

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

<div align="center">
  
**Simpler bookmarks menu.**

![bookmarks](https://github.com/chapit0/Zen-Browser-/blob/40edf7a0b95704430f2a46b46c89255f3f1a43a3/bookmarksMenu.png)
  
</div>

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
<div align="center">
  
**Removes the split view controls.**

![splitView](https://github.com/chapit0/Zen-Browser-/blob/40edf7a0b95704430f2a46b46c89255f3f1a43a3/splitView.png)

</div>

```css
/* Removes the split view controls */
.zen-view-splitter-header-container {
  display: none !important;
}
```
---
