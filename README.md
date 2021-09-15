# Breaking the Point
A non-functioning SwiftUI flag-raising app that uses LLDB expressions to work

## Why?
I was sitting in the office, under the aircon, freezing cold and was very inspired by [this WWDC18 video](https://developer.apple.com/wwdc18/412) on advanced debugging.

Naturally, I thought wouldn't it be funny if I built an app with nothing but the boilerplate code and all the code was run in an `expression` within a breakpoint? So I spent the next 20 minutes doing exactly that, and of course, what else to build other than a flag raising app.

> tldr: I was freezing, funny idea, there went 20 minutes.

## What????
This app is a functioning app the same way SLS is a website. There are buttons, they just don't work. I can't exactly inject `@State` variables and I wasn't about to spend the whole day on a ridiculous joke, like seriously, who does that??

## How??????????????
This app uses the UIKit lifecycle to run, as the SwiftUI lifecycle hates me and keeps pointing towards death or crashing. 

This is built with Xcode 13 RC but should run fine on Xcode 12, I mean I haven't tested it but yes.

## Where???????????????????
The project? Here on GitHub. 

The breakpoint? Uh `SceneDelegate.swift`, line 22. 

The code? Right click on the breakpoint, edit breakpoint, it's there.

The aircon? Still directly above me, freezing me.
