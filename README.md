## Bytesize icons as React components.  
All the icons were designed by [Dan Klammer](https://github.com/danklammer).  
Find the original [SVG icons here](https://github.com/danklammer/bytesize-icons).  


### How to install?

`npm install --save react-bytesize-icons`

### How to use?
Here's an example for using the `<Twitter/>` component.  

```javascript
import React from 'react';
import ReactDOM from 'react-dom';

import { Twitter } from 'react-bytesize-icons';

ReactDOM.render(
  <Twitter width={50} height={50} color="#1da1f2" />,
  document.getElementById('root')
);
```

You can also import this as following.
```
import Twitter from 'react-bytesize-icons/Twitter';
```
You should follow the import method which suits your needs. For details check [#9](https://github.com/abdelhai/react-bytesize-icons/pull/9).

### Components reference
Check out [this guide](https://github.com/danklammer/bytesize-icons#recommended-styles) on how to use the different styles/props listed in the table.  

Component Name  | Component Markup  | Preview | Optional Props
--- | --- | --- | ---
Activity  | `<Activity/>` | ![Activity](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/activity.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Alert | `<Alert/>`  | ![Alert](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/alert.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Archive | `<Archive/>`  | ![Archive](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/archive.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Arrow Bottom  | `<ArrowBottom/>`  | ![Arrow Bottom](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/arrow-bottom.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Arrow Left  | `<ArrowLeft/>`  | ![Arrow Left](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/arrow-left.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Arrow Right | `<ArrowRight/>` | ![Arrow Right](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/arrow-right.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Arrow Top | `<ArrowTop/>` | ![Arrow Top](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/arrow-top.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Backwards | `<Backwards/>`  | ![Backwards](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/backwards.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Bag | `<Bag/>`  | ![Bag](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/bag.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Ban | `<Ban/>`  | ![Ban](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/ban.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Bell  | `<Bell/>` | ![Bell](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/bell.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Book | `<Book/>`  | ![Book](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/book.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Bookmark  | `<Bookmark/>` | ![Bookmark](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/bookmark.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Calendar | `<Calendar/>`  | ![Calendar](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/calendar.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Camera  | `<Camera/>` | ![Camera](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/camera.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Caret Bottom  | `<CaretBottom/>`  | ![Caret Bottom](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/caret-bottom.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Caret Left  | `<CaretLeft/>`  | ![Caret Left](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/caret-left.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Caret Right | `<CaretRight/>` | ![Caret Right](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/caret-right.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Caret Top | `<CaretTop/>` | ![Caret Top](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/caret-top.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Cart  | `<Cart/>` | ![Cart](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/cart.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Checkmark | `<Checkmark/>`  | ![Checkmark](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/checkmark.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Chevron Bottom  | `<ChevronBottom/>`  | ![Chevron Bottom](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/chevron-bottom.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Chevron Left  | `<ChevronLeft/>`  | ![Chevron Left](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/chevron-left.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Chevron Right | `<ChevronRight/>` | ![Chevron Right](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/chevron-right.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Chevron Top | `<ChevronTop/>` | ![Chevron Top](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/chevron-top.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Clipboard | `<Clipboard/>`  | ![Clipboard](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/clipboard.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Clock | `<Clock/>`  | ![Clock](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/clock.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Close | `<Close/>`  | ![Close](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/close.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Code  | `<Code/>` | ![Code](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/code.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Compose | `<Compose/>`  | ![Compose](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/compose.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
CreditCard  | `<CreditCard/>` | ![CreditCard](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/creditcard.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Desktop | `<Desktop/>`  | ![Desktop](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/desktop.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Download  | `<Download/>` | ![Download](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/download.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Edit  | `<Edit/>` | ![Edit](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/edit.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Eject | `<Eject/>`  | ![Eject](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/eject.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Ellipsis Horizontal | `<EllipsisHorizontal/>` | ![Ellipsis Horizontal](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/ellipsis-horizontal.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Ellipsis Vertical | `<EllipsisVertical/>` | ![Ellipsis Vertical](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/ellipsis-vertical.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
End | `<End/>`  | ![End](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/end.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Export  | `<Export/>` | ![Export](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/export.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
External  | `<External/>` | ![External](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/external.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Eye | `<Eye/>`  | ![Eye](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/eye.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Feed | `<Feed/>`  | ![Feed](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/feed.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
File  | `<File/>` | ![File](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/file.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Filter  | `<Filter/>` | ![Filter](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/filter.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Fire  | `<Fire/>` | ![Fire](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/fire.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Flag  | `<Flag/>` | ![Flag](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/flag.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Folder  | `<Folder/>` | ![Folder](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/folder.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Folder Open | `<FolderOpen/>` | ![Folder Open](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/folder-open.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Forwards  | `<Forwards/>` | ![Forwards](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/forwards.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Fullscreen  | `<Fullscreen/>` | ![Fullscreen](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/fullscreen.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
FullscreenExit  | `<FullscreenExit/>` | ![FullscreenExit](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/fullscreen-exit.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Gift  | `<Gift/>` | ![Gift](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/gift.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
GitHub  | `<GitHub/>` | ![GitHub](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/github.svg)   | `width=32, height=32, color='currentcolor', className='example-class' id='example-id'`
Heart | `<Heart/>`  | ![Heart](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/heart.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Home  | `<Home/>` | ![Home](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/home.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Import  | `<Import/>` | ![Import](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/import.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Inbox | `<Inbox/>`  | ![Inbox](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/inbox.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Info  | `<Info/>` | ![Info](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/info.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Lightning | `<Lightning/>`  | ![Lightning](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/lightning.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Link  | `<Link/>` | ![Link](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/link.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Location  | `<Location/>` | ![Location](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/location.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Lock  | `<Lock/>` | ![Lock](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/lock.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Mail  | `<Mail/>` | ![Mail](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/mail.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Menu  | `<Menu/>` | ![Menu](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/menu.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Message | `<Message/>`  | ![Message](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/message.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Microphone | `<Microphone/>`  | ![Microphone](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/microphone.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Minus  | `<Minus/>` | ![Minus](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/minus.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Mobile | `<Mobile/>`  | ![Microphone](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/mobile.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Moon | `<Moon/>`  | ![Moon](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/moon.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Move | `<Move/>`  | ![Move](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/move.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Music | `<Music/>`  | ![Music](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/music.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Mute  | `<Mute/>` | ![Mute](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/mute.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Options | `<Options/>`  | ![Options](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/options.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Paperclip | `<Paperclip/>`  | ![Paperclip](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/paperclip.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Pause | `<Pause/>`  | ![Pause](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/pause.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Photo | `<Photo/>`  | ![Photo](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/photo.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Play  | `<Play/>` | ![Play](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/play.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Plus  | `<Plus/>` | ![Plus](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/plus.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Portfolio | `<Portfolio/>`  | ![Portfolio](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/portfolio.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Print | `<Print/>`  | ![Print](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/print.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Reload  | `<Reload/>` | ![Reload](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/reload.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Reply | `<Reply/>`  | ![Reply](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/reply.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Search  | `<Search/>` | ![Search](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/search.svg)  | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Send  | `<Send/>` | ![Send](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/send.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Settings  | `<Settings/>` | ![Settings](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/settings.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
SignIn  | `<SignIn/>` | ![SignIn](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/sign-in.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
SignOut  | `<SignOut/>` | ![SignIn](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/sign-out.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Star  | `<Star/>` | ![Star](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/star.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Start | `<Start/>`  | ![Start](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/start.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Tag | `<Tag/>`  | ![Tag](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/tag.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Telephone | `<Telephone/>`  | ![Telephone](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/telephone.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Trash | `<Trash/>`  | ![Trash](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/trash.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Twitter | `<Twitter/>`  | ![Twitter](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/twitter.svg)   | `width=32, height=32, color='currentcolor', className='example-class' id='example-id'`
Unlock  | `<Unlock/>` | ![Unlock](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/unlock.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Upload  | `<Upload/>` | ![Upload](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/upload.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
User  | `<User/>` | ![User](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/user.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Video | `<Video/>`  | ![Video](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/video.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Volume  | `<Volume/>` | ![Volume](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/volume.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
Work  | `<Work/>` | ![Work](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/work.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
ZoomIn  | `<ZoomIn/>` | ![ZoomIn](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/zoom-in.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
ZoomOut  | `<ZoomOut/>` | ![ZoomOut](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/zoom-out.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`
ZoomReset  | `<ZoomReset/>` | ![ZoomReset](https://cdn.rawgit.com/abdelhai/react-bytesize-icons/master/icons/zoom-reset.svg)   | `width=32, height=32, strokeWidth='6.25%', strokeLinejoin='round', strokeLinecap='round', color='currentcolor', className='example-class' id='example-id'`


### If you have any questions, then join our [DevChat Slack group!](https://devchat.devolio.net/)  
