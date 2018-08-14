Sidebar Browser: Run Chrome in a Windows 10 sidebar (aka AppBar)
================================================================

What is it?
-----------
Runs Chrome in a Windows side-bar (aka AppBar).  This is different from just docking to the side of the screen in that Windows reserves the side of the screen for the application such that other apps only have access to the rest of the screen.  It also plays nice with the Windows 10 notification panel (that's dragged out from the right of the screen), placing it next to the Sidebar Browser window.

Motivation
----------
Now that most web-apps are responsive (i.e. mobile-friendly), they usually render nicely in a high, narrow browser window, which is what a Windows side-bar is.  My use-case for this is to keep my to-do list (Trello) on my main monitor screen at all times, which helps to keep my on-task.

Source-code
-----------
The source is essentially a merge of [CefSharp's Minimal Example](https://github.com/cefsharp/CefSharp.MinimalExample) and the code in [Mad__](https://www.codeproject.com/script/Membership/View.aspx?mid=898471)'s article. [AppBar using C#](https://www.codeproject.com/Articles/6741/AppBar-using-C).

Improvements
------------
Currently the application is fairly primitive.  Obviously nice-to-haves are:
* resize the side-bar by dragging the edge
* enable scaling (i.e. Ctrl-+ or Ctrl+wheel)
* snap to edges other than the right edge of the main monitor
* right-click menu a la Chrome
