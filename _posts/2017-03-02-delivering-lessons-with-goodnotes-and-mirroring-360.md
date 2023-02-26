---
layout: post
title:
tags: [GoodNotes, Mirroring 360]
redirect_from: "/2017/03/02/delivering-lessons-with-goodnotes-and-mirroring-360/"
---

For a long time I thought about my iPad Pro exclusively as a personal productivity device. I would research and plan my lessons there, I would design my lesson materials there, but after I'd saved everything into OneDrive, it would be the Windows PC connected to my smart board that I'd use to actually display these to my students. Because I was creating my lesson materials in PowerPoint, with my lesson plans in OneNote, this workflow made a lot of sense: one app for my students on the smart board, another app for me on my iPad. 

I think it was getting my Apple Pencil that eventually tipped the balance. When I first got it, I was using it to create my lesson materials, but when I displayed them on the smart board, the only option for marking up and annotating was to use the 'smart ink' function on my PC. This felt buggy and clumsy compared to the precision I had when using my Apple Pencil.

On another level, I had also been thinking a lot about behaviour management. I'm not someone who naturally has a huge amount of presence in a room, so I like to move around my classroom quite a bit to help manufacture this to some extent. When I was writing on the board, I always felt stuck at the front, facing in the wrong direction, at precisely the point when I most needed to be aware of students' attention levels. Being able to move around the room *while* presenting material on the board was an idea that really appealed to me, and it's been really exciting to start trying it out.


## Mirroring 360

If you're in a school where working on an iPad isn't the norm, the infrastructure isn't always a there to allow you immediately to start presenting lessons from your iPad. However, don't be put off by this; there are some good solutions. The most obvious and well documented way is to connect an Apple TV to your projector. I thought about buying one exclusively for this purpose, but I wanted to test it out first to see if it was worth the money. The only Apple TV I was aware of in the school was the one connected to the TV in the staff common room, so I politely asked if I could borrow it for a couple of hours. While it worked quickly without a lot of complicated setup, I wasn't entirely happy with the results. Whether the issue was with the Apple TV or with the projector I'm not sure, but I couldn't get the aspect ratio the way I wanted it. However I tweaked the settings, I ended up either with black bars on all four sides, or bits of the screen spilling off the edges.

I ended up exploring different options, and settled on a software rather than hardware solution to the problem. There are lots of apps for Windows and Mac that can pretend to be Apple TVs and accept video input via AirPlay. I can't say I've tested a lot of these and found the best one, but the one I do use seems to work well and it fits my needs. It's an app called [Mirroring 360](http://www.mirroring360.com/), and it's available for Windows, Mac, and Chrome OS, with client apps for iOS and Android. 

I really liked the business model for this app: after a one-week free trial, I could buy a single device license for $14.99 for the PC in my classroom. It's a one-time purchase, not a annual fee, so it's very affordable even if you're just buying it as an individual. This is much better than the situation with a lot of education apps on PCs, where you can only try them out if you can persuade your IT department to purchase a whole-school license.

![Menu on Windows PC]({{ site.baseurl }}/images{{ page.url }}/mirroring-360-on-windows.png)

