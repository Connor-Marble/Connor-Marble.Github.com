---
layout: post
title: "Switching to Linux: 8 Weeks Later"
description: "My thoughts on Linux 8 weeks after switching from windows"
category: 
tags: [Linux]
---
{% include JB/setup %}

It's been almost exactly 2 months since I made the plunge from spending 95% of my time in windows with ubuntu as a backup to using a linux distro almost 100% of the time. I've dabbled with linux here and there, but frankly I hadn't really given the system a real chance. I had always loathed the cumbersome behemoth that is Microsoft Windows, but assumed that I would hate maintaining a linux system even more. 

###So Why Did I Switch?


I had always had this idea in my head that linux was probably a nicer environment to develop in, and as development has been an increasing large portion of what I do on my computer I figured I might want to switch one day. This nagging pull towards linux was also enhanced by the couple friends of mine who swore by linux and unix like systems. What actually prompted the switch however happened to be a hardware upgrade. Two months ago I finally bought an SSD for my main computer, and I figured it would probably take less time to get linux up and running than to migrate windows to a new drive. So, I downloaded mint 17 (I already knew I wasn't a big fan of unity from my limited ubuntu experience) and installed it as my primary operating system.

###Acclimating

I initially installed cinnamon (currently trying out KDE) as it was the default mint desktop and it does resemble the way windows 7 works in many ways. It worked perfectly really, and I had no problems with it. If I was going to go all in on linux though, I figured I might as well figure out how to take full advantage of the system and start using the terminal for stuff. After spending a number of hours on youtube, I was pretty confident at doing basic file operations and navigation in the terminal, as well as some less basic stuff like grepping files and working with external devices. I also started using emacs. Emacs is great.

I think there were really two major problems that I had in the beginning. The first was understanding why you would want a package manager to manage and install software rather than the familiar practice of downloading install binaries from shady looking download sites. I installed a lot of software in the beginning by googling for a .deb package when I could have installed it with a single apt-get command.

The second thing I had trouble with was figuring out how the hell you were supposed to do something like build a fairly complex project from source when there were often dozens of dependencies. I spent a long time trying to google and download the packages that my build errors told me I needed. This is of course a ridiculously tedious process that often left me at dead ends or with unstable or outdated development versions of the required software. After I learned how to properly use APT however, this all clicked into place and I was rolling.

###Cons of Using Linux

There are of course a number of things I don't like about using linux...

####Games

The first real problem I have with linux is probably the most common reason a person would want to stick with windows, games. Because linux is a much less popular (read: lucrative) than windows, linux doesn't support D3D and many established studios are already windows based, there are far more large scale modern games written for windows than linux. I was however surprised at how many games did actually run natively on linux. I found that very nearly half of my steam library was also available when running linux. I had not been selecting games based on linux compatibility at all, so the fact that I 'accidentally' owned nearly 100 linux games was impressive to say the least. I think that the gaming scene for linux has been greatly improved in  recent years due to things such as Steam OS and Humble Indie Bundle.

####Drivers

I have had hardware compatibility issues as well. Most things worked fine out of the box, some things required minor configuration, but one incredibly annoying problem was (and still is) my Netgear WNA3100 wireless adapter. I could not figure out how to get this thing running even after reading dozens of help threads and even submitting my own. At this point I am routing my internet from my laptop to my desktop via an Ethernet cable, but I should probably think about getting a new wireless adapter that works with linux. 

####It's Less Popular

There are many other issues that simply stem from the fact that windows is the de facto PC operating system. The first disadvantage stemming from this is probably the smaller amount of technical support. The linux support community is extremely helpful and overall awesome, but statistically the odds that someone else has already had the same technical problem as you and asked for help on a public forum is much lower when using a less popular operating system. 

Its also worth considering the fact that linux is simply going to be less important to cross platform developers than windows. This means that if one platform has to come first or be the focus, it will never be linux. 

###Pros of Using Linux

Now the good part, the things I liked about using linux.

####It's faster

Linux is generally considered faster in general than windows, but in particular I enjoy the significantly faster boot times and the increased responsiveness. Linux also has the advantage of using less system resources (depending on the distro of course) and thus having less overhead. Using windows 7 I found myself waiting for windows to respond very frequently, and even on the occasion that I still need to boot into windows 8 on my laptop it is sluggish to start and stutters much more than while running ubuntu on the same hardware. Another advantage that I tend to see is that linux seems to perform better under heavy resource usage. What I mean by this is that when I run something that will just gobble all of my excess cpu cycles (such as a 3D renderer) I risk freezing every other application in windows. Linux however seems much more capable of handling the heavy load without making everything else stop working.

####Makes Development Easier (for me)

This is totally subjective of course, but development seems much easier on linux. I'm not going to get into the text editor vs IDE war, but I do find it much easier to adopt a less typical work flow when I can use the console to run applications rather than trying to find the right plugins or build scripts for eclipse. I also find it to be way easier to use apt or pip or gem to download various apis or libraries than having to manually find and install each one under windows. It is a personal choice, but I do prefer emacs and linux to most other work flows I've used.

####Customization

I've been through Unity, Gnome, KDE and Cinnamon in the past 8 weeks, and I do enjoy how easy it is to customize the linux desktop. I suppose you could do a lot of windows customization as well, but it was always a matter of finding a complete 'theme' you liked. I also admit that you can do quite a lot of customization in windows, but it usually required some third party program that cost money. Right now in KDE I can easily have multiple panels that can be anywhere and any size. I add any number of things to the panels and then have different ones depending on my monitor and 'activity' all without third party software.

####Wine isn't Useless

I have been able to get a number of programs working surprisingly well with wine. When I installed linux I assumed I wouldn't be able to really get anything but the most basic apps working in wine, but I have had some success with fairly complicated ones. My best example of this is the windows version of the Unity 3D editor, which seems to run perfectly after following the installation instructions I found on the Unity 3D wiki. Not only can i compile and build C# based games in linux, but I can test them just as well in linux as I could in windows.

###Conclusion

You can probably tell how I feel by the fact that this post has now turned into a linux ad, but to clarify I think I will probably stick it out with linux for awhile. My only real problem is that I can no longer play many of the games I used to, so I may have to start dual booting when next I get the itch to play a big AAA game, but I still fully intend to use linux for all of my programming and other most daily usage.