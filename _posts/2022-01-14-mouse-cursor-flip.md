---
title: "#@!% Flipping Cursor!"
categories:
  - Blog
tags:
  - UI/UX
  - human factors engineering
  - healthcare IT
  - Microsoft Word
  - mouse cursor
---

ecently I came across some interesting behavior in Microsoft Word. While scrolling through a document I noticed that my pointer had flipped. Instead of seeing the classic arrow pointer (pointing to the upper-left) the pointer had flipped horizontally (arrow pointing to the upper-right). [1] Jiggling the pointer on and off the Word application caused the arrow pointer to flip back-and-forth. A video highlighting this behavior is embedded below.

<!--- 
video on blog:
word_mouse_cursor_flip_only.mov
video on github readme upload (not shown on pages)
https://user-images.githubusercontent.com/6284187/149540340-c1fb54ee-dc7d-4a50-8fa3-8007e27cbf96.mov
-->

<iframe width="560" height="315" src="https://www.youtube.com/embed/1KH5ac92csk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />


The pointer starts out as a normal arrow pointer then changes to a horizontal I beam pointer once the Word application is brought into focus by clicking. As the pointer travels left the pointer switches to a flipped arrow pointer. Traveling to the right we see the horizontal I beam pointer and eventually the normally expected classic arrow pointer. What the #$@!%?

It took me a while to figure this out, because googling “flipped reversed pointer cursor” primarily gives you stuff pertaining to mouse scrolling direction. But I eventually happened across a helpful StackExchange discussion. [2]  Apparently, this is meant to be a useful feature for users. If you click when the pointer is in the flipped configuration Word will highlight the corresponding line of text, see example video below:


<!--- 
word_mouse_cursor_selection_only.mov

https://user-images.githubusercontent.com/6284187/149541375-fc3011b6-5d8d-43b7-9c37-f49b43db7ca3.mov
-->

<iframe width="560" height="315" src="https://www.youtube.com/embed/2izioZDl7BQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />


Once you know about this you might consider it helpful. But really?! It is a buried feature that leads to two outcomes: 1) it doesn’t get noticed by the majority of users or 2) when it does get noticed it causes confusion (🙋🏾‍♂️). Apparently, other MS Office applications do similar things when the pointer goes leftward. [2] However, the Microsoft pointer UI documentation has no mention of why or when a flipped arrow pointer is supposed to be employed. [3]

Maybe I’m totally off-base. Maybe the flipped arrow pointer in MS Office applications leads to features that are loved by the masses. Maybe I have just missed this particular train? Probably not. I have a tendency to agree with the JohnGB on StackExchange that: “Consistency matters in UX, even when it is in things that most people will not be able to consciously notice.”

I think this is a good parting thought, it is especially salient for those of us that work in healthcare IT. The mental workload in healthcare is taxing, so software user experiences should be as simple as possible. There’s no reason to confuse your users by adding complexity and breaking your own design rules, especially if you aren’t providing substantial value.


Erkin  <br />
[Go ÖN Home](../../index.md) <br /><br />


Note: the discrepancy in verbiage between the title and the text. Mouse cursor and pointer seem to be interchangeable when referring to the “pointy thing”. [4] I use pointer through the text as that’s what Apple’s human interface guidelines call it. [1] But the codebase refers to NSCursor, so 🤷🏾‍♂️.

Note 2: below are the versions of the software I was using.
MacOS: 12.0.1 (21A559)
Word 16.56 (21121100)
Pages: 11.2 (7032.0.145)

Note 3: it is annoying that you can’t copy the version number from the About Word window of Microsoft Word.


## Bibliography
1.	Apple. Human Interface Guidelines: Mouse and Trackpad. 2022; Available from: https://developer.apple.com/design/human-interface-guidelines/macos/user-interaction/mouse-and-trackpad/.
2.	@StackUX. When to use reversed/mirror arrow cursor? 2022; Available from: https://ux.stackexchange.com/questions/35435/when-to-use-reversed-mirror-arrow-cursor.
3.	hickeys. Mouse and Pointers - Win32 apps. 2022; Available from: https://docs.microsoft.com/en-us/windows/win32/uxguide/inter-mouse.
4.	Cursor (user interface) - Wikipedia. 2022; Available from: https://en.wikipedia.org/wiki/Cursor_(user_interface).