After that, you just need to download the [iOS app](https://itunes.apple.com/gb/app/mirroring-assist-share-your-screen-to-teach-present/id950117741?mt=8&uo=4&at=1001lsF2) and you're ready to share your screen. On launch the PC app displays the menu above: the most important thing here is the 'mirroring assist' button. This opens up a QR code which the iOS app can read to connect to the PC for the first time. Once connected, you can share your iPad screen via the AirPlay Mirroring button in Control Centre. I'm not sure what the implementation is, but for some reason (probably an iOS system restriction), the PC only shows up in Control Centre as an AirPlay receiver when the [Mirroring 360](https://itunes.apple.com/gb/app/mirroring-assist-share-your-screen-to-teach-present/id950117741?mt=8&uo=4&at=1001lsF2) app is open, but once you've selected it, the app keeps mirroring your screen even when you're in another app. 

![Using Control Centre to start AirPlay]({{ site.baseurl }}/images{{ page.url }}/control-centre-airplay.png)

One slight restriction with this setup is that your iPad and PC need to be on the same network. In my case, My classroom PC is networked via ethernet, so my iPad can talk to it when connected to the school wifi. If you don't have good, reliable wifi in your school, using a software solution like this won't work for you, but you can fall back on the Apple TV hardware solution. The latest generation Apple TV supports AirPlay without the two devices being on the same wifi network.

What I'd love to see in future is the ability to AirPlay your iOS screen over the internet. This would mean I wouldn't have to worry about having a particular app installed on my PC, I could just use a web browser. It would also mean that if I was in another classroom, say for a cover lesson, I would still be able to stream my iPad screen. Mirroring 360 currently has a pro version in beta which allows to you share your screen online, but you can only do this via the PC that is receiving the screen, not directly from the sending device. iOS doesn't currently support AirPlay over the internet, but I hope this is something Apple will consider implementing in the future. 

As a teacher, you do need to be aware that AirPlay mirroring shows *everything* that's on your screen, including notifications and the passcode screen. With Touch ID, the latter isn't an issue, but I'd recommend liberal use of the Do Not Disturb feature in settings to ensure you don't have any text messages, emails, or other notifications popping down from the top of the screen when you're trying to teach algebra to excitable teenagers. Since I just *knew* I would one day forget to turn it on, I decided to use the 'scheduled' option to activate Do Not Disturb at the beginning of every school day and turn it off at the end. Make sure you also select the 'always' option so that notifications are blocked whether or not your iPad is locked. While mirroring my screen, I also make a lot of use of the freeze button on my projector remote so that I can have a look at the next page of a powerpoint or navigate to another document while what students can see on the smart board doesn't change. It would be great to have a bit more control over video output at a system level in iOS. I'd love to be able to hit a freeze button on my iPad rather than using the projector remote. 

![Do Not Disturb Scheduling]({{ site.baseurl }}/images{{ page.url }}/do-not-disturb-scheduling.png)
   
## GoodNotes

[GoodNotes 4](https://itunes.apple.com/gb/app/goodnotes-4-notes-pdf/id778658393?mt=8&uo=4&at=1001lsF2) by Time Base Technology Limited is an excellent companion to [Mirroring 360](https://itunes.apple.com/gb/app/mirroring-assist-share-your-screen-to-teach-present/id950117741?mt=8&uo=4&at=1001lsF2). Unlike many other note taking apps, it is ideal for presentations, since it has a mode that alters the video output feed that is sent via AirPlay. Like PowerPoint presentation mode, it presents a clean, UI-free view on the projector screen, while showing the full UI and tools to the user on the iPad. This means you can navigate pages, change writing tools, select objects and move them around, all without creating visual distractions for your students. This option is enabled via the 'Hide User Interface' option in the app settings. It's worth noting that even when you have GoodNotes in split view, as long as it as the primary app on the left side of the screen, students won't see the secondary app on the right. This is great for looking at your lesson plan, or navigating through documents while delivering a lesson. Swap the apps over, and the split view can be shown, which is also occasionally useful in lessons.

![Hide User Interface option]({{ site.baseurl }}/images{{ page.url }}/hide-user-interface.png)

[GoodNotes](https://itunes.apple.com/gb/app/goodnotes-4-notes-pdf/id778658393?mt=8&uo=4&at=1001lsF2) is also a well designed app with an impressive array of functions. You can create notebooks with multiple different paper types and then group them by categories. As a maths teacher, I mostly use A4 squared paper in landscape, but the app also offers graph paper, lined paper, and even manuscript paper for musical notation. I have one category for each class that I teach and then one notebook for each topic. 

![Categories and Notebooks]({{ site.baseurl }}/images{{ page.url }}/categories-and-notebooks.png)

The drawing tools are simple but effective: different coloured pens, highlighters, erasers, and a tool to convert what you draw to exact straight lines, perfect circles and other geometric shapes. Other features include the following:

- Full Apple Pencil support, as well as support for a number of third-party styluses
- A zoom function which is difficult to describe in words, but allows you to write continuously when zoomed in without having to pan around
- The ability to import images and entire multi-page PDF documents: great for annotating worksheets
- Export to PDF or images
- Auto-backup (in GoodNotes format or PDF) to your cloud service of choice
- A slightly random one, but GoodNotes is the only app on iOS I have so far discovered which can do bulk rotation of the pages of PDF: handy if you've scanned something in the wrong orientation

[GoodNotes](https://itunes.apple.com/gb/app/goodnotes-4-notes-pdf/id778658393?mt=8&uo=4&at=1001lsF2) has also changed the way I do lesson planning. I find writing out my slides with my Apple Pencil helps me think more carefully about the structure and timing. I still take brief notes in [OneNote](https://itunes.apple.com/gb/app/microsoft-onenote/id410395246?mt=8&uo=4&at=1001lsF2), but I find that I'm doing most of the thinking in GoodNotes, where I can easily draw diagrams and use mathematical notation. 

![GoodNotes in action]({{ site.baseurl }}/images{{ page.url }}/goodnotes-in-action.png)

It will be interesting to see to what extent I re-use these slides next year. I haven't yet developed a good workflow for saving the original slides without the annotations and solutions I write on during lessons, so I may have to go back and tidy them up to some extent. One missing feature that I'd love to see in future is the option to duplicate a page. This would mean I could have one page with just the questions I've written, and another with all the answers as well. It is possible to copy a page and then paste it as a new page, but it requires far too many taps at the moment. I raised this with the developers and they have said they'll work on it for a future version.

In terms of behaviour management, it's been a real help. I've often found that with difficult classes, standing at the back of the room can be a bit of a power move, and now I can stand anywhere I like while delivering the lesson. The 12.9" iPad Pro can feel a little unwieldy at times; I think the ideal device for this purpose would probably be the 9.7" iPad Pro, but all things considered I still prefer the 12.9" and I'm not yet tempted by the [#multipad lifestyle](https://www.relay.fm/cortex). What I'd really like next for my classroom is some kind of lectern or sturdy music stand that I could put my iPad on when standing. With my Apple Pencil in one hand and cradling my 12.9" iPad in the other, it can be difficult to gesticulate as much as I would like.

It's also helped me to improve the quality of my lessons. A simple but effective pedagogical tool is to take photos of good examples of students work using the camera input tool in GoodNotes and display them on the board. I've had great class discussions based on talking through these with my class: what the particular student did well in their working and what they could have done better. I can mark up their solution in real time, adding corrections or extra bits of explanation. Students are naturally curious to see each other's work, and they are really motivated to show good working so that their solution gets picked to go up on the board. It's a fantastic way to finish a lesson and summarise the material, since it encourages students to reflect on their own work and others'. 

Using your iPad to present lessons as well as planning them opens up a huge new world of possibilities for students' experience. The whole of the iOS App Store becomes a potential teaching tool. I have used apps like [WolframAlpha](https://itunes.apple.com/gb/app/wolframalpha/id334989259?mt=8&uo=4&at=1001lsF2), [MyScript Calculator](https://itunes.apple.com/gb/app/myscript-calculator-handwriting-calculator/id578979413?mt=8&uo=4&at=1001lsF2), [Notability](https://itunes.apple.com/gb/app/notability/id360593530?mt=8&uo=4&at=1001lsF2), and the wonderful but strange [Qama Calculator](https://itunes.apple.com/gb/app/qama-calculator/id1106592917?mt=8&uo=4&at=1001lsF2), but [GoodNotes](https://itunes.apple.com/gb/app/goodnotes-4-notes-pdf/id778658393?mt=8&uo=4&at=1001lsF2) is still the app I use most often, and the app that is most central to the way I plan and deliver my lessons.

[GoodNotes](https://itunes.apple.com/gb/app/goodnotes-4-notes-pdf/id778658393?mt=8&uo=4&at=1001lsF2) is usually $7.99 in the App Store, but for a limited time is reduced to the amazing price of only $0.99. Get it while you can!


