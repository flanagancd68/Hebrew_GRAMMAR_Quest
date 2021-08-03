---
title: "Hebrew GRAMMAR Quest"
#date: "2021-08-02"
cover-image: images/HGQ_book_cover.png
site: bookdown::bookdown_site
#documentclass: turabian-researchpaper
bibliography: [book.bib, packages.bib]
#biblio-style: APA-like
link-citations: yes
nocite: |
    @rmarkdown2020, @bookdown2016, @stiles2013wsa, @pratico2007, @avraham2012, @beckman, @beckman2012, @delauro2009, @beckmana, @chisholm2006, @chisholm1998
description: "A Hebrew Grammar guidebook for students of Holy Language Institute."
header-includes:
  - \usepackage{pdfpages}
colorlinks: yes
graphics: yes
lot: no
lof: no
#mainfont: Ezra SIL
---




# Cover {.unnumbered}
<div style="display:none"></div>

<img src="images/HGQ_book_cover_draft.png" width="800pt" style="display: block; margin: auto;" />

<small>*Updated*: 2021-08-02</small>

<small>

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" src="./images/00.cover.m4a"> Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


**LICENSE**

© 2021 Holy Language Institute. All rights reserved.

![Creative Commons](images/by-nc-sa.png)

This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. 

This license is for personal use only.  This publication may not be downloaded, redistributed, re-uploaded, published, or used for any other purposes without explicit permission from the copyright holder.

If you received this book but are not a Holy Language Institute member, [become a member today](https://holylanguage.com/subscribe.html)!  Subscribing will give you access to the full Hebrew GRAMMAR Quest course materials, as well as access to Izzy Avraham's complete library of teaching materials.


**CREDITS AND ACKNOWLEDGMENTS**

Unless otherwise noted, English Scripture quotations taken from the NASB. Copyright Copyright © 1960, 1962, 1963, 1968, 1971, 1972, 1973, 1975, 1977, 1995 by The Lockman Foundation. Used by permission.

Scripture quotations marked ESV are taken from The Holy Bible, English Standard Version, copyright © 2001 by Good News Publishers. Used by permission. All rights reserved.

Our thanks to Dr. Gary Pratico and Dr. Myles Van Pelt for <u>Basics of Biblical Hebrew</u>, the seminary textbook that inspired the **Hebrew GRAMMAR Quest** format.  We encourage any of our students who wish to go further with Hebrew grammar to [purchase the book or any related materials](#optional_resources){target="_blank"}.

Additionally, MASSIVE thanks to Dr. John Beckman for making his [extensive library of materials](https://hebrewsyntax.org/bbh2new){target="_blank"} to accompany <u>Basics of Biblical Hebrew</u> freely available for reuse under CC-BY-SA.

As applicable:

* This books' vocabulary portions and accompanying Anki deck are derivatives of [00_vocabulary.pdf](https://hebrewsyntax.org/bbh2new/00_vocabulary.pdf) by John Beckman, used under [CC-BY-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/){target="_blank"}.
* Grammar portions of this book and accompanying Anki deck are derivatives of [00_study_guide.pdf](https://hebrewsyntax.org/bbh2new/00_study_guide.pdf){target="_blank"} and the "overhead" files for each chapter (for example, [Chapter 1-The Hebrew Alphabet](https://hebrewsyntax.org/bbh2new/01_overheads_bw.pdf){target="_blank"}, and so forth for each successive chapter) by John Beckman, used under [CC-BY-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/){target="_blank"}

The photographs of Israel to begin each lesson are courtesy of the [Pictorial Library of Bible Lands](www.bibleplaces.com){target="_blank"}. Used by permission.

Biblical Hebrew text is courtesy of tanach.us (version 26.0). 

Yihui Xie is the genius who developed the [Bookdown](https://bookdown.org/){target="_blank"} tool, which is the engine behind publishing this interactive book.  Without Bookdown, we would not have achieved those bullet points listed on the [What we wanted in our course](#our_course) page related to the ease of lifting the project and making it available to our subscribers for free while maintaining a professional look.

We believe we have made reasonable attempts to acknowledge our sources where indicated. Notwithstanding these attempts, this work, including related materials and videos, may contain certain copyrighted works that we nonetheless believe in good faith are protected by United States federal law and the fair use doctrine.  Section 107 of the U.S. Copyright Act allows for reproduction for purposes such as teaching, scholarship, or research.   Concerns related to a citation/copyright matter may be directed to "contact at holylanguage dot com" for review and, as needed, acknowledgment.

</small>


All honor and glory to Yeshua, our Lord. <span class="he"> שֵׁם יְהוָה אֶקְרָא</span>


<!--chapter:end:index.Rmd-->

# About this course {-}

* [Why is Holy Language Institute offering a Hebrew grammar course?](#motivation)
* [What makes our course distinct?](#our_course)
* [How does this grammar course relate to _Hebrew Quest_?](#hgq_and_hq)
* [What if I haven't finished _Hebrew Quest_?](#finish_hq)


## Why is Holy Language offering a Hebrew grammar course? {- #motivation}


::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" src="./images/00.whyhebrewgrammar.m4a"> Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


If you are familiar with our ministry, you know our flagship course ***Hebrew Quest***, which introduces our students to Yeshua and our Jewish Bible.

***Hebrew Quest*** was designed to get students into the Hebrew text as quickly as possible, with minimal focus on learning rules. For many of our students, this approach is quite successful.  We noticed that many other students started to drop off between lessons 12 and 16, after the Aleph-Bet lectures. For some students, these lessons were too much Hebrew grammar too fast, and for others, it was not enough Hebrew grammar.  

As a result, several of our students have asked us for a grammar resource to supplement _Hebrew Quest_.  

As we searched for a resource to recommend to these students, we noticed that they tended to fall into one of two camps:

1. <u>A workbook or a series of videos that are entirely self-paced/self-directed</u> 
2. <u>Academic/Seminary level textbooks and courses</u>

These two are often opposite extremes.  Self-paced courses can have too little structure and often provide only a superficial review of Hebrew.  In the end, the student may only be slightly more prepared to read the Hebrew Bible than if they had not done the course.  There are also limited feedback opportunities as these courses are designed for independent learning.  On the other hand, seminary courses and seminary-level textbooks are usually incredibly rigorous with copious amounts of reading, rote memorization of paradigms, lectures, and exams. Academic courses are fast-paced and high-stress ^[For example, in a seminary course, the 36 lessons in <u>Basics of Biblical Hebrew</u> are usually completed in 16 weeks.]. Seminary textbooks generally are much more detailed and advanced than most of our students need (or would enjoy)^[For example, there is usually an emphasis on writing Hebrew and conducting English-to-Hebrew translations.  While these may be important skills to become fluent in Hebrew, one does not need these skills to read and understand the Bible, especially from a spiritual or devotional perspective.]
   
Additionally, with either option, our Holy Language students would incur additional fees to purchase these materials.  Many of the resources we researched are top-notch.  Depending on a student's goals, we would not hesitate to recommend them.  It's just that they were not quite what we were seeking for the majority of our students.

See the next section to learn how Hebrew GRAMMAR Quest is distinct.

## How is Hebrew GRAMMER Quest distinct? {- #our_course}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" src="./images/00.howishgqdistinct.m4a"> Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

Our Holy Language goals for a Hebrew grammar course are the following:

* Academically CHALLENGING, but with a LOW-STRESS level
* Primary emphasis on READING and UNDERSTANDING God's Word
    * We use grammar rules, paradigms, and memorization as a means to achieve this goal
    * The "final exam" should be whether you can understand the Bible, not whether you can conjugate a a particular Hebrew verb
    * We do not prioritize writing or speaking in Hebrew^[We believe this course, in conjunction with **Hebrew Quest**, would prepare a pastor or lay-teacher of a small-group, or traditional Christian or Messianic congregation to have a basic understanding of the Hebrew text in order to exegete and communicate beginning and intermediate level Hebrew/Hebraic concepts to a lay audience.  Even so, we are not presenting this as a substitute for seminary-level Hebrew for those who are seeking (or whose vocational position requires) more of a formal instructional approach. With all this said, the more of THIS course and _Hebrew Quest_ you complete, the more rewarding THAT course will be!. In any case, ***our prayer is that this course, along with Hebrew Quest, will give new life to Hebrew application in that person's teaching ministry***.  This book's compiler can testify to this!]
    * We are not addressing Modern Hebrew
* Self-paced for independent learning but with mechanisms to provide FEEDBACK, ENCOURAGEMENT, and ways to CELEBRATE Students' ACCOMPLISHMENTS in the course
* Aligns with our [Holy Language LEARNING PHILOSOPHY](https://holylanguage.com/learning-philosophy.php): emphasize active forms of learning over copious amounts of textbook reading and long lectures
* COMPLIMENTS and INTEGRATES WITH _Hebrew Quest_, but does not replace it; Hebrew GRAMMAR Quest is not a substitute for completing _Hebrew Quest_
* SUSTAINABLE from a technical standpoint, meaning the course is inexpensive and straightforward for the ministry to develop, deliver, and maintain
* FREE of charge for our students
* Most importantly, the course must be YESHUA-CENTERED that approaches learning Hebrew grammar as a spiritual as well as an academic endeavor (which is also a big part of our Learning Philosophy)

We are essentially trying to take the best attributes of a self-paced course and merge them with the best characteristics of a seminary-level Hebrew course!  We believe that result is Hebrew GRAMMAR Quest!

### Holy Language Learning Philosophy {-}

We have talked a bit about our Holy Language Learning Philosophy.  Our belief is you learn best by doing.  Izzy discusses this in greater detail in the clip below from **Hebrew Quest** Lesson 1.  As a reminder, you can increase the speed of YouTube videos by clicking "Settings", then adjusting the "Playback Speed" to your liking.

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/Ex9mBMAqWhI?start=2823" frameborder="0"></iframe>
</div>



## What is the Relationship to _Hebrew Quest_? {- #hgq_and_hq}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" src="./images/00.relationtohq.m4a"> Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

We've said that Hebrew GRAMMAR Quest does not replace _Hebrew Quest_.  Instead, we believe Hebrew GRAMMAR Quest supports and extends _Hebrew Quest_.  In fact, one way to think of Hebrew GRAMMAR Quest could be as "Hebrew Quest: Extended Edition"!  

Suppose you were to take a hypothetical microscope and inspect Lessons 13-15 of _Hebrew Quest_. These are the lessons where Izzy reviews Nouns, Pronouns, Verbs, and other grammar topics.  Under that microscope, <u>Hebrew GRAMMAR Quest</u> is what you would see. 

<img src="images/i.hq_hgq.png" width="800pt" style="display: block; margin: auto;" />

* Hebrew GRAMMAR Quest will start with a brief review of the Aleph-bet and the vowels we learned in _Hebrew Quest_ Lessons 1-12
* Then we begin our deep dive into core grammar topics touched upon in _Hebrew Quest_ Lessons 13-15
* Additionally, starting with Hebrew GRAMMAR Quest Lesson 12, students can elect to complete a "_Hebrew Quest_ Study Passage Track"
    * Primary geared for students who have not yet completed all of _Hebrew Quest_, this will incorporate the Proverbs study and the Bible reading sections from _Hebrew Quest_
    * Students will read through the passage and compose a translation
    * They will then watch Izzy's _Hebrew Quest_ teaching video explaining the passage
    * Students who complete all of the _Hebrew Quest_ Study Passage Tracks will receive extra special recognition upon completion of the course.  It our way of saying you have graduated "with honors"!

## Is completion of _Hebrew Quest_ is a prerequisite? {- #finish_hq}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/00.hqprerequisite.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

Emphatically NO!

If you _have_ finished _Hebrew Quest_, Hebrew GRAMMAR Quest might be a logical next step to go deeper.

On the other hand, maybe you started _Hebrew Quest_ but hit some roadblocks.  In that case, Hebrew GRAMMAR Quest can provide you with important underlying grammatical concepts so, eventually, you can return to _Hebrew Quest_ and finish up. 

It's important to know that Hebrew GRAMMAR Quest is an _extension_ of Hebrew Quest, not a substitute.  

As a best-case, we recommend you complete _Hebrew Quest_ Lessons 1-12 before starting Hebrew GRAMMAR Quest.  So, if you haven't started either course, go ahead and start with the first part of _Hebrew Quest_.  _Hebrew Quest_ [videos are here](https://holylanguage.com/quest.html){target="_blank"}, and the accompanying [Memrise module is here](https://app.memrise.com/course/5406435/hebrew-quest-lessons-1-to-40/){target="_blank"}.

To say it differently, _Hebrew Quest_ and Hebrew GRAMMAR Quest complement one another in a circular (and maybe slightly paradoxical!) form:

* The more _Hebrew Quest_ you have completed, the more you will get out of Hebrew GRAMMAR Quest, and . . .
* The more Hebrew GRAMMAR Quest you have completed, the more you will get out of _Hebrew Quest_ (especially _Hebrew Quest_ Lessons 13-40)
* Either way, you can't go wrong!  The most important thing is to start and ultimately complete both.  Again, the _Hebrew Quest_ study passage track within Hebrew Grammar Quest will get you on your way to this lofty goal of completing both courses.


::: {.box .map}
Let's get started!
:::


<!--chapter:end:00b-introduction.Rmd-->

# Anki Introduction{-}


::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/00.anki_intro.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


::: {.box .light}
* The Hebrew GRAMMAR Quest Guidebook is where you will get introduced to the material
* Anki is where you will LEARN the material
* This section will get you up and running with Anki
:::

<img src="images/weight.png" width="150pt" style="display: block; margin: auto;" /><img src="images/treadmill.png" width="150pt" style="display: block; margin: auto;" />


If one wants to build strength and endurance, it's essential to use the right machines.  Anki is a free^[All platforms are free, except for the iOS app, which costs $25. The developers use the proceeds to fund future development.  Most reviews say the cost is worth it if you have Apple devices and use Anki regularly.] flashcard application that helps you build both Hebrew strength and Hebrew endurance!

::: {.box .info}
As you work through this course, set aside time to review Anki on a DAILY basis
:::

The sections that will help you get started with Anki. There is also an `0. Introduction` section within the Hebrew GRAMMAR Quest Unit 1 Anki deck with additional how-to information.


## How do I get started with Anki/Hebrew Grammar Quest? {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/00.getstarted.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

::: {.box .caution}
Failure to follow the steps below could lead to Anki frustration!^[The first two steps aren't directly related to Anki, but since you'll need them for the course, we'll include them here.]
:::


| Step | Comments | Link to Video
| :-- | :-- | :--
|1. Get Google Account [here](https://accounts.google.com/signup/v2/webcreateaccount?continue=https%3A%2F%2Fwww.google.com%2F&hl=en&dsh=S-1425209384%3A1610207553422339&gmb=exp&biz=false&flowName=GlifWebSignIn&flowEntry=SignUp){target="_blank"} | You will need a Google account to complete many of the activities in this course.  Alternatively, you may wish to create an additional account exclusively for this course. Creating a Google account is free. | [YouTube: Step 1](./images/00.googlesignup.png){target="_blank"}
|2. Download the [course checklist](https://docs.google.com/spreadsheets/d/1t0C7JlygyUqgF_aQWbhq7h3s_VDn0VuvISJn5mp-LdE/copy){target="_blank"} to your personal Google Drive Folder | This is for you to keep track of your progress in this course. Be sure to update it as you complete each lesson, which will help you stay on track to earn `Badges`, Unit completion `Certificates`, and ultimately, `Graduation`! | [YouTube: Step 2](./images/00.HGQChecklist.png){target="_blank"}
3.  Download and install the [free Ezra SIL font](https://software.sil.org/downloads/r/ezra/EzraSIL-2.51.zip ){target="_blank"} | This enables Hebrew font in Anki cards. After downloading, extract the zip file to a location of your choice. Then double-click on `SILEOT.ttf`, which should give you the option to install the font. | [YouTube: Step 3](./images/00.ezrasilfolder.png){target="_blank"}
4. [Sign up for a free Ankiweb account here](https://ankiweb.net/account/register){target="_blank"} | This allows you to backup and sync your data to the cloud and mobile devices | [YouTube: Step 4](./images/00.ankisignup.png){target="_blank"}
5. [Download and Install the Anki Program (Mac/PC/Linux)](https://apps.ankiweb.net/){target="_blank"} | Click the `Download` button, then select the tab with your operating system^[The version numbers will change with the passage of time.  Unless instructed otherwise, download the curent version of the Anki desktop program on their website].  Despite the fact that you will see an `iPhone/Android` tab, you MUST install Anki from a desktop/laptop first | [YouTube: Step 5](./images/00.ankiinstall.png){target="_blank"}
6. Download the Hebrew GRAMMAR Quest Anki Decks | These decks are the backbone of the course.  Research shows using a tool like `Anki` is far more effective than reading or exams alone.  Note: You can download all decks now or, you may wish to start with just `Unit 1`.  Then you can load the remaining decks as you begin each new Hebrew GRAMMAR Quest unit.  We will have reminders in each unit introduction. After downloading, double-click to load into Anki - _you must do this from a desktop/laptop, not a mobile device_ | [YouTube: Step 6](https://youtu.be/)
| [Hebrew GRAMMAR Quest Unit 1 Anki Deck (version 0.1)](./images/HGQ_Anki_Unit1_V00.apkg){target="_blank"} | 
| [Hebrew GRAMMAR Quest Unit 2 Anki Deck (version 0.1)](./images/HGQ_Anki_Unit2_V00.apkg){target="_blank"} |
| [Hebrew GRAMMAR Quest Unit 3 Anki Deck (version 0.1)](./images/HGQ_Anki_Unit3_V00.apkg){target="_blank"} |
| [Hebrew GRAMMAR Quest Unit 4 Anki Deck (version 0.1)](./images/HGQ_Anki_Unit4_V00.apkg){target="_blank"} |
7. Change the Anki settings (see next section) | `Anki` is driven by an algorithm that we can customize for maximum effectiveness | [YouTube: Step 7](https://youtu.be/)
8.  Sync to Ankiweb - in Anki, click on `Sync` (enter Ankiweb credentials) - `upload to Ankiweb` if asked. | Syncing creates a version of your deck in the cloud, which case be used to sync with a mobile device or merely as a backup | [YouTube: Step 8](https://youtu.be/)
9. As desired, download the Anki app to your phone or tablet: [Android app](https://play.google.com/store/apps/details?id=com.ichi2.anki){target="_blank"} or [iOS](https://itunes.apple.com/us/app/ankimobile-flashcards/id373493387?mt=8&ign-mpt=uo%3D4){target="_blank"} | While the Android version is free, the iOS version has a one-time fee of $25. Apple users might consider using the [web version](https://ankiweb.net/account/login){target="_blank"} for the first few lessons while you assess whether the cost is justified
10. To use an `Anki` _mobile_ app, click on `Sync` and click `download from Ankiweb` | Should you go back and forth between mobile and desktop, make sure you `Sync` each time and be careful when you select `upload to` or `download from` to make sure your information is flowing in the correct direction
 
::: {.box .stop}
**Anki NOTE**: Eventually, you can do all work from a mobile device.  _For the initial Anki install, you do need to do these steps from a desktop or laptop_.  The Hebrew GRAMMAR Quest Anki deck can only be imported into the desktop Anki application. 
:::

## Customize Anki Settings {- #anki_settings}

::: {.box .info}
These settings will optimize your Anki experience
:::

| Step | Comments
| :-- | :-- 
1. Change `USER1` Name | 1. In Anki, click `File`, then `Switch Profile`  
| |    2. Select `User 1`, then `Rename` and type your name
2. Change global settings  |  1. Click `Tools,` then `Preferences.` 
| | 2. On the `Scheduling` tab, check the box that says `Anki 2.1 Scheduler`.
Change card learning options | 1. On the main page, click the gear wheel to the right of “Hebrew Grammar Quest” and select `Options` ([click to see example](./images/a.anki_settings.png){target="_blank"})
|`New Cards`^[ See https://docs.ankiweb.net/#/deck-options?id=new-cards for additional information and the definitions of these terms, `New`, `Review`, and `Lapsed`] | `Steps` = 10 1440 4320
| |`New cards/day` = 200
| |`Graduating interval` = 15
| | `Easy interval` = 60
| |`Starting ease` = 250%
| |`Bury related new cards...` = we recommend CHECKED, but this is not mandatory^[Checking this means that cards with two or more questions won't be presented on the same day.  The risk of leaving it unchecked is that you may get Question #2 correct not because you know the answer, but because you just saw the answer when you reviewed Question #1.  Checking the box means you will not see Question #2 on the same day as Question #1.  Thus, checking the box will increase the length of time required to move cards from `Young` to `Mature`, but is the stronger option for learning.]
| `Reviews` | `Maximum reviews/day` = 9999
| | `Easy bonus` = 130%
| |`Interval modifier` = 100
| | `Maximum interval` = 210
| | `Bury related reviews...` = we recommend CHECKED, but this is not mandatory   
| `Lapses` | `Steps` = 10
| | `New interval` = 60
| | `Maximum interval` = 1
| | `Leech threshold` = 8
| | `Leech action` = TAG ONLY

After changing, your settings should look like this:
<div class="figure" style="text-align: center">
<img src="images/anki_custom_new.png" alt="Settings" width="700pt" />
<p class="caption">(\#fig:unnamed-chunk-4)Settings</p>
</div>
    
## How do I navigate within Anki? {-}

::: {.box .map}  
* We have also created a brief tutorial within our Hebrew GRAMMAR Quest `Anki` deck for Unit 1.  
* This is contained in the `0.Introduction` folder.  
* Click on this deck for an introduction and helpful hints
* When you are finished you may `Suspend` the cards (these are the only cards in the deck you should `suspend`!)

:::

* Click the +/- buttons to expand/collapse the folders within the Anki deck [(click to see example)](./images/00.ankifolders.png){target="_blank"}
    * To start with Lesson 01 Vocabulary, click on the plus buttons within Unit 1, until you see `Lesson 01 Vocabulary` and click the `STUDY NOW` button
    * In your initial learning, start with the `module` level, i.e. `Lesson 01 Vocabulary`
    * Once you have learned all cards in all modules, REVIEW at the Lesson level, e.g. `Lesson 01`
    * Once you have learned all cards in all Lessons in a unit, then REVIEW at the Unit level, e.g. `1. Lessons 1-3`
* Many cards have "hints" - click on the `hint` button to reveal [(click to see example)](./images/a.anki_hint.gif){target="_blank"}
    * If you needed a hint, be sure to select `Again` on the answer side
* When you are ready to see the answer, click Spacebar, Enter, or the `Show Answer` button

## How do I know when to hit the `Good` button on an Anki card? {-}

We suggest using the following guidelines:

* `Again`
  * Your answer was incorrect, or a mixture of correct and incorrect on a multi-part answer
  * Your answer was correct, but you required a hint
* `Hard` - You otherwise met the requirements for `Good`, but you struggled to produce the correct answer or guessed. 
* `Good`
  * All parts of the answer are correct; no hints
  * For Bible Verses, mark `Good` when:
    * you can read and understand the verse in Hebrew
    * Your translation is roughly similar to the English answer, even if you need to take a few moments to work through the verse
    * Your verb tense is correct (even though we won't study verbs until Unit 3)
    * You do NOT need to have the passage and its meaning memorized to mark `Good`
  * Be patient and honest with yourself.  If you are unsure between `Again` and `Good,` then select `Again.`
* `Easy`
  * We do not recommend selecting `Easy.` 
  * An exception might be when you are confident that you already have the word, rule, or passage memorized


::: {.box .info}
Be patient with yourself.  It may take you _many_ tries in the early going before you can hit `Good.`
:::

## How do I get help with Anki? {-}

::: {.box .info}

* We do have a [help](#report_issue) for to assist you with any issues related to the course, including our `Hebrew Grammar Quest Anki Deck`. 
* Unfortunately, it is beyond our scope to give you a complete tutorial _or offer any technical support with the Anki software or mobile app_.  
* The good news is that there is a LARGE Anki user community across the globe
    * We encourage you to check out the numerous articles and tutorial videos posted by the Anki community
    * Generally, if you type your question or issue in a web search, you will find exactly the answer you are seeking
* The official Anki documentation is available [here](https://docs.ankiweb.net/#/){target="_blank"}.
:::

<!-- deleted anki cards: -->
<!-- Introduction: -->
<!-- front: I want to test English to Hebrew. How can I set the deck to do this? -->
<!-- back: Our primary goal with Hebrew Grammar Quest is to translate from Hebrew to English.   -->

<!-- Most of our students studying Biblical Hebrew are not going to need to translate from English to Hebrew, although that is certainly a worthy pursuit.   -->


<!-- If you would like to add a reverse direction to your vocabularly words (Prompt with English - Answer with Hebrew) this is can be done in Anki. We have added "Note Types" to accomodate this. -->

<!-- Click "Browse" -->
<!-- From the Left Navigation, scroll down to "Vocab Basic Hebrew" -->
<!-- Select the card(s) you wish to change and add the additional options (To change ALL cards click CTRL+A to select all cards) -->
<!-- Click CTRL+SHIFT+M to change the note type to one of the following: -->
<!-- If you want to be tested on both Hebrew-to-English and reverse, English-to-Hebrew, select note type "Vocab Basic Hebrew/English" -->
<!-- If you have added images and want to be tested on Hebrew-to-English, English-to-Hebrew, and Image-to-Hebrew, select note type "Vocab Basic Hebrew/English/Image" -->
<!-- If you have added images and only want to be tested on Hebrew-to-English and Image-to-Hebrew, select note type "Vocab Basic Hebrew/Image" -->
<!-- Just be aware that changing to one of these optional note types, will literally double (or triple if you chose Hebrew/English/Image) the number of vocabularly cards.  If you decide you want to go back to just Hebrew-to-English, repeat steps 1-4 and select Note Type "Vocab Basic Hebrew." -->

<!-- Type ! (exclamation point) to dismiss this card. -->

<!--chapter:end:00c-Anki.Rmd-->

# Getting Started / Getting Help {-}

1. [How do I navigate around this book?](#navigating)
5. [What is in a typical lesson, and how long will it take?](#typical-lesson)
4. [How do I get started?](#get_started)
5. [How do I use Anki?](#anki_help)
5. [Which resources are required versus optional?](#optional_resources)
2. [How to report an issue, error, omission, or improvement opportunity](#report_issue)
3. [How to ask a question if you get stuck](#get_help)

## Navigating this book {- #navigating}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/00.navigate.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

In the upper-left corner of this page, you will see a series of icons.  

<img src="images/toolbar.png" width="300pt" style="display: block; margin: auto;" />

These do the following tasks:

* the file drawer expands/collapses the sidebar table of contents; you can also click `s`
* the magnifying glass toggles search input; you can also click `f`
* the big `A` allows you to change the font size and theme
* the little `i` shows you available keyboard shortcuts


There are several ways to navigate from page to page within this guidebook:

* Use the left-navigation sidebar (type `s` to reveal/hide)
* Click the left or right arrow on each page to go forward or back
* Use the left or right arrow keys on your keyboard to move forward or back
* Use hyperlinks on selected pages, like this one: [Continue to "A Typical Lesson" section](#features)



## A Typical Lesson {- #typical-lesson}

<img src="images/checklist.png" width="400pt" style="display: block; margin: auto;" />

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/00.typicallesson.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

In this course, you won't just read; you will DO!  This course is going to be jam-packed with activities. Below is what a typical lesson will contain^[We are following the same chapter organization as the textbook <u>Basics of Biblical Hebrew</u>, while extensively leveraging supplemental materials created by Dr. John Beckman, which he has generously made available for free to the Hebrew learning community.  See the [Course Structure](#what_to_expect) and our [Acknowledgments](#acknowledgments) pages for additional information.]:


**Title**|**Description**|**Estimated Minutes**
:-----|:----- | :---
  READING| A general comment about the guidebook: at times, you may feel like information is being shot at you from a firehose.  Often, this is just how it is when learning a new language. The fact is that you may be absorbing more than you think you are.  This is why we emphasize reinforcement of these concepts through activities.  Notice the root word "active" in activities.  You will get introduced to the material via the Lesson Points, but you will LEARN the material through the activities.  
Lesson Itinerary | Introduction and the lesson's learning objectives | <1
Equipment Check|Things you must have in your backpack before proceeding with the next phase of your journey | <1
First Thought |A Bible verse from the lesson in Hebrew, audio from Izzy, and a brief devotional | 5
Lesson Points | The main grammar concepts. Our goal is to give you just enough information to get started in `Anki`.  You can easily identify the Lesson Points as they will be the numbered sections in each lesson. 1.1, 1.2, etc. | 15-45
 ACTIVITIES|
 `Word and Verse Warm-ups`|Starting with Lesson 3, these are brief "stretching" exercises before doing the `Anki` workouts, narrated by Izzy! | 5-10
 `Anki`^[See [appendix](#anki_faq) for more information on Anki if you are not familiar with it.]| This is where the majority of your learning will take place.  There will be four modules to each Anki Lesson: `A. Vocab`, `B. Grammar`, `C. Workbook/Parsing`, and `D. Study Verses` | 60-180 total (Anki is meant to do a little each day as driven by the software's algorithm)
`A. Vocab`|By the end of the course, you will have around 500 Hebrew words memorized
 `B. Grammar`|Here, you will work through the main grammar concepts discussed in the lesson.
 `C. Workbook/Parsing`| Brief Hebrew word activities to reinforce the grammar concepts.  In Unit 3, the focus shifts to what is called "parsing" of verbs.  Verb parsing means identifying the root, stem, person, gender, number, and meaning of a verb.
 `D. Study Verses`| You will begin to translate from Hebrew to English. This component may not be easy at first but stick with it!  Although these verses are similar to the _Hebrew Quest_ Memrise modules, our goal for the `Study Verses` is translation and comprehension, not rote memorization.
`Worksheets`|Additional activities to reinforce learning (selected lessons) | 30-45
`Ruth Pursuit`|Similar to the "bag the letter" activity in the early lessons of  _Hebrew Quest_. You will identify examples of grammar concepts in Ruth Chapter 1 | 15-60
`Quest Quiz`|Self-assessment activity to measure your familiarity with the material for YOU to assess whether you are ready to advance in your quest to the next lesson.  No grades are recorded or granted in this course. There are no quizzes after Lesson 11. | 15-30
`Twelve Tribes Badges`, Unit Completion `Certificates`, and `Graduation`| Fun things to mark and celebrate the completion of various stages of your GRAMMAR Quest | 3-5
TOTAL |Depending on how fast you work:|2.5-6 hours per Lesson

Of course, some lessons will be more involved than others, and each of us works at a different pace. One of the beautiful things about a self-paced class is the speed and due dates are not set by a course syllabus.   With a self-paced class, YOU are in control!

::: {.box .light}
DON'T BE OVERWHELMED!  YOU GOT THIS!

Use the `Course Checklist` to help keep you organized and do a little bit at a time. Instructions for accessing this are on the Quick Start page. If you haven't already downloaded it, you can get it [here](https://docs.google.com/spreadsheets/d/1t0C7JlygyUqgF_aQWbhq7h3s_VDn0VuvISJn5mp-LdE/copy){target="_blank"} 
:::

Also, for those seeking additional translation practice and exposure to the Hebrew Bible, we have an OPTIONAL _Hebrew Quest_ Study Passage Track beginning with Lesson 13.  You will read through the passage, compose a translation, then watch (or re-watch) the _Hebrew Quest_ video where Izzy walks us through the passage.  There is more information on this in the Unit 3 introduction.

Lastly, you might be encouraged by this article on [conquering the Fog](./images/00_Fog_Article.pdf){target="_blank"}.  The "Fog" is a term coined by Dr. Bill Mounce, author of _Basics of Biblical Greek_.  "Fog" describes the feeling that you aren't making any progress in learning a Biblical language when you actually are making TREMENDOUS progress!

## Information Boxes {-}

As you work though the Hebrew GRAMMAR Quest guidebook, you will notice several different information boxes uses to call out various topics.

::: {.infobox .sound}

<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/00.infoboxes.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

::: {.infobox .map}
QUEST BOX

* The Lesson Itinerary - learning objectives
* Ruth Pursuit, Hebrew Quest Study Passages, and other "Quest" related topics
:::

::: {.infobox .stop}
STOP BOX

* Equipment Check - concepts from previous lessons you must know before starting the next lesson
* Other "Dont's"
:::

::: {.infobox .light}
LIGHT  BOX

* A critical point not to be missed
* Other "Do's"
* You will often want to MEMORIZE the concepts in a LIGHT box (but note the memory work will be done in Anki)
:::

::: {.infobox .info}
INFO  BOX


Additional information that is good to know
:::

::: {.infobox .caution}
CAUTION  BOX

A potential pitfall, such as a concept that could be easily confused with another
:::

::: {.infobox .sound}
AUDIO BOX

Either the section narration, read by Chris Flanagan, or the "First Thought" Hebrew verse, read by Izzy Avraham.

* Press the play button to start the audio and make sure your device's volume is at a comfortable level
* You can press one of the speed buttons to play the audio at that speed (2.5x - 0.5x) 
:::

We also have footnotes^[Citations and parenthetical/non-essential points will be included as footnotes throughout each lesson, if indicated.]


  
## Course Resources {- #optional_resources}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/00.resources.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

REQUIRED: 

* Other than being a subscriber to Holy Language Institute, you will not need to purchase or obtain anything for this course (unless you want to)
* You will need a computer with internet access, a free Google account to open and complete documents and exercises, the free Anki desktop software to do the flashcard activities, and a pen or a pencil to complete writing worksheets

OPTIONAL:

Below are additional resources, some of which are free and some paid:

* Free of charge
  * Thanks to his extremely generous reuse license, we have leveraged many of the worksheets and content from [Dr. John Beckman](https://hebrewsyntax.org/bbh2new/){target="_blank"}.  If you want more detail into any lesson, you may wish to refer to his videos and handouts.  Everything on [his site](https://hebrewsyntax.org/bbh2new/){target="_blank"} is free.
  * Dr. Bill Mounce has study guides available for each Chapter of _Basics of Biblical Hebrew_
    * In most cases, these will not add much to the lessons in Hebrew GRAMMAR Quest, but some students might find them valuable
    * For Chapter 1, click [http://hebrew.billmounce.com/BasicsBiblicalHebrew-01.pdf](http://hebrew.billmounce.com/BasicsBiblicalHebrew-01.pdf){target="_blank"}; for other chapters, change the `01` in the URL to the chapter number you are seeking^[Except Chapter 4, which for some reason, is not available.]
* Paid
  * Anki's iOS app requires a one-time purchase through the Apple store of $25.  If you have an iPhone, we believe this is a relatively inexpensive investment in your Hebrew journey, but the decision to purchase is entirely up to you.  You would be able to complete the course without purchase of the app.
  * To further supplement your studies, you may wish to purchase the _Basics of Biblical Hebrew_ textbook or any of the accompanying resources
    * [Basics of Biblical Hebrew Textbook](https://www.amazon.com/gp/product/031053349X/&tag=holylanginst-20)
    * [Basics of Biblical Hebrew Workbook](https://www.amazon.com/gp/product/0310533554/&tag=holylanginst-20)
    * [Basics of Biblical Hebrew Laminated Reference Card](https://www.amazon.com/gp/product/031026295X/&tag=holylanginst-20)
    * We would appreciate it if you would use one of the affiliate links, which allows Holy Language Institute to receive a small commission
    
    
::: {.box .caution}
You might want wait and see how you are doing with Hebrew GRAMMAR Quest through about Lesson 7 or 8 before deciding to purchase the iOS app or any of the books
:::

## Report an Issue {- #report_issue}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/00.reportissue.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


Please do not hesitate to report any errors, omissions, or improvement opportunities.  In fact, we'd rather hear about mistakes sooner rather than later! Feedback is anonymous.  

::: {.box .stop}
If you have a specific question about the content or are stuck on a concept, please use the [Get Help](#get_help) question form instead of the `Report an Issue` form.
:::

<div class="containerLet">
<iframe class="responsive-iframe" src="https://docs.google.com/forms/d/e/1FAIpQLSf3obLnGzJQ6d7Rtyy2YXDln3g-kJWCY-4IlRLE_mnFuWv2AQ/viewform?embedded=true" frameborder="0"></iframe>
</div>

[Open form in new window](https://forms.gle/qhBToGubVgmjdFbx6){target="_blank"}

## Ask a question {- #get_help}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/00.gethelp.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


While this is a self-paced course with no formal instructor or teaching assistant, we want to provide a way for you to get help and ask a question should you get stuck.

We request that before you submit a question, you read through the lesson a couple of times, then attempt to do the Anki cards for that lesson.  Sometimes by doing this, things will "click" on their own.  If you are still unclear, we are here!

Use the form below to ask a question. Please note, we are staffed by volunteers, so please allow a few days for us to research and get back to you.  

::: {.box .stop}
If you have general feedback or wish to report an issue, please use the [`Report an Issue`](#report_issue) form instead of the `Get Help` form. 
:::

<div class="containerLet">
<iframe class="responsive-iframe" src="https://docs.google.com/forms/d/e/1FAIpQLSdWJc7ri0andmyu70D1USeDRtbsrHLaYLNrs0rvI2qBJx-yEg/viewform?embedded=true" frameborder="0"></iframe>
</div>


[Open form in new window](https://forms.gle/tNsvwrhci3nGkvvV6){target="_blank"}

<!--chapter:end:00d-help.Rmd-->

# (PART) Hebrew Grammar Foundations {-}

<!--chapter:end:01a-Part_I_header.Rmd-->

# The Hebrew Aleph-bet {#alephbet}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/01.intro.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

> To comprehend Biblical Hebrew, we must have the Aleph-Bet memorized

<br>

<img src="images/alephbet_multi.png" width="400pt" style="display: block; margin: auto;" />

This graphic shows the evolution of Hebrew. Top to bottom: proto-Canaanite (~1600 BCE), paleo-Hebrew (~900 BCE), Rashi (1500 CE), Ketav Stam (used in Torah scrolls and other formal documents), contemporary block, and modern cursive. This course will use the contemporary block style. 

In this initial lesson, we will meet the Hebrew Aleph-Bet.  The letters are like a family.  Like a family, there can be unique dynamics (including not always playing nice with each other!).  This lesson will take a look at some of those dynamics.


::: {.infobox .map}
**LESSON ITINERARY**

1. Meet the Hebrew Aleph-Bet
1. Understand that Hebrew is written and read from RIGHT to LEFT
1. Identify the group of five letters that have final/Sofit forms
1. Identify the group of six letters that can take a Daghesh Lene
1. Identify the group of four "guttural" letters that cause significant changes in spelling and punctuation (and the one additional letter that sometimes acts as a guttural)
1. Identify the group of ten letters that _sometimes_ behave differently in limited circumstances
1. Differentiate among "look-alike" letters
1. Note differences between "Seminary" and "Sephardic" pronunciation

:::


::: {.infobox .stop}

**EQUIPMENT CHECK**

If you are eager to jump right in with Lesson 1, we understand.  We are also excited for you to start!

"Equipment Check" is where we will pause before each lesson to make sure you have the right tools and supplies in your backpack before heading on the next phase of your Quest.  In future lessons, we will want to make sure you understand specific concepts before continuing.

For Lesson 1, BEFORE CONTINUING, MAKE SURE YOU HAVE COMPLETED ALL OF THE `PRELIMINARY` TASKS ON YOUR `COURSE CHECKLIST` AND ARE READY TO GO WITH `ANKI`!

:::

## First Thought {-}
::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.Deu3203.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

::: {.box .light}
* Listen to the verse in Hebrew
* Practice speaking until you can pronounce just like Izzy 
  * You can slow the audio down if needed
:::

### <span class="he">שֵׁם יְהוָה אֶקְרָא</span> {-}

*For I proclaim the name of Adonai  (Deuteronomy 32:3)*  

As you undertake this study, pray for this Grammar adventure to be fruitful.  May God use your growing knowledge of Hebrew as an instrument to advance His Kingdom, and may you never cease to proclaim His Name! 


<div class="figure" style="text-align: center">
<img src="images/01_Cove of the Sower from top, tbs76029303.jpg" alt="Cove of the Sower - suggested location where Yeshua proclaimed the words of Adonai to the crowd in Mark 4:1. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="600pt" />
<p class="caption">(\#fig:unnamed-chunk-8)Cove of the Sower - suggested location where Yeshua proclaimed the words of Adonai to the crowd in Mark 4:1. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>

<small>Note: acoustic tests performed at this location have confirmed that a person in a boat in the middle of the cove can _easily_ be heard without amplification by people sitting on these rocks several hundred feet up the embankment, and Yeshua didn't have to deal with road noise!  A description of the acoustics study can be found in the following article: Crisler, B. "The Acoustics and Crowd Capacity of Natural Theaters in Palestine." Biblical Archaeologist, vol. 39, no. 4 (1976):128–41.</small>


## The Hebrew Aleph-Bet {#consonants}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.1.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


<img src="images/alephbet.png" width="800pt" style="display: block; margin: auto;" />

Almost every other grammar book would start with a lengthy description of each letter, how to write it, and how to pronounce it.  We omit this because this is (and much more!) covered in detail in [_Hebrew Quest_ Lessons 2-11](https://holylanguage.com/letters.html){target="_blank"}.  

* Hopefully, you have already watched these foundational _Hebrew Quest_ lessons; if not, click the link above!  
* If you need a refresher on identifying each of the letters, there will be cards on the Aleph-Bet in your `Anki` deck for Lesson 1.

The points below and on the following pages will provide some foundations. This way, your grammar journey gets started in the right direction.

* All letters you see in the picture of the Aleph-Bet above are classified as "consonants."

* Whereas English has the vowel letters (A, E, I, O, U) as a core part of the Aleph-Bet, Hebrew treats vowels differently

* א and ע are not vowels but silent consonants; in Sephardic pronunciation, they take on the pronunciation of their associated vowel (if there is one)

* We'll talk about vowels in Lesson 2

::: {.box .stop}
Have you completed _Hebrew Quest_ Lessons 1-11?

If not, we encourage you to stop here and move over to _Hebrew Quest_ to complete the Alephbet lessons.

Besides learning the letters, you will learn deeper meanings each letter teaches us from a spiritual perspective.
:::

## Aleph-Bet Memory Song

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.2.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

As needed, sing along with this video by Dr. John Walton of Wheaton College to help you memorize the Aleph-bet^[Unfortunately, YouTube won't let us embed this video on this page]:

[Open Aleph-Bet video in new tab](https://www.youtube.com/watch?v=hIEB8bpJZhY&feature=youtu.be){target="_blank"}

<img src="images/01.2-alephbet.png" width="500pt" style="display: block; margin: auto;" />

## Hebrew is written and read from RIGHT-to-LEFT {#right_to_left}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.3.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

Note the front of a Hebrew book is the back of an English one:

<img src="images/right_to_left.png" width="300pt" style="display: block; margin: auto;" /><img src="images/hebrewbook.png" width="300pt" style="display: block; margin: auto;" />

* To our western eyes, this looks "backward" (but Israelis would say _we_ are reading backward!)

* When reading Hebrew, always start at the "back" and go from RIGHT to LEFT

*****

See **Hebrew Quest** discussion on Right to Left:

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/4xKQSvRvmN8?start=108" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>



<!-- 1.4 -->
## Five "KiMNePaTZ" letters have different final forms {#sofit_letters}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.4.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

<img src="images/kimnepatz.gif" width="800pt" style="display: block; margin: auto;" />

* Hebrew does not have capital letters the way English does, but a somewhat similar concept is five letters take what are called “Final” or “Sofit”^[_Sofit_ is just the Hebrew word for final] forms when they appear at the END of a word
    * Those letters are in red text above
* The letter Kaf כּ is the first letter in the Aleph-bet with a sofit form
    * The final form is named Kaf Sofit ך
    * Same for Mem מ and Mem sofit ם and so on^["Final Kaf," "Final Mem," etc., are also terms you may hear.]
* The five letters that have these forms are Kaf, Mem, Nun, Pei, and Tsaddi: ך ם ן ף ץ
* You can remember the acronym, KiMNePaTZ, which is the made-up word you get when you string the five letters in a row
* The KiMNePaTZ sofit forms can look like other letters - your `Anki` work for this Lesson will give you practice with identifying look-alike letters



## Activity: Practice Letter Writing  {- #worksheets-1}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.activity_letters.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
::: {.box .info}
Depending on your existing familiarity with the Aleph-bet, you may wish to review the `Lesson 01 A. Vocab` module in Anki before attempting the worksheet.   In fact, these flashcards are borrowed from _Hebrew Quest_! 
:::

* Memorizing the Alephbet is essential
* Normally, Activities will be at the end of a lesson
* In this case however, we would ask you to stop right here and complete the writing activity - it will help you tremendously as you complete the remaining sections of Lesson 1
* Once you complete both parts of the activity, return here and continue the lesson

::: {.box .info}
* In Hebrew GRAMMAR Quest, we try to keep "brute-force memorization" to a minimum
* This way, if we are asking you to memorize something, you will know it's important!
:::

::: {.box .map }
YOUR QUEST (aka, instructions for the activity):

1. Practice writing the letters individually (letter by letter) using the [Letter Writing worksheet](./images/01_Letter_Writing_Worksheet.pdf){target="_blank"}
    * If you would like some tips on how to write the letters, you can use [this guide](01_Letter_Writing_Guide.pdf){target="_blank"} from Dr. Beckman.
    * As we've said before, we strongly encourage everyone to watch (or re-watch) the [_Hebrew Quest_ lessons on the Aleph-Bet](https://holylanguage.com/letters.html){target="_blank"}
    
2. On the reverse side of the worksheet (or on a separate piece of paper), practice writing the entire AlephBet, including the final/sofit forms, until you can do it at least ONCE entirely from memory. Be sure to cover up your previous attempts and any other reference materials.  

::: 

<!-- 1.5 -->
## Six "BeGaD KePHaT" letters take a mark called a Daghesh Lene {#daghesh_lene}
 
::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.5.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

<img src="images/bdgkpt.gif" width="800pt" style="display: block; margin: auto;" />

* Next, we need to learn the "BeGaD KePhaT" letters^[See also Lesson 3 of _Hebrew Quest_]
* The red and blue dots in the above letters are called **DAGHESH LENE**
* The Daghesh Lene is inserted into the middle of the consonant
* The Daghesh Lene affects the pronunciation of these letters 
    * "hard" if the Daghesh Lene present 
    * "soft" if not present
* At one time, all six of these letters had different pronunciations, but today in Hebrew as spoken in Israel, only three do
* These are the letters in blue above **<span class="he">בּ כּ פּ</span>**:
    * <span class="he">ב</span> has a "soft b" sound, in other words, a "v" sound, while <span class="he">בּ</span> has a "hard b" sound, in other words, a "b" sound
    * <span class="he">כ</span> sounds like the "ch" in "bach", while <span class="he">כּ</span> is "k" as in "kangaroo"
    * <span class="he">פ</span> is the "ph" (or "f") in "phone", while <span class="he">פּ</span> is the "p" in "pulley"
    * Since the letters without the Daghesh Lene want to be "lazy" - for example, a weak 'v' instead of a strong 'b'- our mnemonic for these is "BucK uP! You Lazy Letters!"
    * בּכּפּ = BKP, which with a little imagination can mean "BucK uP!"
      
::: {.box .caution}
* There are many other "dots" in Hebrew with various meanings - not all are Daghesh Lene marks
* The Daghesh Lene ONLY applies to Bet - Gimmel - Dalet - Kaf - Pei - and Tav 
    * If a dot appears in any other letter, it is NOT a Daghesh Lene
* We’ll dig deeper into the Daghesh Lene and its much more notable big brother, the Daghesh Forte, over the next several lessons.  Both play a big factor in studying and understanding Hebrew grammar.
:::

<!-- 1.6 -->

<!-- 1.6 -->
## We classify four consonants as **Gutturals** (and one additional consonant is a sometimes-guttural)^[In modern linguistics, these are called `glottals`] {#gutturals}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.6.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

<img src="images/gutturals.gif" width="800pt" style="display: block; margin: auto;" />

* There are four proper gutturals: Aleph, Hei, Chet, and Ayin (in red above)
* The letter Resh <span class="he">ר</span> (in orange above) is not formally a Guttural; but since it can’t decide whether to behave or not, sometimes we include Resh with the other Gutturals
* We like to say that the gutturals (and sometimes Resh) will be our trouble-makers because they tend not to play nice with the other Hebrew rules! 
    * The good news is the behavior of the Gutturals and Resh is entirely predictable
    * We will learn this over the next few lessons (and indeed, the rest of the course) 
* For now, memorize the group of four guttural consonants in red and Resh, the sometimes-guttural-like letter in orange.

::: {.infobox .info}
Learning how the gutturals behave and what spelling changes they cause is one of the most critical facets of Hebrew grammar.

It is core objective of this course.
:::

<!-- 1.7 -->


## We classify ten Hebrew letters as "SQiN eM LeVY" consonants

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.7.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

<img src="images/01_sqinemlevy_gif.gif" width="800pt" style="display: block; margin: auto;" />


* This is another group of letters that can behave differently
* They are called the _SQiN eM LeVY_ letters because of the made-up word that is formed by the letters:
    * S - <span class="he">שׂשׁסצ</span> the Sibilants (letters that make an S sound)^[The ז is also a sibilant, but as it turns out, it is not generally affected by the SQiN eM LeVY exception.]
    * Q - <span class="he">ק</span>
    * N - <span class="he">נ</span>
    * M - <span class="he">מ</span>
    * L - <span class="he">ל</span>
    * V - <span class="he">ו</span>
    * Y - <span class="he">י</span>
* We will save a discussion on exactly how this group (mis)behaves for another lesson
* For now, memorize which letters are the _SQiN eM LeVY_ consonants
    
<!-- 1.8 -->
## Look out for look-alike Letters {#look-alike-letters}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.8.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* Hebrew has many letters that can look similar, especially to someone just learning the Aleph-bet
* For example <span class="he">נ</span>, <span class="he">ג</span> and <span class="he">כ</span>; <span class="he">ס</span> and <span class="he">ם</span>; or <span class="he">ר</span>, <span class="he">ד</span>, and <span class="he">ך</span>
* The `Anki` deck will give you practice on distinguishing these.
* Also, in Hebrew Quest, when Izzy reviewed the Aleph-Bet in lessons 2-11, he talked about each letter’s "twin" and how to spot the difference 
* So again, if you haven't watched those lessons or if it has been a while, we encourage you to revisit those [letter lessons](https://holylanguage.com/letters.html). 

<img src="images/01.izzy_aleph.jpg" width="600pt" style="display: block; margin: auto;" />
<!-- 1.9 -->

## Sephardic versus Seminary Pronunciation {#pronunciation}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.9.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

<img src="images/vav.png" width="800pt" style="display: block; margin: auto;" />

* There are some notable differences between what we might call academic or "seminary^["Seminary Hebrew" is a term borrowed from Dr. John Beckman. We don't say "Seminary Hebrew" to be disrespectful; we only mean to differentiate between the two pronunciation types.]" Hebrew and "real-world" Hebrew spoken in Israel.  Seminary pronunciation is in red above, while Sephardic pronunciation is in blue.
    * Real-world Hebrew is based on Sephardic pronunciation^[There is also what is called Ashkenazi pronunciation, which is beyond the scope of this course.  It also has some different pronunciations.  Most notably, the letter ת is given an "s" sound at the end of a word, and "O" vowels are more prominent.  So שׁבּת (shabbat), would be pronounced "Shabbos" in Ashkenazi]
* We've already talked about how only three of the Daghesh Lene letters need to "BucK-uP"
* With "Seminary Hebrew," all six letters take on a soft pronunciation.
    * The <span class="he">ג</span> without the Daghesh Lene receives something like the GH in "aGHast." The <span class="he">ד</span> and <span class="he">ת</span> without the Daghesh Lene are closer to the English DH/TH like "this" 
* Another difference between Sephardic and Seminary pronunciation is how to pronounce <span class="he">ו</span> 
    * In academia, the consonant receives the "w" sound and is called "waw" (pronounced like the English "wow!")
    * In most non-academic circles, it receives the "v" sound and is pronounced "vav"
    * This is important because a lot of the resources that we will reference come from academia and thus will have the "w" pronunciation.  For example instead of "vav-imperfect", we will frequently see "waw-imperfect"
* There are also significant differences in pronouncing vowels, most notably the short a ("a" like "apple"; versus "ah" like "father")
* For the most part, Hebrew GRAMMAR Quest will follow the Sephardic pronunciation
* Lastly, since we are talking about pronunciation differences, will use "Adonai" or "the LORD" when we encounter the Covenant Name^[Please read Izzy's statement on the Covenant Name: "When I filmed Hebrew Quest I read God's Hebrew name as "Yahweh". This is a relatively common practice in academic circles and was also an expression of my personal love for God's holy name. Since then though I've encountered conclusive evidence that Yeshua and his disciples followed the Jewish tradition of saying "Adonai" instead of using the Sacred Name. It's my deep conviction that we should follow the example of Messiah and his apostles, so I've returned to saying "Adonai" (Hebrew for "the LORD") or "HaShem" (Hebrew for "the Name") instead of using the Sacred Name, and I encourage our students to do likewise." ]
    * Again, in some of the materials that we have leveraged from academic circles, you may see (or hear) the Covenant Name ("Ya---h") written out as this is common in those settings
    * We are taking a devotional approach

## Activity: Anki {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.anki.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

Congratulations on completing your first lesson!

Now we'll move into the Activities.  This is where you take what you learned above and put it into practice using `Anki`.  

* `Lesson 01 A. Vocab` - Learn (or relearn) the Aleph-Bet with Izzy
* `Lesson 01 B. Grammar` - Identify look-alike Hebrew letters
* `Lesson 01 C. Study Verses` - we won't be working on any Study Verses just yet, but we will learn some grammar shorthand that we will use when we get to Lesson 3.

Access Anki using your mobile app, desktop version, or [the web-based version (login may be required)](https://ankiweb.net/decks/){target="_blank"}


## Activity: Ruth Pursuit {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.ruth.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* This is a QUEST activity, similar to "bag the letters" from _Hebrew Quest_.  
* You can do this activity online using Google Docs or download/print and use physical highlighters.
* Click the link to open a [blank copy of Ruth Chapter 1](https://docs.google.com/document/d/1bcT1J-fcVmD1Zn5Jk2nj0560tEddcgtbYZLkwaVVuyE/copy){target="_blank"}
    * You may need to sign in with a Google account
    * You may wish to rename the document with the applicable lesson # as you will be reusing the blank document multiple times
* We strongly encourage you to go line by line through the passage and do not use the "Find" function in your word processor
    * Line by line will take longer, but you will learn more (even though you may think it's a waste of time because at this point you may not know much, if any, Hebrew.  Just go through the passage as best as you can; you may be surprised what sinks in!)

::: {.box .map} 
YOUR QUEST

1. Find ONE example of the following
    1. Identify the four guttural letters in Ruth chapter 1(pink)^[The color is to let you know what color the answer key will use, but feel free to highlight in any color, underline, change the font color, or otherwise identify anyway you like.]
    2. Identify the one half-guttural (red)
    3. Identify the six BeGaD KePHaT letters, both with and without the Daghesh Lene, for a total of 12 letters (green)
    4. Identify the five final/sofit forms (blue)
    5. Identify the 12 remaining consonants not included in the above categories (including both forms of ש)(yellow)
2. Find ALL examples of the names listed below (grey)
    * Ruth - spelled <span class="he">רוּת</span>; also "and Ruth" - <span class="he">וְרוּת</span>
    * Naomi - spelled <span class="he">נָעֳמִי</span> 
    * Bethlehem - spelled <span class="he">בֵּית לֶחֶם  </span>, also "from Bethlehem" - <span class="he">מִבֵּית לֶחֶם</span>
        * Our one word "Bethlehem" is two words in Hebrew: <span class="he">בֵּית</span> means "house of" and  <span class="he">לֶחֶם</span> means "bread"
    * Moab - spelled <span class="he">מוֹאָב</span>, also "Moabites" <span class="he">מֹאֲבִיּוֹת</span>^[As a taste of what is to come, this word מֹאֲבִיּוֹת has 1) defective spelling - notice how the Vav in מוֹאָב is not in מֹאֲבִיּוֹת? (Lesson 2), 2) propretonic reducticn - Compare the markings under the aleph in מֹאֲבִיּוֹת as compared to מוֹאָב. (Lesson 3), and a 3) Feminine plural suffix - Notice the Vav + Tav in מֹאֲבִיּוֹת are not present in מוֹאָב. (Lesson 4)], and "the Moabitess" <span class="he">הַמּוֹאֲבִיָּה</span>
:::


* Check your results against the [Ruth Pursuit #1 Answer Key](./images/01_Ruth_Pursuit_KEY.pdf){target="_blank"}

## Activity: Ruth Pursuit Translation Worksheet {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.ruthtranslate.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* With almost every lesson of Hebrew GRAMMAR Quest, we will be gradually building a translation of Ruth chapter one
* Instead of going sequentially, we will be working to identify concepts; so we may be skipping around the chapter a bit
    * We started with the simple words in the previous section
    * Towards the end of the course, you will be translating complex verbs
* We want you to keep track of your progress because, in Unit 4, you will know enough Hebrew to compose your own translation of Ruth 1
* After you finish each `Ruth Pursuit`, be sure to update the `Ruth 1 Translation` tab in your course checklist

::: {.box .map}
RUTH PURSUIT TRANSLATION WORKSHEET INSTRUCTIONS

* Download and open your `Hebrew GRAMMAR Quest Checklist` if you haven't already done so
* Find the `Ruth 1 Translation` tab
* As you identify complete words (Ruth, Bethlehem and Moab, not the individual letters), enter the English meaning next to the applicable word - note that the same word may occur multiple times in the passage
    * For example, next to each occurrence of <span class="he">מוֹאָב</span>, type the word `Moab`, for <span class="he">רוּת</span>, enter "Ruth" and so forth
    * You might want to make a note of the Lesson # (in this case "1") if you need to refer back to the lesson
    * There is also a column for any notes you wish to make
    * See examples for verse 1 in the worksheet
* You may use either your worksheet or the answer key to populate the Ruth Translation Worksheet
* Remember to update your translation worksheet after each lesson (we will not have `Ruth Pursuit Translation` section like this going forward; you can consider the translation work part of the `Ruth Pursuit`)
* This should be a fun and valuable exercise as you progress through Hebrew GRAMMAR Quest!
:::

## Activity: Quest Quiz {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/01.quiz.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

Again, congratulations on finishing lesson 1.  Here is our first `Quest Quiz`.  Remember to treat this as a self-assessment.  If you do well, you should be ready to progress to Lesson 2.  If not, you may need to go back and review some concepts from Lesson 1.  This is not for a grade, as there are no grades given in this course.

::: {.box .light}
Most of the time, you will want the `Quest Quiz` to be your very last activity in a given lesson.  
In other words after you have completed `Anki` so that all the lesson's cards are in the 'mature' stage, and all the other activities, come back here to your guidebook and attempt the `Quest Quiz` to make sure you are ready to move on to the next lesson.
:::

::: {.box .info}
* Most of the time, videos, quizzes, and other feedback forms will be embedded directly into the Hebrew GRAMMAR Quest Guidebook
* If you ever have issues with the video or form not loading, click the "View in new window" link that will appear below (or instead of) the embedded frame; this will open a new window in your web browser  
:::

<div class="containerLet">
<iframe class="responsive-iframe" src="https://docs.google.com/forms/d/e/1FAIpQLSeqHcE8PvfkOYbTu51cNO8sf-ln6CEnRrcTBUxM0EaeojSSsA/viewform?embedded=true" frameborder="0"></iframe>
</div>

[Open Quest Quiz #1 in a new window](https://docs.google.com/forms/d/e/1FAIpQLSeqHcE8PvfkOYbTu51cNO8sf-ln6CEnRrcTBUxM0EaeojSSsA/viewform){target="_blank"}

<!--chapter:end:01b-Alephbet.Rmd-->

# Hebrew Vowels 

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.intro.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

> To comprehend Biblical Hebrew, we must understand how words are formed and pronounced

As Izzy says in _Hebrew Quest_, “vowels are important!”  Even though our goal may not necessarily be to converse in Biblical Hebrew, hearing the language's sound aids our learning.  Vowels are what give a language its distinctive sound, and are what give words their meaning.  Consider the simple English words "bay," "boy," and "buy."  These words have identical consonants but mean very different things because of the different vowels.  It is the same with Hebrew.


<img src="images/02.Gen0109.png" width="600pt" style="display: block; margin: auto;" />

Above, you see Genesis 1:9.  The black font shows the text with no vowels. This is how the Hebrew Bible was originally written.  Over time, a group known as the Masorites developed the vowel notation we use today. These are the symbols in red.  These are usually under, but sometimes in the middle of or over the affected consonant. This vowel system intends to preserve the pronunciation passed down for centuries via the oral tradition. The Hebrew name for these diacritical dots and dashes is _nikudot_ which is the plural form of the word _nikkud_. The blue font shows additional cantillation marks, which synagogues use for chanting the verses.  These marks also show where the word's accent is.^[Image Source: Originally uploaded as en:File:Example of biblical Hebrew trope.svg on 04:27, 19 November 2006 (UTC) by en:User:SyntaxError55. ]  We will talk more about Cantillation marks in Unit 3.

::: {.infobox .map}
**LESSON ITINERARY**

1. Memorize vowels that are not vowel letters
1. Learn Vocal Sheva and Silent Sheva
1. Memorize the vowel letters
1. Meet "defective" and "plene" spelling 
1. Meet Dagesh Lene's twin, Dagesh Forte
1. Know the rule for a Dagesh Forte
1. Know that the Gutturals and Resh reject Dagesh Forte
::: 

::: {.infobox .stop}
**EQUIPMENT CHECK**

Before continuing, be sure you can recite the following groups of letters from memory.  These are concepts we learned in Lesson 1 and we just want to make sure we are ready to proceed to Lesson 2:

* All twenty-two consonants of the Hebrew Aleph-Bet 
* The six BeGaD KePHaT letters
* The five KiMNePaTZ letters
* The four guttural letters and the one sometimes-guttural letter
* The ten SQiN eM LeVY letters

:::

## First Thought {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.ps107024.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

::: {.box .light}
* Listen to the verse in Hebrew
* Practice speaking until you can pronounce just like Izzy
:::


###  <span class="he">הֵמָּה רָאוּ מַעֲשֵׂי יְהוָה</span> {-}

*They have seen the works of Adonai (Psalms 107:24)*

Reflect on the works of HaShem that you have seen!




<div class="figure" style="text-align: center">
<img src="images/02-Plain of Bethsaida with green grass, tb110206630.jpg" alt="Plain of Bethsaida - suggested location where 5000 saw the works of Yeshua and were fed (Mark 6). Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="600pt" />
<p class="caption">(\#fig:unnamed-chunk-19)Plain of Bethsaida - suggested location where 5000 saw the works of Yeshua and were fed (Mark 6). Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>

<!-- 2.1 -->

## _Hebrew Quest_ Vowels Lecture

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.1.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


View this 28:00 overview video from _Hebrew Quest_, then we will dig into the concepts in greater detail as we progress through the lesson^[As a reminder, you can speed up these videos by pressing the `gear` symbol, then adjusting the `Playback Speed`.].  You can disregard references to the "Hebrew Quest Student Manual" or "Essentials of Biblical Hebrew." Pertinent concepts have been incorporated into this Hebrew GRAMMAR Quest Guidebook. 

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
MlfwNNuWgto?start=0&end=1675&rel=0&showinfo=0autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/MlfwNNuWgto){target="_blank"}

* Start: 00:00
* End: 27:55

## Vowels that are not vowel letters: table

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.2.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

The table below lists the vowels that are not vowel letters.  This table MUST be memorized, including type and class as well as the name and symbol.

::: {.box .light}
* The Anki exercises will help us to commit this table to memory, so you don't necessarily need to drop everything and memorize the table below!
* Review the table and get familiar with it; then review the discussion points on the next slide
:::

* The letter בּ is provided as a placeholder
* Say the vowel _after_ saying the associated consonant^[We will learn that Hebrew loves to break the rules.  In the next lesson, we will learn about an exception to the "vowel comes after" rule, called the *furtive patach*.]. 
  * So, the first vowel example is "baw" not "awb."

<img src="images/02.vowels_not_letters.png" width="600pt" style="display: block; margin: auto;" />




## Vowels that are not vowel letters: discussion


::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.3.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

### Vowels come in three types: Long, Short, Reduced | Vowels come in five classes: A, E, I, O, U {-}

* We memorized the Aleph-bet in Lesson 1, but this knowledge is incomplete without vowels
  * Make sure you can say the name and know how to write the specific vowels
  * We also must know the vowel types (Long, Short, Reduced) and classes (A, E, I, O, or U) 
  * This will make your grammatical life much more comfortable in the future
*   Only **gutturals** take the "Hateph" vowels - 
  * To make it easier, we can pronounce all three Hateph vowels like the A in <u>A</u>muse
  * Hateph vowels are used because Gutturals reject Vocal Sheva
  * We label the reduced O class, "Hateph Qamets Hatuf"
    * Note that other grammars may label this vowel, "Hateph Qamets"
    * Our label, "Hateph Qamets Hatuf," reminds us that this is the reduced O class, not to be confused with the A class Qamets, even though the symbols are the same
    *   A future section will explain the difference between Qamets and Qamets Hatuf
    * For now, remember Qamets is Long A and Qamets Hatuf is Short O


## Vocal and Silent Sheva

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.4.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


* The Sheva can be tricky to grasp at first since vocal and silent Sheva are written the same. They have two very different uses^[Many academic textbooks will use the term "Shewa" instead of "Sheva". Both words mean the same thing.].
* Both are written as קְ
  * Both types of a Sheva mark the END of a syllable
* VOCAL Sheva is a REDUCED vowel but does NOT have a vowel Class
  *  Only non-gutturals can take a Vocal Sheva
      * Gutturals **reject** the Vocal Sheva and take the Hateph vowels instead
    * Pronounced like the A in <u>A</u>muse (same as Hateph Patach)
* SILENT Sheva is not a reduced vowel. In fact, it is NOT A VOWEL AT ALL
    * <u>Any</u> letter, including Gutturals, can take a Silent Sheva
    * Silent/No sound
* We will learn how to distinguish between the two kinds of Sheva in the next lesson

Type | Class | Hebrew | Name | Pronunciation
| :-: | :-: | :-: | :-: | :-: 
Reduced | No Class | <span class="he">בְּ</span> | Vocal Sheva | amuse
Not a Vowel | | <span class="he">בְּ</span> | Silent Sheva | No pronunciation

::: {.box .info}
The Sof Pasuq

* It is worth pointing out that in Hebrew Bibles, we may come across a mark that looks like a super-sized Sheva
* In English, we might say it looks like a giant colon mark (:)
* In Hebrew, this mark is called a Sof Pasuq, and it is used to mark the end of the verse
* Other than this, the mark has no meaning for us whatsoever.  You may ignore it when you encounter it, except that you will know that it always marks the end of a verse.
:::


## Vowels: that are letters: table

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.5.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* As Izzy mentioned in the _Hebrew Quest_ vowels segment, Hebrew has five consonants that can stand in for vowels
  * <span class="he">א, ע, ה, ו, י</span>
* א and ע simply take whichever applicable nikkud mark and are pronounced according to the vowel's sound
* ה, ו, י are slightly different, in that the consonant plus the vowel combines to form a single vowel unit
  * Note these vowels in the table below:
  
<img src="images/02.vowels_letters.png" width="600pt" style="display: block; margin: auto;" />


## Vowels that are letters: 

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.6.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::



### Vowel letters use a consonant plus a nikkud to form a vowel {-}



* Shureq is pronounced like Qibbuts (r<u>u</u>ler)
* Hireq Yod is pronounced like the i in mach<u>i</u>ne (compared to Hireq (Short I), which is pronounced like "b<u>i</u>tter)
* The other vowel letters are pronounced like the corresponding vowel - Qamets Hei is pronounced like Qamets, and so forth
* All vowel letters, except Seghol Hei, are LONG
* Yod and Vav vowels - י,ו 
    * Not only are these Long vowels, they have a unique feature is that they are "immune" from "propretonic reduction"
    * Therefore they are called "Unchangeable long vowels" or sometimes "Irreducible long vowels"
    * We'll explain what this means in the next lesson
* Hei Vowels - ה
    * Hei vowels can **ONLY** occur at the END of a word
    * Hei vowels are extremely common in Hebrew
    * The Hei vowels are Long (except for Seghol Hei) but they are not labeled as irreducible/unchangeable^[Strictly speaking, this point is irrelevant as a vowel at the end of a word would never reduce anyway. But, if you are ever asked "are the Hei vowels irreducible/unchangeable?", the answer is "no."]

::: {.box .caution}
* Do not confuse "vowel reducing" with "defective spelling"
* Although unchangable long vowels CANNOT reduce, they CAN be written defectively
  * For example, what was originally <span class="he">בּוֹ</span> becomes <span class="he">בֹּ</span>
* We will discuss defective spelling next
:::


## "Defective" and "plene" spelling {#defective_spelling}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.7.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


In "defective" spelling, letter vowels can sometimes drop their letter and take on the corresponding non-letter vowel. The meaning of the word does not change.

This is the word for "laws" showing both "plene" spelling and "defective" spelling.  Both spellings mean exactly the same thing: "laws" or "teachings".

<img src="images/defective.gif" width="400pt" style="display: block; margin: auto;" />

* Vowel letters commonly take "defective" forms^["Defective", in this sense, does not have a negative connotation.]
* Holem-Vav can drop the Vav and contract to Holem, as in the example above
* Hireq-Yod can drop the Yod and contract to Hireq
* Shuruq can drop entirely and contract to Qibbuts - this sometimes catches students by surprise - see caution box below.
* The Qamets-Hei <span class="he">ה ָ  </span>sometimes drops the final ה, leaving just the Qamets under the now-final letter.

::: {.box .caution}
An unchangeable long vowel written defectively is still an unchangeable long vowel


* A Qibbuts that is _not_ defective is a short vowel
* A Qibbuts that is a defective Shureq is an unchangeable long vowel

For now, do not be concerned about the difference.  As we progress in the course, you will see this in action.
:::

::: {.infobox .info}    
If any of this is confusing now, as we've said before, hang in there!  As you progress in your knowledge of Hebrew, you’ll start to develop a mental checklist when you encounter something that does not seem to follow the regular rules. Asking yourself, “Could this be a defective spelling?” will be one of those checklist items.
:::



## Transliteration Shorthand

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.8.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


* Most Hebrew grammar books include transliteration values
* While learning the transliteration scheme can help in some instances, our general position is that it can be an unnecessary distraction
* Where it can be useful is as shorthand
  * It would get wordy to write "Holem Vav" repeatedly
  * It's much less clutter to write the shorthand version based on transliteration: $\hat O$
  * Often, the vowel marks in isolation can be difficult to detect; compare ֹ  with $\hat O$
* As we move forward in the course, particularly in unit three, we will be making use of the vowel shorthand listed below

::: {.box .info}

* Short Vowels (no marking): $A$ for Patach, $E$ for Seghol, $I$, Hireq, $O$ for Qamets Hatuf, and $U$, Qibbuts
* Long Vowels that are not letters (bar): $\bar A$ for Qamets, $\bar E$ for Tsere, and $\bar O$ for Holem
* Reduced Vowels (breve): $\breve A$ for Hateph Patach, $\breve E$ for Hateph Seghol, $\breve O$ = Hateph Qamets Hatuf
* Vowel letters (hat): $\hat E$ = Tsere+Yod^[Formal shorthand for Tsere+Hei, Seghol+Hei, and Seghol+Yod is also $\hat E$ but for this course, we will only use $\hat E$ for Tsere+Yod.], $\hat I$ = Hireq+Yod; $\hat O$ = Holem+Vav^[Formal shorthand for Holem+Hei is also $\hat O$ but for this course, we will only use $\hat O$ for Holem+Vav.], $\hat U$ = Shureq, and Qamets+Hei = $\hat A$^[Formal shorthand for Qamets+Yod is also $\hat A$ but for this course, we will only use $\hat A$ for Qamets+Hei.]
* Additionally, we have  Vocal Sheva = $ə$, and $:$ for Silent Sheva^[Vocal Sheva has a "hurried" pronunciation, like the _a_ in _amuse_ or _Tina_. ə is the [international character for this sound](https://en.wikipedia.org/wiki/Mid_central_vowel){target="_blank"}. Silent Sheva has no pronunciation transliteration value.]

:::

* We will use this shorthand frequently when we discuss verbs
* We will review the values again as we get into Unit 3

## The Dagesh Forte Doubles the Consonant {#dagesh_forte}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.9.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


<img src="images/02.daghesh_forte.gif" width="500pt" style="display: block; margin: auto;" />
 

* Notice the dot in the שּׁ in <span class="he">הַשָּׁמַיִם:</span>
  * The dot is called a Dagesh FORTE - it is the Dagesh Lene's big brother
  * Since שׁ is not a בגד כפת letter, we know this *cannot* be a Dagesh Lene
* The letter with the Dagesh Forte both ends one syllable and begins the next syllable - in fact, a way to think of the Daghesh Forte is to call it the "doubling Daghesh"
* In <span class="he">הַשָּׁמַיִם:</span> is pronounced: `hash-sha-mayim`^[ `Mayim` is one syllable as we will learn in Lesson 3.  <span class="he">הַשָּׁמַיִם</span> means "the heavens."  From now on, we won't always provide a translation for every new word you encounter.  It's more important that you focus on the concepts.  You will have PLENTY of vocabulary work in Anki!]
* A similar word in English might be better = bet | ter
    * If we were to transliterate better into Hebrew hypothetically,  it might look like: בּטֶּר*^[The * means this is not a real Hebrew word, but we show it in this form for illustration.]
* Notice the syllable breaks in these words that have a Dagesh Forte:

<img src="images/02.forte.png" width="200pt" style="display: block; margin: auto;" />


## בגד כפת letters can take either a Dagesh Lene OR a Dagesh Forte

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.10.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* Any consonant (except for Gutturals and Resh) can take a Dagesh Forte, including a בגד כפת letter
    * The "Buck-up" letters will take the **hard** pronunciation regardless of a Dagesh Lene or Dagesh Forte - See the final word אַתָּה in the previous section

_Advanced tip:_ When you see a Dagesh Forte, it often means that another letter has disappeared^[Not entirely unlike the English apostrophe in words like _can't_.].  We will talk more about this later in the course.

::: {.infobox .info}
It's good to think of the Dagesh Forte as the "Doubling Dagesh" since it doubles the consonant and often changes a word's meaning.  

Conversely, we can think of the Dagesh Lene as the "Meaningless Dagesh" since it does not ever change a word's meaning
:::


## The Easy Dagesh Forte Rule {#dagesh_forte_in_bgdkpt}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.11.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

So how do you tell whether a Daghesh in a בגד כפת letter is Lene or Forte?

::: {.infobox .light} 
A Dagesh is a Forte if, and only if, it's preceded by a vowel that is not a Sheva^[Remember we said in the introduction that content in "light" information boxes should usually be memorized.  You will definitely want to memorize the Dagesh Forte rule.]
:::

That's it.  That's the rule^[Strictly speaking, there are exceptions.  We only have one in this course and we won't see it until Unit 4.].  

Quiz yourself with these examples (answers below):


* <span class="he">אַתָּה</span> = Is the Dagesh preceded by a vowel that is not a Sheva?^[Yes, a patach. Dagesh Forte]
* <span class="he">בְּרֵאשִׁית</span> = Is the Dagesh preceded by a vowel that is not a Sheva?^[No. Dagesh Lene]
* <span class="he">עַל־פְּנֵי</span> = Is the Dagesh preceded by a vowel that is not a Sheva?^[No. Dagesh Lene.  The "hyphen" looking mark is called a Maqquef.  It has the same function as the Hyphen does in English.]
* <span class="he">מַבְדִּיל</span> = Is the Dagesh preceded by a vowel that is not a Sheva?^[No, it is preceded by a Sheva. Dagesh Lene.]
* <span class="he">מִתַּחַת</span>  = Is the Dagesh preceded by a vowel that is not a Sheva?^[Yes, a Hiriq. Dagesh Forte]

## וּ is usually Shureq, but could be Vav with a Dagesh Forte

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.12.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

*   When a Vav has a Dagesh Forte, it looks like this וּ and, therefore, is identical to a Shureq וּ
*   It's surprisingly easy to tell the difference
*   A Shureq will _never_ have a separate vowel following or preceding
*   If the preceding consonant has a vowel, the וּ is a Vav with a Dagesh - that's the rule we just learned
*   Also, if there is an additional vowel either under or over the same letter, it can't be a Shureq as there are never two vowels in a row (and there is no diphthong involving a Shureq)
* Examples:
  * <span class="he">בוּ</span> = Shureq
  * <span class="he">בְוָּ</span> = Vav with Dagesh Forte - a Shureq would never take an additional vowel
  * <span class="he">בָוּ</span> = Vav with Dagesh Forte ־ the Rule of Sheva:  preceding letter has a vowel 
  * The last example is hypothetical only; generally, a Vav with the Dagesh Forte would have both a preceding vowel/Sheva AND an additional vowel/Sheva
  
::: {.box .info}

When you see <span class="he">וּ</span>, it is usually a Shureq

:::

* A similar situation happens with <span class="he">וֹ</span>
  * Consider the word, <span class="he>מִצְוֹת</span>
    * This is a consonantal Vav with a Holem, pronounced "vo"
    * The previous consonant has a Sheva ending the syllable; the next syllable cannot start with a vowel
    
    
## Gutturals and Resh reject Dagesh Forte {#gutturals_reject_dagesh_forte}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.13.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* We said in Lesson One that the Gutturals don’t play nice with the other Hebrew Rules, and this rejection of the Dagesh Forte is one of those ways
* A Hebrew collision like this means something has to give. . . and the gutturals tend to get their way.
* It's like they have a force-field shielding them from other Hebrew grammar rules!

<div class="figure" style="text-align: center">
<img src="images/02.reject.gif" alt="That's no moon.  That's a Guttural!" width="500pt" />
<p class="caption">(\#fig:unnamed-chunk-25)That's no moon.  That's a Guttural!</p>
</div>

* A large chunk of any Hebrew grammar course involves learning to resolve these guttural entanglements

::: {.box .caution}
MAPPIQ

* You may see הּ. This dot is not a Dagesh because we just learned that gutturals never take a Dagesh but a Mappiq. 
* A word-final ה is typically a vowel
* A Mappiq signifies that a word-final ה is a consonant, not a vowel
* We'll talk more about the Mappiq in Lesson 7
:::

## Lesson Conclusion and Activities {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.conclusion.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

Congratulations on completing the vowels lesson.  Make sure you memorize the vowel classes, the Dagesh Forte rule, and the guttural behavior.  

We're about halfway through the first stage of the course on Hebrew Grammar Foundations.  Keep going! You're doing great!  After you finish all of the activities for this lesson, you can claim the first of our `Twelve Tribes Badges`. 

Take a moment to review the section headings on the screen's left side before heading on to tackle the activities.


## Anki {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.anki.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


* `Lesson 02 A. Vocab` 
  * You will be presented with the vowel symbol and you are to identify the name, type, and class of each vowel
  * There are also "reverse" cards where you will be given the name, type, and class, and you are to identify the symbol
* `Lesson 02 B. Grammar`  - the grammar section will look at vowels as groups, as well as test you on some other topics presented in this lesson
* `Lesson 02 C. Study Verses`
  * Bible verses will arrive next Lesson
  * In this module, we will be learning common Hebrew names
  * Sound out the words using your knowledge of Hebrew consonants and vowels
  * As a general hint, with a couple of exceptions, the English names are pretty close to how they sound in Hebrew
  
Access Anki using your mobile app, desktop version, or [the web-based version (login may be required)](https://ankiweb.net/decks/){target="_blank"}

We can't stress enough how important the Anki activities are.  Anki is where your learning will take place. Try to do a little each day.

## Vowel Writing Worksheet {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.vowel_worksheet.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* Practice writing the vowels using the [Vowel Writing worksheet/drill](./images/02_Vowel_drill.pdf){target="_blank"}
* An answer key is on page two
* Repeat this worksheet until you can complete it correctly entirely from memory at least once
* A note on transliteration
  * Note that our course uses Capital letters, while the answer key uses lower case letters
  * It is more important to make sure the long, short, reduced, and vowel letter marks are accurate
  * You may ignore transliteration for:
    * Tsere Hei / Seghol Hei / Holem Hay
    * Seghol Yod


## Ruth Pursuit {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.ruth.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

::: {.box .map}
YOUR QUEST

1. Identify the four UNCHANGEABLE LONG vowels that use YOD in Verse 1 (blue)^[In most word processors, you may not be able to isolate the vowel to highlight it. Get as close as you can.]
2. Identify the two UNCHANGEABLE LONG vowels that use VAV in Verse 1 (Green)
3. Identify QAMETS HEI in Verse 1.  There is a TSERE Hei between Verses 5-10.  Can you find it?^[The other vowels that use Hei are less common, but we will see them when we discuss verbs.] (Purple)
4. Identify the three LONG vowels in Verse 1 (that are not part of a vowel letter) (pink)
5. Identify three of the five SHORT vowels in Verse 1 (that are not part of a vowel letter)^[We haven't learned to spot Qamets Hatuf yet, and Qibbuts does not appear in this passage] (red)
6. Identify the three REDUCED/HATEPH vowels, including Hateph Qamets Hatuf^[You should be able to make out the word that has the Hateph Qamets Hatuph].  They are in verses 2-4. (grey)
7. One of the more common verbs in the Tanach is <span class="he">וַיֹּאמֶר</span>, which means "(and) he said."     
  * Vav-Patach-**Yod**-Daghesh Forte --וַיּ to start a verb means "And he (did or was something)  
    * If we change the second consonant from a Yod to a **Tav**, we get --וָתּ, "and **S**he (did or was something).  
    * Thus, <span class="he">וַתֹּאמֶר</span> means "and she said."  
    * Challenge: Find the five instances of <span class="he">וַתֹּאמֶר</span> in Ruth Chapter 1^[In at least three of the cases, you should be able to figure out who is speaking.]  (yellow)  
:::

* [Blank copy of Ruth Chapter 1](https://docs.google.com/document/d/1bcT1J-fcVmD1Zn5Jk2nj0560tEddcgtbYZLkwaVVuyE/copy){target="_blank"}
* [Ruth Pursuit Answer Key #2](./images/02_Ruth_Pursuit_KEY.pdf){target="_blank"}
* Update your Ruth Translation worksheet with <span class="he">וַתֹּאמֶר</span> = "and she said"        

## Quest Quiz {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.quiz.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


<div class="containerLet">
<iframe class="responsive-iframe" src="https://docs.google.com/forms/d/e/1FAIpQLSeq_9Cy5IlAKDFy8nx9GNC3dfs5l5bJ_iX2FJ0Az7rPKXq5Jw/viewform?embedded=true" frameborder="0"></iframe>
</div>

[Open Quest Quiz #2 in a new window](https://docs.google.com/forms/d/e/1FAIpQLSeq_9Cy5IlAKDFy8nx9GNC3dfs5l5bJ_iX2FJ0Az7rPKXq5Jw/viewform){target="_blank"}

## Claim your `Twelve Tribes Badge`! {- #twelve-tribes-badge-1}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/02.twelvetribes.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

If you have completed **all activities** in Lessons 1 and 2, congratulations!  You may claim the first of our "Twelve Tribes" badges.  These are a fun way to commemorate your progress.  After you complete the form and confirm you have done the required activites, you will receive an email with a virtual "badge" along with some thoughts about what each of the Twelve Tribes represents from a spiritual perspective.  Be sure you are keeping your Quest Activities Checklist up to date as you complete each lesson and activity.

Use the form below to claim your Asher badge!

<div class="containerLet">
<iframe class ="responsive-iframe" src="https://docs.google.com/forms/d/e/1FAIpQLSeFujHNSMAZ5ZjJbNsr7pFJnma5RGwG-7StAR1uvevGe_5zvg/viewform?embedded=true" frameborder="0"></iframe>
</div>

<!--chapter:end:02-Vowels.Rmd-->

# Syllabification and Pronunciation

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.intro.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

> To comprehend Biblical Hebrew, we must know how syllables function


Initially, the Bible and other ancient documents were written without spaces.  In addition to vowels, the ancient scribes and readers organically adopted a system of syllables and accents.  They knew where one word ended and where the next began without needing to write it down.  

What we call "Hebrew grammar" is truly an exciting journey into the system of spoken and written Hebrew, which had its formation thousands of years ago!

::: {.infobox .map}
**LESSON ITINERARY**

1. Learn the two basic concepts of Hebrew Syllables
1. Learn the rules and terminology related to Hebrew Word Accents
1. Know the Three Rules for Recognizing Silent Sheva
1. Know the Four Rules for Recognizing Vocal Sheva 
1. Learn the primary Hebrew diphthong
1. Understand Vowels and Syllable Preferences
1. Learn three simple miscellaneous concepts: Qamets and Qamets Hatuf, Furtive Patach, Quiescent Alef
:::

::: {.infobox .stop}
**EQUIPMENT CHECK**

Before continuing, can you describe the following concepts?

* The vowels that are not letters, including their type (long, short, reduced) and class (a, e, i, o, u)
* The vowels that are letters, including which are the "irreducible long" type
* The difference between a Dagesh Forte and a Dagesh Lene
:::

Lesson 3 and Lesson 16 are the two most content-heavy lessons in this course.  For that reason, you must have your alephbet and vowels (including the vowel types) memorized.

Assuming you've checked your equipment as directed above, and everything is in tip-top shape for your Lesson 3 adventure, then you're ready to begin. Take your time.  Work through the written material, then do a little Anki work and see if it starts to click. 

If Anki is not making sense, then come back here and re-read the material again. Then go back to Anki.  If you find yourself getting frustrated, take a break, and come back to it later.  Continue to work through "the fog" that we talked about in the introduction

You absolutely must have the concepts from this lesson hard-wired before you continue to Lesson 4.  The good news is that once you get this lesson down, the ones that follow will be relatively straightforward.

In addition to all of these new concepts, the authors have also seen fit to introduce a full set of vocabulary words AND study verses beginning with Lesson 3.  So the overall workload will increase, starting with this lesson (but so will your knowledge of Hebrew!)

We're praying for you in advance as we tackle this section!  Now, go climb the mountain!



## First Thought {-}

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.Ps3202.mp3">
            Your browser does not support the
            <code>audio</code> element.
</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}

function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::



::: {.box .light}
* Listen to the verse in Hebrew
* Practice speaking until you can pronounce just like Izzy 
:::


###  <span class="he">אַשְׁרֵי אָדָם לֹא יַחְשֹׁב יְהוָה לוֹ</span>  {-}

*How blessed is the man to whom the LORD does not impute iniquity  (Psalms 32:2)*

Thank God for his blessings and meditate upon them.

<div class="figure" style="text-align: center">
<img src="images/03-Mount of Beatitudes and Sea of Galilee, tbs75369303 (2).jpg" alt="Mount of Beatitudes and Sea of Galilee - suggested location of Yeshua's eight blessings in Matthew 5:3-12. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="600pt" />
<p class="caption">(\#fig:unnamed-chunk-26)Mount of Beatitudes and Sea of Galilee - suggested location of Yeshua's eight blessings in Matthew 5:3-12. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>

## Hebrew Syllables {#syllables}

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.1.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}


function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::

There are two basic concepts when it comes to Hebrew Syllables:

::: {.infobox .light}

1. Every syllable begins with one consonant and has only one vowel
2. There are only open or closed syllables 

:::

<img src="images/03.syllable.png" width="200pt" style="display: block; margin: auto;" />

We see the two basic concepts at play in this simple word (pronounced "da-var" and means word, matter, thing):

* The two syllables each begin with a consonant and have one vowel
    * דָּ starts with the consonant Dalet and has one vowel, Qamets
      * This is also an example of an "open" syllable - open syllables end with a _vowel_, not a consonant
    * בָר starts with the consonant Bet and has one vowel, also a Qamets
      * This is an example of a "closed" syllable - closed syllables end with a _consonant_, not a vowel 
* If you need to know how many syllables are in a Hebrew word, count the vowels
    * Remember that vowel letters, such as the Hiriq-Yod, and Diphthongs we will see later in this lesson, count as a single vowel unit

## Hebrew Word Accents {#accents}

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.2.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}


function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::

::: {.infobox .info}
* Most frequently, Hebrew words are accented on the last syllable  
* If not, then the accent will be on the next-to-last syllable^[Later in the course, we will learn about a mark called a Maqqef, which is like a hyphen in English.  In Hebrew, the word to the right of the Maqqef technically does not have an accent.]
* Reduced vowels and Sheva never take an accent. If there is a word-final Sheva, the accent will be on the next-to-last syllable 
:::

Unlike English, Biblical Hebrew words are never stressed anywhere else^[Modern Hebrew has words (mostly borrowed from other languages) that don't always follow this rule].

<img src="images/03.accent_stress.png" width="500pt" style="display: block; margin: auto;" />

* The word on the left is stressed on the last syllable
* The word on the right (pronounced "SAY-pher" and means book, scroll, or document) is stressed on the next to last syllable
    * Whenever the accent is NOT on the final syllable, you may see a mark over the syllable to be stressed^[Hebrew also has a very elaborate system of [cantillation marks](https://en.wikipedia.org/wiki/Hebrew_cantillation){target="_blank"} that also serve to indicate where the accent of the word is. are used for chanting and singing.  A study of these marks is beyond the scope of this book.]

## Tonic, Pretonic, and Propretonic Syllables

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.3.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}


function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::

* We will encounter these specific terms for a syllable's position respective to the word's accent
* Let's use the plural of <span class="he">דָּבָר</span> to illustrate: <span class="he">דְּ ׀ בָ ׀ רִים</span>
    * The **Propretonic** syllable is two (or more) steps away from the accent = <span class="he">דְּ</span>
        * Notice how the vowel changed from the Qamets in <span class="he">דָּבָר</span> to a Vocal Sheva in <span class="he">דְּבָרִים</span>
        * This vowel shortening of the propretonic syllable is called _Propretonic Reduction_ and is extremely common in Hebrew
     * The **Pretonic** Syllable is the syllable immediately before the accented syllable = <span class="he">בָ</span>
    * The **Tonic** syllable is the one with the accent =<span class="he"> רִים</span>^[If there is a syllable AFTER the accented syllable, technically it is called "Posttonic," but you will not encounter this term for the remainder of this course.]
    
## Ultima, Penultima, and Antepenultima syllables

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.4.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}


function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::


Since the accent is not always in a fixed location, we sometimes will use other words that describe a syllable's position irrespective of the accent. 

  * _ultima_ = the last syllable
  * _penultima_ = the next-to-last syllable - this is also called the "penult" syllable
  * _antepenultima_ = the syllable(s) before the _penultima/penult_


## Rules for Silent Sheva {#s_sheva}

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.5.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::

Learn the three rules for differentiating a SILENT Sheva from a Vocal Sheva:

<large>A Sheva is SILENT when the previous vowel is short</large>

<img src="images/03.sheva-shortvowel.png" width="200pt" style="display: block; margin: auto;" />

<large>A Sheva is SILENT when the first of two consecutive Shevas _within a word_</large>

<img src="images/03.sheva-firstoftwo.png" width="200pt" style="display: block; margin: auto;" />

<large>A Sheva is SILENT when at the end of a word</large>

<img src="images/03.sheva-endofword.png" width="200pt" style="display: block; margin: auto;" />

::: {.box .map}  
THREE SILENT SHEVA CLUES  

1. The previous vowel is short
2. First of two consecutive Sheva in the MIDDLE of a word, __OR__
3. Word-final Sheva

:::


## Rules for Vocal Sheva {#v_sheva}

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.6.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}


function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::

Learn the four rules for differentiating a VOCAL Sheva from a Silent Sheva

<large>A Sheva is VOCAL when the initial Sheva in a word</large>

<img src="images/03.sheva-initialvocal.png" width="300pt" style="display: block; margin: auto;" />

<large>A Sheva is VOCAL when the second of two consecutive Shevas _within a word_^[A Sheva at the **end** of a word is **always silent**, even when it is the second of two consecutive Shevas.]</large>

<img src="images/03.sheva-secondoftwovocal.png" width="200pt" style="display: block; margin: auto;" />


<large>A Sheva is VOCAL when under a Dagesh Forte</large>

<img src="images/03.sheva-fortevocal.png" width="200pt" style="display: block; margin: auto;" />

<large>A Sheva is VOCAL after an unaccented long vowel</large>

<img src="images/03.sheva-unaccentedlongvocal.png" width="200pt" style="display: block; margin: auto;" />

This one may seem random, but it is relatively common with _long_ vowels in a propretonic position^[These vowels often but do not always reduce. Unchangeable long vowels will never reduce.]  The word above is not kōṯ-vim but kō-ṯᵉ-vîm.


::: {.box .map}  
FOUR VOCAL SHEVA CLUES  

1. Word-initial Sheva
2. SECOND of two Sheva within a word
3. Under a consonant with a _Dagesh Forte_, __OR__
4. After an unaccented long vowel  
:::




## Hebrew Diphthong = Accented Patach-Yod-Hireq {#diphthong}

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.7.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}


function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::


<img src="images/03.diphthong.png" width="500pt" style="display: block; margin: auto;" />

* The diphthong is a single vowel unit, which means it is only one syllable
* We do not pronounce the word on the right above as "BUY-it," but monosyllabic, more like "BITE"^[With this said, "buy-it" makes a handy mnemonic for remembering this word means 'house' - when you see a nice house you want to "buy it." There are several look-alike words.]
* The word on the left is not "sh-MAY-im," but it sounds more like "sh-MIME"

::: {.box .light}
Remember "Accent+Patach+Yod+Hireq" as the main Hebrew Diphthong:  <span class="he">יִ ַ֫</span>
:::

Qamets-Yod-Vav is another Diphthong that you'll see in Lesson 9.  It's the pronoun suffix ending for "his" or "him."

* <span class="he">אֵלָיו</span> (to him) pronounced eLAV
* <span class="he">פָּנָיו</span> (his face) pronounced paNAV

There is scholarly disagreement as to whether (vowel)+Yod are vowel letters or diphthongs.  <u>Basics of Biblical Hebrew</u> treats them as vowel letters.




## Vowels and Syllable Preference {#vowel_pref}

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.8.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}


function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::


::: {.box .light}
Memorize this table:

Syllable | Tonic | Pretonic | Propretonic
| :--: | :--: | :--: | :--:
Open  |  SHORT | LONG | REDUCED
Closed | LONG | SHORT | SHORT

:::

* Tonic syllables PREFER the listed vowels but can take any type
* Pretonic syllable REQUIRE the listed vowels
* Propretonic syllables
  * Closed REQUIRES Short
  * Open REQUIRES reduction from a long vowel to Vocal Sheva (or Hateph if guttural), _except_ when there is an unchangeable long vowel
* Remember <span class="he">דָּבָר</span> and <span class="he">דְּבָרִים</span>
    * The vowel preference table explains why the vowel under the Dalet changes from Qamets in the Open/Pretonic to Vocal Sheva (reduced vowel) in the open propretonic when the plural suffix is added
    * This is called "_propretonic reduction_" - you will encounter this topic frequently
  * As we saw with <span class="he">כֹּתְבִים,</span> unchangeable long vowels that are written "defectively" will not reduce - at their essence, they are still unchangeable
  
::: {.box .caution}  
PAUSAL FORMS

* A notable exception to these preferences is called the "pausal form"
  * This is where a short vowel can become long (for example קָטַל becomes קָטָל) if the word is located at a certain point in a sentence
  * A rough approximation in English would be words concluding with a comma
* Pausal Forms are generally an intermediate Hebrew topic, but it's good to be aware of when you encounter spellings that don't seem to mesh with the vowel/syllable table

:::

## Qamets Hatuf, Furtive Patach, Quiescent Aleph {#misc_vowels}

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.9.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}


function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::

The next three sections will examine these special situations

## Qamets Hatuf

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.10.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::


::: {.infobox .light} 
Qamets Hatuf ONLY occurs in a Closed AND Unaccented syllable

<img src="images/03.qametshatuf.png" width="200pt" style="display: block; margin: auto;" />
:::

* Metheg mark
  * There are many instances where the vowel could be a short Qamets-Hatuf vowel in a closed syllable, or the long Qamets, A-class vowel in an open syllable
  * When this ambiguity occurs, some printings will print a small vertical line called a Meteg בָּֽ.^[Unfortunately, many Tanachs DO not differentiate.]  The Meteg tells you the vowel is the **long, a-class**
  
<img src="images/03.meteg.png" width="100pt" style="display: block; margin: auto;" />

::: {.box .info}
QAMETS OR QAMETS HATUF  

* The A-class is FAR more prevalent
* Nouns such as <span class="he">חָכְמָה</span> that have the pattern (Qamets mark)+Sheva+Qamets+Hei _TEND_ to be O-class
* You may know a word from your vocabulary that has a Holem, such as <span class="he">כֹל</span>
  * When you encounter that same word in its shortened form, <span class="he">כָל־</span>, the vowel will be shortened O-class
  * This is usually the Construct form, which we will study in Lesson 10
:::


## Furtive Patach

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.11.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::

::: {.infobox .info} 
Furtive Patach under final ח or ע is said BEFORE the guttural letter and is not a full vowel

<img src="images/03.furtivepathach.png" width="100pt" style="display: block; margin: auto;" />
:::

The Furtive Patach is a significant exception to just about everything else we've discussed related to vowels and syllabification:

  * The vowel is pronounced *before* the guttural - so the above word is **Ruach**, not "rucha"
  * The Furtive Patach is not a full vowel and is not counted in syllabification 

## Quiescent Aleph

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.12.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::

::: {.infobox .info} 
Quiescent Aleph is silent. It is neither a consonant nor a vowel

<img src="images/03.quiescentaleph.png" width="100pt" style="display: block; margin: auto;" />
:::

* When you see an Aleph with no vowels, it is acting as a silent letter
    * English has all kinds of silent letters, like the 'p' in receipt - the Quiescent Aleph works the same way
    * In terms of syllabification, the Aleph is neither a vowel nor a consonant, so it doesn't count at all - it is just an extra letter
    
## Lesson Conclusion and Activities {-}

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.conclusion.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::

Congratulations on getting this far! We realize that there are a lot of heavy concepts you face in this Lesson.

Some of you may try to read this lesson then do the Anki work (perhaps repeated a few times), and you still aren't getting it.  The Fog isn't clearing.  If this is the case, and you want a more in-depth lecture covering this material, we recommend [Dr. John Beckman's hour-long YouTube Lecture on lesson 3](https://www.youtube.com/watch?v=AY7KAsD4fZg&feature=youtu.be){target="_blank"}

For this lesson, we introduce two new activities that correspond with the official launch of `Vocabulary` and `Study Verses` you will see in `Anki`.

### Introduction to Video Warm-ups {-}

* On the next two pages are videos of the vocabulary words and then the study verses
* Practice speaking the word/verses aloud, following along with Izzy 
* You may not know what the words mean yet, and that's fine (that's where Anki comes in)
* Consider this some "syllabic stretching" before you do your full Anki workout!

Then after watching these, go ahead and jump into `Anki`.

* `Lesson 03 A. Vocab` - This is our first lesson with the <u>Basics of Biblical Hebrew</u> vocabulary list
* `Lesson 03 B. Grammar` - This module will reinforce and expand on the major points of this lesson
* `Lesson 03 C. Study Verses`
  * This is also our first lesson using the <u>Basics of Biblical Hebrew</u> study verses
  * With `Study Verses`, our goal is to incorporate the immersive learning aspects of _Hebrew Quest_
    * We want to expose you to Hebrew, even though you may not fully understand all the rules at this stage
  * The translation may be quite difficult at first
    * We encourage you to use a Dictionary (such as [this one](https://holylanguage.com/resources/Pocket-Hebrew-Dictionary-Feyerabend.pdf){target="_blank"}) to help you when you come across unfamiliar words
    * You can also edit the card and add your own hints to remember certain words
    * Other dictionaries [are available here](https://holylanguage.com/resources-dictionaries.php){target="_blank"}
    * To help with this, for Lessons 3-10, longer verses will be divided into multiple sections
  * It may take you SEVERAL attempts before you can select `Good`
  * Be patient and stick with it - you'll get it!
  * By the end of the course, you will learn close to 500 verses in Hebrew
  
::: {.box .info}
Your vocabulary and understanding will grow if you look up `study verses` words in a dictionary before revealing the answer
:::

## Word Warm-up {-}


<div class="container">
<iframe class ="responsive-iframe" src="https://www.youtube.com/embed/h0Ni1_Zya2U" frameborder="0"></iframe>
</div>
[Click to open `Word Warm-up` video in a new tab](https://youtu.be/h0Ni1_Zya2U){target="_blank"}

## Verses Warm-up {-}

* Over the entire 35-lesson course, you will learn to translate almost 500 Hebrew Verses.  The most extraordinary journey begins with a single step.  You are now about to take that step!

<div class="container">
<iframe class ="responsive-iframe"  src="https://www.youtube.com/embed/9IkIvWPArlA" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/9IkIvWPArlA){target="_blank"}
  
## Ruth Pursuit {-}

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.ruth.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::

::: {.box .map}
YOUR QUEST  

1. Identify all Tetragrammaton examples, which we pronounce "Adonai" when we encounter it in Scripture.  There are six instances of the Name. Also, <span class="he">שַׁדַּי</span> is another name for God.  It means "Almighty."  Find two examples of this name. (Blue)
2. In verse 16, highlight, <span class="he">"עַמֵּךְ עַמִּי וֵאלֹהַיִךְ אֱלֹהָי"</span> in green. This is the famous verse, "your people (will be) my people, and your God, my God."  One of your vocabulary words is <span class="he">אֱלֹהִים</span>. In the last two words of what you just highlighted, you can still see the core portion of <span class="he">אֱלֹהִים</span> present.  Begin to notice how Hebrew uses different suffixes to denote "your" and "my."
3. In verse 1, find one Sheva that begins a word and one Sheva that concludes a word. (Yellow). Which one is a silent Sheva, and which one is the vocal Sheva?
4. Find the Quiescent Aleph in verse 1 (pink)
5. Find the Hebrew words for Elimelech, Machlon, Chilion, and Judah in verses 1-7. Chilion has the prefix "וְ" which means "and." (gray)
6. For personal reflection, open an English translation side-by-side with your Hebrew version of Ruth 1.  Note how the foreigner Ruth uses both <span class="he">אֱלֹהִים</span> and the Tetragrammaton in verses 16 and 17, respectively.  Why do you think this might be? Would you say the names are used interchangeably, or do you think there is a deeper purpose?  May we always seek HIM, just as you have done in this activity!

:::

* [Blank copy of Ruth Chapter 1](https://docs.google.com/document/d/1bcT1J-fcVmD1Zn5Jk2nj0560tEddcgtbYZLkwaVVuyE/copy){target="_blank"}
* [Ruth Pursuit Answer Key #3](./images/03_Ruth Pursuit KEY.pdf){target="_blank"}
* Be sure to update your `Ruth Pursuit Translation` worksheet with this lesson's words.  We encourage you to use "HaShem" or "Adonai" for the Tetragrammaton.


## Quest Quiz {-}

<div class="containerLet">
<iframe class="responsive-iframe" src="https://docs.google.com/forms/d/e/1FAIpQLSfCy3m3L8z1a5EjEMtEBVWjoci-JvWfYzUVEIpnQHIgGwvu1g/viewform?embedded=true" frameborder="0"></iframe>
</div>

[Open Quest Quiz #3 in a new window](https://docs.google.com/forms/d/e/1FAIpQLSfCy3m3L8z1a5EjEMtEBVWjoci-JvWfYzUVEIpnQHIgGwvu1g/viewform){target="_blank"}


## Request your `Unit 1 Completion Certificate`! {-}

::: {.infobox .sound}
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03.certificate.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
:::

If you have completed **all activities** in Lessons 1, 2, and 3, you may claim the first of our `Unit Completion Certificates`.

::: {.box .caution}
* Note that the Anki Requirement for the `Unit Completion Certificate` is different from the `12 Tribes Badges` requirement.
* You must submit a screenshot showing that all cards are **MATURE**
  * No cards may be "New," "Young," "Suspended," or "Buried"
  * From the Anki manual, ["A mature card is one that has an interval of 21 days or greater."](https://docs.ankiweb.net/#/stats?id=types-of-cards){target="_blank"}
* See the `Hebrew Grammar Quest Checklist` for additional information
:::

[Please open and submit the Unit Completion Certificate Request form in new window](https://forms.gle/hkHMebEtNi61waidA){target="_blank"}


<!--chapter:end:03-Syllabification.Rmd-->

# (PART) Nouns, Adjectives, Pronouns {-}

<!--chapter:end:04a-Part_II_header.Rmd-->

# Introduction to Unit II {-}


::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03b.unit2intro.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

Congratulations again on completing unit 1!

* In Unit 1, we covered the foundational elements of Hebrew 
    * Consonants
    * Vowels, Sheva, and Dagesh Forte
    * Syllabification
    * Make sure you are relatively comfortable with these concepts before moving on to Unit 2 (and if you've been keeping up with your Anki work, this should be no problem for you!)
* Now in Unit 2, we will use those building blocks from Unit 1 to form nouns, prepositions, and adjectives
* In units 3 and 4, we will transition to verbs

<large>Changes for Unit 2</large>:

* _Hebrew Quest_ Videos
    * If you recall from the Introduction, we described Hebrew GRAMMAR Quest, Lessons 4-35 as the expanded edition of the original _Hebrew Quest_ grammar overview lessons (13-15) - you are now about to embark on that expanded edition!
    * For Unit 2, each lesson will have one (sometimes more than one) clip from the grammar lessons of _Hebrew Quest_
    * You can ignore any references Izzy makes to the "Hebrew Quest Student Manual" or the "Essentials of Biblical Hebrew" book
    * As we talked about in the Lesson 3`Word Warm-up` video, you can speed up or slow down the video speed by clicking the gear icon, then changing the `Playback Speed`
* `Anki` Workbook modules
    * Many grammar textbooks have accompanying workbooks that give students additional practice
    * While it is reasonable to think of `Anki` as one giant workbook, beginning with Unit 2 we are adding in a `workbook` chapter where we will begin to dissect words or short passages
    * Our goal is to `parse` and `translate`
        * `Parsing` is identifying the gender, number, person (if applicable), and the lexical form
        * `Translating` is identifying the word's meaning

Now, if you're ready, let's begin our Unit 2 Quest!


<!--chapter:end:04c-unit2intro.Rmd-->

# Hebrew Nouns {.Nouns}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.intro.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

> To comprehend Biblical Hebrew, we must understand how nouns are formed, how they are pluralized, and how to look words up in a dictionary.  Often, we need to employ the Rule of Sheva to help us identify the dictionary form of a word.


Nouns consist of a person, place, thing, or idea and can be singular, dual or plural.  Hebrew also introduces the concept of "gender."  This lesson will review aspects of the Hebrew noun with specific attention focused on pluralization rules.

We will also learn the Rule of Sheva, which is responsible for the most common spelling variations in the Hebrew Bible

::: {.infobox .map}
**LESSON ITINERARY**

1. Understand a Noun's gender and number
1. Define what is meant by "lexical form"
2. Examine singular noun endings and "endingless" nouns for both masculine and feminine nouns
3. Examine endings for plural and dual nouns
4. Identify special dual forms
6. Examine other/irregular Pluralization
7. Describe the Rule of Sheva

:::

::: {.infobox .stop}
EQUIPMENT CHECK

Before continuing, can you describe the following concepts?

* Vowel and syllable preference
* The rules for Silent Sheva vs. Vocal Sheva
:::

Additionally, starting with this lesson, we will invoke the shorthand we've been learning in Anki (e.g. , MP = Masculine Plural, FS = Feminine singular).



## First Thought {-}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.deu0405.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

### <span class="he">רְאֵה לִמַּדְתִּי אֶתְכֶם חֻקִּים וּמִשְׁפָּטִים</span> {-}

*See, I have taught you statutes and judgments (Deuteronomy 4:5)*

Give thanks to God for His Word and ask that you never depart from His commands





*****

<div class="figure" style="text-align: center">
<img src="images/04-Capernaum and Mount of Beatitudes from Sea of Galilee, tb100805596 (2).jpg" alt="Capernaum and Mount of Beatitudes - suggested location of Yeshua's teachings we call 'the Sermon on the Mount' (Matthew 5-7). Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="600pt" />
<p class="caption">(\#fig:unnamed-chunk-41)Capernaum and Mount of Beatitudes - suggested location of Yeshua's teachings we call 'the Sermon on the Mount' (Matthew 5-7). Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>


## _Hebrew Quest_ Grammatical Gender and Plural Endings Lecture

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.1.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

View this 10:37 overview video from _Hebrew Quest_, then we will dig into the concepts in greater detail as we progress through the lesson^[As we mentioned in the Unit 2 introduction, you can disregard references to the "Hebrew Quest Student Manual" or "Essentials of Biblical Hebrew."  Pertinent concepts have been incorporated into this Hebrew GRAMMAR Quest Guidebook.]. We will be studying the "Construct Form" in Lesson 10.

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
yY3O8ByYNwI?start=0&end=637&rel=0&showinfo=0autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/yY3O8ByYNwI){target="_blank"}

* Start: 00:00
* End: 10:37


## Gender and Number {#gender_number}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.2.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* All Hebrew nouns have Gender and Number
* Grammatical Gender
    * The "gender" sometimes does, but usually does not, have anything to do with biological gender
    * <span class="he">סֵ֫פֶר</span> is masculine (M), while <span class="he">תּוֹרָה</span>  is feminine (F). There is nothing inherently masculine about books, nor is there anything feminine about laws or instructions
    * The gender of a noun never changes
* Number
    * A noun is either singular (S), plural (P), or less frequently, dual (D)
        * Dual is precisely two of something
        * Apart from the words "pair" or "both", English doesn't have too many dual forms
        * In Hebrew, typically paired body parts are in the dual form (eyes, ears)
    * The number of a noun CAN change
* A word's ending can indicate both the NUMBER and the GENDER - we will learn the endings later in this lesson
    
::: {.box .info}
Person
    
* In Lesson 8, (Pronouns) we will introduce the concept of "person"  
* Collectively, when you see "PGN" in grammar, this refers to "person, gender, and number"; e.g., "3MS" means "3rd person, masculine, singular".

:::

## Lexical Form {#lexical_form}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.3new.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

::: {.box .map}
The Lexical Form is the dictionary version of the word.
:::

* English examples:
    * "Oxen" may not be its own entry, but you would find it under "ox"
    * You may not find "went," but you would find "go"
* Hebrew dictionaries (called "Lexicons" in academia) work the same way
    * For nouns, the Lexical Form is the SINGULAR version of the noun
    * For verbs, the Lexical Form is (usually) the PERFECT 3ms form of the verb^[So in a typical Hebrew Lexicon, you wouldn't actually find the meaning of the equivalent of "to go" under "go"; you _would_ find it under the equivalent of "(he) went"]



## Parsing vs. Inflecting

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.4new.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* When we take a base word and do something with it, such as change its gender or number, we call that _inflecting_ the word
    * For example, say you had the English word `mouse`.  The word `mice` would be inflecting `mouse` into its plural form
    * In this course, you will NOT need to know how to inflect a word.  Reading the Hebrew Bible never requires this skill.
* _Parsing_ is somewhat of the opposite concept where we take an inflected word and break it down into its base form to determine its meaning
    * For example, let's say you had the english word `mice`, you didn't know what it meant and needed to look it up.  
    * Let's further assume there was no dictionary entry for `mice` (Hebrew dictionaries often do not have separate entries for a word's plural forms).  
    * You would need to PARSE it = `Mice is the plural form of mouse.` In other words, `mice` is two or more of whatever a `mouse` is.
    * You could then look up `mouse` and be on your way
    * Reading the Hebrew Bible **does** require us to _parse_
* When we parse a word, we identify the lexical form and the inflected person, gender, and number to understand what the word is communicating to us
    * Or, if we don't know what it means, we have at least identified the lexical form so we can look it up in a dictionary
* Beginning with this lesson, you will see an `Anki` chapter called `Workbook`, which will have some activities like parsing

## Singular Noun Endings {#sing_noun_endings}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.4.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

:::{.box .light}
A noun's ending, or lack of one, indicates NUMBER and (usually) GENDER
:::

* Masculine singular (MS)
    * MS are usually "endingless" 
        * This means, most often, there is no special identifying ending to let you know it is a masculine singular word
        * Usually the absence of a Feminine, Dual, or Plural ending is enough to let you know you are looking at an MS word
    * Occasionally an MS noun may end in (accented) <span class="he">ה ֶ֫</span> - for example <span class="he">שָֹדֶה</span> means "field"
* Feminine Singular (FS):
    * <span class="he">תּוֹרָה</span> (the (accented) Qamets+Hei ending is most typical)
    * Nouns that end in ($E$, $A$, $\bar A$, or $\hat U$)^[Remember this is shorthand for Tsere, Pathach, Qamets and Shurek respectively. When we say something like "Qamets+Hei, we mean a Qamets under the preceding consonant followed by ה] + <span class="he">ת</span> are _usually_ FS
        * <span class="he">בַּת</span> (daughter)
        * <span class="he">תִּפְאֶ֫רֶת</span>  (glory)
        * <span class="he">בְּרִית</span> (covenant)
        * <span class="he">מַלְכּוּת</span> (kingdom)
        * Exception: <span class="he">ת</span> - <span class="he">תּוֹרוֹת</span> is FP (laws/teachings)
    * <span class="he">אֶ֫רֶץ</span> (land - endingless, but feminine - less common)^[Not all endingless nouns are MS.  Some common words are endingless but are classified as FS: <span class="he">אֶ֫רֶץ</span> (land), <span class="he">עִיר</span> (city), and <span class="he">אֶ֫בֶן</span> (stone). When this occurs, most vocabulary lists will mark the word as "(F)".]
        
::: {.box .caution}
Some students fall into a habit of thinking every word-final ה is feminine.  

* Remember <span class="he">ה ֶ֫</span>  is masculine
* UNACCENTED Qamets+Hei is NOT the FS ending

Also, while most endingless words are masculine, remember some are feminine
:::

## Plural Noun Endings {#noun_pluralization}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.5.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::


* MP - <span class="he">ים ִ </span> 
    * Since most MS nouns are endingless, simply affix the MP ending <span class="he">ים ִ</span>, e.g.<span class="he">סוֹס </span> (horse) becomes **<span class="he">סוּסִים</span>** (horses) 
    * <span class="he">דָּבָר</span> becomes **<span class="he">דְּבָרִים</span>**
        * A one-syllable ending affixed to a two syllable word, now is a three-syllable word and therefore, has a propretonic syllable
        * A vowel under a non-Guttural will reduce to Vocal Shewa -<span class="he"> דְּבָרִים</span>
        * As we saw in Lesson 3.2,<span class="he"> דְּבָרִים</span> changes from <span class="he">דָבָר </span>because an open propretonic syllable prefers a reduced vowel. 
    * <span class="he">עָנָן</span> becomes **<span class="he">עֲנָנִים</span>** (clouds)
        *  A vowel under a guttural will take a Hateph vowel, usually Hateph Patach - <span class="he">עֲנָנִים</span>
    * <span class="he">כּוֹכָב</span> becomes **<span class="he">כּוֹכָבִים</span>** (stars)
        *  An irreducible long vowel will not reduce - so in <span class="he">כּוֹכָבִים</span>, the $\hat O$ (Holem Vav) remains
    * Under the MP endings above, note the propretonic reduction when the original word is more the one syllable. 
* FP: <span class="he">וֹת</span>, e.g., **<span class="he">מְלָכוֹת</span>** (queens)
    * <span class="he">תּוֹרָה</span> becomes **<span class="he">תּוֹרוֹת</span>** 


## Dual Noun Endings

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.6.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* MD: <span class="he">יִם ַ</span>, e.g., <span class="he">סוּסַ֫יִם</span> (two horses)
* FD: <span class="he">יִם ַ </span>, e.g., <span class="he">יָדַ֫יִם</span> (two hands) or <span class="he">תַ֫יִם ָ</span> as in <span class="he">תּוֹרָתַ֫יִם</span> (two laws)

::: {.box .caution}
Occasionally, we will see the defective spelling of the plural and dual endings: <span class="he">סוּסִם תּוֹרֹת</span>; the gender and number of the word will not change.
:::

## Special dual forms {#dual_forms}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.7.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* Hebrew has three common words that have the unique dual ending 
* These words are usually translated as singular
    * <span class="he">שַׁמַ֫יִם</span> heaven, sky (sometimes "heavens")
    * <span class="he">מִצְרַ֫יִם</span> Egypt
    * <span class="he">מַ֫יִם</span> water (sometimes "waters")

    * Additionaly, on a similar note, <span class="he">פָּנִים</span> has the MP ending but it is translated as the singular "face"


## Irregular Pluralization  {#irregular_pluralization}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.8.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* Like any language, Hebrew has a handful of irregular nouns 
* For example, you won't find <span class="he">נָשִׁים</span> in a dictionary; you need to know the singular form, <span class="he">אִשָּׁה</span>

::: {.box .light} 
Memorize these nine most common pairs^[You don't have to memorize them right this instant.  They will be in Anki!]:

| S   | Def      | P     | Def.      |
|:-----|:----------|:-------|:-----------|
|<span class="he"> אִישׁ </span>| man      | **<span class="he">אֲנָשִׁים</span>** | men       |
|<span class="he"> אִשָּׁה </span>| woman    | **<span class="he">נָשִׁים</span>  **| women     |
|<span class="he"> עִיר </span>| city     | **<span class="he">עָרִים </span>** | cities    |
|<span class="he"> אָב </span> | father   | **<span class="he">אָבוֹת </span>** | fathers   |
|<span class="he"> בַּ֫יִת</span> | house    | **<span class="he">בָּתִּים </span>** | houses    |
|<span class="he"> בַּת</span>  | daughter | **<span class="he">בָּנוֹת </span> **| daughters |
|<span class="he"> בֵּן</span>  | son      | **<span class="he">בָּנִים </span> **| sons      |
|<span class="he"> יוֹם</span> | day      | **<span class="he">יָמִים </span>** | days       |
|<span class="he">יָם</span> | sea      | **<span class="he">יַמִּים</span>** | seas      
:::

* The plural forms retain the gender of their singular noun
* <span class="he">אָבוֹת</span> is still masculine,  and <span class="he">נָשִׁים</span> is still feminine, despite the plural endings.


## Segholate Nouns follow a standard vowel pattern when pluralizing 

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.9.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* Did you notice that the words <span class="he">דֶּ֫רֶךְ</span> and <span class="he">סֵ֫פֶר</span> have the accent is on the first syllable?
* Many two-syllable words accented on the penult are classified as _Segholate_ nouns.  
* They get this name because frequently, though not always, there are two Seghol vowels. <span class="he">נַ֫עַר</span>  (boy, youth) is a Segholate noun even though it doesn't have any Seghol vowels.

::: {.box .info}
PLURAL SEGHOLATE NOUN HINT

A plural word that has Vocal Sheva/Hateph under the first consonant and Qamets under the second, with the normal MP or FP ending is probably a Segholate noun

* <span class="he">מֶ֫לֶךְ</span> to **<span class="he">מְלָכִים</span>**
* <span class="he">סֵ֫פֶר</span> to **<span class="he">סְפָרִים</span>**
* <span class="he">נַ֫עַר</span> to **<span class="he">נְעָרִים</span>**

:::

## Geminate Words take a Daghesh Forte

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.10.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

_Geminate_ (from the Latin for "twins") words appear to have two visible letters (which we call "biconsonantal").  At one point in history, the second consonant appeared twice.  Example <span class="he">עַם</span> (people) was once *<span class="he">עמם</span>.  The lexical form drops the extra consonant.

::: {.box .info}
When we pluralize a Geminate word, the "twin" letter "reappears" but as a Daghesh Forte instead of a consonant.  So in our example,<span class="he"> עַם</span> becomes <span class="he">עַמִּים</span> (peoples).
:::

::: {.box .light}
* The reason we don't have a Daghesh Forte in עַם is that **a "word-final" letter (i.e. the last consonant of a word) ALWAYS rejects the Daghesh Forte when it has no vowel**
* This is the second of three major scenarios where a Daghesh Forte is rejected
    * we looked at the first scenario in Lesson 2 - Gutturals and Resh ALWAYS reject the Daghesh Forte
    * There is one more rejection scenario that we will meet in Lesson 5
    
:::

## Working back to the Lexical Form {#back_to_lexical_form}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.12new.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* As we mentioned at the beginning of this lesson, to understand the Hebrew Bible, you WON'T need to know how to take a singular word and make it plural
* You WILL need to know how to take a plural word and identify its singular counterpart
* Below is how to go from a plural noun to the singular, lexical form (assuming you didn't already know the singular Lexical Form):
    1. Remove the plural or dual ending
    2. Perhaps add a Feminine Singular ending (usually ה ָ ), or less frequently, ה ֶ for Masculine Singular
    3. For Geiminate nouns, drop the Dagesh Forte in the final letter when it lacks a vowel
    4. Often change vowels
        * Propretonic reduction - often without the plural ending, a reduced propretonic vowel in the plural will be a long tonic vowel in the singular
        * Recognize the plural pattern of a Segholate noun
    5. Memorize the most common irregular pluralizations (Anki will have both singular and plural forms of these words)

::: {.box .info}
Of course, the more vocabulary words you know, the less you will need to mechanically go through these steps!
:::


## Rule of Sheva I {#rules_sheva}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.13new.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* Hebrew does not allow two reduced vowels in a row to remain (or "stand")
    * If you see two Sheva in a row in the text, the second one must be Silent
    * We remember the reduced vowels are _Vocal_ Sheva, Hateph Patach, Hateph Seghol, and Hateph Qamets Hatuf
    * _Silent_ Sheva is not a reduced vowel; it's not a vowel at all
* Sometimes, according to grammar rules, we end up with a scenario where we would have two reduced vowels such as two Vocal Sheva, back to back - this is another conflict that must be resolved
    * Grammar rules sometimes REQUIRE two reduced vowels next to each other
    * Grammar rules also PROHIBIT tho reduced vowels next to each other
    * <u>The "prohibit" rule wins!</u>
* The "Rule of Sheva" defines what happens to resolve: **the first reduced vowel lengthens to become a short vowel**
* We must learn to recognize when a word has vowels modified because of the Rule of Sheva

::: {.box .light}
If a word BEGINS with a short vowel followed by a reduced vowel, it may originally have been two reduced vowels
:::

We'll explain more in Rule of Sheva, part II.

## Rule of Sheva II

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.14new.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

Three common Rule of Sheva scenarios:

1. No Gutturals - the two Vocal Sheva become **Hireq + Silent Sheva** 
    * In other words, say you're reading the Hebrew Bible and you see a word that has $I + :$.  
    * Your Hebrew grammar antenna should go up and you should wonder whether this was originally two vocal sheva
2. Either consonant is a guttural -  **the first vowel becomes the corresponding short vowel of the Hateph vowel**
3. When the second consonant is a Yod - the two reduced vowels and the consonant Yod in between "converts" to the vowel letter $\hat I$ (Hireq+yod)
    * This is surprisingly frequent in Hebrew
    

::: {.box .light}
RULE OF SHEVA

Review this table - Anki will help you to commit these concepts to memory

| Type | After Rule of Sheva | Before*^[When you see an asterisk in the context of a word form, it means this form is impossible.]
| :-: | :-: | :-:
| Strong | <span class="he">קִטְ</span>^[Hebrew Grammars have what are called "paradigm words" to represent any combination of consonants meeting the patter. קטל is a paradigm for any three strong (non-guttural) letters, עמד represents any guttural in the first position, and בחר represents any guttural in the second position.] | <span class="he">קְטְ</span>*
| Yod | <span class="he">קִי</span> | <span class="he">קְיְ</span>*
| Patach/Sheva | <span class="he">עַמְ</span> | <span class="he">עֲמְ</span>*
| Seghol/Sheva | <span class="he">עֶמְ</span> | <span class="he">עֱמְ</span>*
| Sheva/Patach | <span class="he">בַּחֲ</span> | <span class="he">בְּחֲ</span>*
| Sheva/Seghol | <span class="he">בֶּחֱ</span> | <span class="he">בְּחֱ</span>*


:::

NOTES

* Note how the "After" form has the short vowel that corresponds to the reduced vowel of the "Before" form - we can consider this the "Hateph copy-cat rule" - take whatever the hateph vowel is and drop the hateph, leaving only the resulting short vowel
* When a prefix is added to <span class="he">אלֹהִים</span> and the Tetragrammaton, the vowel changes are irregular:
    * With <span class="he">אֱלֹהִים </span> the aleph becomes quiescent after a prefix:
        * <span class="he">אֱלֹהִים + לְ = לֵאלֹהִים</span>
    * With the Tetragrammaton, the prefixed letter with take a Patach, with nothing under the Yod:
        *  <span class="he">בַיהוָה</span>
    

::: {.box .map}
RULE OF SHEVA

* Understanding that a syllable may have “originally” had a reduced vowel is an important clue in translating and parsing
* Taking time to learn when an original form has been altered by the Rule of Sheva will be extremely important as we move into Unit 3
* Remember a Silent Sheva is not a reduced vowel; it is not a vowel at all - it is not affected by the Rule of Sheva

:::


## Lesson Conclusion {-}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.conclusion.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::


This lesson may have felt like you were "drinking from a firehose" as the saying goes.  Well, often that's how it is with learning a language. Remember, this is a self-paced course; most likely you are not on any external timeline.  Be patient and give these concepts time to soak in.  Remember the concept of feeling like you are in "the fog" is completely natural.

Over time, Anki will help these concepts to "stick" - if you are struggling with Anki then, as we've said before, come back here to the guidebook and re-review the material.  If you feel you need a detailed, academic approach, [Dr. Beckman's course lectures](http://youtu.be/9LxaKsDifCo) are available on YouTube, but we would recommend to try Anki first.  You may be absorbing more than you think you are.

Once you get the hang of them, we're confident you will find that Hebrew noun concepts are not that difficult to grasp.

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/SSHPbptJG4s" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/SSHPbptJG4s){target="_blank"}

## Verses Warm-up {-}


<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/WFSv-Gv3z7o" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/WFSv-Gv3z7o){target="_blank"}

## Anki {-}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.anki.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* `Lesson 04 A. Vocab`
* `Lesson 04 B. Grammar` 
* `Lesson 04 C. Workbook` 
    * With Lesson 4, we are gradually increasing the depth of work in `Anki`
    * The `Workbook` will have short activities such as translation, examples of concepts taught in the lesson and word "parsing"
    * When we parse a Hebrew word, we identify three things:
        * the Person (if applicable), Number, and Gender of the word
        * the Lexical form
        * the definition of the original word
    * For example, if the instruction is to parse <span class="he">שִׁירִים</span>, we would respond with: "MP שִׁיר  Songs"
    * You may not know every word -
        * **That is the point of this exercise!**  
        * As you read your Hebrew Bible, you will invariably come across words you don't know.  
        * It is important to be able to break down a word into its Lexical form so you can look it up
        * In the [appendix](#lexicon), we have links to some lexicons (dictionaries) you may use with this course.  You can download an abridged version [here](./images/BBH_Lexicon.pdf){target="_blank"} 
    * Future lessons will incorporate additional aspects into our parsing activities, such as verb conjugation
* `Lesson 04 D. Study Verses`
    * We will continue with study verses that provide examples of the Lesson's vocabulary
    * Hints will be provided for less familiar verbs

## Ruth Pursuit {-}        

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/04.ruth.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::


::: {.box .map}
YOUR QUEST

1. Find one regular singular segholate noun in V1.  In this verse, there is also a segholate noun with a propositional prefix that we haven't studied yet; this world also takes on vowel changes, which we'll cover in a few lessons (yellow)
2. Find all words that are regular masculine plural in the chapter (pink). Some words are prefixed with the definite article, which we will cover in the next lesson.  Also, find all regular Feminine plural nouns in the chapter (pink).  One of the words in verses 2-6 has a MP ending but is actually an irregular FP.  Highlight this word in (green).
    * Be sure to research any words you don't know. HLI has a [lexicon available here.](https://holylanguage.com/resources-dictionaries.php){target="_blank"}
3. <span class="he">כַלֹּתֶיהָ
</span> is a word meaning her daughters-in-law (in verse 22, this word is in the singular).  It comes from a verb meaning "finish" or "end" (we'll let you ponder that!). Find all four examples of these feminine nouns, including one with the "and" prefix (grey)
4. Find the vocabulary word <span class="he">עִיר</span>. In Ruth 1, it appears as <span class="he">הָעִיר</span>. In the next lesson, we will learn about the prefix ה
(blue)
:::

* [Blank copy of Ruth Chapter 1](https://docs.google.com/document/d/1bcT1J-fcVmD1Zn5Jk2nj0560tEddcgtbYZLkwaVVuyE/copy){target="_blank"}
* [Ruth Pursuit Answer Key #4](./images/04_Ruth_Pursuit_KEY.pdf){target="_blank"}

## Quest Quiz {-}

[Open Quest Quiz #4 in a new window](https://forms.gle/2LCEgvmpHr5mqB5Z6){target="_blank"}

<div class="containerLet">
<iframe 
    class="responsive-iframe"
    src="https://forms.gle/2LCEgvmpHr5mqB5Z6">
    </iframe>
</div>




<!--chapter:end:04f-NounsPlural.Rmd-->

# Definite Article and Conjunction Vav {.Article}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.intro.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

> To comprehend Biblical Hebrew, we must identify the definite article and the conjunction Vav whenever we see them in a word.

As we say often, our focus with Hebrew GRAMMAR Quest is not to write or speak Biblical Hebrew but to _read and comprehend_ Biblical Hebrew.  In this lesson, the sections that deal with meaning are more important than those that deal with the specific spelling<small>^[<small>In contrast, _Basics of Biblical Hebrew_ places significant emphasizes on learning the spelling rules. This is not wrong; it is just not our approach.</small>]</small>.

It is unlikely you will ever need to write the article or the conjunction with the correct vowel. We discuss these spelling details because you must know how to recognize them in the Bible when you encounter them.


::: {.infobox .map}
**LESSON ITINERARY**

1. Translate the Vav Conjunction
2. Identify the Vav Conjunction
3. Understand why the Dagesh Forte is your friend
4. Translate the Article 
5. Identify the Article
6. Understand the concepts of definiteness and indefiniteness in Hebrew
7. Discuss what makes a noun definite
:::

::: {.infobox .stop}
**EQUIPMENT CHECK**

Before continuing, can you describe the following concepts?

* Identifying the lexical form of a noun
* The "rule of Sheva," including what happens in different combinations of two contiguous reduced vowels
* How vowels can shift when the number of syllables changes
* The masculine and feminine plural endings

:::

## First Thought {-}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.isa4012.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

### <span class="he">מִי־מָדַד בְּשָׁעֳלוֹ מַיִם וְשָׁמַיִם</span> {-}

_Who has measured the waters in the hollow of His hand, And marked off the heavens'  (Isaiah 40:12)_

Give thanks to the Creator for the beauty and precision of His creation



*****

<div class="figure" style="text-align: center">
<img src="images/05-Mount of Beatitudes hillside, tbs75359303 (2).jpg" alt="Mount of Beatitudes hillside reflecting the beauty of the Galilee region. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="600pt" />
<p class="caption">(\#fig:unnamed-chunk-42)Mount of Beatitudes hillside reflecting the beauty of the Galilee region. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>

## _Hebrew Quest_ Vav Lecture (from HQ Lesson 5)

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.1.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

View this 3-minute video from _Hebrew Quest_ discussing how the letter Vav can mean the conjunction "and". 

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
oZ1VbPCpMvw?start=729&end=900
&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/oZ1VbPCpMvw?t=729){target="_blank"}

Start: 12:09
End: 15:00



## _Hebrew Quest_ Conjunction Lecture (from HQ Lesson 13)

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.2.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

View this 3:30 overview video from _Hebrew Quest_, then we will dig into the concepts in greater detail as we progress through the lesson.  You may disregard references to the Hebrew Quest Student Handbook/Essentials of Biblical Hebrew.

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
yY3O8ByYNwI?start=2460&end=2671
&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/yY3O8ByYNwI&t=2460){target="_blank"}

Start: 41:00
End: 44:31

## Translate the Vav Conjunction {#vav_translate}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.3.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* The Vav conjunction serves _many_ different purposes in Hebrew
    * Some of these can be translated into English
    * Other times there is no direct English translation; these uses can be more like "stage directions" in a play that the directors and actors see in the script but are not read aloud
* When translating the Vav, we must make sure our translation fits the context
    * Most often, it merely means "and", but other options can include then, and then, but, also, even, together with, that is  
    * Occasionally, the best option is to leave it untranslated
* When you were learning English, we had it drilled into us that we should never begin sentences with "and" or have multiple "and" clauses in a sentence
    * We were told these are "run-on sentences", and they were to be avoided
* Hebrew LOVES to start sentences with "and", and is just fine with run-on sentences!
* As you advance in Hebrew, you will enjoy seeing how the Bible authors employ the Vav at the beginning of a sentence or clause to evoke different meanings
    * For example, when added to a verb, it usually serves to continue or advance the narrative
    * When added to a non-verb, it is often those stage directions we mentioned: a contrast, a scene shift, or a parenthetical comment
* It's safe to say, there is a LOT packed in to this little letter ו!


::: {.box .info}
TRANSLATION TIPS

* As you are starting out in Hebrew, go ahead and start your translation of the Vav Conjunction with "And", but remember to be flexible
* Another word, such as "but" or "then" might make more sense depending on the context of the passage
* Many times for smooth English, we will need to leave the Vav untranslated
:::



## Identify the Vav Conjunction {#vav_identify}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.4.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

<img src="images/05.vav_conjunction.png" width="50pt" style="display: block; margin: auto;" />

* The Vav conjunction is usually <span class="he">וְ</span> prefixed to a word
* You will see <span class="he">וּ</span> before  <span class="he">במפ</span> - remember "BuMP"- this is the ONLY time a vowel will ever begin a syllable
    * The <span class="he">ב</span> and <span class="he">פ</span> will lose their Dagesh Lene 
    * It's <span class="he">בֵּן</span>, (between), but it's <span class="he">וּבֵן</span> (and between)
    * The conjunction will also be <span class="he">וּ</span> before a consonant that has a Sheva
* You may see <span class="he">וָ</span> before some accented syllables (remember the Vowel-Syllable preferences)
* Since Vav takes a Vocal Sheva, the Rule of Sheva applies when <span class="he">וְ</span> is prefixed to a word beginning with a reduced vowel (Vocal Sheva or Hateph vowel)

::: {.box .info}
How to tell the difference between the conjunction and words that start with <span class="he">ו</span>?

* **A Vav or Shureq as the first letter of a word is ALMOST ALWAYS the conjunction Vav.**
* Only 10 words start with Vav, and only two occur more than once
    * <span class="he">וָו</span> means "hook," and  <span class="he">וָוִים</span> means "hooks - occurs 13 times in Exodus 26-38, talking about the hooks for the Tabernacle
    * <span class="he">וַשְׁתִּי</span> - Queen Vashti - it appears only in the book of Esther
:::

## Loss of Dagesh Forte {#loss_Dagesh_forte}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.5.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* We've been referencing the Dagesh Forte in almost every Lesson of this course; you're probably getting the idea that the Daghesh Forte must be kind of a big deal. 
    * It is.  Now we're about to see another reason why as we move in to our discussion of the Hebrew Article
* We like to think of the Dagesh Forte as your friend
    * When you see it, it is Hebrew's way of saying "pay attention; something is different"
* Sometimes the Dagesh Forte gets rejected from time to time
* We've discussed two of those already, and in this lesson, we'll add a third; We'll also now introduce a concept called "compensatory lengthening", which we'll define in the next section
* The two we've already discussed are:
    * Gutturals/Resh ALWAYS reject the Daghesh Forte (Lesson 2)
    * A word-final consonant without a vowel ALWAYS rejects the Daghesh Forte (Lesson 4)
* The new guideline  for this lesson is: A SQiN eM LeVY consonant with a Sheva SOMETIMES rejects the Dagesh Forte
    * When this happens, there is NEVER compensatory lengthening
    * Remember we had you memorize the ten SQiN eM LeVY consonants in Lesson 1.  Do you remember them?
* See table below for a summary of these three rules:

| Loss of Daghesh Forte Scenario | Rejects Dagesh | Compensatory Lengthening
| :-: | :-: | :-: 
| Gutturals/Resh | Always | Sometimes
| Word-final consonant without a Vowel (Lesson 4) | Always | Sometimes
| **SQiN eM LeVY WITH SHEVA** | SOMETIMES | NEVER


::: {.box .info}
SQiN eM LeVY Rule

* Please don't worry if you don't understand this at first
* When you start to see the SQiN eM LeVY rule in action, it will get easier
* See [this handout](./images/05_sqin_em_levy.pdf){target="_blank"} for additional discussion on SQiN eM LeVY consonants
:::



## Compensatory Lengthening

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.6.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* In Compensatory Lengthening, a short vowel _lengthens_ to become a long vowel to _compensate_ for the loss of a "doubling" Dagesh Forte (or sometimes a vowel) in the following consonant
    * Patach will lengthen to Qamets
    * Hireq will lengthen to Tsere
    * Qibbuts will lengthen to Holem
* Compensatory Lengthening can occur in ANY letter that precedes a Dagesh Forte-rejecting consonant...but it does not _always_ occur
* Compensatory Lengthening can also occur in a word with a Quiescent Aleph that rejects a Sheva.

::: {.infobox .info}
* When SQiN eM LeVY consonants reject the Dagesh, there is NEVER compensatory lengthening.
* Sometimes there is no change to the preceding vowel - this is called "virtual doubling."  As Dr. Van Pelt, the co-author of Basics of Biblical Hebrew likes to say 
""Virtual Doubling" should be called "virtually no doubling", because no spelling changes occur."
:::

## _Hebrew Quest_ Article Lecture

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.7.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

View this 2-minute overview video from _Hebrew Quest_, then we will dig into the concepts in greater detail as we progress through the lesson. We will discuss the Interrogative Article in Lesson 8.

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
yY3O8ByYNwI?start=1650&end=1835
&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/yY3O8ByYNwI&t=1650){target="_blank"}

Start: 27:30
End: 29:18

## Translate the Article {#article_translate}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.8.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

::: {.box .light}
ARTICLE

* Hebrew just has one article for definiteness
* It is often simply called the "Article"
* The Hebrew "Article" is equivalent to the English "Definite Article"  
:::

* In English, we have two "indefinite articles" = "a" or "an", and one "definite article" = "the"
* Strictly speaking, Hebrew has no "indefinite article"
* The Hebrew (definite) article has many translations: "the", "this", "o" (as in "O king"), "his", "her", "my".
* <span class="he">הַיּוֹם</span> is literally "the day"; however, a better translation is "today", or sometimes "this day"
* The Hebrew article can also make an adjective superlative: <span class="he">הַתּוֹב</span> is literally "the good", but can mean "the best".



## Identify the Article {#article_identify}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.9.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::
<img src="images/05.def_art.png" width="100pt" style="display: block; margin: auto;" />

* The usual form is Hei with a Patach and a Dagesh Forte in the next letter ("Hei+Patach+Dagesh")<small>^[<small>By definition, the Dagesh is a Forte as it comes after a vowel that is not a Sheva.</small>]</small>
* As we've been saying, some unusual things can happen when the letter following the <span class="he">ה</span> rejects the Dagesh Forte:
    * Virtual Doubling
        * <span class="he">ּ הַ</span> becomes simply <span class="he">הַ</span> (no Dagesh Forte):
        * Before SQiN eM LeVY with a Sheva
        * Before a ח or another <span class="he">ה</span> (see הֶ note below)
    * Compensatory Lengthening
        * Becomes <span class="he">הָ</span> (no Dagesh Forte and the Patach lengthens to Qamets):
        * Before <span class="he">א ע ר or הָ֫ </span>
    * Becomes <span class="he">הֶ</span> (no Dagesh Forte and a Seghol instead of a Patach) before accented or unaccented <span class="he">חָ</span>, or unaccented <span class="he">הָ</span> or <span class="he">עָ</span>

::: {.box .info}
* The goal is not to memorize the alternate forms as much as recognize that they exist
* "Hei+Patach+Dagesh" is the form you need to memorize
:::


## Hebrew Indefiniteness {#indefiniteness}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.10.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* Hebrew (and Greek) lacks an indefinite article 
* A word without the Article is indefinite
* Occasionally you will see "one" (<span class="he">אַחַת אֶהַד</span>) to indicate indefiniteness

## Other Hebrew Definiteness {#definiteness}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.11.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* The Article is not the only way Hebrew indicates definiteness
* An individual's name and most proper nouns are definite by definition.
    * <span class="he">דָּוִד</span> is definite
        * We will never see: <span class="he">*הַדָּוִד</span>
        * In English we would never say "The Izzy teaches Hebrew".  It's just "Izzy teaches Hebrew".
        * On the other hand, names of people groups and some geographic features often take the article. <span class="he">הַיַּרְדֵּן</span>= the Jordan River.
* A word with a pronominal suffix is definite since the suffix indicates possession, and possession is definite<small>^[Pronominal suffixes are the subject of Lesson 9</small>]</small>.  
    * In English, we don't say "his the book"; we say, "his book".  "Book" is understood to be definite.
* A Hebrew word in its construct state is definite when the last word in the construct chain is definite  
    * A construct chain in English might be "the book of the sister of the king"; in other words in English we generally do add the definite article
    * Hebrew would literally be, "book of sister of the king", but all words in the chain are understood to be definite
    * We will discuss construct chains in Lesson 10

## Lesson Conclusion and Activities {-}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.conclusion.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::
You made it through another lesson!  Way to go!  Even though we only studied two concepts - the word for "and" and the word for "the" - these concepts in Hebrew are quite different from English.

You may be noticing how each new lesson builds upon the previous ones. If something isn't entirely making sense, or if you find yourself asking, "why in the world do I need to know this?" just be patient, and it should start to come together in a lesson or two.  Now might also be an excellent time to look back and see how far you have come in just five lessons.

As far as activities, we have the warm-up videos, Anki, the Ruth Pursuit, and the Quest Quiz. When you finish all of that, we have our second `Twelve Tribes Badge` you can claim.

Take your time and let these oncepts in this chapter sink in.  You're about half-way through the "non-verbs" portion of the course.  Lessons 6-10 will be continuing to build out sentences with prepositions, adjectives, and pronouns.  Then we'll take a little bit of a break with numbers in Lesson 11 before moving on to Unit 3 and Hebrew verbs.

Keep with it; you're doing great!


## Word Warm-up {-}


<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/WQqcvmjdq1k" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/WQqcvmjdq1k){target="_blank"}

## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/Wf-nQAErcj8" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/Wf-nQAErcj8){target="_blank"}

## Anki {-}

* `Lesson 05 A. Vocab`
* `Lesson 05 B. Grammar` 
* `Lesson 05 C. Workbook`
    * In this activity, we will have short passages of scripture that illustrate the definite article and the Vav conjunction.
    * Make sure you look up any words you do not know.  You can download an abridged [lexicon here](./images/BBH_Lexicon.pdf){target="_blank"}.
* `Lesson 05 D. Verses`

## Ruth Pursuit {-}        

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/05.ruth.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

::: {.box .map}
YOUR QUEST

1. Find five examples of the conjunction vav: וְ (note the Vocal Sheva) (Yellow)
2. find five examples of the standard definite article ּ  הַ (Green)
3. Find the first three examples of "Compensatory Lengthening" of the definite article.  There is one example of "Virtual Doubling" of the definite article in verses 10-15.  Can you find it? (Light Blue)
4. הִנֵה is a widespread Biblical expression that means, "look!" or "behold." Find the one example of הִנֵה in Ruth 1. (Pink)
5. Find all instances of <span class="he">אִישׁ</span> (man), and <span class="he">אִשָּׁה</span>, wife/woman. (grey) 
    * In verses 1 and 2, note that <span class="he">אִשְׁתּוֹ</span> has a pronominal suffix, so the word means "his wife."  Words that normally end with a ה tend to lose the ה when suffixes are added. We'll study more about pronominal suffixes in Lessons 9 and 19.
    * In verses 12 and 13, note that <span class="he">לְאִישׁ
</span> has a prepositional prefix mean "to" or "for."  We will learn about prepositions in the next lesson.
6. Find the vocabulary word <span class="he">כֹּה</span>. It appears once with the Vav conjunction and once without. (red)

:::


* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/copy){target="_blank"}
* [Ruth Pursuit Answer Key #05](./images/05_Ruth_Pursuit_KEY.pdf){target="_blank"}
* Update your `Ruth Pursuit Translation` worksheet.


## Quest Quiz {-}

[Open Quest Quiz #05 in a new window](https://forms.gle/NsrAS9XKMbtLToW1A){target="_blank"}

<div class="containerLet">
<iframe class="responsive-iframe" src="https://docs.google.com/forms/d/e/1FAIpQLSc-PREmjGXSzCh1l2qenbHEHJlGV35voeamfxuAcc_JB_2j5A/viewform?embedded=true" frameborder="0"></iframe>
</div>

## Claim your next `Twelve Tribes Badge`! {-}


When you have completed all activities on your `Hebrew GRAMMAR Quest Checklist` through lesson 5, complete the certification below, and your badge will be on its way!

<!-- Tribe Badge 2 = Benjamin -->

<div class="containerLet">
<iframe class="responsive-iframe" src="https://docs.google.com/forms/d/e/1FAIpQLSdUEWHBbR9iuUrUMSJ76Fucn0qyqIPxILQpfh3Ss6Hmz8bPZA/viewform?embedded=true" frameborder="0"></iframe>
</div>

<!--chapter:end:05-DefArt_Conjunction.Rmd-->

# Hebrew Prepositions

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/06.intro.m4a"> 
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

> To comprehend Biblical Hebrew, we must be able to identify prepositions as we read the Text.

Prepositions give us space and context.  Prepositions are on almost every page as the authors seek to communicate this context to us.  Furthermore, there is one Hebrew word, <span class="he">מִן</span>, that is classified as a preposition, but, depending on the context, can convey a wide array of meanings. 

::: {.infobox .map}
**LESSON ITINERARY**

1. Recognize that a Nun with Silent Sheva becomes a Dagesh Forte
2. Describe Independent and Maqqef prepositions
3. Define Inseparable prepositions
4. Identify when a word with an inseparable preposition also has the definite article
5. Understand how <span class="he">מִן</span> is constructed
6. Define how <span class="he">מִן</span> is used
7. Identify the Definite Direct Object (DDO) marker
:::


::: {.infobox .stop}
**EQUIPMENT CHECK**

Before continuing, can you describe the following concepts?

* The construction of the definite article, including what happens when the Dagesh Forte is rejected
* The construction of the Vav conjunction
* How Hebrew handles indefinite words
:::

Prepositions are a lot of fun because of what they communicate to us.  So let's dig in!

## First Thought {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/06.ps7702.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

### <span class="he">  בְּיוֹם צָרָתִי אֲדֹנָי דָּרָשְׁתִּי </span> {-}

_In the day of my trouble, I sought the Lord  (Psalms 77:3)_

Meditate and celebrate that the Lord is in the midst of our problems.

The בּ in <span class="he">בְּיוֹם</span> is an example of an "inseparable preposition" that means "in."  We will study various types of prepositions in this lesson.

*****

<div class="figure" style="text-align: center">
<img src="images/06-Nazareth Mount of Precipitation from west panorama, tb041003219.jpg" alt="Mt. Precipice in Nazareth - suggested location of Luke 4:29 when the townsfolk took Yeshua 'up' the mountain, wanting to throw Him 'from' the cliff, 'down upon' the rocks, 'into' the valley below.  Again, He prevailed in His day of trouble.  Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="600pt" />
<p class="caption">(\#fig:unnamed-chunk-45)Mt. Precipice in Nazareth - suggested location of Luke 4:29 when the townsfolk took Yeshua 'up' the mountain, wanting to throw Him 'from' the cliff, 'down upon' the rocks, 'into' the valley below.  Again, He prevailed in His day of trouble.  Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>



## _Hebrew Quest_ Prepositions Lecture

View this 8-minute video from _Hebrew Quest_ introducing prepositions.  We will dig into the concepts in greater detail as we progress through the lesson. 

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
yY3O8ByYNwI?start=1839&end=2303
&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/yY3O8ByYNwI?t=1839){target="_blank"}

Start: 30:40
End: 38:23


## Nun with Silent Sheva Becomes Dagesh Forte

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/06.2.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
<img src="images/06.nun-assimilation.gif" width="600pt" style="display: block; margin: auto;" />

* Nun is considered a "weak letter" 
* One aspect of weak letters is that they disappear from a word under specific scenarios
* One such scenario is when the nun appears with a SILENT Sheva <span class="he">נְ</span> (or no vowel at all)
* When then nun drops, whenever possible, it will be replaced with a Dagesh Forte
* The technical term for this is called "assimilation"
    * So grammarians say, "the נ has assimilated into a Dagesh Forte"
* To get back to the original/lexical form, we would substitute the Dagesh Forte for the Nun+Sheva

::: {.box .light}
ASSIMILATED NUN

A Dagesh Forte frequently indicates an assimilated נ
:::

* When the Dagesh Forte is rejected, we have lost our big clue that a letter like נ has gone missing
    * We've said before that the Daghesh Forte is our friend; it alerts us that something unusual is going on
    * When the Daghesh Forte is rejected, we run the risk of missing out on something the language is trying to tell us
    * Occasionally, but not always, we will have Compensatory Lengthening to help us out


## Independent and Maqqef prepositions 

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/06.3.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* There are three different types of Hebrew prepositions: independent, Maqqef, and inseparable
* An _independent preposition_ is a separate word with a space before it and after it
    * The preposition comes first, followed by its object (just like English). E.g.,  <span class="he">תַּחַת אֹתוֹ</span> (under it)
* _Maqqef_ is a mark like the English hyphen
    * The two marks are nearly identical in meaning and appearance
        * the Hebrew Maqqef is raised: א־בּ 
        * the English hyphen is midline: a-b  
    * Like the hyphen used to join two English words, the Maqqef lets us know that two Hebrew words are closely connected grammatically
* In a _Maqqef preposition_, the Maqqef connects a preposition to its object
    * Again, the preposition comes first:  <span class="he">עַל־מֶלֶךְ</span>
        * English prepositions are NOT written this way; we would never see "on-a-king."
    * One notable aspect about the Maqqef is that the first word (to the left of the Maqqef) loses its accent
        * As a result, the vowel that loses its accent may change
    
::: {.box .info}
The same preposition may be written both with and without the Maqqef

* The meaning does not change
* <span class="he">עַל מֶלֶךְ</span> means the same as <span class="he">עַל־מֶלֶךְ</span>
:::

## Inseparable prepositions

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/06.4.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* Like <span class="he">וְ</span> for the word "and," an inseparable preposition is a one-letter prefix affixed to its object
* Three Hebrew prepositions are **ALWAYS** inseparable
    * <span class="he">בְּ</span> - in, at, with, by, against
        * <span class="he">בְּמֶ֫לֶךְ</span> -  With a king
    * <span class="he">כְּ</span> - as, like, according to
        * <span class="he">כְּמֶ֫לֶךְ</span> - Like a king
    * <span class="he">לְ</span> - to, toward, for
        * <span class="he">לְמֶ֫לֶךְ</span> - To/towards a king

::: {.box .info}
* A mnemonic to remember these three inseparable prepositions is "BucKLe"
* The first word of the Bible contains an inseparable preposition: <span class="he">בְּרֵאשִׁית</span> = "In (the) beginning"
:::

* In the lexical form of these prepositions, there is a Vocal Sheva vowel under the "buckle" consonant
* If there is a Sheva or Hateph vowel in the next letter, the Rule of Sheva come into play (see Lesson 4)
    * Before another Vocal Sheva, the preposition usually takes a Hireq
    * Before a Guttural with a Hateph vowel, the preposition takes the corresponding short vowel
    * Note the names of God again receive special treatment: <span class="he">לֵאלֹהִים</span> and <span class="he">לַיהוָה</span>
:::


* Finally, the ב and כ when they are the first letter of a word (as they usually will be), will take a Dagehsh Lene giving them the "hard" pronunciation
    * We actually saw this last lesson, but in a different context
    * It's <span class="he">בֵּן</span>, (between), but it's <span class="he">וּבֵן</span> (and between)
        * The conjunction ו becomes a וּּ before a BuMP letter
        * In this same example, you can see that <span class="he">בֵּן</span> (between) HAS the Dagesh Lene, but<span class="he">וּבֵן</span> (and between) does not and is pronounced with a "v" sound 

## _Hebrew Quest_ Preposition with Definite Article Lecture

View this 2-minute video from _Hebrew Quest_. You can ignore the references to Essentials of Biblical Hebrew. We will dig into the concepts in greater detail as we progress through the lesson. 

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
yY3O8ByYNwI?start=2303&end=2460
&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/yY3O8ByYNwI?t=2303){target="_blank"}

Start: 38:23
End: 41:00


## The Article and Inseparable Prepositions

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/06.6.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
* When a word has both the Article and an inseparable preposition, a form of contraction occurs:
    * The one-letter preposition replaces the <span class="he">ה</span> of the Article
    * The vowel under the preposition and the Dagesh Forte (if it is there) are your clues that the word is definite.

<img src="images/06.preposition_article.png" width="800pt" style="display: block; margin: auto;" />

### FIX GRAPHIC ^^^

* On reason we spend so much time talking about the Dagesh Forte is that it is an extremely useful clue as to what is going on within a word
* When a letter rejects the Dagesh Forte, this clue is gone
* Below is how we can tell whether there is the article with a preposition in the absence of a Dagesh

::: {.box .light}
ARTICLE WITH PREPOSITION

* NO ARTICLE if there is a Sheva under the preposition - the article never takes a Sheva
* NO ARTICLE if the short vowel under the preposition can be explained by the Rules of Sheva: 
    * <span class="he">אֲנָשִׁים + לְ = לַאֲנָשִׁים</span> - for men, (not 'for the men')
* ARTICLE if vowel under the preposition is not Sheva and can NOT be explained by the Rule of Sheva: 
    * <span class="he">לַהֵיכָל</span> = for THE temple
:::

## The flexible מִן: construction

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/06.7.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* <span class="he">מִן</span> is a unique preposition
    * It can be a Maqqef preposition, as in <span class="he">מִן־זָהָב</span>
    * It can also be an inseparable preposition: <span class="he">מִזָּהָב</span>
    * Both examples above literally mean "from gold" 
* Note the spelling of the inseparable preposition:

<img src="images/06.preposition_min.jpg" width="100pt" style="display: block; margin: auto;" />

* When we see `Mem+Hireq+Dagesh`, we know it is <span class="he">מִן</span> written as an inseparable preposition
* As we know by now, the Gutturals and Resh reject the Dagesh Forte:
    * <span class="he">א ע ה ר</span> have compensatory lengthening, so the Hireq becomes Tsere
    * <span class="he">ח</span> has virtual doubling, which as we remember means "virtually no doubling" in that the vowel under the <span class="he">מ</span> remains a Hireq
* SQiN eM LeVY with a Sheva may reject the Dagesh
    * As we know, there will never be any Compensatory Lengthening with a SQiN eM LeVY scenario
    * When we see מִקְ, מִיְ or Mem+Hireq followed by a SQiN eM LeVY letter and there is no Dagesh Forte, this may be a clue
    * We should say to ourselves, "I don't see a Dagesh Forte, but that's a `SQiN eM LeVY` letter. This may still be מִן."

## The Article and מִן

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/06.8.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

Unlike the regular "BucKLe" inseparable prepositions, the <span class="he">ה</span> of the article is ALWAYS RETAINED with <span class="he">מִן</span>

* <span class="he">מֵהָאָ֫רֶץ</sp = from the land.

<!-- 6.9 -->
## The flexible מִן: meanings 

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/06.9.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* <span class="he">מִן</span> occurs 7,592 times in the Bible, and can have multiple meanings
* The most direct purpose is "from" - <span class="he">מֵהָאָ֫רֶץ</span> from the land
* <span class="he">מִן</span> can also have comparative (think "bigger") and superlative (think "biggest") meanings depending on the context
    * <span class="he">טוֹבָה חָכְמָה מִזָּהָב</span> = wisdom is better *than* gold 
    * <span class="he">קָשָׁה הָעֲבֹדָה מֵהָאֲנָשִׁים</span> = the work is *too* difficult *for* the men
    * <span class="he">עָרוּם מִכֹל חַיַּת הַשָֹּדֶה</span>  = the *most* clever living thing *of all* the field
* There is also a use called "partitive" that denotes a portion or part of something else:
    * <span class="he">מֵהָאֲנָשִׁים</span> may mean "*some* *of* the men" (lit. from the men)
* Other uses: 'because', 'by', 'without', 'even', 'namely'.


::: {.box .info}
MEANING OF <span class="he">מִן</span>

* This is a word that takes practice to appreciate the various nuanced meanings
* As you are starting out in Hebrew, when you see <span class="he">מִן</span>, start your translation with "from..."
* However, don't be surprised if "from" does not make sense
* For example, if our translation is something like, "good the wisdom from the gold," we know that doesn't make sense
    * We need to remember the comparative or superlative uses
    * "_Better_ is wisdom _than_ gold"
:::

## The Definite Direct Object marker 

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/06.10.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* Hebrew has a word that is often used to mark a definite direct object (DDO)
* It has no translational value
* Spelling:
    * <span class="he">אֵת</span> (independent) 
    * <span class="he">אֶת־</span> (Maqqef)
* The challenge can be that this is the same spelling as the preposition "with" 
* As both the DDO and preposition can take pronominal suffixes, we will save a discussion of differentiating between the two words for Lesson 9 

::: {.box .info}
We see the DDO twice in the first verse of the Bible:

<span class="he">בְּרֵאשִׁית בָּרָא אֱלֹהִים *אֵת* הַשָּׁמַיִם *וְאֵת* הָאָרֶץ</span>

:::

## _Hebrew Quest_ discussion of Genesis 1:1 

* As a conclusion to this lesson, please watch the video below where Izzy discusses how to read a passage using Genesis 1:1
* Genesis 1:1 contains examples of the Article, the conjunction, an inseparable preposition and the DDO marker (Izzy also discusses how the DDO speaks of Messiah!)
* We encourage you to take notes using [a blank copy of Genesis 1:1-5](https://docs.google.com/document/d/1FIQAtWfWlrWmzX5pKR6esRLzJKFdv5Szx3mb5_zWwLg/copy){target="_blank"}^[In Unit 3, you will have the option of completing our "_Hebrew Quest_ Study Passage Track".  In Lesson 17, we will study Genesis 1:1-5, which is why this document has verses 1-5.]

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/sQKorif_GBk?start=732&end=2815" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/sQKorif_GBk?t=732){target="_blank"}

Start: 12:12
End: 46:55

## Conclusion {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/06.conclusion.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
How are you feeling so far?  Is any component of "the fog" refusing to dissipate? Keep sticking with `Anki`, and try to do your reviews at least once daily.

To help with this, we've gone a little bit lighter on the Grammar cards and the Ruth Pursuit for Lesson 6.  While there are some differences, prepositions are used much the same way in Hebrew as they are in English.  There is no sense in creating a lot of busy work.

We recommend using the time between now and starting Lesson 7 to get caught up and make sure the new concepts begin to take hold.  You might notice the intensity pick up with the next few lessons as we get into some ways Hebrew handles adjectives and pronouns.  Until then, enjoy learning some more of God's word with Izzy in the `Word warm-up` and `Verse warm-up`.

### Anki {-}

* `Lesson 06 A. Vocab`
* `Lesson 06 B. Grammar`
* `Lesson 06 C. Workbook`
    * In this activity, we will have brief passages of scripture that illustrate prepositions.
    * Make sure you look up any words you do not know.  You can download an abridged lexicon [here](./images/BBH_Lexicon.pdf){target="_blank"}.
* `Lesson 06 D. Verses`


## Word Warm-up {-}


<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/LL7YtEVZ8F0" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/LL7YtEVZ8F0){target="_blank"}



## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/isjp1Q3WPRE" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtube.com/embed/isjp1Q3WPRE){target="_blank"}

## Ruth Pursuit {-}        

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/06.ruth.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

::: {.box .map}
YOUR QUEST

1. Highlight the following words that begin with the inseparable prepositions and provide a definition (Yellow)
    * <span class="he">בָּאָרֶץ</span>
    * <span class="he">בַדֶּרֶךְ</span>     
    * <span class="he">לְבֵית</span>
    * <span class="he">לִי</span>     
2. Find examples of מִן (there is one Maqqef and the rest are inseparable) - translate the Maqqef phrase (look up the object of the מִן preposition in a lexicon if needed) (Green)
3. Find one example of the DDO (Maqqef) (Blue)
4. Find Lesson 6 vocabulary words:
    * <span class="he">עַד</span>
    * <span class="he">אַחֲרֵי
</span> (note: In Ruth 1, one instance of this word also has a מִן prefix (inseparable form) as well as a pronominal suffix, which we will study in Lesson 9)
    * <span class="he">כָּל־</span>(Pink)
:::

* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/copy){target="_blank"}
* [Ruth Pursuit Answer Key #6](./images/06_Ruth_Pursuit_KEY.pdf){target="_blank"}


## Quest Quiz {-}

[Open Quest Quiz #6 in a new window](https://forms.gle/oeB8E6K4y4mTjPWGA){target="_blank"}


<div class="containerLet">
<iframe class="responsive-iframe" src="https://docs.google.com/forms/d/e/1FAIpQLScSk6Jya_wOUJ4W88s8wcvY-3NyS2FnDmle4T6yo00Fus4Nmg/viewform?embedded=true" frameborder="0"></iframe>
</div>

<!--chapter:end:06-Prepositions.Rmd-->

# Hebrew Adjectives {#adjectives}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/07.intro.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

> To comprehend Biblical Hebrew, we must be able to identify and translate an adjective based on its usage, as well as its gender and number


::: {.infobox .map}
**LESSON ITINERARY**

1. Understand how an adjective relates to the noun it is modifying
1. Define and identify Substantival use
1. Define and identify Attributive use
1. Define and identify Predicative use
1. Determine the appropriate adjectival use in a passage
1. Define the function of the Mappiq and differentiate it from Daghesh marks
1. Recognize the Directional Ending and differentiate it from the vowel ה ָ
:::

::: {.box .stop}
EQUIPMENT CHECK

Before continuing, can you describe the following concepts?

* Inseparable prepositions with and without the definite article
* Construction and meaning of מִן, including assimilation of the נ

:::

## First Thought {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/07.ecc0311.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

### <span class="he">אֶת־הַכֹּל עָשָׂה יָפֶה בְעִתּוֹ</span> {-}

_He has made everything appropriate (beautiful) in its time.  (Ecclesiastes 3:11)_

Offer a word of gratitude that HaShem has made you beautiful!

<span class="he">יָפֶה</span> is an example of predicate adjective use, which we will study in this lesson.


<div class="figure" style="text-align: center">
<img src="images/07-Tabgha sacred stone where Jesus stood, tb102602022.jpg" alt="Tabgha - suggested location of Yeshua's restoration (making beautiful) of Shimon Kefa (Peter) on the beach in John 21, following Peter's denial of Yeshua a few days earlier. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="600pt" />
<p class="caption">(\#fig:unnamed-chunk-49)Tabgha - suggested location of Yeshua's restoration (making beautiful) of Shimon Kefa (Peter) on the beach in John 21, following Peter's denial of Yeshua a few days earlier. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>

## _Hebrew Quest_ Adjectives Lecture

View this 5-minute overview video from _Hebrew Quest_ Lesson 13.  If you looked at the Lesson Itinerary, you may not have been previously familiar with the terms "attributive" and "predicative" in terms of adjectives. In the video, when Izzy says, "the good trees", this is called the ATTRIBUTIVE use. When he says, "the trees are good", this is the PREDICATIVE use.


<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
yY3O8ByYNwI?start=2671&end=2978
&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>



[Click to open video in a new tab](https://youtu.be/yY3O8ByYNwI?t=2671){target="_blank"}

Start: 44:30
End: 49:38

## Inflecting Adjectives

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/07.2.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::


Adjective inflection is relatively straight-forward.

We will use the paradigm word <span class="he">טוֹב</span> to illustrate

<img src="images/07_adjective_gif.gif" width="300pt" style="display: block; margin: auto;" />

::: {.box .light}
WHY WOULD WE NEED TO INFLECT?

* Technically we don't; we will never be asked in reading the Hebrew Bible to take a MS adjective and inflect it into the FP
* We DO need to be able to identify the gender and number of an adjective based on its ending
* We MAY also need to identify the lexical form of an unfamiliar adjective when it has an ending and the vowels have changed
* For these reasons, learning adjectival inflection is beneficial
:::

1. An adjective is either masculine or feminine
2. An adjective is either singular or plural (dual nouns take plural adjectives)
3. An adjective will match the gender and number of the noun that it modifies or for which it substitutes
    * This is a big difference from nouns, which can change number but never gender
    * Note that for irregular nouns, the adjective will not necessarily match the exact ending
    * <span class="he">נָשִׁים טוֹבוֹת</span> - even though "<span class="he">נָשִׁים</span>" has the irregular -im ending, the adjective <span class="he">טוֹבוֹת</span> remains the regular feminine plural
4. An adjective will use expected gender and number endings as shown in the graphic above
5. The Lexical Form of an adjective is the MS
    * The MS form is usually endingless
    * The MS can be Seghol+Hei as in <span class="he">יָפֶה</span>, which is MS for pleasing, beautiful.

::: {.box .caution}
Note that unlike <span class="he">טוֹב</span>, most adjectives undergo vowel changes when the inflectional endings are added. 

The good news is you already know what to do. Adjectives follow the same rules as nouns.

:::

## Substantival Use

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/07.3.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
* In the Substantival use, the adjective acts as a noun
    * We could say the "Substantive Substitutes" for a noun
    * Perhaps an obvious example of this from pop culture is the film "The Good, The Bad, and The Ugly"  
        * The three words, "good", "bad", and "ugly" are adjectives being used as nouns
        * They are substantival adjectives
* In the substantival use, the noun is implied but not stated
    * It could be the "good one", the "bad man", or the "ugly idol"
* Remember that Hebrew gender does not always refer to an animate object
    * <span class="he">הַטּוֹבָה</span> - "the good" 
    * The word above is "the good (feminine singular something)"
    * Depending on the context, it could be "the good woman", or a feminine object like "the good Torah"

::: {.box .light}
SUBSTANTIVAL USE IS RELATIVELY EASY TO IDENTIFY 

* When you see an adjective but no related noun that matches in gender and number, the adjective is in the Substantival Use
* Think "the Good, the Bad, and the Ugly"
:::

## Attributive Use

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/07.4.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
* In the Attributive use, the adjective modifies and describes a noun
    * "Good" in "The good book" is Attributive 
* Hebrew makes it much easier to identify the Attributive use - see the mnemonic below
    * The adjective MUST come AFTER the noun it modifies
    * It MUST AGREE in definiteness 
        * This means both the noun and the adjective either HAVE the definite article or they both WILL NOT have the article
* <span class="he">הָאִשָּׁה הָטּוֹבָה</span> - the good woman
* <span class="he">אִשָּׁה טוֹבָה</span> - a good woman (or "the woman is good"-predicate use; see next section)

::: {.box .light}
ATTRIBUTIVE MNEMONIC

**A**ttributive **A**lways **A**fter noun, **A**rticle **A**grees

:::

## Predicative Use

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/07.4.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
* The Predicative use (often called the predicate use) asserts something about the noun
* In English translation, we must insert the applicable form of the verb "to be"
* The noun is the subject, and the adjective is the predicate of the sentence: "The book is good."
* In some ways, the rules for Hebrew Predicative use are the opposite of Attributive rules
    * The Predicative adjective will NEVER have the article
    * The Predicative adjective can come before or after the noun
    * The only ambiguity is when both the adjective and noun are indefinite and the adjective comes after the noun
* Examples:
    * <span class="he">טוֹבָה הָאִשָּׁה</span> - "the woman is good"
    * <span class="he">הָאִשָּׁה טוֹבָה</span> - "the woman is good"
    * <span class="he">טוֹבָה אִשָּׁה </span>- "a woman is good"
    * <span class="he">אִשָּׁה טוֹבָה</span> - this can either be Attributive "a good woman" or "a woman is good"

::: {.box .light}
PREDICATIVE MNEMONIC

**P**redicative de**P**rived of the article; **P**erhaps **P**rior

:::

## Adjective Use Comparison

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/07.6.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

As a brief review, determine whether the adjective is acting as Attributive, Predicative, or Substantival.  The answers and explanations are in the footnotes.

* <span class="he">הָאִשָּׁה הָטּוֹבָה</span> -^[**ATTRIBUTIVE - "Attributive Always After, Article Agrees"**  While a Predicative adjective can occur after the noun, this example can't be Predicative because the adjective has the article - "Predicate dePrived of Article..."]
* <span class="he">טוֹבָה הָאִשָּׁה</span> -^[**PREDICATIVE - "Predicative dePrived of article, Perhaps Prior"**  This example can't be attributive because the adjective comes before the noun and the article does not agree - "Attributive Always After, Article Agrees"]
* <span class="he">הָאִשָּׁה טוֹבָה</span> -^[**PREDICATIVE - "Predicative dePrived of article..."** This example can't be Attributive because the article does not agree  "Attributive Always After, Article Agrees"]
* <span class="he">טוֹבָה אִשָּׁה</span> -^[**PREDICATIVE - "Predicative dePrived of Article, Perhaps Prior"**While the adjective and noun agree in definiteness (both are indefinite), this example can't be Attributive because the adjective comes before the noun: "Attributive Always After..."]
* <span class="he">אִשָּׁה טוֹבָה</span> -^[**ATTRIBUTIVE or PREDICATIVE** The only time there can be any ambiguity between Attributive and Predicative is when the adjective comes after the noun and both are indefinite.  In these situations, we need to let the context determine the use]
* <span class="he">הַטּוֹבָה</span> -^[**SUBSTANTIVAL** This example can't be Attributive or Predicative because there is no noun that the adjective is modifying]

## The Mappiq 

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/07.7.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
* The Mappiq is a mark that you will see when reading the text
* The Mappiq looks exactly like a Daghesh (Lene or Forte), but it ONLY is found in the letter <span class="he">ה</span> and ONLY when it is the last letter of a word
    * Gutturals never take either Daghesh
    * Dagesh are never in the final letter of a word
* A word-final <span class="he">ה</span> is always part of a vowel unless it has a Mappiq (<span class="he">הּ</span>).
* The Mappiq is a sign that the breathy sound of the consonantal hei should be accentuated slightly
* It does not affect the word's meaning or syllabification


## The Directional Ending 

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/07.8.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* We've studied the fact that the <span class="he">ה ָ</span>  is the Feminine Singular ending
* We now need to refine this definition slightly: it is USUALLY the Feminine Singular ending
    * An ACCENTED <span class="he">ה ָ</span>  is the FS ending
    * However, an UNACCENTED <span class="he">ה ָ</span>  is known as a "directional ending"
* The directional ending is used to indicate motion towards or to, whatever the noun is
    * <span class="he">אַ֫רְצָה</span> - to/toward a land
    * <span class="he">הָעִ֫ירָה</span> - to/toward the city
* <span class="he">אֶל־הָאָ֫רֶץ</span> and <span class="he">אַ֫רְצָה</span> are synonymous
* <span class="he">אָנֹכִי אֵרֵד עִמְּךָ מִצְרַ֫יְמָה </span>
    * _I will go down with you to Egypt (Gen 46:4)_

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/5Hxru5RFuCA" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/5Hxru5RFuCA){target="_blank"}

## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/kDiDSdSHV3o" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/kDiDSdSHV3o){target="_blank"}

## Anki {-}

* `Lesson 07 A. Vocab`
* `Lesson 07 B. Grammar` 
* `Lesson 07 C. Workbook`
    * In this activity, we will have short passages of scripture that illustrate adjectives, including examples of attributive and predicate use
    * Be sure to look up any words you do not know.  
* `Lesson 07 D. Verses`


## Ruth Pursuit {-}        

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/07.rutn.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

Curiously, there are a lack of adjectives in Ruth 1.  There are _participles_, which are verbal adjectives, we will study in Lesson 22.  

::: {.box .map}
YOUR QUEST

1. Locate a few of the Mappiq marks (yellow)
2. Vocabulary words (green)
    1. Find the Hebrew word for "name," that you learned in the Lesson 3 Vocab; frequently, the word has the Vav conjunction
    2. Find the word for "very"
    3. Find the word for "daughters" - it occurs with a pronominal suffix, and means "my daughters"
    4. Find the phrase joined with a Maqqef that means "to the land (of)"
3. Other words (pink)
    1. Towards the end of the chapter, Naomi says, "don't call me Naomi (pleasant) call me 'Mara' (bitter)
        * Find the word for "bitter"
        * It occurs twice in two different forms
    2. Find the word for "Orpah"
    3. <span class="he">רֵיקָם</span> is a word that means "empty." It only occurs 16x in the entire Bible, and almost always with the sense of sending someone away empty-handed.<small>^[<small>A chuckle-worthy example is 1st Samuel 6:3 when the Philistines realize that the Ark is causing nothing but trouble for them.  They purposed to send the Ark back to Israel, but said "send it not empty!" They sent it back with trespass offerings representing the plagues they suffered: five golden mice and five golden tumors, which some scholars believe were actually hemorrhoids!</small>]</small>. In Ruth 1, Naomi said she left full but was sent back empty.  Find the lone example of this word near the end of the chapter.
    
Be sure to update your `Ruth Pursuit Translation Worksheet` with the findings from your Quest!

:::


* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/copy){target="_blank"}
* [Ruth Pursuit Answer Key #7](./images/07_Ruth_Pursuit_KEY.pdf){target="_blank"}
* Don't forget to update your `Ruth Pursuit Translation` worksheet with new words identified through lesson 7.

## Quest Quiz {-}

[Open Quest Quiz #07 in a new window](https://forms.gle/uYiUgRBWeRJikaR57){target="_blank"}

<div class="containerLet">
<iframe class="responsive-iframe" src="https://docs.google.com/forms/d/e/1FAIpQLSdheixGPVo9sfn-K51QEgjP8qaZQyqd2uQY6yAGV4hn8vqYyg/viewform?embedded=true" frameborder="0"></iframe>
</div>


## Claim your next `Twelve Tribes Badge`! {-}

When you have completed all activities on your `Hebrew GRAMMAR Quest Checklist` through Lesson 7, complete the certification below, and your Dan badge and devotional will be on their way!

<!-- Tribe Badge 3 = Dan -->

<div class="containerLet">
<iframe class="responsive-iframe" src="https://forms.gle/u7NiyG7MzE4inxj86" frameborder="0"></iframe>
</div>

<!--chapter:end:07-Adjectives.Rmd-->

# Hebrew Pronouns

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/08.intro.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

> To comprehend Biblical Hebrew, we must be able to identify pronouns with gender, number, and person 

Pronouns are a form of shorthand so we don't have to keep repeating nouns (because saying all of those nouns over and over can really wear you down<small>^[If you grew up in the late 70s and early 80s, you might be familiar with the [Schoolhouse Rock Pronoun video](https://www.youtube.com/watch?v=cZaMXYAu9h0){target="_blank"}</small>]</small>).

The main challenge with a pronoun is determining the noun _it_ replaces.  See what happened there?  We used the pronoun "it".  You probably deduced "it" was referring to the word "pronoun," not "noun."  That is because you are very familiar with English context and syntax.  

* The example, "John saw Bob. He said, 'hello'" is ambiguous; we are not sure what the author meant to convey
* The example "John saw Sally. He said, 'hello'" is not ambiguous at all
* Hebrew works very similarly

As such, this is an important topic that will take two lessons (8 and 9). A firm grasp of pronouns helps us to decipher what is happening in the narrative.

::: {.infobox .map}
**LESSON ITINERARY**

1. Define the phrase "independent personal pronoun"
2. Identify and define Hebrew's relative pronoun
3. Identify Hebrew's interrogative pronouns
4. Distinguish the interrogative particle from the definite article
5. Identify and translate the near and far demonstratives
6. Detect demonstrative adjective use
7. Detect demonstrative pronoun use
:::

::: {.box .stop}
EQUIPMENT CHECK

Before continuing, can you describe the following concepts?

* Define and translate substantival, attributive, and predicate adjectives (at a summary level)
* How Hebrew inflects adjectives, so we can identify Gender and Number
* The directional ending as compared with the FS ending

::: 

## First Thought {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/08.is3021.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

### <span class="he">זֶה הַדֶּרֶךְ לְכוּ בוֹ</span> {-}

_This is the way, walk in it  (Isaiah 30:21)_

Pray that you continually walk in His way, not your own way



The first word in the passage above is an example of a "demonstrative pronoun". The first two words are translated, "this is the way".  Contrast "this is the way" with the phrase "this way."  "This way" would be written <span class="he">הַדֶּרֶךְ הַזֶּה</span>.  "This way" is an example of a "demonstrative adjective."  

*****

<div class="figure" style="text-align: center">
<img src="images/08-Sea of Galilee and Plain of Gennesaret panorama, tb03250771p.jpg" alt="Sea of Galilee and Plain of Gennesaret. Yeshua likely walked this way through the valley on His way from Nazareth to Capernaum (a town on the coastline, roughly in the center of the picture above). Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="600pt" />
<p class="caption">(\#fig:unnamed-chunk-51)Sea of Galilee and Plain of Gennesaret. Yeshua likely walked this way through the valley on His way from Nazareth to Capernaum (a town on the coastline, roughly in the center of the picture above). Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>

## _Hebrew Quest_ Independent Pronouns Lecture

View this 5-minute overview video from _Hebrew Quest_.  The first table Izzy reviews is reproduced in the next section. Pronominimal suffixes will be discussed in the next lesson.

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/yY3O8ByYNwI?start=638&end=912&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/yY3O8ByYNwI?t=638){target="_blank"}

Start: 10:38
End: 15:12

## Independent Personal Pronoun Table

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/08.2.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

P/G | S | P
:-: | :-: | :-:
1C | <span class="he">אֲנִי ,אָנֹכִי</span> | <span class="he">אֲנַ֫חְנוּ</span> 
2M  | <span class="he">אַתָּה</span> | <span class="he">אַתֶּם</span> 
2F | <span class="he">אַתְּ</span> | <span class="he">אַתֵּ֫נָה</span>  
3M  | <span class="he">הוּא</span> | <span class="he">הֵם ,הֵ֫מָּה</span> 
3F  | <span class="he">הִיא ,הִוא</span> | <span class="he">הֵן ,הֵ֫נָּה</span>  

* You will work on memorizing these in `Anki`
* The 3FS form הִוא is found only in the Torah

::: {.box .info}
PRONOUN TIPS

* All 1st person pronouns begin with <span class="he">אנ</span> 
* All 2 begin with accented <span class="he">אַתּ֫</span> - note the Daghesh Forte
* All 3 begin with accented <span class="he">ה֫</span>
* All MP end with either <span class="he">מָה</span> or <span class="he">ם.</span> Think "monks" since men are monks
* All FP end with either <span class="he">נָה</span> or <span class="he">ן.</span> Think "nuns" since women are nuns
* Hu (<span class="he">הוּא</span>) is he
* Hi (<span class="he">הִיא</span> ) is she
* Mi <span class="he">מִי</span> is who?
:::

## Independent Personal Pronouns Discussion

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/08.3.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* Independent personal pronouns are _always_ subjects, meaning they are equivalent to I, you, she, he, it, and they in English (NOT me, my, her, him, his)
* This is the first time we are officially using all three elements of Person, Gender, and Number
    * 3MS is shorthand for Person = 3rd Person, Gender = Masculine, Number=Singular
* 1st person
    * Like English, Hebrew does not distinguish between gender in the first person
    * A woman says "I" and a man says "I"
    * <span class="he">אָנֹכִי</span> is considered more formal or emphatic.  It is often translated, "I, myself"
* Do not confuse <span class="he">אַתָּה</span> (you 2MS) with <span class="he">עַתָּה</span> (now)
    
## Relative Pronoun אֲשֶׁר

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/08.4.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* Hebrew has one general-purpose relative pronoun
* <span class="he">אֲשֶׁר</span> is a vocabulary word for this lesson
* This word does not inflect/the spelling never changes
* It can refer to people (who) or things (that), subjectively (who) or objectively (whom)
* <span class="he">אֵלֶּה הַדְּבָרִים *אֲשֶׁר* דִּבֶּר מֹשֶׁה</span>
    * _These are the words *that* Moses spoke (Deuteronomy 1:1)_



## Interrogative Pronouns

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/08.5.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
* <span class="he">מִי</span> = who
* <span class="he">מָה</span> = wha
    * Can also be written as Maqqef - note the vowel shortens <span class="he">מַה־</span>
*   <span class="he">לָמָה</span> = why
    * <span class="he">אֵלִ֣י אֵ֖לִי לָמָ֣ה עֲזַבְתָּ֑נִי</span>
    *  _My God, my God, WHY have you forsaken me? (Psalms 22:1)_

::: {.box .info}

Usually, interrogative pronouns will appear at the beginning of a clause

:::

## _Hebrew Quest_ Interrogative Particle Lecture

View this 2-minute  video from _Hebrew Quest_, then we will dig into the concepts in greater detail as we progress through the lesson. 

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
yY3O8ByYNwI?start=1758&end=1835
&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/yY3O8ByYNwI&t=1758){target="_blank"}

Start: 29:18
End: 30:35

## Interrogative Particle הֲ

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/08.7.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::

* English has a question mark at the end of a sentence
* Hebrew has what is called an interrogative particle at the BEGINNING of a sentence
* The interrogative particle ONLY asks a yes/no question
    * Questions that ask who? what? or why? will use interrogative pronouns
* We notice that  <span class="he">הֲ</span> looks a lot like the definite article - the next section will examine differences

## Interrogative Particle vs. Definite Article 

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/08.8.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
* Despite the similarity, we will not usually have trouble differentiating the Article from the Interrogative Particle
* Below are potential sources of ambiguity:
    * 1st word of a clause before <span class="he">חָ֫,חָ, הָ, עָ</span>   = both are <span class="he">הֶ</span>
    * 1st word of a clause before <span class="he">ה, ח</span> without Qamets or SQiN eM LeVY with Sheva = both are <span class="he">הַ</span>
    * In these situations we will need to let context determine whether a question is being asked
* With lots of reading practice, this will get easier
* Additionally, the Definite Article is about **300X more common**




## _Hebrew Quest_ Demonstratives Lecture


View this brief overview video from _Hebrew Quest_, then we will dig into the concepts in greater detail as we progress through the lesson. 

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
yY3O8ByYNwI?start=1160&end=1232
&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/yY3O8ByYNwI?t=1160){target="_blank"}

## Near and Far Demonstratives

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/08.10.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
* Demonstratives indicate distance
* Hebrew has three words to indicate nearness; grammarians call these "near demonstratives"
    * MS - <span class="he">זֶה</span> - "this"
    * FS - <span class="he">זֹאת</span> - "this"
    * (M/F)P - <span class="he">אֵ֫לֶּה</span> - "these"
* The Hebrew words for farness ("far demonstratives") are the same as the subject pronouns
    * MS - <span class="he">הוּא</span> -"that"
    * FS - <span class="he">הִיא</span> - "that"
    * MP - <span class="he">הֵם ,הֵ֫מָּה</span> - "those"
    * FP - <span class="he">הֵן ,הֵ֫נָּה</span> - "those"
    
::: {.box .caution}
POTENTIAL AMBIGUITY

<span class="he">הוּא הָאִישׁ</span> can mean either "he is the man," (personal pronoun) or "that is the man" (demonstrative pronoun)

:::

## Demonstrative Pronoun

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/08.11.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
* Demonstratives act as adjectives or as pronouns
* As we saw in the example <span class="he">הוּא הָאִישׁ</span>, a demonstrative pronoun takes the place of a noun as the subject of a clause<small>^[<small>When <span class="he">הוּא הָאִישׁ</span> means "he is the man", the personal pronoun "he" is the subject</small>]</small>
* The behavior of the demonstrative pronoun is a lot like the Predicative Adjective use: 
    * Always comes before the noun (Pronoun Perpetually Precedes)
    * Does NOT have the article (Pronoun dePrived of article)
    * Matches Gender and Number
        * <span class="he">זֹאת הַמַּלְכָּה</span>  = this is the queen (FS)
        * <span class="he">זֶה הַמֶּ֫לֶךְ</span> = this is the king (MS)

::: {.box .info}
DEMONSTRATIVE PRONOUN MNEMONIC

Demonstrative Pronoun Perpetually Precedes, Perpetually dePrived of article

:::


## Demonstrative Adjective 

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/08.12.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
* A demonstrative adjective modifies a noun just as an attributive adjective does
* The behavior is a lot like the Attributive Adjective use: 
    * Always comes after the noun (Dem Adjective Always After)
    * Always has the Article (Dem. Adjective Always Article)
        * A demonstrative adjective is referencing a specific something or someone; therefore, it is always definite
    * Always matches in Gender and Number
    * <span class="he">הָאִשָּׁה הַזֹּאת</span> = this woman (FS)
    * <span class="he">הָאֲנָשִׁים הָהֵם</span>  = those men (MP)

::: {.box .info}
DEMONSTRATIVE ADJECTIVE MNEMONIC

Demonstrative Adjective Always After the noun, Always has Article, Always Agrees

:::


## Lesson 8 Conclusion {-}

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/08.conclusion.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
* Your mission is to focus on building your pronoun vocabulary!
    * You may notice more `Anki` words than usual to learn, but most of these are short
    * After you finish the stack in `Anki,` we have two pronoun worksheets for you to test your memory
* Know the gender, number, and, where necessary, the person of each pronoun
    * For learning purposes, get in the habit of providing the PGN whenever translating "you"
        * For example, אַתֵּ֫נָה = "you" (2FP)

::: {.box .map}

If you can picture yourself hiking the trails of Israel,  Lessons 8, 9, and 10 may represent some steeper hills where you may need to push a little bit to make it to the top.  Then we'll get a bit of a breather with Lessons 11 and 12 before ramping up again with Qal Verbs in Unit 3.  Keep pushing forward!  You're doing awesome!

<div class="figure" style="text-align: center">
<img src="images/08-manna-ko-hiking-en-gedi.jpg" alt="Hiking in Ein Gedi, Israel, 2013. Photo by Chris Flanagan. Used by permission." width="600pt" />
<p class="caption">(\#fig:unnamed-chunk-52)Hiking in Ein Gedi, Israel, 2013. Photo by Chris Flanagan. Used by permission.</p>
</div>
:::

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/_5MpcMzKxWk" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/_5MpcMzKxWk){target="_blank"}

## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/wUF6y7MHtuc" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/wUF6y7MHtuc){target="_blank"}

## Anki {-}

* `Lesson 08 A. Vocab`
* `Lesson 08 B. Grammar`
* `Lesson 08 C. Workbook`
* `Lesson 08 D. Verses`

## Worksheets: Pronouns {-}


We have two worksheets for this lesson. Make sure you do the Anki work first before tackling these worksheets.

While our focus is on reading Hebrew, pronouns are so prevalent that it's highly beneficial to commit them to memory.  Review the column on the right, then cover it up and try to complete the remaining columns by memory (right to left).

1. [Subject Personal Pronouns](./images/08_subject_paradigm.pdf){target="_blank"}
2. [Demonstrative Pronouns](./images/08_demonstrative_paradigm.pdf){target="_blank"}


## Ruth Pursuit {-}        

::: {.infobox .sound}
<figure> <audio id="myAudio" controls controlsList="nodownload" 
src="./images/08.ruth.mp3">
Your browser does not support the <code>audio</code> element.</audio><button onclick="x25()" type="button">2.5x</button><button onclick="x2()" type="button">2x</button><button onclick="x15()" type="button">1.5x</button><button onclick="x1()" type="button">1x</button><button onclick="x075()" type="button">.75x</button><button onclick="x05()" type="button">.5x</button><script>
var x = document.getElementById("myAudio");
function x05() { 
    x.playbackRate = 0.5;
    x.play();}
function x075() { 
    x.playbackRate = 0.75;
    x.play();} 
function x1() { 
    x.playbackRate = 1;
     x.play();}
function x15() { 
    x.playbackRate = 1.5;
     x.play();} 
function x2() { 
    x.playbackRate = 2;
     x.play();} 
function x25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script></figure>
:::
::: {.box .map} 
YOUR QUEST

Just as the vocabulary for Lessons 8 and 9 are a bit longer, the `Ruth Pursuit` exercise for this lesson has 33 total "finds." There are 34 words to locate in `Ruth Pursuit` #9.  Be patient, and you'll find them all!

Identify each occurrence of the following:

1. Pronoun Vocabulary (yellow)
    1. The relative pronoun meaning "who, whom, that, which," and the related pronoun meaning "as, when"
    2. Independent Pronouns: I, he, she, them, they, you (these may have prepositional prefix)
2. Interrogative (green)
    1. Interrogative pronouns from Lesson 8 vocabulary
    2. The idiom <span class="he">הַעוֹד־לִי</span>, means "have I yet?" or "do I have?"
    2. Other uses of the interrogative particle
2. Other vocabulary words(blue)
    1. because/for/if
    2. also/even
    3. Therefore (also has interrogative particle)
4. Find one near demonstrative pronoun (also has interrogative particle) (Pink)
    * Translate the demonstrative
    
:::

* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/copy){target="_blank"}
* [Ruth Pursuit Answer Key #8](./images/08_Ruth_Pursuit_KEY.pdf){target="_blank"}


## Quest Quiz {-}

[Open Quest Quiz #8 in a new window](https://forms.gle/Ew13bcUBZM8T7ck86){target="_blank"}

<div class="container">
<iframe class="responsive-iframe" src="https://docs.google.com/forms/d/e/1FAIpQLSd4cI1lk3APqQvyt8FT7muC_i3dR-wwiD6zgIdKwJCiXbgMuQ/viewform?embedded=true" frameborder="0"></iframe>
</div>


<!--chapter:end:08-Pronouns.Rmd-->

# Hebrew Pronominal Suffixes

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/09.intro.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

> To comprehend Biblical Hebrew, we must be able to translate a noun or preposition with a pronominal suffix

In this lesson, we continue the discussion on pronouns.  In Lesson 9, we focus on an aspect of pronouns we don't have in English - pronominal suffixes.  


::: {.infobox .map}
**LESSON ITINERARY**


1.  Understand the meaning of pronominal suffixes
2.  Define Type 1 and Type 2 suffixes
3.  Differentiate Type 1 from Type 2
4.  Identify the Lexical Form of a Noun with a Type 1 Suffix
5.  Identify the Lexical Form of a Noun with a Type 2 Suffix
6.  Recognize unusual changes with pronominal suffixes
7.  Identify look-alike words involving pronominal suffixes
:::

::: {.box .stop}
EQUIPMENT CHECK

Before continuing, can you describe the following concepts?

* Independent personal pronouns (memorized)
* The difference between the definite article and the interrogative particle
* Hebrew demonstratives
:::

## First Thought {-}

### <span class="he">וַיֹּאמְרוּ שָׁאוֹל שָׁאַל־הָאִישׁ לָנוּ וּלְמוֹלַדְתֵּנוּ </span> {-}

*This man heavily questioned us and our kindred. (Genesis 43:7)*

In addition to offering up our petitions, let us be sure to hear God's questions.  What is He asking you (or asking of you) today?  Take a moment.

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/09.gen4327.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>


*****

<div class="figure" style="text-align: center">
<img src="images/09-Banias waterfall, tb032704275.jpg" alt="Banias waterfall. Region of Caesarea Philippi where Yeshua asked his talmidim a fundamental question, 'who do YOU say that I am?'. With our choices, we have the opportunity to answer this same question practically every moment of every day. See Matthew 16:13-17. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-53)Banias waterfall. Region of Caesarea Philippi where Yeshua asked his talmidim a fundamental question, 'who do YOU say that I am?'. With our choices, we have the opportunity to answer this same question practically every moment of every day. See Matthew 16:13-17. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>

## _Hebrew Quest_ Possessive Pronominal Suffixes Lecture

View this overview video from _Hebrew Quest_ on possessive suffixes.  Don't fret if you don't fully understand this material on the first pass through the video.  We will break down these concepts as we progress through the lesson.   We will discuss Construct forms in Lesson 10.

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
yY3O8ByYNwI?start=912&end=1647
&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/yY3O8ByYNwI?t=912){target="_blank"}

Start: 15:12
End: 27:27

## _Hebrew Quest_ Pronominal Suffixes

Although this 10-minute video is from the "Complex Verbs" section of _Hebrew Quest_, the concepts Izzy discusses apply to Lesson 9 of Hebrew GRAMMAR Quest.  At this time, don't worry about any references to verb stems. We will study _verbal_ pronominal suffixes in Lesson 19.

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/hWmwyosdP-s?start=2731&end=3341&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/hWmwyosdP-s?t=2731){target="_blank"}

Start: 45:31
End: 55:41

## Possessive Pronominal Suffix Meaning

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/09.3.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

Hebrew has another type of pronoun in addition to stand-alone words.  In Lesson 6, we learned about one-letter preposition prefixes to words.  Pronominal suffixes work similarly. The difference is these go on the back of words instead of the front.

* On a noun, a pronominal suffix indicates the one who owns or is related to the noun:  His books / her houses / their house / our father
* On a preposition, the suffix indicates the object: to her / with them / behind him / in front of it
* Verbs also take pronominal suffixes, which will indicate the verb's object.  We will study these in Lesson 19.

Pronominal suffixes have *gender*, *number*, and *person*.

::: {.box .info}
* Independent personal pronouns were always "subject" pronouns (e.g., I, she, he, it, and they)
* Pronominal suffixes are always "object" or "possessive" pronouns (e.g., me, my, her, him, them, theirs)
:::

::: {.box .caution}
* "You" can be an ambiguous term in English, not only with number and gender but also, "you" can be either a subject or object
* Hebrew has distinct ways of saying 2MS, 2FS, 2MP, and 2FP, as well as different forms for subject and object
:::

## Type 1 and Type 2 Suffixes

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/09.4.m4a"> Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script> 
</figure>
:::

* Hebrew has two distinct groups of Pronominal suffixes
* **Type 1** suffixes go on **SINGULAR** nouns<small>^[<small>As with most grammar rules, there are exceptions. For now, stick with these definitions of Type 1 and Type 2.</small>]</small>
    * Keep in mind there are both plural and singular Type 1 suffixes for use on singular nouns
    * Multiple people can have ownership of a single object
    * In English, we would say "his house" and "their house"
* **Type 2** suffixes go on **PLURAL** nouns
    * Similar to above, there are both singular and plural type 2 suffixes for use on plural nouns
    * "his houses" as well as "their houses"
* The type of suffix on a preposition means nothing in terms of translation; each preposition will only take one class or the other

## Singular Suffixes

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/09.5.m4a"> Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script> 
</figure>
:::
* While Type 1 and Type 2 suffixes have key differences, there are also some commonalities with both types' singular suffixes.
* Below are the singular suffixes

<img src="images/09.ps_sing_tbl.png" width="400pt" style="display: block; margin: auto;" />

* 1CS end with י
* 2MS/2FS end with ך
* Not all 3M/3F have ה, but every ה is 3M/3F

## Plural Suffixes

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/09.6.m4a"> Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script> 
</figure>
:::
Below are the plural suffixes:

<img src="images/09.ps_plrl_tbl.png" width="400pt" style="display: block; margin: auto;" />

* 1CP ends with נוּ
* 2MP/2FP have כ
* Not all 3M/3F have ה, but every ה is 3M/3F
* 2MP/3MP has מָה or ם ('monks')
* 2FP/3FP has נָה or ן ('nuns')

## Distinguish Type 1 from Type 2

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/09.7.m4a"> Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script> 
</figure>
:::
Look at the chart below with the two types side-by-side.

::: {.box .light}
Type 2 **always** contains vowel + yod, but **not** hiriq + yod  
Type 1 **never** contains yod, *unless* it's hiriq+yod
:::

* This simple rule, plus the tips on the previous pages about patterns in gender and number, should make it easier to identify the pronominal suffix.
* When you encounter a word with a suffix, always start by asking, "is there a vowel + yod, that is not hiriq + yod?"
* If yes, then we have a Type 2 suffix, which indicates the noun is plural


<img src="images/09.ps_both_tbl.png" width="600pt" style="display: block; margin: auto;" />


## Identifying the Lexical Form with Type 1

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/09.8.m4a"> Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script> 
</figure>
:::
Part of learning to read Biblical Hebrew is assembling a set of skills that make it easier to navigate when you encounter an unfamiliar word in the Text.  A noun is more likely to be unfamiliar to you than a preposition, so we'll focus on nouns.  Below is a procedure you may follow that should help with this.  The steps for a Type 1 suffix are on this page, and the steps for Type 2 are in the next section.

1. Remove the pronominal suffix
    * With שִׁיר, we are done at step 1
2. Remembering that type one suffixes can *only* go with SINGULAR nouns, the next step is to fix the singular ending as needed 
    * If the remaining word has a word-final <span class="he">ת</span>, it is likely feminine. Replace <span class="he">ת ַ</span> or <span class="he">ת ָ</span>  with<span class="he"> ה ָ</span> (usually)
        * See תּוֺרָתָם as an example
        * Note בֵּית does not have a feminine ending; we will recognize this word from our vocabulary memory
    * If the remaining word does not end with a <span class="he">ת</span>, it is likely masculine.  Most often, masculine words are endingless, but sometimes you may need to add the masculine singular ending <span class="he">ה ֶ</span>
        * See שָֹדֶה, which is another word that should be memorized
3. If there is a word-internal tsere + yod (i.e. in the middle of the word), replace with the diphthong <span class="he">יִ ַ֫</span>
    * See word בֵּיתְךָ
4. Change other vowels as needed according to the vowel preference table we studied several lessons ago
    * See word דָּבָר
 
Here is Dr. Beckman's example of the four steps using five example words with Type 1 suffixes.  Note that words do not always need all four steps.

<img src="images/09.lex_type1_tbl.png" width="400pt" style="display: block; margin: auto;" />

## Identifying the Lexical Form with Type 2

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/09.9.m4a"> Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script> 
</figure>
:::
::: {.box .light}
* Type 2 suffixes can *only* go with PLURAL nouns
* The Lexical Form is going to be the SINGULAR
* The only additional step from a Type 1 is we need to address the plural ending (step 2)
:::

1. Remove the pronominal suffix
2. Remove the <span class="he">וֹת</span> ending if there is one
        * Keep in mind that the word could exhibit defective spelling as with <span class="he">שְֹדֹת</span> below
3. Add the appropriate singular ending, if needed
    * If the word ended with a <span class="he">וֹת</span>, it is Feminine. Replace with <span class="he">ה</span> ָ (usually)
    * If the remaining word does not end with <span class="he">וֹת</span>, it is likely masculine.  Most often, masculine words are endingless, but sometimes you may need to add the masculine singular ending <span class="he">ה ֶ</span>
4. If there is a word-internal tsere + yod (i.e. in the middle of the word), replace with the diphthong <span class="he">יִ ַ֫</span>
5. Change other vowels as needed according to the vowel preference table we studied several lessons ago.

Here is Dr. Beckman's example of the five steps.  Note that words do not always need all five iterations.

<img src="images/09.lex_type2_tbl.png" width="400pt" style="display: block; margin: auto;" />

## Unexpected changes

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/09.10.m4a"> Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script> 
</figure>
:::
Two of the prepositions we studied in Lesson 6 undergo some irregular changes you will encounter as you read the Bible.

* <span class="he">כְּ</span> (like, as) and <span class="he">מִן</span> (from, etc.) often insert an extra <span class="he">מוֹ</span> or <span class="he">מּ</span> in some forms
    * Like you (2MS): <span class="he">כָּמ֫וֹךָ</span>
    * From you (2MS): <span class="he">מִמְּךָ</span>

* <span class="he">אָח</span> adds a hireq + yod before all type 1 suffixes
    * My brother (1CS): <span class="he">אָחִי</span>
    * Our Brother (1CP): <span class="he">אָחִינוּ</span>
    
The rule still applies:

::: {.box .light}  
* Type 2 suffixes **always** contain with vowel + yod, but **not** hireq + yod
* Type 2 suffixes **never** contain vowel + yod **unless** it's hireq + yod
:::


## Look-alike words: אֵת as "with" or as Definite Direct Object (DDO) marker

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/09.11.m4a"> Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script> 
</figure>
:::
* As we learned previously, <span class="he">אֵת</span> can mean either the DDO or the preposition "with".  They are spelled the same way, and either form can take a pronominal suffix.
* <span class="he">אֵת</span> with a regular Type 1 pronominal suffix is the DDO when the <span class="he">א</span> has a vowel-marked as <span class="he">אֹ</span> or <span class="he">אֶ</span>
    * 3MS: <span class="he">אֹתוֹ</span>
    * 2FP: <span class="he">אֶתְכֶן</span>
* When then author intends to communicate the preposition with, as in "with him", the א will take a Hireq in all forms
    * With me (1CS): <span class="he">אִתִּי</span>
    * With them (3FP): <span class="he">אִתָּן</span>

## Look-alike words: עִם, "with", or עַם "people" 

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/09.12.m4a"> Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script> 
</figure>
:::
These two words frequently take pronouns.  It could be easy to get them confused.  The trick is to pay close attention to the vowel under the ע.

* <span class="he">עִם</span> , with, will always have Ayin+Hireq, whereas <span class="he">עַם</span>, people, will always have Ayin+Patach
    * With Me (1CS): <span class="he">עִמִּי</span>
    * My People (1CS): <span class="he">עַמִּי</span>
    * With them (3MP):  <span class="he">עִמָּם</span>
    * Their people (3MP):  <span class="he">עַמָּם</span>

## Look-alike words: אֵל "God", or אֶל, "to"

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/09.13.m4a"> Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script> 
</figure>
:::

This one is _slightly_ easier.  

* <span class="he">אֵלִי</span>, my God is the only form of <span class="he">אֵל</span> that appears with a pronominal suffix in the Bible
* to me (1CS) is: <span class="he">אֶלַי</span> - Patach under the <span class="he">ל</span>

Although <span class="he">אֵל</span> may not appear with a suffix apart from this one time, <span class="he">אֱלֹהִ֑ים</span> can, and in the Torah, frequently does take suffixes.   The words below are close but not equivalent.

* <span class="he">אֱלֹהֶ֑יךָ</span>  = your God (See Deuteronomy 6:5)
* <span class="he">אֵלֶ֫יךָ</span> = to you (2MS)
* <span class="he">אֱלֹהִ֑ים</span>  = God, gods
* <span class="he">אֲלֵיהֶם</span> = to them (3MP)
* <span class="he">אֱלֹהֵֽינוּ</span> = our God (Exodus 3:18)
* <span class="he">אֵלֵ֫ינוּ</span> = to us (1CP)
* <span class="he">אֱלֹהָֽי</span> = my gods (Genesis 31:30)
* <span class="he">אֵלֶ֫יהַ</span> = to her/it (3FS)

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/J81JGz2CZak" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/J81JGz2CZak){target="_blank"}

## Word Warm-up: pronominal suffixes {-}

We have created a special `Word Warm-up` for the pronominal suffixes.

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/V12n6fg2ASE" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/V12n6fg2ASE){target="_blank"}


## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/il-4zlhzD_Y" frameborder="0"></iframe>
</div>


[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/il-4zlhzD_Y){target="_blank"}

## Anki {-}

* `Lesson 09 A. Vocab`
* `Lesson 09 B. Grammar` 
* `Lesson 09 C. Workbook` - Pay close attention to gender and number
* `Lesson 09 D. Verses`

## Worksheets: Pronominal Suffixes {-}


After you have done your Anki work, we have an additional worksheet to help you drill your pronominal suffixes.  As with previous worksheets, study, then cover-up the first column on the right and see if you can complete the remainder of the worksheet by memory.

[Pronominal Suffix](./images/09_pronominal_suffix_paradigm.pdf){target="_blank"}

## Ruth Pursuit {-}        

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/09.ruth.m4a"> Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); } 
</script> 
</figure>
:::

::: {.box .map} 
YOUR QUEST

1. Identify words with pronominal suffixes affixed to the following familial nouns (yellow)
    * sons
    * children
    * people (be mindful of the difference between `people` and `with`)
    * daughters
    * God/gods (be cognizant of the difference between `God` and `to them`.)
    * mother-in-law <span class="he">לַחֲמוֹתָהּ</span>
    * widow <span class="he">יְבִמְתֵּךְ</span>
    (we are excluding "his wife", "her daughters-in-law", and "her husband" since you found those in previous lessons!)
2. Identify words with pronominal suffixes affixed to the following other nouns (green)
    * voice
3. Identify words with pronominal suffixes affixed to the following prepositions (pink)
    * between
    * with
    * in
    * to
    * about
4. Identify the vocabulary word for "food" or "bread" that is NOT part of a city's name (blue)

> You may see other words with pronominal suffixes.  These are verbs that we will cover in Lesson 19.

:::


* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/copy){target="_blank"}
* [Ruth Pursuit Answer Key #09](./images/09_Ruth_Pursuit_KEY.pdf){target="_blank"}<small>^[<small>Note: Many English Bibles contain a footnote at Ruth 1:20 that Naomi means "pleasant"; however, the precise etymology of Naomi's name is unclear.  While her name appears to have a Type 1 1CS suffix, since it is a proper name, we are not including it in our answer key.</small>]</small>


## Quest Quiz {-}

<div class="containerLtr">
<iframe class="responsive-iframe" src="https://forms.gle/7Jgs8W2vi6XKTukG6" frameborder="0"></iframe>
</div>

[Open Quest Quiz #9 in a new window](https://forms.gle/7Jgs8W2vi6XKTukG6){target="_blank"}

<!--chapter:end:09-Pronominal_Suffixes.Rmd-->

# Hebrew Construct Chain {.ConstructChain}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/10.intro.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

> To comprehend Biblical Hebrew, we must be able to identify words in a construct state.

You might be surprised to learn that you are already familiar with at least one Hebrew Construct chain.

<span class="he">בֵּית לֶחֶם</span>, the word you probably know as "Bethlehem", literally means "house of bread" and is a Hebrew construct chain.  The first thing you might notice is that <span class="he">בַּ֫יִת</span>, the word for "house", is spelled a little differently.  The reason for this is that <span class="he">בֵּית</span> is in what we call a "construct" form or state.  

* <span class="he">בַּ֫יִת</span> means "house", and is said to be in "absolute" form
* <span class="he">בֵּית</span> means "house of", and is said to be in "construct" form

In this lesson, we will discuss the parameters of a Hebrew construct chain.  Keep in mind that we do not need to spell the construct state for a given noun.  Our primary goal is to *recognize* it and translate it adequately when we read our Bibles.

::: {.infobox .map}
**LESSON ITINERARY**

1. Describe what is meant by the term "construct chain"
2. Define a Hebrew construct chain 
3. Review and identify what makes a word definite 
4. Determine the definiteness of a chain
5. Differentiate between absolute state and construct state words
:::

::: {.box .stop}
**EQUIPMENT CHECK**

Before continuing, can you describe the following concepts?

* The pronominal suffixes (you have them memorized)
* Define Type 1 and Type 2 pronominal suffixes
:::

## First Thought {-}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/10.09.pro0808.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

### <span class="he">בְּצֶדֶק כָּל־אִמְרֵי־פִי</span> {-}

_All the utterances of my mouth are in righteousness (Proverbs 8:8)_



<span class="he">כָּל־אִמְרֵי־פִי</span> "all _of_ the utterances _of_ my mouth" is a construct chain.

*****

<div class="figure" style="text-align: center">
<img src="images/10-Capernaum synagogue interior, tb102702014.jpg" alt="Capernaum synagogue. Although this structure was built after the time of Yeshua, archeologists are convinced the current building rests on the foundation of an earlier synagogue.  This  synagogue was the probable location where Yeshua taught in righteousness as recorded in Mark 1:21-28, Luke 4:31-37, and John 6:59. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="600pt" />
<p class="caption">(\#fig:unnamed-chunk-59)Capernaum synagogue. Although this structure was built after the time of Yeshua, archeologists are convinced the current building rests on the foundation of an earlier synagogue.  This  synagogue was the probable location where Yeshua taught in righteousness as recorded in Mark 1:21-28, Luke 4:31-37, and John 6:59. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>


## What is a Construct Chain?
::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/10.1.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

A construct chain consists of at least two nouns linked together.  

The first important thing to know about a Hebrew construct chain is this:

> The very last noun in the chain is said to be in the "absolute state".  All words in the chain before the absolute noun are said to be in "construct state."

* Back to <span class="he">בֵּית לֶחֶם</span>, "house of bread" 
    * "bread" would be in the absolute state
    * "house of" is in the construct state
    * The entire phrase would be called a "construct chain"  
        * A construct chain has one and only one absolute noun and one or more construct nouns

::: {.box .caution}
The purpose of the chain is to describe the **first** _noun_ in the chain.  

* It might be reasonable to think that the chain would be describing the noun in the absolute state, but that is not the case
* In <span class="he">בֵּית לֶחֶם</span>, we are describing the house, not the bread  
* A chain describes the first (true) NOUN in the chain, not necessarily the first word in the chain, which may be an adjective acting as a noun
* If there were a substantival adjective as the first word, e.g., "wise of heart", the chain is describing "heart," not "wise"

:::

* In English, we would typically add the word "of" after each word in the construct state.  
    * We could say "the king's son" or the "son of the king," and both would mean the same thing
    * Translating a construct word as "of" is a _starting point_ and not a hard-and-fast requirement
* Just like we may add `'s`, Hebrew has different spelling for nouns in construct
    * The absolute noun is the "normal" spelling and meaning


## What makes a construct chain different?

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/10.2.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* What makes a Hebrew construct chain different is that nothing else comes between the words of the chain
    * In English, we could add an adjective like "the servant of the _wicked_ son of the king"
    * In Hebrew, any adjectives must come after the whole chain
        * A literal translation would look like: "servant of son of the king the wicked"    
        * To resolve, we would need to go back and determine which word the adjective modifies by matching the gender and number
* In the example of "servant of son of the king the wicked" there is ambiguity
    * Without more context, it is impossible to determine which of the three men is the wicked one
    * Translating is more straightforward when the nouns in the construct chain are of a mixed number or gender
    * For example: "the wife of David the strong the smart, the beautiful"
        * If "strong" and "beautiful" were FS, then we know they are referring to David's wife
        * If "smart" was MS, we know it is referring to David
        * The sentence translation would be clear: "The strong and beautiful wife of smart David"

## Review: what makes a word definite 

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/10.3.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

::: {.box .caution}
Nouns in construct state NEVER take the article.
:::

Construct Chains have strict rules regarding definiteness, so now would be a good time to refresh our list of what makes a noun definite in light of this lesson and Lesson 9.

A word is definite if it:

* Has the article - <span class="he">הַמֶּלֶךְ</span>
* Has a pronominal suffix - <span class="he">מַלְכִּי</span>
* Is a proper noun - <span class="he">דָּוִיד</span>
* Is in a construct chain where the last, absolute, word is definite - <span class="he">בֶּן הַמֶּלֶךְ</span> = THE son of the king

Even though a noun in construct may not have the definite article, it is deemed definite when the last word (the absolute noun) is definite.  We explain more on the next page.

## The Absolute noun establishes the definiteness of a chain

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/10.4.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

:::{.box .light}
A construct chain is either entirely definite or entirely indefinite

A construct chain will never mix definite and indefinite nouns
:::

* It is the last, absolute, word that defines whether the chain is definite or indefinite
    * <span class="he">בֶּן הַמֶּלֶךְ</span> = the son of the king
    * <span class="he">בֶּן מֶלֶךְ</span> = a son of a king
    * You will never see "a son of the king" or "the son of a king" in a construct chain
    * It's only one or the other
* There are examples in the Bible of mixing definiteness and indefiniteness but these are not done using construct chains^[<span class="he">מִ֭שְׁלֵי שְׁלֹמֹ֣ה</span> is a construct chain that means "THE proverbs of Solomon."<span class="he">מִזְמ֗וֹר לְדָ֫וִ֥ד</span> means "a psalm of (to) David", but this is not a construct chain.].


## How to Recognize a Construct Chain

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/10.5.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

The following are characteristics of nouns in the construct state:

* Never an article
* Never a pronominal suffix
* Never an unaccented long vowel unless it is a vowel letter 
    * We will see Tsere-yod and Holem-Vav
    * We will not see Holem, Qamets, or Tsere
    * We will see _accented_ long vowels in the penult^[That is the next to last syllable position.] - <span class="he">סֵ֫פֶר</span>
* No diphthong (will see Tsere+Yod or Holem-Vav)
* May have a reduced vowel in the penult
* Noun endings may change (next page)
* Two nouns connected by maqqef is a construct chain
    * <span class="he">כְּבוֹד־יְהוָה</span> = The glory of the LORD

::: {.box .light}
Long vowel, not accented, not a vowel letter = absolute
:::

## Identifying Construct state by Noun Endings


::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/10.6.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* Nouns in construct often sometimes (but will not always) change endings
* The table below shows the Absolute ending and then the difference in the Construct form

<img src="images/10_construct_endings.png" width="300pt" style="display: block; margin: auto;" />

Other nouns may not change endings but will exhibit a loss of long vowels, as discussed in the previous section

::: {.box .light}
Word-final Tsere+Yod is diagnostic of Plural and Dual construct forms
:::


## Construct Chain Conclusion {-}

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/10.conclusion.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::
* Remember the rules for what makes a noun definite.  This will help you determine whether the entire construct chain is definite or indefinite (for it can only be entirely definite or entirely indefinite)
    * "THE son of the queen" OR "A son of a queen"
* All words, except for the last, are in the "construct state"
    * No article or pronominal suffix
    * Long vowels are limited
        * ("Long vowel, not a vowel letter = Absolute" - Dr. Beckman)
    * No diphthong
    * Review ending changes chart
        * Tsere+yod is a very common ending for a masculine plural construct noun
    * A reduced vowel in the penult is usually construct - <span class="he">נְבִיא</span>
    * Noun with Maqqef is construct - <span class="he">בֶּן־</span>

There are four extremely common constructs in the Bible, so we must be able to recognize them.  These will be reviewed in `Anki`.

* <span class="he">כָּל־</span> - all of
* <span class="he">אֲבִי־</span> = father of
* <span class="he">אֲחִי־</span> = brother of
* <span class="he">אֵ֫שֶׁת־</span> = wife of

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/YF2XieUoR3Y" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/YF2XieUoR3Y){target="_blank"}


## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/hxpScJEBMcY" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/hxpScJEBMcY){target="_blank"}



## Anki {-}

* `Lesson 10 A. Vocab`
* `Lesson 10 B. Grammar`
* `Lesson 10 C. Workbook`
* `Lesson 10 D. Verses`

## Worksheets: Construct Identification {-}

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/10.worksheets.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

This attachment has a list of words, some are in absolute, and some are in construct. See if you can determine the differences^[Odd 1-35, 39, 41, 42, 44, 45, 47 are Absolute; 37 and 38 are ambiguous; even 2-36, 40, 43, 46, and 48 are Construct. Most often it is "Long vowel, not a vowel letter" that identifies absolute.].

[Construct Practice](./images/10_construct_practice.pdf){target="_blank"}

This next attachment is not really a worksheet, but is a summary of common construct vocabulary that occurs in the Bible for your review.

[Construct Vocabulary](./images/10_construct_vocab.pdf){target="_blank"}


## Ruth Pursuit {-}        

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/10.ruth.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

::: {.box .map} 
YOUR QUEST

1. Find the following construct nouns:
    * days of (yellow)
    * field(s) of (green)
    * two of (blue)
        * two construct M <span class="he">שְׁנֵי</span>
        * two construct F <span class="he">שְׁתֵּי</span>
    * house of (pink)
2. Find the following vocabulary words (gray)
    * Again
    * Death
    * Loyalty

As always, words may have prefixes or suffixes.  Try to identify whether the construct is definite or indefinite based on the absolute noun.  
:::

* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/copy){target="_blank"}
* [Ruth Pursuit Answer Key #10](./images/10_Ruth_Pursuit_KEY.pdf){target="_blank"}


## Quest Quiz #10 {-}

<div class="container">
<iframe class="responsive-iframe" src="https://forms.gle/ST6XfCvKRXHRfxfVA" frameborder="0"></iframe>
</div>


[Open Quest Quiz #10 in a new window](https://forms.gle/ST6XfCvKRXHRfxfVA){target="_blank"}

## Claim your next `Twelve Tribes Badge`! {-}


When you have completed all activities on your `Hebrew GRAMMAR Quest Checklist` through Lesson 10, complete the certification below, and your badge will be on its way!

<!-- Tribe Badge 4 = gad -->

<div class="containerLtr">
<iframe class="responsive-iframe" src="https://forms.gle/7X1tmBcU5WtGT46A7" frameborder="0"></iframe>
</div>

<!--chapter:end:10-ConstructChain.Rmd-->

# Hebrew Numerals

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/11.intro.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

> To comprehend Biblical Hebrew, we must be able to figure out numbers, with or without a dictionary, when we encounter them in the Bible


You have worked very hard on the first ten lessons!  Way to go!  The authors of <u>Basics of Biblical Hebrew</u>, wisely in our opinion, strategically placed a necessary but lighter discussion on numerals right here in Lesson 11.  We are emerging from what may be a lot of foggy concepts with all of the noun, pronoun, and adjective concepts in lessons 4-10 (particularly Lessons 8-10).  The bulk of the work in Lesson 11 will be in `Anki` learning numbers from _Hebrew Quest_.

For the next 25 lessons, we will focus on the Hebrew verbal system and -- the entire point of this course -- reading and understanding Scripture, especially with the _Hebrew Quest_ study passages.

Enjoy this brief lesson on numbers!

::: {.infobox .map}
**LESSON ITINERARY** 

1. The Biblical text always spells out numbers
2. Notes and footnotes use symbols for numbers
3. Be Familiar with Hebrew Ordinal Numbers - First through Tenth
4. Hebrew Cardinal Numbers 1-9
5. Digits 1 and 2 match the gender of the noun
6. Digits 3-10 take the opposite gender of the noun
7. Learn the Cardinal Numbers Above 10
:::

::: {.box .stop}
**EQUIPMENT CHECK**

Before continuing, can you describe the following concepts?

* The difference between construct and absolute states
:::

## First Thought {-}


::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/11.jos0402.mp3">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

### <span class="he"> קְחוּ לָכֶם מִן־הָעָם שְׁנֵים עָשָׂר אֲנָשִׁים</span> {-}

_Take for yourselves twelve men from the people (Joshua 4:2)_

Give Him praise that you are among those counted as His talmidim (disciples)!


<div class="figure" style="text-align: center">
<img src="images/11-Tabgha from boat, tb011500051.jpg" alt="Tabgha, the traditional location of the calling of the twelve disciples. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="600pt" />
<p class="caption">(\#fig:unnamed-chunk-61)Tabgha, the traditional location of the calling of the twelve disciples. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>


## _Hebrew Quest_ Numerals Lecture

View this 17-minute overview video from _Hebrew Quest_ on Hebrew Numerals.  Don't fret if you don't understand this material completely.  

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/MlfwNNuWgto?start=1675&end=2710
&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/MlfwNNuWgto?t=1675){target="_blank"}

Start: 27:55  
End:  45:10

## The Biblical text always spells out numbers

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/11.2.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* You will not see "1", "200", or "969", either in modern symbols or in Rabbinic characters (using the Aleph-bet) in the Hebrew text
* Numerals will always be spelled out as words
* Example: 
  * <span class="he">כָּל־יְמֵי מְתוּשֶׁלַח **תֵּשַׁע וְשִׁשִּׁים שָׁנָה וּתְשַׁע**</span>
  * "all the days of Methuselah (were) **nine and sixty years (i.e., 960) and nine (i.e., 969)**."

## Notes and footnotes use symbols for numbers

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/11.3.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

::: {.box .info}
This section is presented for information only  

:::

* You may come across a system of counting that uses numerical values for each of the Hebrew letters
  * א ב ג ד ה ו ז ח ט represent 1-9
  * י כ ל מ נ ס ע פ צ represent 10-90 by tens
  * So to say 33, would be 30 and 3 = לג or often ל״ג, with the ״ indicating that this is not a real word
* ק ר ש ת are 100, 200, 300, and 400, 
* Finally, we use the sofit forms ך ם ן ף ץ for 500-900
* In some reckonings, a series of dots or diamonds above the letters, or ’ is used for numbers above 999.  For example, 1000 is ’א
* Below is how a Hebrew reference might say "Genesis 1:1"
  * בראשית פרק א
  * This means "Genesis Chapter 1"
* Next, note the diminished א indicating "1" for the first verse

<img src="images/11.gen0101.png" width="600pt" style="display: block; margin: auto;" />

## Hebrew Ordinal Numbers

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/11.4.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::


* Ordinal numbers denote order.  first, second, third
* In Hebrew, these are attributive adjectives
* They follow the noun and match in gender, number, and definiteness (Attributive Always After, Always Agree)
    * <span class="he">יוֹם רִאשׁוֹן</span> or <span class="he">הַיּוֹם הָרִאשׁוֹן</span> = first day or the first day
* Ordinal numbers end in Hireq-Yod (M) or Hireq-Yod_Tav (F)
    *  <span class="he">שְׁלִישִׁי</span> and <span class="he">שְׁלִישִׁית</span> mean "third"
* To denote the 11th position or higher, we would use cardinal numbers
    * We are dependent on the context of the passage to indicate whether the number is cardinal or ordinal
    * <span class="he">בִּשְׁנַת הָאַרְבָּעִים</span>  = in the year of the forty = in the 40th year
* We encourage you to once again review the "days of the week" song with Izzy in the video below

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/MlfwNNuWgto?startt=2596&end=2661" frameborder="0"></iframe>
</div>

[Open video in new window](https://www.youtube.com/embed/MlfwNNuWgto?t=2596){target="_blank"}


## Cardinal Numbers 1-10

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/11.5.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* The numeral one is an attributive adjective - it follows its noun and agrees in gender, number, and definiteness
    * As we mentioned previously, it is sometimes used as an indefinite article
    * <span class="he">אִישׁ אֶחָד</span> = one man = a man
* Two through Ten are nouns
    * They have both masculine and feminine forms
    * They have absolute and construct forms
* Higher numbers are nouns with no specific gender


### Digits 1 and 2 match the gender of the noun {-}

For example:

* <span class="he">בֵּן אֶחָד</span> = one son
* <span class="he">בַּת אַחַת</span> = one daughter

### Digits 3-10 take the opposite gender of the noun {-}

Additionally, they are "singular" even though the noun is plural.  

For example:

* <span class="he">שְׁלֹשָׁה בָּנִים</span> = three sons
* <span class="he">שְׁלֹשׁ בָּנוֹת</span> = three daughters

The technical term for this is "chiastic concord" (you don't need to know this)

## Cardinal Numbers Above 10

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/11.6.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* 11-19
    * 11-12 match gender, 13-19 swap
        * 11 <span class="he">אַחַד אָשָֹר</span>
        * 13 <span class="he">שְׁלֹשָׁה אָשָֹר</span>
* Decades 30 through 90 are spelled as masculine plural of the corresponding 3-9 number
    * 3 = <span class="he">שָׁלֹשׁ</span>  
    * 30 = <span class="he">שְׁלֹשִׁים</span>
* 20 is a bit unusual
    * The word for two is <span class="he">שְׁנַיִם</span> (male) and <span class="he">שְׁתַּיִם</span> (female)
    * Since these words already have a non-singular ending, Hebrew uses the masculine plural of ten
    * <span class="he">עֶשֶׂר</span> is 10
    * <span class="he">עֶשְׂרִים</span> is 20
* 100 is <span class="he">מֵאָה</span>
* 200 is <span class="he">מָאתַיִם</span>, the plural of 100
* 300 is <span class="he">שְׁלֹשׁ מֵאוֹת</span> ("three one hundred" and so forth up to 1000)
    
## Lesson 11 Conclusion {-}

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/11.conclusion.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* This chapter omits many details about numbers and counting
* We aimed to provide an introduction to have basic familiarity when you encounter numbers in the Bible.
* For Hebrew GRAMMAR Quest, it is sufficient for you to learn the Ordinals 1-10, and the Cardinals 1-10, then 20-100 by 10s, and 1000
* There is no quiz and no Anki `Workbook` section for this lesson

::: {.box .map}

You are at an exciting point in the course.  In the next lesson, we get into Hebrew Verbs, where your understanding of Hebrew Scripture will start to move into high gear!

:::

### Anki {-}
* `Lesson 11 A. Vocab` 
    * The vocab work will be a little bit longer than in a usual lesson.  
    * We will have the typical set of words from <u>Basics of Biblical Hebrew</u>
    * We will also incorporate the numerals cards from <u>Hebrew Quest</u>
* `Lesson 11 B. Grammar` 
* `Lesson 11 C. Study Verses` - Note: there is no `Workbook` component to this lesson.

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/Pb8TIHYRFhI" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/Pb8TIHYRFhI){target="_blank"}


## Verses Warm-up {-}


<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/JeU84P1AdEM" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/JeU84P1AdEM){target="_blank"}

## Ruth Pursuit {-}        

::: {.infobox .sound}
<figure>
<audio id="myAudio" controls controlsList="nodownload" src="./images/11.ruth.m4a">
            Your browser does not support the <code>audio</code> element.</audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button> <button onclick="setPlaySpeed2()" type="button">2x</button> <button onclick="setPlaySpeed15()" type="button">1.5x</button> <button onclick="setPlaySpeed1()" type="button">1x</button> <button onclick="setPlaySpeed075()" type="button">.75x</button> <button onclick="setPlaySpeed05()" type="button">.5x</button> 
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

::: {.box .map} 
YOUR QUEST

1. Find the following numbers:
    * one (yellow)
    * second (green)
    * ten (pink)
2. Find the following vocabulary words (blue)
    * there
    * night
:::


* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/copy){target="_blank"}

* [Ruth Pursuit Answer Key #11](./images/11_Ruth_Pursuit_KEY.pdf){target="_blank"}

## Claim your Unit 2 Completion Certificate! {-}

If you have completed **all activities** in Lessons 1-11, you may claim the second `Unit Completion Certificate`.

::: {.box .caution}
* A remember that the Anki Requirement for the `Unit Completion Certificate` is different from the `12 Tribes Badges` requirement
* You must submit a screenshot showing that all cards are **MATURE**
    * No cards may be "New," "Young," "Suspended," or "Buried"
* See the `Hebrew Grammar Quest Checklist` for additional information
:::

[Please open and submit the Unit Completion Certificate Request form in new window](https://forms.gle/hkHMebEtNi61waidA){target="_blank"}

<!--chapter:end:11-Numerals.Rmd-->

# (PART) Qal Stem {-}

# Introduction to Unit 3 {-}

::: {.infobox .sound}
<figure>
<audio
        id="myAudio"
        controls controlsList="nodownload"
        src="./images/03b.unit2intro.m4a">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
<button onclick="setPlaySpeed25()" type="button">2.5x</button>
<button onclick="setPlaySpeed2()" type="button">2x</button>
<button onclick="setPlaySpeed15()" type="button">1.5x</button>
<button onclick="setPlaySpeed1()" type="button">1x</button>
<button onclick="setPlaySpeed075()" type="button">.75x</button>
<button onclick="setPlaySpeed05()" type="button">.5x</button>
<script>
var x = document.getElementById("myAudio");
function setPlaySpeed05() { 
    x.playbackRate = 0.5;
    x.play();
}
function setPlaySpeed075() { 
    x.playbackRate = 0.75;
    x.play();
} 
function setPlaySpeed1() { 
    x.playbackRate = 1;
     x.play();
}
function setPlaySpeed15() { 
    x.playbackRate = 1.5;
     x.play();
} 
function setPlaySpeed2() { 
    x.playbackRate = 2;
     x.play();
} 
function setPlaySpeed25() { 
    x.playbackRate = 2.5;
     x.play(); 
} 
</script> 
</figure>
:::

* Unit 3 represents a pivot point in this course
* From now through the end of the course, we will focus on verbs
* In Unit 3 we will be spending our time learning what is called the Qal verb stem in depth
* Then in Unit 4 we will learn the six so-called "derived" stems

We wanted to let you know of some changes:


1. Vowel Shorthand
2. $Pre$ = a diagnostic word-initial combination
3. Changes to Hebrew GRAMMAR Quest for Units 3 and 4
    1. No more quizzes!
    2. Study Verses
        * Cantillation marks added to study verses
        * Verses will be taken as a whole, versus split into smaller components
    3. OPTIONAL _Hebrew Quest_ Study Passage Translation


## Vowel Transliteration/Shorthand {-}

We will begin to use the vowel transliteration introduced in Lesson 2

::: {.box .info}

* Short Vowels (no marking): $A$ for Patach, $E$ for Seghol, $I$, Hireq, $O$ for Qamets Hatuf, and $U$, Qibbuts
* Long Vowels that are not letters (bar): $\bar A$ for Qamets, $\bar E$ for Tsere, and $\bar O$ for Holem
* Reduced Vowels (breve): $\breve A$ for Hateph Patach, $\breve E$ for Hateph Seghol, $\breve O$ = Hateph Qamets Hatuf
* Unchangeable Long Vowels (hat): $\hat E$ = Tsere+Yod^[Formal shorthand for Seghol+Yod is also $\hat E$ but for this course, we will only use $\hat E$ for Tsere+Yod.], $\hat I$ = Hireq_+Yod; $\hat O$ = Holem+Vav, and $\hat U$ = Shureq
* Additionally, we have the ending Qamets+He = $\hat A$, Vocal Sheva = $ə$, and $:$ for Silent Sheva^[Vocal Sheva has a "hurried" pronunciation, like the _a_ in _amuse_ or _Tina_. ə is the [international character for this sound](https://en.wikipedia.org/wiki/Mid_central_vowel){target="_blank"}. Silent Sheva has no pronunciation transliteration value.])

:::

## $Pre$ = Diagnostic Word-initial Combinations {-}

* A Hebrew strong verb conjugation, regardless of the stem, can usually be identified based on its initial combination of consonants, vowels, and from time-to-time, the presence of a Daghesh Forte
* For example, in Lesson 15, we will learn the "Imperfect Preformatives" (we'll describe what a preformative is a little later)
    * The 3ms and 3mp strong forms will always have:
        * Preformative consonant = Yod
        * $V_P = I$ (Hireq), and
        * $V_1 = \ :$ (Silent Sheva)
    * We can further shorten this by saying $Pre =$ <span class="he">יִקְ</span>, where ק represents $R_1$ of any strong verb
    * $Pre$ is not simply the verb's prefix or preformative, but the entire word-initial combination of preformatives, vowels, and possibly a Dagesh that can help us identify and translate a specific verb form

## Changes for Unit 3: No more quizzes! {-}

* The quizzes in Units 1 and 2 provided a checkpoint before proceeding to the next lesson
    * We wanted to make sure you had the essential components of the lesson
* At this stage of the course, we can dispense with the quizzes and leave it up to your judgment as to whether you are ready to proceed with the next lesson
* The overload workload is steadily increasing, and of course, the Anki reviews are growing (so be sure to keep up with daily reviews!)

## Changes for Unit 3: Changes to `Anki Study Verses` {-}

* In Unit 2, we split longer verses into two sections; starting with Unit 3, we're going to take it up a notch and have you review the entire study verse in one answer
* For Unit 3, we are also adding Cantillation Marks added to Study Verses
* Back in Lesson 2, we also referenced additional marking called cantillation marks
* These are the marks in addition to vowels and consonants we sometimes see in Hebrew
    * Here is the example we looked at from Genesis:

<img src="images/02.Gen0109.png" width="600pt" style="display: block; margin: auto;" />

* Up until now, we have been using a simple accent mark whenever a Hebrew word has an accent on the second to last syllable
    * For example, <span class="he">נֶ֫גֶב</span>
    * While the Lessons and other materials will continue to use these simple accents, from now on, we will graduate to using the full set of Hebrew accents in our Study Verses and Workbook exercises
* Why do this?
    * When you read from a Tanach, you are much more likely to encounter the complete set of Hebrew accent marks
    * Becoming more comfortable with the Hebrew Bible includes having a basic familiarity with these additional marks
* Things to keep in mind:
    * There are over 20 different cantillation marks
    * We won't go into what each one means, but there are plenty of resources on the Internet if you are interested in digging deeper
    * Remember that a syllable can have only one vowel
    * Most often, there is only one cantillation mark per word - <u>where you see the mark is where the accent goes</u>
    * Occasionally, you will see a mark near the front or middle of the word, as well as a mark near the end of a word         
        * The first mark is a secondary accent
        * Remember, a primary Hebrew accent can ONLY be on the LAST or SECOND-TO-LAST syllable
* The vertical line | that can appear between two words can be ignored
* When in doubt, listen to Izzy's audio carefully as he reads each verse to determine where the accent goes

::: {.box .light}
If you see a mark that is not a vowel you recognize (such as an upside-down wishbone) or in the wrong place (such as a dot above a consonant instead of inside or below) it is a cantillation mark.

:::

::: {.box .info}
Trying to read with these marks can be visually distracting and overwhelming at first. With practice, you will get used to them.  Cantillation marks are part of the rich tradition of Biblical Hebrew passed down to us from many centuries ago.

:::

## Changes for Unit 3: OPTIONAL _Hebrew_ Quest Study Passage Translation {-}

* `Hebrew Quest Study Passages` are designed for those who seek more opportunities for additional Hebrew Bible reading and translating activity
* They also offer a method to simultaneously complete _Hebrew Quest_ and Hebrew GRAMMAR Quest
* Completion of this activity may require a significant time investment to complete
    * For this reason, completing the `Hebrew Quest Study Passage Track` is not required to earn any Hebrew GRAMMAR Quest `Badges`, `Certificates`, or the `Graduation Diploma`
* Whether you have already completed _Hebrew Quest_ or not, this activity is sure to significantly expand your Hebrew reading skills
* We will start off slowly with the verses from the Proverbs study
* Then we will go in _Hebrew Quest_ order, beginning with Genesis 1 (_Hebrew Quest_ Lesson 17) through 1 Kings 18 (_Hebrew Quest_ Lesson 40)
* Here is what we want you to do in these Study Passages activities:
    1. Download or print the applicable study passage document
    2. Read the passage straight through to gain an overview
    3. Read again, but this time, compose a translation
        1. First, see how much you can do without a reference
        2. Then, look up any words you don't know in a lexicon
    4. Watch the _Hebrew Quest_ video where Izzy reads and breaks down the passage, often with spiritual insights^[Note: Izzy intentionally speaks very slowly, so as you advance in Hebrew, you may wish to increase the speed of the YouTube video].
        * As you are watching, compare your translation with Izzy's explanation
        * How did you do?  Can you see how much you are learning?
        * For Tanach passages, [this website](https://scholarsgateway.com/search/WLC-KJV%201611-ESV/Genesis/1:1-5) has information on parts of speech and PGN information when you hover over a word
    5. Ask what the Spirit of Holiness, the Ruach HaKodesh, is teaching you

## Lessons 13-16 are critical! {-}


<div class="figure" style="text-align: center">
<img src="images/11b.bethabara.JPG" alt="Jordan River High Water Sign. The sign says 'Level of the Jordan.'  Photo by Chris Flanagan, taken 2/12/2013." width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-64)Jordan River High Water Sign. The sign says 'Level of the Jordan.'  Photo by Chris Flanagan, taken 2/12/2013.</p>
</div>


* The image above is of the Jordan River baptismal area in Israel near Jericho - it was taken less than a month after flooding of the area
* Lessons 13-16 could be considered the "high-water mark" of the course
    * There will be a lot of details to digest as we talk about the two most critical verb forms in the Bible, the Qal Perfect and the Qal Imperfect
    * YOU MUST MASTER the material in these four chapters
    * Doing so will make the rest of the course much smoother, and more importantly, this will help you better understand your Hebrew Bible
* The "high water" will start to recede a little starting with Lesson 17
* The rest of the course from Lessons 17-35 build upon Chapters 13-16


## _Hebrew Quest_ Verb Summary Lecture {-}

Although this three-minute _Hebrew Quest_ lecture comes at the very end of Izzy's discussion on Hebrew verbs, we wanted to share it with you here.  Izzy offers tremendous encouragement for you, which you can apply throughout your verbal journey. 
    
<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/hWmwyosdP-s?start=3343&end=3512&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/hWmwyosdP-s?t=3343){target="_blank"}

Start: 55:43  
End:  58:32

::: {.box .map}
* Hang in there and keep going!  
* We are studying grammar to draw closer to the Holy One!
* Slow and steady wins your Hebrew verbal race!

Now, let's get to Hebrew Verbs!

:::

<!--chapter:end:11b-Unit3_Intro.Rmd-->

# Introduction to Hebrew Verbs

Hebrew is a verbal, action-oriented language.  Now that we have concluded our discussion on nouns, pronouns, adjectives, and prepositions, we will now focus on verbs.

Around 70% of Hebrew verbs are in what we call the Qal stem, so we will spend Lessons 13-22 learning that stem inside and out.  Qal verbs represent simple action. 

Our quest is to translate accurately.  To do this, we must identify the root, stem, conjugation, person, gender, and number of verbs. This Lesson will provide a detailed introduction to the verb system as a whole and some general conventions.

::: {.box .map}
LESSON ITINERARY

1. The Verbal Root
1. Preformatives and Sufformatives
1. Verbal Vowels
1. The Seven Hebrew Verb Stems
1. Person, Gender, Number
1. The Eight Basic Hebrew Verb Conjugations
1. Finite and Non-Finite Conjugations
1. Parsing Conventions
1. Strong and Weak Verbs

:::

::: {.box .stop}
EQUIPMENT CHECK

Before continuing, have you completed all requirements for your certificate for Lessons 1-11?
:::

## First Thought {-}

### <span class="he">וְהֽוּא־הָלַ֤ךְ בַּמִּדְבָּר֙ דֶּ֣רֶךְ י֔וֹם </span> {-}

*But he himself went a day's journey into the wilderness . . . (1 Kings 19:4)*

As we begin a long stretch in Hebrew Verbs, at times, you may feel as exhausted, dry, and isolated as if you were Elijah (the subject of 1 Kings 19:4) driven into the wilderness.  

In these times, we must depend on God to sustain us.  It is times like these where God can pour into us and prepare us for our next adventure.  Moses, Elijah, John the Immerser, and several others all had their time in the Wilderness that God used to mold them as servant-leaders.  Of course, we can point to Yeshua himself and his time in the wilderness at the beginning of his ministry.  Embrace the wilderness!

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/12.04.1ki1904.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>

<div class="figure" style="text-align: center">
<img src="images/13-Acacia tree in Red Canyon, tb030101203.jpg" alt="Acacia tree in Red Canyon. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-65)Acacia tree in Red Canyon. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>




## _Hebrew Quest_ Verb Introduction Lecture

View this 8-minute overview video from _Hebrew Quest_ on Hebrew Verbs. You may disregard references to the "Student Manual" and "Essentials of Biblical Hebrew." We will break down the concepts Izzy discusses as we progress through this lesson.  Also make sure you have watched the _Hebrew Quest_ video segment in the Unit 3 Introduction.

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
hfu4gjNo2K4?start=2344&end=2846&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/hfu4gjNo2K4?start=2344){target="_blank"}

Start: 39:04
End: 47:26

::: {.box .map}

"I advise beginners not to perplex themselves about any rule that at first view seems difficult, which will be of great advantage to carry on their design in the knowledge of this Primitive Tongue with success."  

-Judah Monis, on the back of the title page of his Hebrew Grammar, published in 1735. 

:::
## A note on the paradigm strong verb קטל

* As Izzy mentions in the video we just watched, Hebrew grammars for the past several centuries have used the verb <span class="he">קטל</span> as what is called the "paradigm verb"
* <span class="he">קטל</span> is meant to represent _ANY_ "strong" verb (we'll discuss strong and weak verbs later in this Lesson)
* What makes <span class="he">קטל</span> awkward is the word means "to kill"
* As we go through this course, remember that the actual translation of <span class="he">קטל</span> is not material to our purposes
* In this respect, it is similar to a math formula
    * In $a^2 + b^2 = c^2$, the letters "a", "b", and "c" have no direct, literal meaning
    * In the Pythagorean formula above, "a", "b", and "c" are meant to represent the lengths of the three sides of a right triangle
* We encourage you to think of <span class="he">קטל</span> the same way
    * The letters <span class="he">.ק.ט.ל</span> are just variable or placeholder letters that are part of a formula with a larger purpose than the direct, literal meaning
    * Also, like Izzy says, we can always think of <span class="he">קטל</span> as "killing" sin, bad habits, or things that can interfere in our relationship with the Holy One
    
## The Verbal Root

* A _Root_ is the set of consonants on which a verb (and often nouns) are based
* The majority of verbs have three _root consonants_ from which the other words are derived.
* Consider the root <span class="he">מלך</span>; the graphic below lists just a few of the nouns and verbs that derive from this single root

<img src="images/12-verb-root.gif" width="700pt" style="display: block; margin: auto;" />

## Inflecting and Parsing Review

* Back in Lesson 4, we discussed the difference between "inflecting" and "parsing"
* Inflecting is when we take a verb root such as <span class="he">מלך</span> and transform it by adding vowels, prefixes or suffixes to generate a specific form with a unique meaning
    * For example, if you were told to inflect <span class="he">מלך</span> into Qal Perfect first-person, common singular (QP1cs), you would provide "<span class="he">מָלַכְתִּי</span>"
* As we said back in Lesson 4, no part of reading the Hebrew Bible requires you to inflect
* Parsing can be thought of as going in the reverse direction
    * Say you encounter a verb such as "<span class="he">מָלַכְתִּי</span>"
    * In time, you will be able to determine that <span class="he">מָלַכְתִּי</span> is the QP1cs form of <span class="he">מלך</span>, and means "I ruled" or "I was king"
* To accurately translate the Hebrew you read in Scripture, you will be doing a lot of parsing

## Person, Gender, Number

* The inflected person, gender, and number refer to the _subject_ of the verb
    * Pronominal suffixes are used to denote the object of the verb.  We will study these in Lesson 19
* Person, Gender, and Number for verbs are the same as for nouns
    * "Common" gender is for verb forms that could be either M or F; In Hebrew, as in English, the words for "I" and "we" are Common (i.e., there is not a masculine form of "I" and a separate feminine form of "I")
    * Person
        * 1st person is the speaker - "I/we sat"
        * 2nd person is the person being spoken to - "you sat"
        * 3rd person is anyone else - "he/she/it/they sat"
    * Number is singular or plural - there are no dual verb forms
    
::: {.box .info}
When parsing, it is standard to use parsing code "3ms" to mean "third person, masculine, singular."
:::

## Verb nomenclature

*  As a convention, many Hebrew grammars label the three root letters $R_1$, $R_2$, and $R_3$^[Older Hebrew grammars, including "Essentials of Biblical Hebrew" available in the holylanguage.com resource library, refer to these as "Pe", "Ayin" and "Lamed" positions, from the verb פעל. ].
* For the verb <span class="he">מָלַכְתִּי</span> (I was king):
    * The _root_ is <span class="he">מלך</span> (no vowels)
        * $R_1$ = מ
        * $R_2$ = ל
        * $R_3$ = ך

## Lexical form for Verbs

* Also important to know is the _Lexical Form_ 
* The _lexical form_ is how you would locate the word in a dictionary
* As Izzy discussed in the introductory video, the lexical/dictionary form for verbs is almost always the Qal Perfect 3rd Person Masculine Singular.
* For the verb <span class="he">מָלַכְתִּי</span> (I was king):
    * The _root_ is <span class="he">מלך</span> (no vowels)
    * The _lexical form_ is <span class="he">מָלַךְ</span> (take the _root_ and inflect it as QP3ms form)
        
## Preformatives, Sufformatives, Prefixes, and Suffixes

* While many dictionaries would consider "preformative" synonymous with "prefix" and "sufformative" synonymous with "suffix", Hebrew grammars often use the terms "preformative" and "sufformative" exclusively for verbs
* A verbal _preformative_ (if any) goes before $R_1$ and a _sufformative_ (if any) goes after $R_3$
    * A sufformative can also be referred to as an _afformative_ 
* Any _prefix_ such as the interrogative particle, or (commonly) the conjunction vav, goes _before_ the preformative
* Any _suffix_, such as a pronominal suffix, goes _after_ the sufformative
* For the verb <span class="he">קָטַ֫לְתִּי</span>
    * The sufformative is <span class="he">תִּי</span> 
    * There is no preformative 
    * There is no prefix or suffix
* For the verb <span class="he">יִקְטְלוּ</span>
    * The preformative is <span class="he">יִ </span>
    * The sufformative is <span class="he"> וּ</span>
    * There is no prefix or suffix
* For the verb <span class="he">יִקְטְל֫וּהָ</span>
    * The preformative is <span class="he">יִ</span>
    * The sufformative is <span class="he">וּ</span>
    * The pronominal suffix is <span class="he">הָ</span>

::: {.box .map}

On your quest to translate verbs, identifying preformatives and sufformatives on verbs is the key to accurate parsing.

:::

## Verbal Vowels

* Identifying a verbal vowel's position is necessary to determine the Verbal Root and the Stem
* Similar to our shorthand for the root consonants, we use $V_P$ (the vowel with the prefix or preformative immediately before $R_1$), $V_1$ and $V_2$ - the vowels with $R_1$ and $R_2$, and $V_S$, which is what is called the _stem_ vowel
    * The $V_S$ is usually $V_2$ 
    * The vowel associated with $R_3$ turns out to be less important, so we do not need to identify this
* For the verb <span class="he">יִקְטְל֫וּהָ</span>
    * $V_P = I$ (remember I is shorthand for Hireq)
    * $V_1 = \ :$ (Silent Sheva)
    * $V_2$/$V_S = ə$ (Vocal Sheva)
    * Note: while we have said Silent Sheva is technically not a vowel, it is occupying the vowel position of $R_1$.  For this purpose, it is acceptable to say $V_1 = \ :$.


## _Hebrew Quest_ Verb Stems Lecture

View this 8-minute overview video from _Hebrew Quest_ where Izzy summarizes the seven Hebrew verb stems. Note that the table Izzy uses has a slightly different layout from the table used later in this lesson, but both convey the same information.

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/hWmwyosdP-s?start=827&end=1268&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/hWmwyosdP-s?t=827){target="_blank"}

Start: 13:47  
End: 21:08

## The Seven Hebrew Verb Stems


* The verb __stem__ affects the meaning of the verb itself
* At a basic level, the stem provides the _type of action_ (simple, causative, intensive) and the _voice_ (active or passive)
* The _Qal_ stem is the basic or simple verb stem.  All other stems are derived from Qal

1. _Qal_ - Active (versus passive) voice and a simple type of action (without nuance) - “he broke the vase”
    * Parsing code: Q
2. _Niphal_ - Passive or reflexive voice with a simple action - “the vase was broken”
    * Interestingly in English, many translations of Niphal verbs are still active voice
    * For example, a fair translation of "he was seen" might be "he appeared"
    * Parsing code: N
3. _Piel_ - Active/intensive - “he shattered the vase”
    * Parsing code: D (the Piel paradigm has a Daghesh Forte in $R_2$ - the D stands for "doubling Daghesh")
4. _Pual_ - Passive/intensive - “the vase was shattered”
    * Parsing code: Dp (passive of the Piel (D))
5. _Hiphil_ - Active/Causative - “he caused the vase to be broken”
    * Parsing code: H
6. _Hophal_ - Passive/Causative - “the vase was caused to be broken”
    * Parsing code: Hp (passive of the Hiphil (H))
7. _Hitpael_ - Reflexive/Intensive - “he caused himself to be holy"
    * Parsing code: tD (very similar to Piel (D) and has a ת in every preformative form)

We'll explain the "Parsing codes" in a few sections 



## The Seven Stems: Summary Table

* There is scholarly debate about the table below
* Hebrew verbs can have any one of several nuanced meanings depending on the context
* The table provides a good starting place, but it is not the "final word" on verb stems
* We will discuss these nuances as we introduce each stem
    
| |Active Voice| Passive Voice | Reflexive Voice
|:- |:- |:- |:-
Simple Action	| Qal | Niphal | (Niphal)
Cause a State	| Piel | Pual | Hitpael
Cause an Action	|Hiphil | Hophal


## Conjugation

* While the stem provides the overall meaning, the _conjugation_ provides additional descriptive information needed for translation
* Strictly speaking, Hebrew does not have past, present, future, tense, as with English
    * Instead, the easiest way of thinking about it is that Hebrew has complete vs. incomplete action
* Like English, Hebrew also has command (called Imperative), infinitive, and participle conjugations


## The Eight Basic Conjugations

1. The _Perfect_ conjugation describes completed action, whether in the past, present, or future
    * Most often, we translate this as English past tense - "She went"
    * Verbs that describe a state of being as well an action that is completed in the future will be in the Perfect conjugation
    * Parsing code: P
2. The _Imperfect_ conjugation describes an incomplete action, whether in the past, present, or future
    * Most often, we translate this as English future tense - "She will go"
    * Verbs that describe an incomplete process or incomplete action, even if that action is in the past, will tend to be in the Imperfect conjugation
    * Parsing code: I
3. The _Imperative_ 2nd person Volitional - a command: "Go!"
    * Parsing code: M
4. The _Cohortative_ 1st Person Volitional - wish, purpose: "I should go"^[Some grammars classify "Corhortative" and "Jussive" as "Verb Moods" and the remaining as "Verb Tenses."].
    * Parsing code: C
5. The _Jussive_ 3rd Person Volitional - conjugation is similar to the Imperative - "He should go."
    * Parsing code: J
6. The _Infinitive Construct_ Verbal Noun -  "to go", or a verbal noun as in, "going"
    * Parsing code: ∞
7. The _Infinitive Absolute_ Verbal Noun - special uses, less common and has no direct equivalent in English
    * Parsing code: A
8. The _Participle_ - Verbal adjective - "runner," "one who runs"
    * Parsing code: Pt
    
    
::: {.box .info}

Vav prefix

* Some grammars identify three other forms, each with a Vav prefix, as additional conjugations/tenses:
    * Perfect + Vav
    * Imperfect + Vav
    * Imperfect Vav Consecutive 
* We will discuss these forms further in Lesson 17

:::

## Finite vs. Non-Finite Conjugations

* _FINITE_ verbs have "person"
    * Perfect, Imperfect, Imperative, Cohortative, Jussive
* _NON-FINITE_ verbs do NOT have "person"
    * Infinitive Construct, Infinitive Absolute, Participle
    * Only Participles have Gender and Number


## Parsing

* As we stated above, parsing is the process of breaking down a verb into its component parts
* The following should be included when parsing a verb (as applicable):
    * Stem
    * Conjugation
    * Person (only for finite)
    * Gender (except for Infinitive forms)
    * Number (except for Infinitive forms)
    * Either the _Root_ form or the _Lexical_ form

    
## Parsing Codes

* Constantly writing the full parsing descriptions, such as "Hitpael Cohortative, Third Person, Masculine Plural" would become tedious
* Therefore, many Hebrew grammarians use what is called "parsing code"  
* Unfortunately, the terminology for morphology is not standardized
* We will be using Dr. John Beckman's code as he has applied it to "Basics of Biblical Hebrew"
* Dr. Beckman's shorthand for the above would be "tDC3mp"
* For comparison, Logos software's code would be "VgI3MS-C"


## Strong and Weak Verbs

* As we get into each stem, there will be separate chapters devoted to strong and week verbs
* Therefore, it will be useful for you to know what we mean by these terms
* Each conjugation will have a basic paradigm that prescribes vowels, accents, preformatives, and sufformatives for each PGN
* Strong verbs will follow this paradigm, so we will call this the "strong verb paradigm"
* Weak verbs will have one or more weak letters that result in some deviation from the paradigm
    * For example the first video by Izzy, he mentioned how the נ in <span class="he">נתן</span> can disappear in certain forms
    * This is because נ is a weak letter
* Strong verbs are "regular," and weak verbs are "irregular"
* The next two pages list some of the major weak categories

## Weak Verbs

* A weak verb has a root consonant that causes it to deviate from the strong-verb paradigm
* A verb may have one such letter that causes deviation in one stem or conjugations but not in others
    * ר is only weak in forms that try to put a Dagesh Forte in it
    * 1נ wants to assimilate whenever it has a Silent Sheva
        * Because this never happens to $R_1$ in the Qal Perfect, 1נ is strong in the Qal Perfect
        * We will learn this will happen in the imperfect, so 1נ is weak in that conjugation
        
## Weak Verb Classes {#weak-class}

* We classify weak verbs by their problem letter
    * 3נ, "third Nun," means that $R_3$ is נ, as in <span class="he">זקן</span>
    * 3ת, "third Tav," means that $R_3$ is ת, as in <span class="he">ברת</span>
    * 1G, "first guttural," means that $R_1$ is a guttural, as in <span class="he">אמר</span>
    * 2G, "second guttural," means that $R_2$ is a guttural, as in <span class="he">בחר</span>
* We can't simply say "3G" for any $R_3$ guttural because it turns out that א and ה each behave differently
    * 3עח, "third Chet/Ayin," means that $R_3$ is ע or ח, as in <span class="he">מנע</span> <span class="he">לקח</span>
    * 3א, "third Aleph," means that $R_3$ is א, as in <span class="he">מצא</span>
    * 3ה, "third Hei," means that $R_3$ is the vowel Qamets+Hei, as in <span class="he">בנה</span>
    * Geminate - $R_2$ = $R_3$ <span class="he">סבב</span>
    * Biconsonantal (also called Hollow) - $R_2$ is a vowel letter <span class="he">בוֹא</span> <span class="he">שִׁים</span>* <span class="he">קוּם</span>*
    * Doubly Weak is any combination of two (or three) weak letters, as in <span class="he">עַלָה</span>
    
## Weak Verbs Are Usually Predictable

* The good news is when Hebrew verbs are weak, the behavior is usually predictable
* In fact, you have already learned almost every behavior change we will encounter with weak verbs
    * For example, you already know that Gutturals reject Vocal Sheva and the Daghesh Forte
    * It will just be a matter of applying that which you already know to a new area
* Weak verbs may take a little more thought, but overall they are nothing to be concerned about
* The better you know your _vocabulary_ and the _strong_ verb paradigms, the easier the _weak_ verbs will be

## Hebrew GRAMMAR Quest is a Quest for RECOGNITION, NOT RECALL

* Older Hebrew Grammars focused on memorizing dozens of verb paradigm charts
* Students had to memorize many different stems, conjugations, as well as strong and weak verb paradigms in those conjugations
* In this course, you will memorize only a handful of paradigms in the Qal Stem
* From here, we will be on a quest for pattern recognition
* Think of it like this: instead of taking a traditional approach to learning a language by brute-force, rote memorization, we are going to take more of a mathematical approach
    * A mathematician doesn't brute-force memorize the solution to every possible problem
    * She or he uses a series of formulas and plugs the specifics into the most appropriate formula for the situation
    * For example, consider the formula for the area of a square: $Area = S^2$ - the length of one of its sides multiplied by itself
    * Studying Hebrew the old way would require you to memorize the areas of hundreds of different squares
    * It is much simpler to memorize the formula
        * Then when you encounter a square that has a side $S = 5$, you can use the formula: $5^2$ to get the answer of $Area = 25$
        * If the next square you encounter has $S = 3$, you can use the same formula to get the answer $9$.
* You will begin to see things in a special $formula font$ - we will use $this font$ when there are consistent patterns
    * For example, whenever you see $Pre =$, this tells you that the verb has a specific combination of prefixes/preformative letters, vowels, and possibly Dagesh Forte marks that are characteristic of that verb class
    
## Stem Comparison Table

* As we move through the course, we will build a table to compare stems
* At the end of the course, your table will look like this:

<img src="images/34_stemcomp.png" width="600pt" style="display: block; margin: auto;" />

* The marks in RED are the distinctive $Pre$ patterns for the strong verbs in that stem/conjugation
* The vowels in BLUE and the "formula" in the last column are the $V_S$ patterns for that stem/conjugation
* You do not need to do anything with this table right now - we only want to show you how this relatively simple series of patterns will help you unlock the meaning of the Bible


::: {.box .map}

That's enough for this introduction to Hebrew verbs.  Let's get to the exercises!

:::


## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/MGk-CGqJwUY" frameborder="0"></iframe>
</div>


[Click to open `Word Warm-up` video in a new tab](https://youtu.be/MGk-CGqJwUY){target="_blank"}


## Verses Warm-up {-}

Note: See Unit 3 Introduction for a discussion of the cantillation accent marks you see on the video. 

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/AS03bG1xjBE" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/AS03bG1xjBE){target="_blank"}

## Anki {-}

* `Lesson 12 A. Vocab`
* `Lesson 12 B. Grammar` 
* `Lesson 12 C. Workbook`
* `Lesson 12 D. Study Verses`

## Ruth Pursuit {-}        

::: {.box .map} 
YOUR QUEST

Find the following miscellaneous words:

* <span class="he">בְּמֵעַי</span> - "in my belly/womb" (yellow)
* <span class="he">תִקְוָה</span> - "hope." (green)
    * The Israeli national anthem is called <span class="he">הַתִּקְוָה</span>. 
    * [Watch the _Hebrew Quest_ Lesson on "HaTiqvah"](https://holylanguage.com/hebrew-history-8.php){target="_blank"}
* <span class="he">בִּתְחִלַּת</span> - "in the beginning" (pink)
* <span class="he">קְצִיר</span> - "harvest of" (blue)
* Vocabulary word for "no, not" (immediate and specific prohibition) - (gray)

:::

* [Blank copy of Ruth 1](https://docs.google.com/document/d/1bcT1J-fcVmD1Zn5Jk2nj0560tEddcgtbYZLkwaVVuyE/copy){target="_blank"}
* [Ruth Pursuit Answer Key #12](./images/12_Ruth_Pursuit_KEY.pdf){target="_blank"}

## OPTIONAL _Hebrew Quest_ Study Passage Track: Proverbs Study #1-4 {-}

::: {.box .map}
YOUR HEBREW QUEST!

1. BEFORE WATCHING THE VIDEO, read through the passage on your own straight through one time - pick up as much as you can. [Blank copy of Proverbs #1-4](https://docs.google.com/document/d/1r7-fkkTsioVcMIxxtw3AP5ukrK6QH-8QjtoTtsd_-4U/copy){target="_blank"}
2. Now re-read the passage critically
    1. Highlight any words you do not know and look them up in a [lexicon](https://holylanguage.com/resources-dictionaries.php){target="_blank"}
    2. Sketch out a translation - there is a blank line between each verse
3. Now, using your marked-up copy of the passage, watch Izzy's _Hebrew Quest_ videos (video opens in a new tab)
    1. [Proverbs #1](https://holylanguage.com/proverbs-1.php){target="_blank"}
    1. [Proverbs #2](https://holylanguage.com/proverbs-2.php){target="_blank"}
    1. [Proverbs #3](https://holylanguage.com/proverbs-3.php){target="_blank"}
    1. [Proverbs #4](https://holylanguage.com/proverbs-4.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?
:::



<!--chapter:end:12-Verbs_Intro.Rmd-->

# Qal Perfect - Strong Verbs {.QP-s}



Over 2/3 of all verbs in the Hebrew Bible are in the Qal stem.  To understand Biblical Hebrew, we must be able to translate Qal verbs.

While our focus is not on writing Biblical Hebrew, we need to be able to write the details on the Qal strong verb paradigms. This will make it easier to recognize Qal weak and non-Qal verbs.  This lesson will begin with the Perfect conjugation.

::: {.box .map}
LESSON ITINERARY

1. Qal is simple action, active voice; Perfect is completed action or state
1. Components of the Qal Perfect Strong Paradigm
    1. $V_S$ is accented in Finite verbs
    1. A Sheva precedes a Finite verb sufformative 
    1. The Perfect Sufformatives
    1. The Qal Perfect Vowels
1. Building the Qal Perfect Paradigm
1. Deviations from the Strong Paradigm
:::

::: {.box .stop}
EQUIPMENT CHECK

Before continuing, make sure you understand the $R_n$ and the $V_n$ nomenclature, including $V_S$
:::



## First Thought {-}

### <span class="he">לֹא־שָׁמְר֤וּ אֲבוֹתֵ֙ינוּ֙ אֶת־דְּבַ֣ר יְהוָ֔ה </span> {-}

*Our fathers did not keep the word of Adonai (2 Chronicles 34:21)*

<span class="he">שָׁמַר</span> means to guard or keep, in the sense of obeying.  It is a verb that frequently occurs in the Hebrew Bible. 

In <span class="he">לֹא־שָׁמְרוּ</span>, the word לֹא serves to negate the verb it precedes.  Literally, this might be "not they kept", but we would say "they did not keep" in English.

Every day, and frequently throughout each day, we have two choices.  We can keep His word, or we can ignore His word.  

Let us strive to have it be told of all of us, <span class="he">שָׁמְרוּ אֶת־דְּבַר יְהוָה </span>, "they KEPT the word of Adonai."

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/13.08.2chr3421.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>



<div class="figure" style="text-align: center">
<img src="images/13.Mount Gerizim, Shechem, Mount Ebal from east, tb070507660.jpg" alt="Mt Gerezim, Shechem, Mt. Ebal from east.  In Deuteronomy 11, Moses instructs that when Israel enters the land, she is to read the blessings from Mt. Gerezim and the curses from not following His word from Mt. Ebal. Today, Shechem is also known as the Arab city of Nablus. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="600pt" />
<p class="caption">(\#fig:unnamed-chunk-68)Mt Gerezim, Shechem, Mt. Ebal from east.  In Deuteronomy 11, Moses instructs that when Israel enters the land, she is to read the blessings from Mt. Gerezim and the curses from not following His word from Mt. Ebal. Today, Shechem is also known as the Arab city of Nablus. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>




## _Hebrew Quest_ Qal Perfect Lecture

View this 3-minute overview video from _Hebrew Quest_ on Hebrew Verbs.  We will break down the concepts Izzy discusses as we progress through this lesson.  Note: the terms "afformatives" used by Izzy, and "sufformatives" used by <u>Basics of Biblical Hebrew</u> are synonymous.

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
hfu4gjNo2K4?start=2846&end=3062&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/hfu4gjNo2K4?start=2846){target="_blank"}

Start: 47:26
End: 51:02

##  Qal is Simple action, Active voice

| |Active Voice| Passive Voice | Reflexive Voice
|:- |:- |:- |:-
Simple Action	| __QAL__ | Niphal | (Niphal)
Intensive	| Piel | Pual | Hitpael
Cause an Action	|Hiphil | Hophal

*  Remember this table is very high-level and perhaps over-simplified; but, it is a good starting place for understanding the meaning each stem
*  Qal is the primary Hebrew stem
*  The other six major stems are said to be "derived" from the Qal stem, hence the name "derived stems"

## Perfect is completed action or a state as a whole

* In translating, we will most often use the simple English past tense
    * For example, "she studied"
* It is commonly taught that the Hebrew perfect is equivalent to the English past tense
    * This is a generality; it is often true, but it is not always true
    * Other translations may be appropriate depending on the context
        * Present perfect: "she has studied"
        * Past perfect: "she had studied"
        * Future perfect: "she will have studied"
* Stative verbs describe a state of being; these verbs are also Perfect
    * English present is often a better translation: She is wise, she knows, she loves
    * English past might also be appropriate: she was wise
    * In a few sections, we will learn that in Hebrew, stative verbs are sometimes spelled differently
    
::: {.box .info}
The Hebrew perfect aspect describes an action or a state of being as a whole, not as a process

I.e., "she was studying" is an incomplete process, but "she had studied" is completed action  
:::

## Preformatives and Sufformatives

* In Lesson 12, we introduced the concept of preformatives and sufformatives
* These are unique verbal beginnings and endings that indicate person, gender, and number
* The Perfect has a set of "perfect sufformatives"
    * Only the 3ms does not have a perfect sufformative
    * We will learn the sufformatives for the remaining forms in the next section
    * The perfect does not have preformatives
    * A verb without a preformative, and a perfect sufformative will be diagnostic of a Perfect conjugation
    * The perfect sufformatives are the same across all verb stems, so what you learn for the Qal can be applied to the derived stems
* The Imperfect primarily has "imperfect preformatives"
    * All forms have an imperfect preformative
    * Many forms also have an imperfect sufformative

## The Perfect Sufformatives I

* The table below shows the perfect sufformatives in the middle column  
* Note how the 1st person, 2nd person, and 3fs forms are similar to the respective pronominal suffix
* 2MP and 2FP are called "Heavy Sufformatives" because, as we will learn, they draw the accent


<img src="images/13_perfect sufformatives.png" width="700pt" style="display: block; margin: auto;" />




## The Perfect Sufformatives II

* The table below lists the perfect sufformatives
    * Stand-alone
    * Affixed to the <span class="he">קטל</span> paradigm verb
* Note 3ms does not have a perfect sufformative but all the other forms do
* Since 3mp and 3fp are the same in the Perfect, we simply say "3cp" - Third-person, common, plural

<img src="images/13.qptable.png" width="700pt" style="display: block; margin: auto;" />

::: {.box .map}
GOOD NEWS

As you continue with your Hebrew GRAMMAR Quest into Unit 4, you will learn these sufformatives REMAIN THE SAME throughout all seven Perfect conjugations.
:::

## A Sheva precedes a Finite Sufformative

* This is a general rule that results in a Sheva under $R_3$ or $R_2$
* This only applies to finite verbs (Perfect, Imperfect, Imperative, ; )
* Of course, when the Sheva is under $R_2$, this means the Sheva displaces the conjugation's normal $V_S$
* Because of this rule, when the sufformative has a בגדכפת letter (usually ת), that letter will take a Daghesh Lene
* Take a look at this table again and note how there is a sheva next to the sufformative
    * 3MS has no sufformative so it has no sheva
    * 3CP looks a little different because the sufformative starts with a vowel
        * The ל already has an associated vowel, Shureq
        * A consonant cannot have more than one vowel
        * Therefore the Sheva displaces the Patach in $V_2$
        * The same thing happens in 3FS; the Sheva can't go under the ל because it already has a vowel
    
<img src="images/13.qptable.png" width="700pt" style="display: block; margin: auto;" />
    
::: {.box .caution}
The Sheva is rejected in the following circumstances:

* A Sheva does not replace an unchangeable long vowel
* A Sheva does not replace $V_1$ of the Qal Perfect (and only the Qal Perfect)
* When $R_3$ is <span class="he">א</span>, the א quiesces (generally resulting in Compensatory Lengthening of $V_2$)

:::



## Qal Perfect Vowels: $V_1$ is almost always Qamets

* On previous chart, you likely noticed other markings under <span class="he">קטל</span> besides the sufformatives
* These are the other characteristics of the Qal perfect paradigm
* $V_1 = \bar A$ (Qamets) almost always
    * As we learned way back in this course, an unaccented long vowel in an open propretonic syllable will undergo propretonic reduction
    * When this happens, you will see a Vocal Sheva, but you will be able to deduce that $V_1$ used to be a long vowel - and if it's a Qal verb, you'll know it used to be a Qamets
* Study the chart below showing $V_1$
    * The vertical line in 3FS and 3CP is called a "metheg" and is used to distinguish $\bar A$ (Qamets) from $O$ (Qamets Hatuf) when followed by a Sheva
    * Note 2MP and 2FP have undergone propretonic reduction and have $ə$ (Vocal Sheva) instead of $\bar A$
    
<img src="images/13.qptablev1.png" width="700pt" style="display: block; margin: auto;" />

## Qal Perfect Strong $Pre =$ <span class="he">קָ</span>

* HGQ SHORTHAND: $Pre$ = Strong Form Diagnostic Word-initial Sequence
* Each of the stems/conjugations has a distinctive combination of consonants, vowels, and occasionally Daghesh Forte marks the first one or two syllables of a given verb
* This serves to make the strong form of the verb easy to differentiate from the other stems
* We will call this diagnostic sequence "$Pre$"
    * Saying "diagnostic word-initial sequence of consonants and vowels" would get tiresome!
* For Qal Perfect (QP), $Pre =$ <span class="he">קָ</span>
    * ק represents any strong letter in $R_1$ 
    * This means the distinctive word-initial sequence of a <u>Q</u>al <u>P</u>erfect verb is no prefix/preformative and a Qamets in $V_1$

    
## Qal Perfect Strong $V_S = A$

* For QP, $V_2$ prefers Patach 
* For strong verbs, $V_S = V_2$
    * So we could either say "$V_S$ for Qal Perfect Strong equals Patach"
    * Or we could use formula shorthand and say, "Qal $V_S = A$", since "A" is our shorthand for a short A vowel, i.e., Patach
* In 3cp and 3fs, the Sheva of the perfect sufformative goes in $V_2$

<img src="images/13.qptablevs.png" width="700pt" style="display: block; margin: auto;" />

::: {.box .caution}
EXCEPTIONS

* The $V_S$ can change based on other grammar rules, for example, when the vowel must reduce to a Sheva/Reduced Vowel
* Some stative verbs can also take a Tsere or Holem in $V_2$ (see "Stative Verbs..." section in this Lesson)

:::
    

## Each Stem will have a $V_S$ Formula

* As we progress through the verbs, each major stem will end up with a formula that looks something like this: 

$$V_{S} =  Î[A] \sim  Î(Ē)$$

* This is probably complete gibberish to you right now
* As we get into Unit 4, this formula (in combination with the $Pre$ pattern) will save you hours of paradigm memorization of the derived stems
* You will only need to memorize the Qal paradigms, then apply this formula to the other stems
* So let's start to build this formula for the Qal:

$$V_{S} = A \sim$$

* In the formula, $A$ refers to Patach
* This formula is telling you that the Stem Vowel of the Perfect Conjugation _prefers_ Patach
* The _Imperfect_ Stem Vowel will be to the right of the $\sim$ mark - we'll address this in Lesson 15

            

## $V_S$ is accented in Finite verbs

* As we introduced in Lesson 12, verbs that have "person" designation are called Finite verbs
    * Perfect, Imperfect, Imperative, Cohortative, Jussive are FINITE
    * Infinitive Construct, Infinitive Absolute, Participle are NON-FINITE because they do not have "person"
* The $V_S$ is accented in Finite verbs, when possible
    * As we said in the previous lesson, $V_S$ usually = $V_2$ 
        * In <span class="he">קָטַל</span> $V_S = A$ (Patach)
    * If $R_2$ is a vowel letter, then $V_S$ = $V_1$
        * In <span class="he">קוּם</span> $V_S = \hat U$ (Shuruq)
    * If $R_2$ disappears, then $V_S$ = $V_1$ 
        * In <span class="he">קָם</span> $V_S = \bar A$ (Qamets)
* Take a look at this table again and note where the accent lands:

<img src="images/13.qptablevs.png" width="700pt" style="display: block; margin: auto;" />

::: {.box .caution}
EXCEPTIONS

* When $V_S$ is a Sheva or Hateph vowel:
    * Sheva/reduced vowels _never_ take an accent
    * In the Perfect, we will see this in QP3fs and QP3cp
* When the verb has a "heavy sufformative"
    * A heavy sufformative takes the accent
    * There are two heavy sufformatives in Hebrew:  2mp - תֶּ֫ם and 2fp - תֶּ֫ן
* When the verb has a pronominal suffix (Lesson 19)
* When $V_S$ is not one of the final two syllables

:::





## Building the Qal Perfect Strong Paradigm

* Understanding how we build the paradigm will prepare you to identify verbs in the Bible
* It will also prepare you to spot when deviations occur in weak verbs
* Study the graphic and the steps below carefully
* It may be confusing at first, but over time, it will begin to make sense

<img src="images/13.Qal_Perfect_Strong.gif" width="600pt" style="display: block; margin: auto;" />

1. Add the perfect sufformatives 
2. Put a Sheva before the sufformative 
    * 3fs/3cp - the Sheva can't go under $R_3$ because $R_3$ already has a vowel
        * A consonant can't have more than one vowel
        * For these forms, the Sheva goes under $R_2$
3. Add Dagesh Lene to תּ that comes after any Sheva
    * all 2nd person forms and 1cs
4. $V_S = A$ (Patach) in the Qal Perfect Strong paradigm (13.5)
    * UNLESS $V_2$ is already a Sheva from step two
5. Accent $V_S$ (unless there is one of the exceptions listed in 13.6)
6. $V_1 = \bar A$ (Qamets) (13.5)
    * 2mp/2fp - the Qamets is then reduced to a Vocal Sheva because of propretonic reduction
7. OPTIONAL - Add a metheg mark to $V_1$ 3fs/3cp 
    * The Metheg can denote that the vowel is Qamets followed by a vocal Sheva and not Qamets Hatuf followed by a Silent Sheva
    * Most Hebrew Bibles do not employ a Metheg for this purpose.
    
## Qal Perfect Strong Paradigm

Below is the complete paradigm.  Be sure to listen to Izzy read the forms with the paradigm verb, קטל and take note of pronunciation and accents.  


| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">קָטַל</span>  | 3cp | <span class="he">קָטְלוּ</span> 
| 3fs | <span class="he">קַטְלָה</span> | 
| 2ms | <span class="he">קָטַ֫לְתָּ</span> | 2mp | <span class="he">קְטַלְתֶּם</span>
| 2fs | <span class="he">קָטַ֫לְתְּ</span> | 2fp | <span class="he">קְטַלְתֶּן</span>
| 1cs | <span class="he">קָטַ֫לְתִּי</span> | 1cp | <span class="he">קָטַ֫לנוּ</span>


<figure>
    <figcaption>Listen to the Qal Perfect Strong Paradigm from _Hebrew Quest_</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/13.Qal_perfect.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>

## Worksheet: Qal Perfect Strong Paradigm {-}

* We are going to go a little out of order
* Typically, we save all of the activities for the end of the lesson, but here, we want you to pause and complete the [Qal Perfect Strong Paradigm](./images/13_qal_perfect_strong_paradigm.pdf){target="_blank"}.

> Complete the paradigm from memory at least once, then return here and continue in the guidebook.

* We know you're tempted to keep on clicking to read the pages that follow.  Resist!
* Doing the worksheet now will maximize your learning time
* In other words, the material that follows in this lesson will make more sense to you if you have the paradigm in your short-term memory

## Qal Perfect Strong Examples

* <span class="he">יָדַ֥ע</span>
    * No Preformative + No sufformative =  $P3ms$ conjugation
    * $Pre =$ <span class="he">קָ</span> and  $V_2 = A$ are diagnostic of $Q$ stem
        * In the Qal, can also have $V_2 = \bar A$
    * This combination of Preformatives, sufformatives, and vowels can only be Qal Perfect 3MS (QP3ms) - he knows
    * As we said in the introduction to Unit 3, you will start to see the cantillation marks in words and passages.  If you don't recognize a mark as a vowel, it is a cantillation mark.
* <span class="he">שָׁמְר֤וּ</span>
    * No preformative + וּ sufformative = $P3cp$ conjugation
    * $Pre =$ <span class="he">קָ</span> is diagnostic of $Q$ stem
        * $V_2 = :$
        * The Perfect sufformative is preceded by a Sheva whenever possible
        * In the P3cp and P3fs, the Sheva of the sufformative displaces $V_2$
        * If we know our vocab, we also understand that the Lexical form is <span class="he">שָׁמַר</span>.
    * שָׁמְר֤וּ is Qal Perfect 3cp (QP3cp) - they guarded/observed

::: {.box .map}
NAVIGATION TIP

* As we will learn in Unit 4, when there are no other signs of a different stem, we can default to Qal; this is because Qal is the most common stem
* As with <span class="he">זָכָ֑רְתְּ</span>, there are times where $V_2= \bar A$ or $V_2 = A$
    * These are often spelling variants that occur over the many hundreds of years the Tanach was written<small>^[<small>This is not unlike seeing "olde" or even "auld" on an English document from a few hundred years ago.  We know they both mean "old"</small>]</small>
    * There is nothing otherwise to suggest that these are not Qal verbs

:::

## Deviations from the Paradigm

* As we talked about in Lesson 12, what makes a verb "weak" versus "strong" is when one or more letters cause a deviation from the strong verb paradigm
* While the bulk of the discussion on weak verbs will be in Lesson 14, there are three weak forms we will introduce in this lesson: 
    * Words where $R_3$ = <span class="he">נ</span>, which we abbreviate as  or sometimes III-נ (pronounced as, "third nun")
    * Words where $R_3$ = <span class="he">ת</span>, called  or 3ת
    * Stative verbs where $V_2 \not = A$

> In most cases, you already know the behaviors of "weak" letters!  

While "stative" verbs may be a new concept, we have already discussed the tendency of ת and נ to assimilate under certain circumstances.  This is what happens when we encounter 3ת and 3נ verbs.

## 3נ and 3ת Verbs

* We mentioned above how a Sheva will be placed before a Finite sufformative (if possible)
* When ת and נ have a Silent Sheva, each may assimilate depending on the letter that follows
    * In other words, the verb will lose $R_3$ and a Daghesh Forte will be placed into the first letter of the sufformative
    * An $R_3$ of ת with a Silent Sheva will only assimilate when the sufformative begins with ת
        * Not <span class="he">כָּרַ֫תְתָּ</span>*<small>^[<small>Remember, the * means the Hebrew word is an impossibility, but is shown for illustrative purposes</small>]</small> but <span class="he">כָּרַ֫תָּ</span>
        * Not <span class="he">כְּרַתְתֶּם</span>*, but <span class="he">כְּרַתֶּ֫ם</span>
        * IMPORTANT: Note how the Daghesh in the ת shifts from a Lene to a Forte (because the Daghesh is now preceded by a vowel that is not a Sheva)
            * This is your cue that something has changed, usually that a letter is missing
            * In theory, the root could be either <span class="he">כרן</span> or <span class="he">כרת</span>, but you already know כרת from your vocabulary work (and there is no verb root <span class="he">כרן)
    * An $R_3$ of נ with a Silent Sheva will tend to assimilate to either נ or ת
        * <span class="he">נַתַן</span> is an extremely common 3נ verb meaning "to give"
        * Not <span class="he">נָתַ֫נְנוּ</span>*, but <span class="he">נָתַ֫נּוּ</span>
        * Not <span class="he">נָתַ֫נְתָּ</span>*, but <span class="he">נָתַ֫תָּ</span>
    
## Stative Verbs MAY have a different $V_S$

* Stative verbs describe a state of being, such as "wise", "old", or even "dead"
* The $V_S$ may change in some forms
    * There is what is called a "Patach Stative" that prefers $V_S$ of (wait for it...) Patach
        * Since Qal Perfect _already_ prefers a $V_S$ of Patach, there is no visible change
        * Patach Stative has a different $V_S$ in the Imperfect conjugation
        * <span class="he">גָּדַ֫ל</span>, "he is great" is an example - this word maintains the Perfect Strong paradigm all the way through
    * Tsere Stative has $V_S$ of Tsere in the P3ms ONLY
        * <span class="he">כָּבֵ֫ד</span> = "he is honored"
        * All other PGN follow the Perfect Strong
    * Holem Stative has $V_S$ of Holem in P3ms, P2ms, and P1cp
        * Holem Statives are relatively rare and do not even appear in the Bible as P2fs or any of the plural forms other than P1cp
        * <span class="he">יַכֹ֫ל</span> = "he is able to" or "he can"
        * <span class="he">קָטֹ֫נְתִּי</span> = "I am small"
            * Note the נְ DOES NOT assimilate - Hebrew likes to keep you guessing!
            * When you see only $R_1$ and $R_2$ and then a Daghesh Forte in the next consonant, it's better to ask, "did $R_3$ assimilate?"



## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/PuYs3ZTVXVg" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/PuYs3ZTVXVg){target="_blank"}



## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/kgMX1hbnbSE" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/kgMX1hbnbSE){target="_blank"}

## Anki {-}

* `Lesson 13 A. Vocab`
* `Lesson 13 B. Grammar` 
* `Lesson 13 C. Workbook` 
    * The verb parsing exercises are taking directly from the Study Verses
    * As we will learn next week, "weak" verbs are a lot more common than "strong" verbs
    * Even though we will formally study weak verbs in Lesson 14, you should be able to use your knowledge of $V_1$ and the Perfect preformatives to determine the parsing solution
        * Of course, we've only studied the Qal Perfect!
        * When you encounter a "weak" verb, such as <span class="he">מָלְאָ֥ה</span>, which is 3א, or <span class="he">יָדָ֔עוּ</span>, which is 3עח (A ח or ע as $R_3$), try to see what changes occur (based on what you already know about Gutturals)
* `Lesson 13 D. Study Verses`


## Ruth Pursuit {-}        

::: {.box .map} 
YOUR QUEST:

1. Identify and translate the following Qal Perfect Strong Verbs:
    * פקד QP3ms (yellow)
    * זקן QP1cs (green)
        * What is unique about this verb?
    * ילד QP1cs (gray)
    * דבק QP3fs (blue)
        * Hint: See [page 65 of this dictionary](https://holylanguage.com/resources/Pocket-Hebrew-Dictionary-Feyerabend.pdf){target="_blank"}
2. Identify and translate מלא FS (adjective)(pink)

:::


* [Blank copy of Ruth 1](https://docs.google.com/document/d/1bcT1J-fcVmD1Zn5Jk2nj0560tEddcgtbYZLkwaVVuyE/copy){target="_blank"}
* [Ruth Pursuit Answer Key #13](./images/13_Ruth_Pursuit_KEY.pdf){target="_blank"}




## Claim your next `Twelve Tribes Badge`! {-}

<!-- Lesson 13 Tribe Badge 5 = Issachar -->

When you have completed all activities on your `Hebrew GRAMMAR Quest Checklist` up to and including this lesson, complete the certification below, and your badge will be on its way!

<div class="containerLtr">
<iframe class="responsive-iframe" src="https://forms.gle/ywRYeNmuKkK441Pj9" frameborder="0"></iframe>
</div>

## OPTIONAL _Hebrew Quest_ Study Passage: Proverbs #5-7 {-}

::: {.box .map}
YOUR HEBREW QUEST:

1. BEFORE WATCHING THE VIDEO, read through the passage on your own straight through one time - pick up as much as you can - [Blank copy of the Proverbs studied in sessions 5-7.](https://docs.google.com/document/d/15D5W-prZoVTGEFa9QzuBCnfW4kQnwXT4TBNYNPhcRW8/copy){target="_blank"}
2. Now re-read the passage critically
    1. Highlight any words you do not know and look them up in a [lexicon](https://holylanguage.com/resources-dictionaries.php){target="_blank"}
    2. Sketch out a translation - there is a blank line between each verse
3. Now, using your marked-up copy of the passage, watch Izzy's _Hebrew Quest_ videos (video opens in a new tab)
    1. [Proverbs #5](https://holylanguage.com/proverbs-5.php){target="_blank"}
    1. [Proverbs #6](https://holylanguage.com/proverbs-6.php){target="_blank"}
    1. [Proverbs #7](https://holylanguage.com/proverbs-7.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?

:::

<!--chapter:end:13-Qal_Perfect_Strong.Rmd-->

# Qal Perfect - Weak Verbs {.QP-w}

In the Bible, weak verbs are much more common than strong verbs.

A weak verb is defined as one with one or more letters that cause the word to deviate from the strong verb pattern.  

Many Hebrew grammar textbooks asked students to memorize all of the differences in each stem and conjugation.  Fortunately, there is an easier way.  

We can simply study the changes caused by weak letters. These changes then become clues we can use to uncover the applicable strong verb pattern.  This will enable us to correctly determine a weak verb's stem and conjugation to translate it accurately.


::: {.box .map}
<span class="he">LESSON ITINERARY<span class="he">

1. 3נ and 3ת assimilate
1. 1G, 2G reject Vocal Sheva
1. 2fs form of 3ע/ח is irregular
1. 3א usually quiesces
1. $R_3$ in 3ה is a vowel, not a consonant
1. Geminate and Biconsonantal often have only two root letters visible
1. Clues for your Qal Perfect Quest
:::

::: {.box .stop}
EQUIPMENT CHECK

Before continuing, can you describe the following concepts?

* You must have the Qal Perfect Strong Paradigm memorized!

:::

##  First Thought {-}

### <span class="he">בָ֤אָה נַחֲלָתֵ֙נוּ֙ אֵלֵ֔ינוּ מֵעֵ֥בֶר הַיַּרְדֵּ֖ן מִזְרָֽחָה׃</span> {-}

*our inheritance has fallen to us on this side of the Jordan toward the east (Numbers 32:19)*

Numbers 32 begins, "The Reubenites and Gadites, who had very large herds and flocks, saw that the lands of Jazer and Gilead were suitable for livestock."  They followed their eyes, which saw profit. They took the easy path, which caused tension between the tribes. Students of history know that these lands to the east were often easily invaded. The lesson for us is to make sure we seek what the Lord wants for us and not our own desires.

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/14-03-Num.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/14_Cows of Bashan with Mount Hermon, tb032905276.jpg" alt="Cows of Bashan with Mount Hermon. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-76)Cows of Bashan with Mount Hermon. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>


## Introduction and Review

* Strong verbs follow the קטל strong-verb paradigm
    * The literal meaning of קטל is not material to our study
    * Like a math formula, these three letters are placeholders represent any verbal root containing three strong letters
* A weak letter behaves differently in some fashion
    * It could reject a dagesh forte, prefer a different vowel, or disappear entirely under certain situations
* A weak verb is a verbal root with one or more weak letters
* It is possible for a verb may be strong in one conjugation but weak in another
    * For example, Resh is only a weak letter in verbs that try to put a Daghesh Forte in it
    * The Qal stem does not require a Dagesh Forte in any form; therefore, verbs with Resh are not weak in Qal
    * In Unit 4, we will learn the Piel stem requires a Daghesh Forte in $R_2$; therefore, a verb with a Resh (or any guttural) in $R_2$ is a weak verb in the Piel
* Weak verbs are classified by their problematic root letter 
    * [Refer to Lesson 12](#weak-class) for a review of weak verb classes


## 3נ and 3ת with Silent Sheva Assimilate to Dagesh

* A Tav with a Sheva assimilates to another Tav only
    * It becomes a Dagesh Forte in the following Tav
    * This occurs in all Qal Perfect 2nd person forms as well as 1cs
    * NOT <span class="he">כָּרַתְתָּ</span>*, BUT <span class="he">כָּרַתָּ</span>
* A Nun with a Silent Sheva assimilates to anything
    * It becomes a Daghesh Forte in the next letter
    * This occurs in all Qal Perfect 1st and 2nd Person forms
        * NOT <span class="he">נַתַ֫נְתָּ</span>*, BUT <span class="he">נַתַ֫תָּ</span> 
        * NOT <span class="he">נָתַנְנוּ</span>*, BUT <span class="he">נַתַ֫נּוֹ</span>
* The Dagesh 2MS ending is usually a Lene, but each becomes a Forte (Why?<small>^[<small>A Daghesh is a Forte if it is preceded by a vowel that is not a Sheva.</small>]</small>)

::: {.box .info}
DAGESH FORTE

* The Dagesh Forte is your clue that something is different
* Often, it replaces a missing letter

:::

## Review of Guttural Principles

* Gutturals and Resh reject Dagesh Forte, often resulting in compensatory Lengthening:
    * From $I$ to $\bar E$ 
    * From $A$ to $\bar A$ 
    * From $U$ to $\bar O$
* Gutturals Take Hateph Vowels instead of Vocal Sheva
    * Usually Hateph Patach, sometimes Hateph Seghol, rarely Hateph Qamets Hatuf
    * This can affect the preceding vowel, as well as the vowel associated with the guttural:
        * NOT <span class="he">עְמַדְתֶּם</span>*, BUT <span class="he">עֲמַדְתֶּם</span>
* Gutturals prefer Patach
    * NOT <span class="he">יִשְׁלֹח</span>*, BUT <span class="he">יִשְׁלַח</span>   

## 1G, 2G

* The Guttural will take Hateph Patach instead of Vocal Sheva
* 1G - affects QP2mp and QP2fs
    * NOT <span class="he">עְמַדְתֶּם</span>*, BUT <span class="he">עֲמַדְתֶּם</span>
    * Otherwise, $V_1 = \bar A$ as is diagnostic of the QP conjugation
* 2G - affects QP3fs, QP2fs, QP3cp
    * NOT <span class="he">בָּחְרוּ</span>*, BUT <span class="he">בָּהֲרוּ</span>
    * In 2G, $V_1 = \bar A$ (unless reduced in 2mp/2fp) as is diagnostic of the QP conjugation

::: {.box .light}
To get back to the strong verb paradigm, substitute Sheva for the Hateph vowels
::::

    
## 3-ע/ח

* Because different $R_3$ gutturals behave in different ways, we are unable to simply say "third guttural"
    * 3 ע/ח is discussed below
    * א 3 and 3 ה will be discussed in separate sections
* 3 ע/ח: We said earlier that the Gutturals reject VOCAL Sheva, but the Sheva in the 2nd (except 2fs) and 1st person forms is SILENT, so it stays
    * <span class="he">שָׁמַ֫עְתָּ</span>
* For reasons scholars don't fully understand, the 2fs form is irregular        
    * The  3rd ע or ח takes a Patach instead of a Sheva:
        * <span class="he">שָׁמַ֫עַתְּ</span>
    * The Dagesh is a LENE despite the preceding vowel
    * It is not necessary to memorize this oddity
* In all 3G, $V_1 = \bar A$ (unless reduced in 2mp/2fp) as is diagnostic of the QP conjugation - in other words, no matter what happens to $V_S$, you will usually be able to diagnose Qal Perfect by the regular Qamets in $V_1$

    
## א3 

* Aleph quiesces with Silent Sheva
    * Occasionally, it also quiesces with Hateph vowels (i.e., Vocal Sheva)
    * Usually, there is Compensatory Lengthening (CL)
    * $V_2 = \bar A$ (Qamets) unless reduced by the perfect sufformative
    * QP2ms: NOT <span class="he">מָצַ֫אְתָּ</span>*, BUT <span class="he">מָצָ֫אתָּ</span>
    * QP3ms, the Aleph is already quiescent (CL): NOT <span class="he">מָצַא</span>*, BUT <span class="he">מָצָא</span>
    * בגד כפת have Dagesh Lene only if not after a vowel
        * In other words, the Quiescent Aleph is ignored
        * Note how the 2fs forms drop the Dagesh Lene and final Silent Sheva if a vowel is before the בגד כפת:
        * NOT <span class="he">מָצַאְתְּ</span>*, BUT <span class="he">מָצָאת</span>
* As mentioned, in 3G, $V_1 = \bar A$ (unless reduced in 2mp/2fp) as is diagnostic of the QP conjugation - (are you beginning to see the pattern?)

## יָרֵא is 3א AND Tsere Stative

* $V_S = \bar E$ unless reduced (P3fs, P3cp)
* Most Tsere statives have $\bar E$ only in the 3ms  
* <span class="he">ירא</span> is irregular


## 3ה  

* 3ה verbs are in a unique class
* $R_3$ is not a consonant; in fact, there is no $R_3$ consonant
* 3ה verbs only have two root consonants, $R_1$ and $R_2$ - the final slot is taken up by $\hat A$ (Qamats+Hei)

::: {.box .info}
Historically, third ה verbs used to be 3-י.  In some conjugations, the Yod "reappears."
:::

* $V_2$ of 3ה verbs follow a unique pattern:
    * IF there is no sufformative, THEN add the vowel $\hat A$ in the Perfect
    * IF the sufformative starts with a vowel, THEN the vowel of the sufformative is $V_2$
    * IF the sufformative starts with a consonant, THEN $V_2$ is (vowel)+Yod
        * The specific (vowel) depends on the conjugation
        * For the Perfect, $V_2 = \hat I$ (Hireq+Yod)
* Additionally, to avoid ambiguity with the P3ms, the P3fs sufformative becomes <span class="he">תָה</span>
* With all these changes, the  $V_1 = \bar A$ (unless reduced in 2mp/2fp) diagnostic of QP does not change

::: {.box .light}
3ה ENDINGS

* 3ה Verbs are frequent, so we will want to memorize these rules and endings
* They are consistent throughout all stems; e.g., P3ms 3ה verbs end in $\hat A$ (Qamets+Hei) in all seven stems

:::

## Doubly Weak

* Doubly weak verbs have two (or all three<small>^[<small>Even those verbs with three weak letters are still referred to as 'doubly weak'</small>]</small>) weak letters
* Most frequently, it will be a 3ה verb with a 1G or 2G
* These verbs have an additional step to scavenger hunt our way back to the Strong Verb Paradigm
* We simply need to combine the 1G/2G aspects of the Hateph vowel instead of a Sheva with the 3ה endings we studied in the previous section

## הָיָה

* This is a very common verb meaning "to be"
* As you can see, it is both 1G and 3ה
* It follows the 3ה endings we discussed above
* $V_1$ is <span class="he">הֱ</span> in 2mp and 2fp
    * <span class="he">הֱיִיתֶם</span> and <span class="he">הֱיִיתֵן</span>
    * The first Yod is $R_2$
    * The second is $V_2 = \hat I$ (Hireq+Yod)

## Geminate Paradigm

* In Geminate verbs, $R_3 = $R_2$
* No Hebrew words have $R_1 = R_2$ - this will prove to be important later in the course
* Frequently, $R_2$ assimilates into its twin $R_3$
    * $R_3$ will then take a Dagesh Forte, unless it is the final consonant in a word
    * 3rd person forms will have both
        * <span class="he">סַב</span> or <span class="he">סָבַב</span>
    * When there is assimilation, the accent tries to shift to $V_1$ since that is the new Stem Vowel
        * The accent must be on the last two syllables
        * The heavy sufformatives (2mp and 2fp) continue to take the accent
    * $V_2 = \hat O$ before sufformative that starts with a consonant
* Review the table below, noting $V_1$ and accent changes:


| PGN | Gem | Strong
| :- | :- | :-
3ms | <span class="he">סָבַב</span> | <span class="he">קָטַל</span>
3fs | <span class="he">סָֽבְבָה</span> | <span class="he">קָֽטְלָה</span>
2ms | <span class="he">סַבּ֫וֹתָ</span> | <span class="he">קָטַ֫לְתָּ</span>
2fs | <span class="he">סַבּוֹת</span> | <span class="he">קָטַלְתְּ</span>
1cs | <span class="he">סַבּ֫וֹתִי</span> | <span class="he">קָטַ֫לְתִּי</span>
3cp | <span class="he">סָֽבְבוּ</span> | <span class="he">קָֽטְלוּ</span>
2mp | <span class="he">סַבּוֹתֶם</span> | <span class="he">קְטַלְתֶּם</span>
2fp | <span class="he">סַבָּוֹתֶן</span> | <span class="he">קְטַלְתֶּן</span>
1cp | <span class="he">סַבּ֫וֹנוּ</span> | <span class="he">קָטַ֫לְנוּ</span>



::: {.box .map}
Geminate verbs are relatively infrequent, so the changes in the table above needn't distract you from your verb parsing quest!
:::

## Geminate Vocabulary

You will learn the major geminate verbs in your vocabulary. To start with, here are a few of the most common:

* <span class="he">סָבַב</span>, to surround
    * We can also see QP3ms as <span class="he">סַב</span>
* <span class="he">שָׁלַל</span>, to plunder
* <span class="he">אָרַר</span>, to curse
    * Resh rejects = Compensatory Lengthening
    * <span class="he">אָר֫וֹתִי</span> = QP1cs
    * In the table on the previous page, note how $V_1 = A$, but in <span class="he">אָר֫וֹתִי</span>, $V_1 = \bar A$
* <span class="he">תָמַם</span>, to finish
    * The first מ will assimilate into a Dagesh Forte (except QP3ms)
    * <span class="he">תַּ֫מּוּ</span> = QP3cp


## Biconsonantal

* Biconsonantal have two root consonants, $R_1$ and $R_3$
* What appears to be $R_2$ is actually an unchangeable long vowel, Holem+Vav, Shuruq, or Hireq+Yod
    * This vowel is called the __LEXICAL VOWEL__
    * It will be important to memorize the Lexical Vowel
        * For example, NOT <span class="he">קִים</span>**, NOT <span class="he">קוֹם</span>**, BUT <span class="he">קוּם</span>
    * The word with the Lexical Vowel is the Lexical Form (the version that is in the dictionary)
    * This is an exception to the QP3ms = Lexical Form guideline
* $V_S$ and its accent move to $V_1$ and do not reduce
    * $V_S$ lengthens in 3rd person
    
Review the table below, noting $V_1$ and accent changes:


| PGN | קוּם  | Strong
| :- | :- | :-
3ms | <span class="he">קָם</span> | <span class="he">קָטַל</span>
3fs | <span class="he">קָ֫מָה</span> | <span class="he"></span>
2ms | <span class="he">קַ֫מְתָּ</span> | <span class="he">קָטַ֫לְתָּ</span>
2fs | <span class="he">קַמְתְּ</span> | <span class="he">קָטַלְתְּ</span>
1cs | <span class="he">קַ֫מְתִּי</span> | <span class="he">קָטַ֫לְתִּי</span>
3cp | <span class="he">קָ֫מוּ</span> | <span class="he">קָֽטְלוּ</span>
2mp | <span class="he">קַמְתֶּם</span> | <span class="he">קְטַלְתֶּם</span>
2fp | <span class="he">קַמְתֶּן</span> | <span class="he">קְטַלְתֶּן</span>
1cp | <span class="he">קַ֫מְנוּ</span> | <span class="he">קָטַ֫לְנוּ</span>


## מוּת is Biconsonantal and Stative

* Recognize Biconsonantal by the accent and missing root consonant
* $V_S$ and accent moved to $V_1$
* Tsere stem vowel in 3rd person
* In the perfect, only occurs in 3rd person and 1cp
* Compare <span class="he">מוּת</span> and <span class="he">קוּם</span> in the table below:


| PGN | קוּם  | מוֹת
| :- | :- | :-
3ms | <span class="he">קָם</span> | <span class="he">מֵת</span>
3fs | <span class="he">קָ֫מָה</span> | <span>
3cp | <span class="he">קָ֫מוּ</span> | <span>
1cp | <span class="he">קַ֫מְנוּ</span> | <span class="he">מַ֫תְנוּ</span>

## Qal Perfect Quest Clues

1. No preformative
2. Perfect sufformative
3. $V_1 = \bar A$ (Qamets)
    * $V_1$ will be reduced if 2mp/2fp
    * $V_1 =A$ (Patach) if Biconsonantal or Geminate 1st or 2nd Person
    * $V_1$ will be reduced if there is a pronominal suffix - Lesson 19
    
## Clues for Qal Perfect Special Situations

::: {.box .map}
MISSING A ROOT CONSONANT

* If $V_1$ is accented, it is biconsonantal or geminate
* 1st or 2nd person: look at the vowel before the sufformative
    * <span class="he">י ִ</span> = 3ה
    * <span class="he">וֹ ּ </span> = GEMINATE
    * <span class="he">ְ </span> = BICONSONANTAL
    * <span class="he">תּ ַ </span> (where Tav is the sufformative) = 3נ/ת
    * <span class="he">נּוּ ַ </span> in the 1cp = 3נ
* 3rd Person
    * Dagesh Forte in what looks like $R_2$ = GEMINATE
    * $V_1$ is accented and no Dagesh in $R_2$ = BICONSONANTAL
    * $V_2$ accented as usual = 3ה
:::

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/eoDmrjNixN4" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/eoDmrjNixN4){target="_blank"}

## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/8MouGMH5bCQ" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/8MouGMH5bCQ){target="_blank"}

## Anki {-}

* `Lesson 14 A. Vocab`
* `Lesson 14 B. Grammar` 
* `Lesson 14 C. Workbook`
* `Lesson 14 D. Study Verses`

> Unless there is something unique to point out, we will omit the Anki section from the Hebrew GRAMMAR Quest Guidebook going forward. You know the drill!  Be sure to do the four Anki levels after each Lesson.

## Ruth Pursuit {-}    

::: {.box .map} 
YOUR QUEST

Identify and translate the Qal Perfect Weak Verbs below.  All verbal roots are vocabulary words from Lesson 12 or Lesson 14.

1. שׁמע QP3fs
2. היה QP3fs
3. עשה QP2mp
4. אמר QP1cs
5. יצא QP3fs - why is this verb 3fs?
6. שׁוּב QP3fs (occurs two times)
7. הלך QP1cs
8. ענה QP3ms
9  בוֹא QP3cp

:::

* [Blank copy of Ruth 1](https://docs.google.com/document/d/1bcT1J-fcVmD1Zn5Jk2nj0560tEddcgtbYZLkwaVVuyE/copy){target="_blank"}
* [Ruth Pursuit Answer Key #14](./images/14_Ruth_Pursuit_KEY.pdf){target="_blank"}



## OPTIONAL _Hebrew Quest_ Study Passage: Proverbs #8-10 {-}



::: {.box .map}
YOUR HEBREW QUEST:

1. BEFORE WATCHING THE VIDEO, read through the passage on your own straight through one time - pick up as much as you can. [Blank copy of the Proverbs studied in sessions 5-7.](https://docs.google.com/document/d/15D5W-prZoVTGEFa9QzuBCnfW4kQnwXT4TBNYNPhcRW8/copy){target="_blank"}
2. Now re-read the passage critically
    1. Highlight any words you do not know and look them up in a [lexicon](https://holylanguage.com/resources-dictionaries.php){target="_blank"}
    2. Sketch out a translation - there is a blank line between each verse
3. Now, using your marked-up copy of the passage, watch Izzy's _Hebrew Quest_ videos (video opens in a new tab)
    1. [Proverbs #8](https://holylanguage.com/proverbs-8.php){target="_blank"}
    1. [Proverbs #9](https://holylanguage.com/proverbs-9.php){target="_blank"}
    1. [Proverbs #10](https://holylanguage.com/proverbs-10.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?

:::

<!--chapter:end:14-Qal_Perfect_Weak.Rmd-->

# Qal Imperfect - Strong Verbs {.QI-s}

To comprehend Biblical Hebrew, we must be able to parse and translate Qal imperfect verbs

In a few lessons, we will learn about the Vav Conjunction.  The Vav Conjunction + the Qal imperfect is the most frequent verb form in the Hebrew Bible, so understanding the imperfect is essential.  Like the Qal Perfect Strong paradigm, we must have a robotic-like recall of the Qal Imperfect Strong Paradigm.

<span class="he">וַיֹּאמֶר אֱלֹהִים יְהִי אוֹר וַיְהִי־אוֹר׃</span>

You might recognize this from Genesis 1:3 - "And God said, 'Let there be light'; and there was light."  There are three verbs in this short sentence, and all three are Qal Imperfect.

::: {.box .map}
LESSON ITINERARY

1. Imperfect is future, modal, or imperfective
1. Components of the Qal Imperfect Strong Paradigm
    1. The Imperfect Preformatives and Sufformatives
    1. The Qal Imperfect Vowels
1. Building the Qal Imperfect Paradigm
1. Deviations from the Strong Paradigm
1. Negative Commands
:::

::: {.box .stop}
EQUIPMENT CHECK

Before continuing, can you describe the Qal Perfect Strong Paradigm from memory?

:::

## First Thought {-}

### <span class="he">יִ֝שְׁמֹ֗ר כָּל־אָרְחֹתָֽי </span> {-}

*He watches all my paths (Job 33:11)*

There's a story of a small child who was beginning to understand the implications of God's power.  "Do you mean God is watching everything I do?" the child asked with mounting fear.  Her father quickly replied, "God loves you so much, He can't take His eyes off you."

Let that sink in as you study Biblical Hebrew.


<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/15-02-Job.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/15.Ascent of Adummim Roman road remains, tb113006725.jpg" alt="Ascent of Adummim Roman road remains. This was the main route from Jericho to Jerusalem in antiquity. It was notoriously treacherous, both in terms of physical exertion, rising 3500 feet in just 15 miles, as well as in terms of physical safety. This latter aspect provided the geographical context of Yeshua's story of the Good Samaritan in Luke 17. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="600pt" />
<p class="caption">(\#fig:unnamed-chunk-77)Ascent of Adummim Roman road remains. This was the main route from Jericho to Jerusalem in antiquity. It was notoriously treacherous, both in terms of physical exertion, rising 3500 feet in just 15 miles, as well as in terms of physical safety. This latter aspect provided the geographical context of Yeshua's story of the Good Samaritan in Luke 17. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>


## _Hebrew Quest_ Qal Imperfect Lecture

View this 4-minute overview video from _Hebrew Quest_ on Hebrew Qal Imperfect Verbs.  We will break down the concepts Izzy discusses as we progress through this lesson.  


<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
hfu4gjNo2K4?start=3044&end=3308&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/hfu4gjNo2K4?start=3044){target="_blank"}

## Translating the Imperfect

* The Imperfect has many potential translations
* Watch to see whether the imperfect verb begins a clause as this is a clue
* When the Imperfect does not begin a clause . . .
    * future, "I will run"
    * imperfective, "I am running" or "I was running"
* When the Imperfect begins a clause (and does not have a Vav Consecutive prefix)<small>^[<small>An imperfect verb _with_ the Vav Consuctive changes the verb's aspect to Perfect.  We'll study this in Lesson 17.</small>]</small> . . .
    * modal, cohortative: "I should run" or "I might run" or "let us run"
    * modal, jussive: "may he run"
    * We will study the modal forms in greater detail in Lesson 18
* When the imperfect is preceded by <span class="he">לֹא</span> or <span class="he">אַל</span> it is a negative command
    * We'll have more to say about this towards the end of the lesson
    

## The Imperfect Always has a Preformative

* All stems have the same set of preformatives
* The Imperfect is called the Prefix Conjugation
* <span class="he">י</span> for 3ms, 3mp
* <span class="he">א</span> for 1cs
* <span class="he">נ</span> for 1cp
* <span class="he">תּ</span> for everywhere else (3fs,3fp, 2ms, 2fs, 2mp, 2fp)


## Qal Imperfect Vowels

Qal Imperfect strong verbs have a diagnostic $V_P$ + $V_1$ combination

* All QI strong verbs except 1cs begin with Hireq+Silent Shewa
    *  <span class="he">ְ יִ</span> for 3ms, 3mp
    *  <span class="he">ְ נִ</span> for 1cp
    *  <span class="he">ְ תִּ</span> for all others except 1cs
* 1cs begins with Aleph+Seghol+Silent Sheva <span class="he">ְ אֶ</span>
* The vowels behave as if they were from the Rule of Sheva (they aren't)
* We can summarize this by saying, "for the QI, $Pre =$ <span class="he">יִקְ</span>
    * <span class="he">יִ</span> represents any of the Imperfect preformatives with a Hireq or <span class="he">אֶ</span>
    * <span class="he">קְ</span> represents any strong letter in $R_1$ with a Silent Sheva

<img src="images/15-rule-of-sheva.png" width="400pt" style="display: block; margin: auto;" />


## Imperfect Sufformatives

* Of the singular forms, only 2fs has a sufformative
    * It is <span class="he">י ִ</span>
    * The <span class="he">ְ תִּ</span> preformative with the <span class="he">י ִ</span> sufformative is diagnostic of the QI2fs
* Of the plural forms, only 1cp does NOT have a sufformative
    * 2mp/3mp sufformative - <span class="he">וּ</span>
        * Occasionally, there may be what is called a Paragogic Nun, as in <span class="he">וּן</span>
        * The ן sometimes causes the shuruk to shorten to a Qubbutz
        * In other words, you may see <span class="he">יִקְטְלוּ</span> or <span class="he">יִקְטְלוּן</span> or <span class="he">יִקְטְלֻן</span>.  All three words are QI3mp
    * 2fp/3fp sufformative - <span class="he">נָה</span>
    * You'll note that QI2fp and QI3fp are identical.   The context will determine whether the verb is being used in the 3rd person or the 2nd person.  These forms are relatively infrequent.
* There are no "heavy sufformatives" in the Imperfect
    * In fact, the two we studied previously (2mp and 2fp) are the only ones
* The Imperfect is a Finite verb, so a Sheva prefers to go before a finite verb sufformative


> Now we're ready to put all this together and learn the Qal Imperfect Strong Paradigm, the same way we built the Qal Perfect Strong Paradigm!

## Building the Qal Imperfect Strong Paradigm

Study the graphic and the steps below carefully.  It may seem confusing at first but, with practice, you'll get it.  You'll note that the steps work from left to right.


<img src="images/15.Qal_imperfect_Strong.png" width="900pt" style="display: block; margin: auto;" />

1. Add Imperfect Preformatives 
2. Add Imperfect Sufformatives
3. A Sheva goes before a finite sufformative
    * Sheva goes under $R_2$ (displacing $V_S/V_2$) when $R_3$ already has a vowel
4. $V_S = \bar O$ unless already reduced by the Sheva of the finite sufformative
    * Qal Formula: $V_S = A \sim \bar O$
        * Perfect = Patach
        * Imperfect = Holem
5. Accent $V_S$ unless it reduced
6. $V_P = I$ and $V_1 = \ :$, except 1cs ($V_P = E$)
    * Qal $Pre =$ <span class="he">יִקְ</span>
7. Add Dagesh Lene to בגד כפת after Sheva (N/A for קטל)



## Qal Imperfect Strong Paradigm


| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">יִקְטֹל</span>  | 3mp | <span class="he">יִקְטְלוּ</span> 
| 3fs | <span class="he">תִּקְטֹל</span> | 3fp | <span class="he">תִּקְטֹ֫לְנָה</span> 
| 2ms | <span class="he">תִּקְטֹל</span> | 2mp | <span class="he">תִּקְטְלוּ</span>
| 2fs | <span class="he">תִּקְטְלִי</span> | 2fp | <span class="he">תִּקְטֹ֫לְנָה</span>
| 1cs | <span class="he">אֶקְטֹל</span> | 1cp | <span class="he">נִקְטֹל</span>


<figure>
    <figcaption>Qal Imperfect Strong (Singular) read by Izzy</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/15.QIsingularIzzy.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>

<figure>
    <figcaption>Qal Imperfect Strong (Plural) read by Izzy</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/15.QIpluralIzzy.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>

## Worksheet: Qal Imperfect Strong Paradigm {-}

As with Lesson 13, we want you to pause here and do the [Qal Imperfect Strong Paradigm](./images/15_qal_imperfect_strong_paradigm.pdf){target="_blank"}.

> Complete the paradigm until you can do it from memory at least once, then return here and continue in the guidebook.


Doing the worksheet now will maximize your learning time. In other words, the material that follows in this lesson will make more sense to you if you have the paradigm in your short-term memory.

## Qal Imperfect Strong Examples

* <span class="he">תִּזְכְּר֔וּ</span>
    * Preformative: Tav+Hireq+Sheva = QI2xx or QI3Fx
    * Sufformative: Shuruq = I2mp or I3mp
    * Together: QI2mp
    * You will remember
* <span class="he">יִכְתֹּ֤ב</span>
    * Preformative: Yod+Hireq+Sheva = QI3mx
    * Sufformative: none = QIxxS or QI1CP
    * Together: QI3ms
    * He will write
* <span class="he">תִשְׁבַּ֤ת </span>
    * Preformative: Tav+Hireq+Sheva = QI2xx or QI3Fx
    * Sufformative: none = QIxxS or QI1CP
    * Together: QI3fs or QI2fs - context will determine which one
    * Context: <span class="he">לָ֣מָּה תִשְׁבַּ֤ת הַמְּלָאכָה֙</span> = Lit: why she will stop, the work" or "Why should the work stop" = the verb is modifying "the work" which is a feminine noun.
    * QI3fs


## Deviations from the Paradigm

* All stative verbs have $V_S = A$  (QI strong paradigm $V_S = O$)
    * This is true in all PGN except where $V_S$ has been replaced by a Sheva (in step 3 of the workflow)
    * <span class="he">יִגְדַּל</span> = he/it will be great or let him/it be great
* 3נ assimilates to a consonant as usual when the sufformative starts with a consonant
    * This happens in the QI(2/3)Pfp
    * <span class="he">תִּשְׁכֹּנָּה</span> = you (fp)/they (f) will dwell
    * Since $V_1$ is a Sheva in the imperfect, 1נ verbs will be affected by this (Lesson 16)
    


## Translating Negative Commands

* An imperfect form that is preceded by a negation is a negative imperative
* Hebrew has an imperative form (Lesson 18), but this form is not used for negative commands
* Hebrew has two primary words for negative commands: <span class="he">לֹא</span> and <span class="he">אַל</span>
* <span class="he">לֹא</span> + imperfect is for permanent prohibitions
    * <span class="he">לֹא תִּרְצָח</span> Thou shalt not murder (Ex 20:13)
* <span class="he">אַל</span> + Jussive (closely related to imperfect) is usually a temporary or circumstantial prohibition
    * <span class="he">אַל־ת־ִשְׁמְעוּ אֶל־דִּבְרֵי נְבִיאֵיצֶם</span> Do not listen to the words of your prophets (Jer 27:16)
    * Jeremiah is not saying, "Don't EVER listen to ANY prophets"
    * In this circumstance, the people were listening to FALSE prophets
    * The specific circumstance of listening to false prophets is what Jeremiah is prohibiting



## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/IA1LEEbvOKw" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/IA1LEEbvOKw){target="_blank"}


## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/fellWe2bUt8" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/fellWe2bUt8){target="_blank"}

## Ruth Pursuit {-}   

::: {.box .map} 
YOUR QUEST

Identify and translate the Qal Verbs below.  

* היה QP1cs
* גדל QI3mp

:::

* [Blank copy of Ruth 1](https://docs.google.com/document/d/1bcT1J-fcVmD1Zn5Jk2nj0560tEddcgtbYZLkwaVVuyE/copy){target="_blank"}
* [Ruth Pursuit Answer Key #15](./images/15_Ruth_Pursuit_KEY.pdf){target="_blank"}



## OPTIONAL _Hebrew Quest_ Study Passage: Proverbs #11-14 {-}

::: {.box .map}
YOUR HEBREW QUEST:

1. Read the passage - [Blank copy of Proverbs #11-14](https://docs.google.com/document/d/1E1Qbbx3tHw8pOfMSGwQHwD406eHIMd1O5lAS_tDWllE/copy){target="_blank"}
2. Now re-read the passage critically
    1. Highlight any words you do not know and look them up in a [lexicon](https://holylanguage.com/resources-dictionaries.php){target="_blank"}
    2. Parse as many verbs as you can
    3. Sketch out a translation - there is a blank line between each verse
3. Next, using your marked-up copy of the passage, watch Izzy's _Hebrew Quest_ videos (video opens in a new tab)
    1. [Proverbs #11](https://holylanguage.com/proverbs-11.php){target="_blank"}
    1. [Proverbs #12](https://holylanguage.com/proverbs-12.php){target="_blank"}
    1. [Proverbs #13](https://holylanguage.com/proverbs-13.php){target="_blank"}
    1. [Proverbs #14](https://holylanguage.com/proverbs-14.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?

:::

<!--chapter:end:15-Qal_Imperfect_strong.Rmd-->

# Qal Imperfect Weak {.QI-w}

This is a critical and dense chapter.

Almost every weak verb class experiences some change in the Imperfect.

::: {.box .map}
LESSON ITINERARY

Work through the various weak verb forms in the Qal Imperfect

:::

::: {.box .stop}
EQUIPMENT CHECK

The Qal Imperfect Strong Paradigm must be memorized.

:::

## First Thought {-}

### <span class="he">וְעֵינֵיכֶ֖ם תִּרְאֶ֑ינָה</span> {-}

*Your eyes will see (Malachi 1:5)*


<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/16-06-Mal.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/16_Jezreel Valley from Mount Carmel panorama, tb032407526.jpg" alt="Jezreel Valley from Mount Carmel panorama. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="900pt" />
<p class="caption">(\#fig:unnamed-chunk-80)Jezreel Valley from Mount Carmel panorama. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>


## Our Quest

As we progress through the material in this chapter, our quest is to learn how the weak verbs behave in order to work our way back to the Qal Imperfect Strong Verb indicators.

Recall the two primary diagnostic indicators of the Qal Imperfect Strong:

* $Pre \ =$ <span class="he">יִקְ</span>
* $V_S = \bar O$


## 2G 

* When $V_2$ reduces, it will be a Hateph Vowel instead of Vocal Sheva
* Gutturals prefer Patach
    * When NOT reduced, $V_S = A$ instead of $\bar O$ 

::: {.box .light}
Although $V_S = A$, 2G verbs are easily recognized as Qal Imperfect since the $Pre \ =$ <span class="he">יִקְ</span> diagnostic is retained
:::

|  | 2G | Strong | 
| :-  | :- | :-  
| 3ms  |  <span class="he">יִבְחַר</span>  | <span class="he">יִקְטֹל</span>
| 3mp  |  <span class="he">יִבְחֲרוּ</span> | <span class="he">יִקְטְלוּ</span>



## 3חע

* Prefer $V_S = A$

::: {.box .light}

Although $V_S = A$, 3חע verbs are easily recognized as Qal Imperfect since the $Pre \ =$ <span class="he">יִקְ</span> diagnostic is retained  
:::

|  | 3חע | Strong | 
| :-  | :- | :-  
| 3ms  | <span class="he">יִשְׁלַח</span> | <span class="he">יִקְטֹל</span>
| 3mp  |  <span class="he">יִשְׁלְחוּ</span>| <span class="he">יִקְטְלוּ</span>

## 3א  

* While 3חע prefer $V_S = A$, 3א prefer $V_S = \bar A$ primarily
* 3/2fp
    * Will see $V_S = E$, or sometimes $V_S = \bar E$
    * 3א quiesces with Silent Sheva (and sometimes with vocal)

::: {.box .light}
Although $V_S$ can vary, 3א verbs are easily recognized as Qal Imperfect since the $Pre \ =$ <span class="he">יִקְ</span> diagnostic is retained  
:::

|  | 3א | Strong 
| :-  | :- | :-  
| 3ms | <span class="he">יִמְצָא</span> | <span class="he">יִקְטֹל</span>  
| 3fp/2fp | <span class="he">תִּמְצֶ֫אנָה </span> | <span class="he">תִּקְטֹ֫לְנָה<span class="he">

## 3ה 

::: {.box .caution}
3ה verbs lose the final ה root consonant in every form

:::

* _IF_ there is no sufformative, _THEN_ $V_2 \ =$ vowel + HEI:
    * Perfect - QAMETS+HEI: <span class="he">בָּנָה</span> - QP3ms
    * Imperfect - SEGHOL+HEI: <span class="he">יִבְנֶה</span> - QI3ms
* _IF_ the sufformative starts with a vowel, _THEN_ the sufformative IS $V_2$
    * QI3cp - <span class="he">יִבְנוּ</span>
    * QP3cp - <span class="he">בָּנוּ</span>
* _IF_ the sufformative starts with a consonant, _THEN_ $V_2 \ =$ vowel + י
    * Perfect - HIREQ+YOD- <span class="he">בְּנִיתֶם</span> - QP2mp
    * Imperfect - SEGHOL+YOD - <span class="he">תִּבְנֶ֫ינָה</span> - QI(3/2)fp 
    

::: {.box .light}

Despite the endings, 3ה verbs are easily recognized as Qal Imperfect since the $Pre \ =$ <span class="he">יִקְ</span> diagnostic is retained.

:::


|  | 3ה | Strong | Notes
| :-  | :- | :-  | :-
| QI3ms | <span class="he">יִבְנֶה</span> | <span class="he">יִקְטֹל</span>  | Seghol+Hei
| QI3mp | <span class="he">יִבְנוּ</span> | <span class="he">יִקְטְלוּ</span> | Sufformative Replaces
| QI(3/2)fp | <span class="he">תִּבְנֶ֫ינָה</span> | <span class="he">תִּקְטֹ֫לְנָה</span> | Seghol+Yod

## 3ה ending comparison table

The table below shows a comparison of 3ה verbs when there is no sufformative.

| Conj | Hebrew | Vowel
| :- | :- | :-
| P | <span class="he">בָּנָה</span> | Qamets+Hei
| I | <span class="he">יִבְנֶה</span> | Seghol+Hei

::: {.box .light}
3ה ENDINGS

* 3ה Verbs are frequent, so we will want to memorize these rules and endings
* They are consistent throughout all stems; e.g., I3ms 3ה verbs end in (Seghol+Hei) in all seven stems

:::


## 1G

* Remember the Rule of Sheva that prevents two contiguous Vocal Sheva/Hateph Vowels
    * NOT <span class="he">יְקְ</span>, BUT <span class="he">יִקְ</span>
    * Whenever we see the $Pre \ =$ <span class="he">ְ יִ</span> of the Qal Imperfect, think "Rule of Sheva"<small>^[<small>Historically the QI $Pre$ did not come the Rule of Sheva, however pretending that it did makes it easy to recognize QI 1G verbs.</small>]</small>
* The 1G will reject the Vocal Shewa in favor of a Hateph Vowel

::: {.box .light}
To identify QI from a 1G verb:

* Turn <span class="he">יַחֲ</span> or <span class="he">יֶחֱ</span> back to <span class="he">יִקְ</span>
* Turn <span class="he">יֶהֶזְ</span> or <span class="he">יַחַלְ</span> back to <span class="he">יִקְטְ</span>
:::


|  | חזק |  חלף  | Strong 
| :-  | :- | :-  | :-  
| 3ms | <span class="he">יַחֲלֹף</span> | <span class="he">יֶחֱזַק</span> | <span class="he">יִקְטֹל</span>  
| 3mp | <span class="he">יַחַלְפוּ</span> | <span class="he">יֶחֶזְקוּ</span> | <span class="he">יִקְטְלוּ</span>

## 1א "Angry Baker"

* There is a special class of  1א verbs that are irregular ONLY in the QI
* They are given the mnemonic "angry baker":
    * "I said אמר,
    * I want אטה you
    * To eat אכל what
    * I bake אפה, or
    * I _may_ seize אחז you<small>^[<small>"MAY seize" here is intentional. Sometimes אחז is regular and sometimes it is "angry."</small>]</small>, and you
    * will perish אבד."
* $V_P = O$ and the א in $R_1$ is quiescent  (usually $V_S = A$)
    * QI1cs: NOT <span class="he">אֹא</span>, BUT <span class="he">אֹ</span>
* Although only a few verbs undergo this change, these verbs frequently appear in the Bible
    * אמר occurs 2,973 times


|  | Reg. 1א | Angry 1א | Strong 
| :-  | :- | :-  | :-
| 3ms | <span class="he">יֶאֱסֹף</span> | <span class="he">יֹאמַר</span> | <span class="he">יִקְטֹל</span>  
| 1cs | <span class="he">אֶאֱסֹף</span> | <span class="he">אֹמַר</span> | <span class="he">אֶקְטֹל</span>
| 3mp | <span class="he">יַאַסְפוּ</span> | <span class="he">יֹאמְרוּ</span> | <span class="he">יִקְטְלוּ</span>

::: {.box .info}
You saw this already with an earlier `Ruth Pursuit`.  וַתֹּאמֶר is an "angry baker" verb.
:::

## Geminate

* $Pre \ =$ <span class="he">יָ</span>
* Geminate Lose $R_2$ - Dagesh Forte in remaining twin letter (unless word-final or guttural letter)
    * In alternate forms, the Dagesh appears in $R_1$ and $V_P = I$ (see table below)
* There is also a Geminate form (let's call it "Type 2") that takes $Pre \ =$ <span class="he">יֵ</span>
* Imperfect Preformatives/Sufformatives remain
* $V_S$ and Accent shift to $V_1$
* There will be a connecting vowel before a sufformative that starts with a consonant
    * QP2fp - <span class="he">סַבּוֹתֶן</span>
    * QI2fp - <span class="he">תְּסֻבֶּ֫ינָה</span>

::: {.box .info}
Recognizing the Imperfect preformatives/sufformatives and Geminate vocabulary knowledge will help you recognize QI for Geminate verbs
:::

|  | Gem | Gem (alt) | Gem T2 | Strong 
| :-  | :- | :-  | :- | :-
| 3ms | <span class="he">יָסֹב</span> | <span class="he">יִסֹּב</span> |  <span class="he">יֵתַם</span> | <span class="he">יִקְטֹל</span>  
| 3mp | <span class="he">יָסֹ֫בּוּ</span> | <span class="he">יִסֹּּבּוּ</span>  |  <span class="he">יֵתַ֫מּוּ</span> | <span class="he">יִקְטְלוּ</span>


## Biconsonantal

* $Pre \ =$ <span class="he">יָ</span>
* $V_S$ and accent move to $R_1$
* The Lexical Vowel REMAINS, though sometimes it is defective
    * <span class="he">יָקוּם</span>
    * <span class="he">יָקֻם</span>

::: {.box .info}
The retention of the Lexical Vowel, $V_P = \bar A$ and the Imperfect preformative/sufformative will indicate QI of a Biconsonantal verb
:::

|  | קוּם | Strong 
| :-  | :- | :-  
| 3ms | <span class="he">יָקוּם</span> | <span class="he">יִקְטֹל</span>  
| 3mp | <span class="he">יָק֫וּמוּ</span> | <span class="he">יִקְטְלוּ</span>

## 1-Yod 

* ALWAYS drops 1-yod $R_1$
    * $V_P =\bar E$ or $V_P = \hat I$ (Hireq+Yod) - not the consonant Yod but the vowel letter
    * $V_S = \bar E$ or $V_S = A$
    * See examples

| | To return ישׁב | To iInherit ירשׁ | Strong
| :-  | :- | :-  | :-
| 3ms | <span class="he">יֵשֵׁב</span> | <span class="he">יִירַשׁ</span> | <span class="he">יִקְטֹל</span>  
| 3mp | <span class="he">יֵשְׁבוּ</span> | <span class="he">יִירְשׁוּ</span> | <span class="he">יִקְטְלוּ</span>

::: {.box .info}
* When $V_P = \hat I$, you can visualize the remnants of the QI Strong $Pre$ as well as the 1st yod
* When $V_P = \bar E$, you will need to recognize the Imperfect pre/sufformatives and your knowledge of vocabulary<small>^[<small>Also, you could imagine one of the dots of the Tsere representing the dropped Yod - turn it into a Yod and you have $\hat I$, which is a more normal-looking QI $Pre$.  If you "see" this and it helps, great!  If you don't, forget about it and don't let it confuse you!</small>]</small>
:::


## הלך 

* הלך is an irregular verb that acts like 1-Yod in the Qal Imperfect
* The ה drops and $V_P = \bar E$
* $V_S = \bar E (A)$
    * The (A) means in the Feminine Plural forms, we will see Patach instead of Tsere
    * This will be common notation in Unit 4

| | ישׁב | To walk הלך | Strong
| :-  | :- | :-  | :-
| 3ms | <span class="he">יֵשֵׁב</span> | <span class="he">יֵלֵךְ</span> | <span class="he">יִקְטֹל</span>  
| 3mp | <span class="he">יֵשְׁבוּ</span> | <span class="he">יֵלְכוּ</span> | <span class="he">יִקְטְלוּ</span>

## <span class="he">יכל</span> takes $V_P = \hat U$

| | ישׁב | To be able יכל | Strong
| :-  | :- | :-  | :-
| 3ms | <span class="he">יֵשֵׁב</span> | <span class="he">יוּכַל</span> | <span class="he">יִקְטֹל</span>  
| 3mp | <span class="he">יֵשְׁבוּ</span> | <span class="he">יוּכְלוּ</span> | <span class="he">יִקְטְלוּ</span>


## 1נ Assimilates with Silent Sheva

* If guttural or Resh after the נ, the נ usually remains
* Dagesh Forte in $R_2$ when נ assimilates
    * SQiN eM LeVY + Sheva may drop the Dagesh

::: {.box .info}
To get back to QI Strong paradigm, remove the Dagesh Forte and add <span class="he">נְ</span>
:::

|  | 1נ | Strong 
| :-  | :- | :-  
| 3ms | <span class="he">יִפֹּל</span> | <span class="he">יִקְטֹל</span>
| 3mp | <span class="he">יִפְּלוּ</span> | <span class="he">יִקְטְלוּ</span>

## לקח

* Just as <span class="he">הלך</span> thinks it's 1י, <span class="he">לקח</span> thinks it's 1נ
* Note $R_2 =$ <span class="he">ק</span> is SQiN eM LeVY

| | 1נ | To take לקח | Strong
| :-  | :- | :-  | :-
| 3ms | <span class="he">יִפֹּל</span> | <span class="he">יִקַּח</span> | <span class="he">יִקְטֹל</span>
| 3mp | <span class="he">יִפְּלוּ</span> | <span class="he">יִקְחוּ</span> | <span class="he">יִקְטְלוּ</span>

## Doubly Weak

* As with the Qal Perfect, there is nothing overly complex about Imperfect Doubly Weak Verbs
* Simply address the changes caused by each weak letter, then and work your way back to the strong form
* Note <span class="he">עשֹה</span> to do/make, in the table below
    * 1G affects $V_P$ and $V_1$
    * 3ה affects $V_2$
    
| | 3ה | Dbl. Weak | 1G
| :-  | :- | :-  | :-
| 3ms | <span class="he">יִבְנֶה</span> | <span class="he">יַעֲשֶֹה</span> | <span class="he">יַחֲלֹף</span>  
| 3mp | <span class="he">יִבְנוּ</span> | <span class="he">יַעֲשֹוּ</span> | <span class="he">יַחַלְפוּ</span>

## נתן is 1נ and 3נ

* 1n assimilates as usual
* 3n assimilates as usual
* The result is only ONE root letter!  
    * But fortunately, this only occurs in QIfp forms
    
::: {.box .light}
<span class="he">נתן</span> is extremely common, so we must study and understand these changes
:::

| | 1נ | To give נתן | Strong
| :-  | :- | :-  | :-
| 3ms | <span class="he">יִפֹּל</span> |  <span class="he">יִתֵּן</span> | <span class="he">יִקְטֹל</span>
| 3mp | <span class="he">יִפְּלוּ</span> |  <span class="he">יִתְּנוּ</span> | <span class="he">יִקְטְלוּ</span>
| 3fp | <span class="he">תִּפֹּ֫לְנָה</span> | <span class="he">תִּתֵּ֫נָּה</span> | <span class="he">תִּקְטְלוּ</span>


## ראה vs. ירא

* ירא is 1-yod and 3-aleph
    * $V_P = \hat I$ like 1י
    * 3א quiesces with Sheva (FP forms)
* ראה is  2-guttural and 3-hei
    * Follows normal 3ה patterns - no $R_3$

|  | ראה | ירא | Strong 
| :-  | :- | :-  | :-
| 3ms | <span class="he">יִרְאֶה</span> | <span class="he">יִירָא</span> | <span class="he">יִקְטֹל</span>  
| 3mp | <span class="he">יִירְאוּ</span> | <span class="he">יִרְאוּ</span> | <span class="he">יִקְטְלוּ</span>

## Qal Imperfect Weak Summary

This is the densest chapter in _Basics of Biblical Hebrew_ yet also one of the most important.  

Once you get comfortable with this chapter's changes, the rest of the course WILL get easier.

Our goal was to give you enough of an overview to get you started on the Anki exercises. Take your time working through `Anki`, and be sure you keep up with your reviews each day.  What may seem foggy now will begin to make sense soon!  

If, as you do the exercises, things just are not clicking into place, we can recommend [Dr. Beckman's lecture on _Basics of Biblical Hebrew_ Chapter 16](https://www.youtube.com/watch?v=IqAlZba1liQ&feature=youtu.be){target="_blank}.  Note that it is over two-hours in length, so it is very thorough.

Apart from a few irregular changes, the Qal Imperfect is relatively easy to recognize with the distinctive preformatives.  We just need to remember the changes weak letters cause and work our way back to the strong paradigm.



## Word Warm-up {-}

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/AVjuXDd5BbI){target="_blank"}


<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/AVjuXDd5BbI" frameborder="0"></iframe>
</div>


## Verses Warm-up {-}

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/z6AvUVjwSzo){target="_blank"}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/z6AvUVjwSzo" frameborder="0"></iframe>
</div>


## Ruth Pursuit {-}   

::: {.box .map} 
YOUR QUEST

Identify and translate the Qal Verbs below. Be sure to look up any unfamiliar words.  (Hint: most of these verbs come from Ruth's famous oath of loyalty.)

* נתן QI3ms
* שׁוּב QI1cp
* הלך QI2fp
* הלך QI2fs
* הלך QI1cs
* לין QI2fs
* לין QI1cs
* םוּת QI2fs
* מוּת QI1cs
* עשֹה QI3ms
* קתא QI2fp

:::

* [Blank copy of Ruth 1](https://docs.google.com/document/d/1bcT1J-fcVmD1Zn5Jk2nj0560tEddcgtbYZLkwaVVuyE/copy){target="_blank"}
* [Ruth Pursuit Answer Key #16](./images/16_Ruth_Pursuit_KEY.pdf){target="_blank"}





## Claim your next `Twelve Tribes Badge`! {-}

<!-- Lesson 16 Tribe Badge 6 = Joseph -->

Once you have completed <span class="he">all activities<span class="he"> through this lesson, you can fill out the form below and receive your next badge!


<div class="containerLtr">
<iframe class="responsive-iframe" src="https://forms.gle/y2JPkZAxVGEsmACr6" frameborder="0"></iframe>
</div>


## OPTIONAL _Hebrew Quest_ Study Passage: Proverbs #15-17 {-}

::: {.box .map}
YOUR HEBREW QUEST:

1. Read through the passage - [Blank copy of Proverbs #15-17](https://docs.google.com/document/d/1ZuH8tOF8VEtLYCvAexzt0oScAKlfVEkSecPQ-ZjfuhM/copy){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3. Next, using your marked-up copy of the passage, watch Izzy's _Hebrew Quest_ videos (video opens in a new tab)
    1. [Proverbs #15](https://holylanguage.com/proverbs-15.php){target="_blank"}
    1. [Proverbs #16](https://holylanguage.com/proverbs-16.php){target="_blank"}
    1. [Proverbs #17](https://holylanguage.com/proverbs-17.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?

:::


<!--chapter:end:16-Qal_Imperfect_Weak.Rmd-->

# Vav Consecutive {.wc}

Way back from Lesson 2 of _Hebrew Quest_, there was a vocabulary word that illustrates the Vav Consecutive: <span class="he">וּכְתַטְתָּם</span>.

The initial ו means "and", so this one word is translated "AND you will write them".  It also has a grammatical purpose of changing the verb's meaning from past tense to future tense.  <span class="he">כָּתַטְתָּ</span> means "you (ms) wrote" (perfect), but putting a ו as prefix changed the meaning to "and you will write" (imperfect).  We'll learn more about these changes in this Lesson.

The terminology on this topic is a bit fluid. The term "Waw Consecutive" is significantly more prevalent than "Vav Consecutive", so we will stick with the seminary style phrasing for this chapter.

| Hebrew | Description | Also known as | Shorthand
| :- | :- | :- | :-
<span class="he">וְקָטַל</span> | Qal Perfect + ו | Weqatal | QP + ו
<span class="he">וְיִקְטֹל</span> | Qal Imperfect + ו | Weyiqtol | QI + ו
<span class="he">וְקָטַל</span> | Qal Perfect Waw Consecutive  | Weqatal | QPwc
<span class="he">יַיִּקְטֹל</span> | Qal Imperfect Waw Consecutive  | Wayyiqtol | QIwc

::: {.box .map}
LESSON ITINERARY

1. Qal Perfect + ו 
1. Qal Imperfect + ו
1. Qal Perfect Waw Consecutive
1. Qal Imperfect Waw Consecutive

:::

::: {.box .stop}
EQUIPMENT CHECK

Before continuing, be sure you have the Perfect and Imperfect strong paradigms memorized.

:::

## First Thought {-}

### <span class="he">וַיַּשְׁכִּ֣מוּ בַבֹּ֔קֶר וַיַּֽעֲל֥וּ אֶל־רֹאשׁ־הָהָ֖ר </span> {-}

*In the morning, however, they rose up early and went up to the ridge of the hill country (Numbers 14:40)*

The conjunction ו is a powerful linguistic tool in Scripture.  Later in this lesson, we will study Genesis 1:1-5 from _Hebrew Quest_.  Verse 2 begins with the conjunction prefixed to a noun, while verses 3-5 begin with the "Waw Consecutive", which is to say the letter Vav is prefixed to a verb.

Like the dawning of a new day, after you complete this lesson, most of the verb forms that appear in the Hebrew Scriptures will be opened to you.  We hope you are as excited about taking this new step into a larger world as we are excited for you!

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/17-13-Numb.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/17_Masada sunrise over Dead Sea, dg030401281.jpg" alt="Masada sunrise over the Dead Sea. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-81)Masada sunrise over the Dead Sea. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>

## _Hebrew Quest_ Qal Vav Consecutive Lecture (from Lesson 14)
View this 2-minute overview video from _Hebrew Quest_ Lesson 14 on Hebrew Qal Vav Consecutive Verbs.  We will break down the concepts Izzy discusses as we progress through this lesson.  


<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
hfu4gjNo2K4?start=3308&end=3425&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/hfu4gjNo2K4?start=3308){target="_blank"}

## _Hebrew Quest_  Vav Consecutive Lecture (from Lesson 5)

View this 2-minute overview video from _Hebrew Quest_ Lesson 5 on the letter Vav's grammatical function as a consecutive/conversive; that is, changing an imperfect verb to perfect and a perfect verb to imperfect.  


<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
oZ1VbPCpMvw?start=1508&end=1811&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/oZ1VbPCpMvw?start=1508){target="_blank"}



## Review of the Conjunction Vav

* Usually spelled <span class="he">וְ</span>
    * Spelled <span class="he">וּ</span> before פ, מ, ב, or Sheva
    I* Rule of Sheva can create <span class="he">וִי</span>
or the "Hateph copy-cat",<span class="he">וַעֲ</span>

## Perfect + וְ: Spelling

* Always first letter
* Accent shift to ultima in 2ms and 1cs

| | QP | + ו 
| :- | :- | :- 
3ms | <span class="he">קָטַל</span> | <span class="he">וְקָטַל</span>
1cs | <span class="he">קָטַ֫לְתִּי</span> | <span class="he">וְקָטַלְתִּ֫י</span>
3cp | <span class="he">קָטְלוּ</span> | <span class="he">וְקָטְ֫לוּ</span>

## Perfect + וְ: Translating

* Parsing code: Pwc (Perfect Waw Consecutive)
* Often used for the next event in a future narrative
* Usually translated as IMPERFECT
    * Future: And I will study
    * Modal: And I would/could/should study
    * Imperfective: And I am/was/will be studying
* After an imperative, we usually will translate as another imperative:
    * Go and study!
* Can be translated as the regular perfect (past tense)
    * Parsing code, in this case, would be the perfect code "+ ו", as in QP3ms + ו
    * The accent MAY be a clue
        * <span class="he">וְשָׁמַרְתִּ֫י</span> = QPwc1cs - and I will guard
        * <span class="he">וְשָׁמַ֫רְתִּי</span> = QP1cs + ו - and I guarded
    * Context is a better guide
    

## Imperfect + וְ: Spelling

* Always first letter
* Usually spelled וְ
    * On the Perfect, there is no difference between the spelling of the Conjunction and the Waw Consecutive - both are, וְ
    * On the Imperfect, the CONJUNCTION is spelled, וְ
    * The Imperfect Waw CONSECUTIVE is spelled, וַיִּ

| | QI | + ו 
| :- | :- | :- 
3ms | <span class="he">יִקְטֹל</span> | <span class="he">וְיִקְטֹל</span>
1cs | <span class="he">אֶקְטֹל</span> | <span class="he">וְאֶקְטֹל</span>
3cp | <span class="he">יִקְטְלוּ</span> | <span class="he">וְיִקְטְלוּ</span>

## Imperfect with Vav often indicates purpose

* Instead of "and", translate, "so that...may"
    * "Shall I go call a Hebrew nurse SO THAT she MAY nurse the child for you?" (Ex 2:7)
    * "Let's make a tower...SO THAT we MAY make a name for ourselves." (Gen 11:4)
* Regular imperfect translations are possible (same as Pwc)

## Imperfect Waw Consecutive: Spelling (Strong)

* Vav + Patach + Dagesh Forte
    * Similar to the independent preposition with the definite article
* In the 1cs form, the Aleph preformative rejects the Dagesh, resulting in Compensatory Lengthening

| | QI | QIwc
| :- | :- | :- 
3ms | <span class="he">יִקְטֹל</span> | <span class="he">וַיִּקְטֹל</span>
1cs | <span class="he">אֶקְטֹל</span> | <span class="he">וָאֶקְטֹל</span>
3cp | <span class="he">יִקְטְלוּ</span> | <span class="he">וַיִּקְטְלוּ</span>


## Imperfect Waw Consecutive: Spelling (Weak)

* 3ה verbs drop the suffix
* Biconsonantal verbs change
* Some other verbs change stem vowel to Seghol

|3ms | QI | QIwc
| :- | :- | :- 
3ה | <span class="he">יִבְנֶה</span> | <span class="he">וַיִּבֶן</span>
Bicons | <span class="he">יָקוּם</span> | <span class="he">וַיָּקָם</span>
Seghol | <span class="he">יֹאמַר</span> | <span class="he">וַיֹּ֫אמֶר</span>

## Imperfect Waw Consecutive: Translation

### Usually, translate Iwc as PAST TENSE {-}

* Often used for the next event in a past-time narrative
* Uses the opposite form from what we might expect:
    * Iwc in a PAST narrative
    * Pwc in a FUTURE narrative
* He did X (the first verb will be P), and then he did Y (the next verb is Iwc), and then he did Z (Iwc)
* He will do X (the first verb is I), then he will do Y (the next verb is Pwc)

## Summary

* Iwc is most common <span class="he">וַיִּקְטֹל</span>
* Pwc is next <span class="he">וְקָטֹל</span>
* P+ו and I+ו are relatively uncommon

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/_usEc7vYIXI" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/_usEc7vYIXI){target="_blank"}



## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/mfNf7nNcRPA" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/mfNf7nNcRPA){target="_blank"}

## Worksheet: Qal Vav-Consecutive Paradigms {-}

Write the paradigm until you can complete it from memory at least once.

[Qal Vav-consecutive Paradigms](17_qal_waw-consecutive_paradigms.pdf){target="_blank"}

## Ruth Pursuit {-}   

::: {.box .map} 
YOUR QUEST

1. Identify and translate the Qal Vav Consecutive Verbs below from verses 1-5. Be sure to look up any unfamiliar words
    * היה QIwc3ms x2
    * הלך QIwc3ms
    * בוא QIwc3mp
    * היה QIwc3mp
    * מות QIwc3ms
    * נשׂא QIwc3mp
    * ישׁב QIwc3mp
    * מות QIwc3mp

2. Identify, parse, and translate all remaining Qal Vav Consecutive verbs in verses 6-22
    * There is one QPwc, and the rest are QIwc
    * As needed, break down the preformatives and sufformatives and identify the lexical form to look up its meaning
    * For completeness, we will note the instances of <span class="he">וַתֹּאמֶר</span> in gray on the answer key

:::

* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/copy){target="_blank"}
* [Ruth Pursuit Answer Key #17](./images/17_Ruth_Pursuit_KEY.pdf){target="_blank"}



## OPTIONAL _Hebrew Quest_ Study Passage: Genesis 1:1-5 {-}

With this lesson, we move away from the selected verses in Proverbs to lengthier study passages.

::: {.box .map}
YOUR HEBREW QUEST:

1. Read the passage - [Blank copy of Genesis 1:1-5](https://docs.google.com/document/d/1FIQAtWfWlrWmzX5pKR6esRLzJKFdv5Szx3mb5_zWwLg/copy){target="_blank"}, or you may use your copy from Lesson 6
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3.[Watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/genesis-1.php){target="_blank"}
    * Though we would encourage viewing the entire segment, since you already reviewed Genesis 1:1 back in Lesson 6, you can start with Genesis 1:2 at the 46:50 mark
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?

:::

::: {.box .info}
MEMRISE

* If your goal is to simultaneously complete both _Hebrew Quest_ and Hebrew GRAMMAR Quest, you may wish to complete the associated _Hebrew Quest_ passage memorization in Memrise
* The Genesis passage begins in [Memrise Level 17](https://app.memrise.com/course/5406435/hebrew-quest-lessons-1-to-40/17/garden/learn/?source_element=level_details_session&source_screen=level_details){target="_blank}
    * Note that the Memrise work may contain vocabulary and passages in addition to the study passage (for example, Names of God, Titles of Messiah, Terms of Love/Friendship, and Proverbs)
* Although the majority of time in each _Hebrew Quest_ lesson is spent on the Study Passages, be sure to set aside time to watch the lesson's video in its entirety to meet the _Hebrew Quest_ Graduation requirements (also be sure to complete any videos/Memrise modules for Lessons 1-16 that you have not completed)
* See additional resources on the Holylanguage.com page:
    * [Hebrew Quest Overview](https://holylanguage.com/quest.html){target="_blank"}
    * [Hebrew Quest Graduation](https://holylanguage.com/graduate.html){target="_blank"}
    * [Memrise](https://holylanguage.com/memrise.html){target="_blank"}
:::

<!--chapter:end:17-Vav_Consecutive.Rmd-->

# Qal Imperative {.QM}

Lesson 18 marks the start of the second semester of a traditional first-year Hebrew Course.  In other words, congratulations! You are halfway through the course!

Many students believe the second half of the course is easier than the first half.  This is because the foundational work is behind us; reading the Bible, while not yet fluid, is definitely becoming more enjoyable.

We have covered the two primary uses of the Qal stem: the Perfect and Imperfect (including the Waw-Consecutive).  For the remainder of Unit 3, we will round out our study of Qal Verbs with the Volitional forms (Lesson 18), the Infinitive forms (Lessons 20 and 21), and the Participle forms (Lesson 22).

Keep going!

::: {.box .map}
__LESSON ITINERARY__

1. 2nd Person Imperative
1. 1st Person Cohortative
1. 3rd Person Jussive
1. Negative Commands do not use the Imperative
1. Complications
:::

::: {.box .stop}
__EQUIPMENT CHECK__

Before continuing, can you describe the following concepts?

* The Qal Imperfect Strong form
* The Rule of Sheva
:::

## First Thought {-}

### <span class="he">וְעַתָּ֣ה יִשְׂרָאֵ֗ל שְׁמַ֤ע אֶל־הַֽחֻקִּים֙ וְאֶל־הַמִּשְׁפָּטִ֔ים אֲשֶׁ֧ר אָֽנֹכִ֛י מְלַמֵּ֥ד אֶתְכֶ֖ם לַעֲשׂ֑וֹת</span> {-}

*Now, O Israel, listen to the statutes and the judgments which I am teaching you to perform (Deuteronomy 4:1)*

The _Hebrew Quest_ Study Passage for this lesson is the Shema, from Deuteronomy 6. Yeshua quoted it as the "greatest commandment."  The Shema reminds us that we study Hebrew to draw closer to Him and love Him with all that we are.

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/18-08-Deut.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>


<div class="figure" style="text-align: center">
<img src="images/18_Mezuzah near Western Wall, tb091306071.jpg" alt="Mezuzah near Western Wall. Inside a Mezuzah is a small section of scripture, frequently Deuteronomy 6. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-82)Mezuzah near Western Wall. Inside a Mezuzah is a small section of scripture, frequently Deuteronomy 6. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>


## _Hebrew Quest_ Qal Imperative Lecture

View this 1-minute overview video from _Hebrew Quest_ on Hebrew Qal Imperative Verbs.


<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
hfu4gjNo2K4?start=3425&end=3505&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/hfu4gjNo2K4?start=3425){target="_blank"}

## Volitional Forms Introduction

* Volitional conjugations express someone's will (their volition)
    * Command or permission
    * Wish or desire
    * Purpose
    * Occasionally, used to indicate a result (even if that result was not intended)
* The most common volitional form is the Imperative (Parsing code: M)
    * "Study!"
    * 2nd person
* The Jussive (J) is the 3rd person volitional form
    * "May he study" or "she should study"
    * 2nd person jussives exist
* The Cohortative (C) is the 1st person volitional form
    * "Let us study"
    * "I shall run!"
    
## Negative Commands use the Jussive or the Imperfect

* Negative commands never use the imperative
* לֹא + imperfect
    * An absolute, permanent, blanket prohibition
    * You shall not murder (Ex 20:13)
* אַל + jussive or cohortative
    * An immediate, circumstance-specific prohibition
    * "Do not listen to your prophets!" (Jer 27:9)
    * In this context, Jeremiah is prohibiting the people from listening to FALSE, misguided prophets, not a blanket prohibition of ANY and ALL prophets
    * 2nd person jussives are used for negative commands


## The Imperative is the Imperfect without the Imperfect Preformative

* Apply Rule of Sheva to 2fs and 2mp

|  | QI | QM | 
| :-  | :- | :-  
| 2ms | <span class="he">תִּקְטֹל</span>  | <span class="he">קְטֹל</span>
| 2fs | <span class="he">תִּקְטְלִי</span>  | <span class="he">קִטְלִי</span>
| 2mp | <span class="he">תִּקְטְלוּ</span>  | <span class="he">קִטְלוּ</span>
| 2fp | <span class="he">תִּקְטֹ֫לְנָה</span>  | <span class="he">קְטֹ֫לְנָה</span>

* Rule of Sheva - 2mp is NOT <span class="he">קְטְלוּ</span>, BUT <span class="he">קִטְלוּ</span>

## Identifying QM

1. Lacks I preformative
2. Retains I sufformative (or no sufformative)
3. $V_1$ IS or WAS reduced
    * Rule of Sheva in 2fs/2mp
4. Imperfect $V_S$

## <span class="he">נָה</span> can follow volitional verbs

* <span class="he">נָה</span> may be independent or joined by maqqef
* Scholars debate what this means or whether it means anything
* "Please" or "now" have been suggested
* May leave it untranslated depending on the context

::: {.box .info}
<span class="he">נָה</span> only follows volitional verbs. This helps with parsing.
:::

## Distinguishing QM2ms, QI3ms, and QP3ms

|  | QI3ms | QM2ms | QP3ms
| :-  | :- | :-  | :-
| Spell | <span class="he">תִּקְטֹל</span>  | <span class="he">קְטֹל</span>  | <span class="he">קָטַל</span>
| $V_1$ |  $:$  |$ə$  | $\bar A$
| $V_2$ | $\bar O$  |$\bar O$  | $A$

## Paragogic ה 

* Paragogic ה is an extra ה appended to  M2ms<small>^[<small>Scholars debate whether this has any meaning.  "Paragogic" is Greek for "dragged along."</small>]</small>
* It occurs 311 times on M2ps forms
    * <span class="he">קְטֹל</span> - regular QM2ms
    * <span class="he">קָטְלָה</span> (Qamets Hatuf) - QM2ms with paragogic ה OR pronominal suffix (Lesson 19) 
        * Note how $V_S = O$ (Qamets Hatuf)
* We will NEVER see the directional ה on verbs, so we can rule that out
* We will need to determine from the context whether the Qamets+Hei is paragogic or a pronominal suffix

## 3ה Verbs

3rd ה verbs undergo the usual changes we have been studying. Now, we are adding a new (vowel) + ה ending for the Imperative:

* No sufformative = Add ה vowel letter
    * Perfect - <span class="he">ה ָ </span> (Qamets+Hei)
    * Imperfect - <span class="he">ה ֶ </span> (Seghol+Hei)
    * Imperative - <span class="he">ה ֵ </span> (Tsere+Hei)
* If sufformative starts with a vowel, use that vowel for $V_2$
* If sufformative starts with a consonant, add (vowel)+Yod
    * Perfect - <span class="he">י ִ </span> (Hireq+Yod)
    * Imperfect/Imperative - <span class="he">י ֶ </span> (Seghol+Yod)

## 3ה Comparison Table

We can now add the Imperative to our table of 3ה verbs with no sufformative.

| Conj | Hebrew | Vowel
| :- | :- | :-
| P | <span class="he">בָּנָה</span> | Qamets+Hei
| I | <span class="he">יִבְנֶה</span> | Seghol+Hei
| M | <span class="he">בְּנֵה</span> | Tsere+Hei


::: {.box .light}
3ה ENDINGS

* 3ה Verbs are frequent, so we will want to memorize these rules and endings
* They are consistent throughout all stems; e.g., M2ms 3ה verbs end in (Tsere+Hei) in all seven stems

:::


## 1נ and 1י

* 1י drops in the QM
* 1נ _sometimes_ drops in the QM
    * For example, נסע, נתן do; נפל does not
* These have the Imperfect $V_S$, unless it has reduced

::: {.box .light}
Carefully study the verbs in the table below
:::

|  | QI2ms | QM2ms  | QM2mp | 
| :-  | :- | :-  | :-  
| <span class="he">ישׁב</span> | <span class="he">תֵּשֵׁב</span>  | <span class="he">שֵׁב</span>  | <span class="he">שְׁבוּ</span>  
| <span class="he">ירשׁ</span> | <span class="he">תִּירַשׁ</span>  | <span class="he">רַשׁ</span> | <span class="he">רְשׁוּ</span>
| <span class="he">נסע</span> | <span class="he">תִּסַּע</span>  | <span class="he">סַע</span>  | <span class="he">סְאוּ</span>
| <span class="he">נתן</span> | <span class="he">תִּתֵּן</span>  | <span class="he">תֵּן</span>  | <span class="he">תְּנוּ</span>
| <span class="he">נפה</span> | <span class="he">תִּפֹּל</span>  | <span class="he">נְפֹל</span> | <span class="he">נִפְלוּ</span>


## Biconsonantal and Geminate

* These verbs pose little problems
* The imperfect preformative is dropped
* The Imperfect $V_S$ is retained; since this is in the $V_1$ position, the vowel does not reduce

| Verb | QI2ms | QM2ms
| :- | :- | :-
| <span class="he">קוֹם </span> | <span class="he">תָּקוֹם </span> | <span class="he">קוֹם</span>
| <span class="he">שִׁים </span> | <span class="he">תָּשִׁים </span> | <span class="he">שִׁים </span>
| <span class="he">בוֹא </span> | <span class="he">תָּבוֹא </span> | <span class="he">בּוֹא </span>
| <span class="he">סבב</span> | <span class="he">תָּסֹב</span> | <span class="he">סֹב </span>
| <span class="he">תמם</span> | <span class="he">תֵּתַם</span> | <span class="he">תַּם</span>

## Masculine Third Person QP and 2nd Person QM are potential look-alikes

* QP3ms doesn't drop $R_1$ 
* QP3ms has $V_1 = \bar A$ consistently
* Memorizing the 3ה rules for each conjugation will help us distinguish

| Type | QP3ms | QM2ms
| :- | :- | :-
| Strong | <span class="he">קָטַל</span> | <span class="he">קְטֹל</span>
| 1י | <span class="he">יָשַׁב</span> | <span class="he">שֵׁב</span>
| 1נ | <span class="he">נָסע</span> | <span class="he">סַע</span>
| 3ה | <span class="he">בָּנָה</span> | <span class="he">בְּנֵה</span>
| Bicons. | <span class="he">קָם </span> | <span class="he">קוּם</span>


| Type | QP3mp | QM2mp
| :- | :- | :-
| Strong | <span class="he">קָטְלוּ</span> | <span class="he">קִטְלוּ</span>
| 1י | <span class="he">יָשְׁבוּ</span> | <span class="he">שְׁבוּ</span>
| 1נ | <span class="he">נָסְעוּ</span> | <span class="he">סְעוּ</span>
| 3ה | <span class="he">בָּנוּ </span> | <span class="he">בְּנוּ</span>
| Bicons. | <span class="he">קָ֫מ </span> | <span class="he">ק֫וּמוּ </span>

## Cohortative and Jussive Introduction

* These are more nuanced conjugations
* Cohortative (parsing code C)
    * 1st person volitional
    * Often translated as "let us...", or "may I..."
* Jussive (parsing code J)
    * 3rd Person volitional
    * "let him...", "let them...", "may he..."
* Often, the spelling of a Jussive is identical to the Imperfect
    * Word placement in a clause is key to translation; see info box below
* The Cohortative usually (but not always) ends in $\hat A$ (Qamets+Hei)
    * **אֶקְטְלָה*** = QC1cs
* Less frequently, there are 2nd person Jussives
    * Less forceful than a command
    * For example, "would that you..."
    
::: {.box .info}
IDENTIFYING THE COHORTATIVE/JUSSIVE

If an Imperfect verb (without a Vav prefix) is the FIRST WORD in a clause, then see if a volitional translation fits better than an unnuanced Imperfect translation
:::

## Some weak verbs often shorten the Jussive singular


| Type | QI3ms | QJ3ms | Translation
| :- | :- | :- | :-
| 3ה | <span class="he">יִבְנֶה</span> | <span class="he">יִבֶן</span> | Let him build
| Bicons. | <span class="he">יָשִֹים</span> | <span class="he">יָשֵֹׁם</span> | Let him put
| Bicons. | <span class="he">יָשׁוּב</span> | <span class="he">יָשֹׁב</span> | Let him return

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/Ycsb8GLkFRA" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/Ycsb8GLkFRA){target="_blank"}



## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/3mMX0zLi0cU" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/3mMX0zLi0cU){target="_blank"}


## Worksheet: Qal Volitional Forms {-}

Write the Qal Volitional paradigm until you can complete it from memory at least once.  Focus on using the rules we have studied rather than forced memorization of the paradigm.


[Qal Volitional Forms](18_qal_volitive_paradigm.pdf){target="_blank"}

## Ruth Pursuit {-}   

::: {.box .map} 
YOUR QUEST

1. Identify, parse, and translate eight Qal Imperatives
2. Identify, parse, and translate the one 3rd person Jussive 
3. Identify, parse, and translate the two negated commands
:::

* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/view?usp=sharing){target="_blank"}
* [Ruth Pursuit Answer Key #18](./images/18_Ruth_Pursuit_KEY.pdf){target="_blank"}

## OPTIONAL _Hebrew Quest_ Study Passage: The Shema {-}


::: {.box .map}
YOUR HEBREW QUEST:

1. Read  the passage - [Blank copy of The Shema](https://docs.google.com/document/d/1YOCp_Jm-FlLlRlTNHJN1hjNPb0Yh_7xzWDQQFqZ8-6w/copy){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3.[Watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/deuteronomy-6.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?

:::

<!--chapter:end:18-Qal_Imperative_strong.Rmd-->

# Pronominal Suffixes on Verbs {.VerbSuffix}

Instead of learning something new, Lesson 19 will be one where we take a concept you already know and apply it to a new scenario.

The verbal pronominal suffixes are the same suffixes we learned from Lesson 9.  In fact, Verbs ONLY use the "Type 1" suffixes.  

The more challenging aspects can include significant spelling and accent changes.  This can result in words that are identically spelled but have different meanings.  

One of the first vocabulary words in _Hebrew Quest_ was <span class="he">וּכְתַטְתָּם</span>.  We mentioned in Lesson 17 how this word has the Vav Consecutive (AND you shall write them).  It also has a 3mp pronominal suffix (and you will write THEM).



::: {.box .map}
__LESSON ITINERARY__

Understand vowel and accent changes when pronominal suffixes are applied to verbs

:::

::: {.box .stop}
__EQUIPMENT CHECK__

Before continuing, be sure you understand Type 1 pronominal suffixes from Lesson 9

:::

##  First Thought {-}

### <span class="he">אֲנִֽי־קְרָאתִ֣יךָ כִֽי־תַעֲנֵ֣נִי אֵ֑ל הַֽט־אָזְנְךָ֥ לִ֝֗י שְׁמַ֣ע אִמְרָתִֽי׃</span> {-}

*I have called upon You, for You will answer me, O God; Incline Your ear to me, hear my speech. (Psalms 17:6)*

Imagine walking along a path like the one pictured below on a day Yeshua taught in this same area. What would you be thinking and feeling?  

* Would you be giddy, as if if you got special access to a famous entertainer or dignitary?  Would you try to get His autograph or a "selfie" with Him?
* Would you be skeptical, wondering whether this man named Yeshua you have heard about is really "all that"?  In the back of your mind, would you even be questioning whether He is a fraud?
* Would He be just another voice with a platform like all the people with thousands of followers on YouTube today?
* Or, would you know there is something special about Him? Would you have realized that Yeshua is God, come to bridge the divide between you and the Father?  

Be honest.  

Meditate on that as you work through this lesson, and as you study the "Avinu" in this lesson's _Hebrew Quest_ Study Passage.


<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/19-14.Psalms 17.6.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/19_Mount of Beatitudes path through olive grove, tb032805784.jpg" alt="Mount of Beatitudes path through an olive grove. This vicinity is the suggested location of Yeshua's teachings we call 'the Sermon on the Mount' (Matthew 5-7).  Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-83)Mount of Beatitudes path through an olive grove. This vicinity is the suggested location of Yeshua's teachings we call 'the Sermon on the Mount' (Matthew 5-7).  Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>




## _Hebrew Quest_ Pronominal Suffixes

Although we watched this 10-minute _Hebrew Quest_ video back in Lesson 9, the concepts Izzy discusses will apply to both Lesson 9 and 19. Since it may have been several weeks since you viewed this previously, we encourage you to review the video before starting this lesson.

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/hWmwyosdP-s?start=2731&end=3341&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/hWmwyosdP-s?t=2731){target="_blank"}


## Hebrew Direct Object Pronouns

* We learned in Lesson 9 that Hebrew has a Definite Direct Object marker <span class="he">אֵת</span> that takes pronominal suffixes
    *  For example, <span class="he">אֹתִי</span>, is "me" and <span class="he">אֹתְךָ</span> is "you (ms)"
* Hebrew also attaches pronominal suffixes to verbs
* We already learned that the PGN of the verb indicates the subject: <span class="he">אָכַל </span> = HE ate
* A pronominal suffix provides the OBJECT of the verb:  <span class="he">אֲכָלוֹ</span> = He ate IT


## Verbs use Type 1 Suffixes

* This is good news as you will be able to recognize the suffix immediately (provided you remember them from Lesson 9!).
* The 1cp pronominal suffix is <span class="he">נוּ</span>, which, unfortunately, is the same as the P1cp sufformative
* The preceding vowel/Sheva can help in most cases:
    * _IF_ SHEVA, _THEN_ the <span class="he">נוּ</span> is the is P1cp sufformative
        * A Sheva precedes a finite sufformative
    * _IF_ Vowel that is not a Sheva, _THEN_ <span class="he">נוּ</span> is the pronominal suffix

## Qal Perfect Vowel and Accent Changes When a Pronominal Suffix is added

* Accent shifts to sufformative
* $V_1$ reduces
* $V_S$ is LONG in the 3rd person (usually reduces in 3cp)
* 2fs and 1cs are identical
* (QP2fp - $\nexists$<small>^[<small>This is the mathematical symbol for "does not exist"; in our context, it means there are no examples of the QP2fp with a pronominal suffix in Scripture.</small>]</small>)


|  | QP | QP + Pron.
| :- | :- | :-
| 3ms | <span class="he">קָטַל</span> | <span class="he">קְטָל</span>
| 3fs | <span class="he">קָטְלָה</span> | <span class="he">קְטָלַ֫ת</span>
| 2ms | <span class="he">קָטַ֫לְתָּ</span> | <span class="he">קְטַלְתּ֫</span>
| 2fs | <span class="he">קָטַלְתְּ</span> | <span class="he">קְטַלְתִּ֫י</span>
| 1cs | <span class="he">קָטַ֫לְתִּי</span> | <span class="he">קְטַלְתִּ֫י</span>
| 3cp | <span class="he">קָטְלוּ</span> | <span class="he">קְטָל֫וּ</span>
| 2mp | <span class="he">קְטַלְתֶּם</span> | <span class="he">קְטַלְתּ֫וּ</span>
| 1cp | <span class="he">קָטַ֫לְנוּ</span> | <span class="he">קְטַלְנ֫וּ</span>

## QI Vowel Changes 

* Imperfect $V_S$ reduces before a pronominal suffix, unless:
    * IF the original $V_S = A$, THEN instead of reducing, $A$ _lengthens_ to $\bar A$
* QI3fp/QM2fp - $\nexists$

|  | QI | QI + Pron.
| :- | :- | :-
| 3ms | <span class="he">יִקְטֹל</span> | <span class="he">יִקְטְל</span>
| 3fs | <span class="he">תִּקְטֹל</span> | <span class="he">תִּקְטְל</span>
| 2ms | <span class="he">תִּקְטֹל</span> | <span class="he">תִּקְטְל</span>
| 2fs | <span class="he">תִּקְטְלִי</span> | <span class="he">תִּקְטְלִי</span>
| 1cs | <span class="he">אֶקְטֹל</span> | <span class="he">אֶקְטְל</span>
| 3mp | <span class="he">יִקְטְלוּ</span> | <span class="he">יִקְטְלוּ</span>
| 2mp | <span class="he">תִּקְטְלוּ</span> | <span class="he">תִּקְטְלוּ</span>
| 1cp | <span class="he">נִקְטֹל</span> | <span class="he">נִקְטְל</span>

## QM Vowel Changes

* QM2ms is Qamets Hatuf + Silent Sheva
* QM2fs/QM2fp - $\nexists$

|  | QM | QM + Pron.
| :- | :- | :-
| 2ms | <span class="he">קְטֹל</span> | <span class="he">קָטְל</span>
| 2mp | <span class="he">קִטְוּ</span> | <span class="he">קִטְלוּ</span> or <span class="he">קִטְלֻ</span> 


## Imperative/Perfect Ambiguity when normal Imperative $V_S = A$

* As with the Imperfect, if the original Imperative $V_S = A$, THEN instead of reducing, $A$ _lengthens_ to $\bar A$
* In the imperative, this occurs with Stative, 2G, and 3G verbs
* The result is ambiguity between the Perfect and the Imperative, as reflected in the table below
    * QM2ms+suffix looks like QP3ms+suffix
    * QM2mp+suffix looks like QP3cp+suffix
    * The context will determine whether the verb is directed TO someone (2nd person) or is ABOUT someone (3rd)

| QP/Suf | QM/Suf $V_S = A$ | QM/Suf $V_S =O$
| :- | :- | :-
| <span class="he">קְטָל</span> | <span class="he">קְטָל</span> | <span class="he">קָטְל</span>
| <span class="he">יְטָלוּ</span> | <span class="he">יְטָלוּ</span> | <span class="he">קִטְלוּ</span> or <span class="he">קִטְלֻ</span> 


## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/VnY-EzVTywk" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/VnY-EzVTywk){target="_blank"}



## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/tY9vx7ZRSwQ" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/tY9vx7ZRSwQ){target="_blank"}


## Ruth Pursuit {-}        

Most verbal pronominal suffixes in Ruth 1 are in the Qal Infinitive Construct conjugation.  We will study the Qal Infinitives in lesson 20 and 21.  Therefore, there is no `Ruth Pursuit` for lesson 19.


## Claim your next Twelve Tribes Badge! {-}


<!-- Lesson 19 Tribe Badge 7 = Judah -->

Once you have completed <span class="he">all activities<span class="he"> through this lesson, you are eligible for your next `Twelve Tribes Badge`.  Fill out the form below!

<div class="containerLtr">
<iframe class="responsive-iframe" src="https://forms.gle/4Q8STELkBPRy6mEw8" frameborder="0"></iframe>
</div>

## OPTIONAL _Hebrew Quest_ Study Passage: Matthew 6 {-}

::: {.box .map}
YOUR HEBREW QUEST:

1. Read through the passage - [Blank copy of Matthew 6](https://docs.google.com/document/d/1ICe0FEaE8wRBuKGR4q34drqfEIxQDG_9NRwa-n3Wgd8/edit?usp=sharing){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3.[Watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/matthew-6.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?

:::

<!--chapter:end:19-Pronominal_Suffix_Verbs.Rmd-->

# Qal Infinitive Construct {.Qinfinitive}

Infinitive constructs are verbal nouns.

There is a unique aspect that makes identifying and parsing the ∞<small>^[<small>If you ever have a need to generate the infinity symbol on a desktop computer, ∞, make sure the `Num Lock` is on (and use the numbers on the keypad layout, not the ones on the top row), hold down the `Alt` key and type `236`, then let go of the `Alt` key. On a phone, you can often type `infinity` and the ∞ symbol will appear.</small>]</small> super easy (but you'll have to read on!)


::: {.box .map}
__LESSON ITINERARY__

1. Spelling  the Infinitive Construct
1. Translating the Infinitive Construct
1. Negating the Infinitive Construct
:::


## First Thought {-}

###  <span class="he">וְשָׁ֣מַרְתָּ֔ אֶת־מִצְוֺ֖ת יְהוָ֣ה אֱלֹהֶ֑יךָ לָלֶ֥כֶת בִּדְרָכָ֖יו וּלְיִרְאָ֥ה אֹתֽוֹ׃</span> {-}

*Therefore, you shall keep the commandments of Adonai your God, to walk in His ways and to fear Him. (Deuteronomy 8:6)*

It is easy to follow Adoni's commandments when they align with our desires.  When they do not align, we face a more difficult decision.  Do we follow in HIS ways, or do we continue in OUR ways?

In our _Hebrew Quest_ Study Passage for this lesson, we will read the story of when Adonai commanded Abraham to sacrifice Isaac.  This passage is as beautiful as it is troubling.  How could Adonai ask such a thing?  How could Abraham willingly obey so easily?  What is Adonai trying to teach us?  What would I do if God asked a difficult task of me?

Ponder these things as you work through this Lesson and the study passage.

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/20-6.Deut 8.6.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>


<div class="figure" style="text-align: center">
<img src="images/20_Western Wall plaza and Dome of the Rock with snow, tb022503204.jpg" alt="Western Wall plaza and Dome of the Rock with snow.  The Temple Mount,  specifically the rock enshrined by Islam's Dome of the Rock, is the traditional location of Abraham's near-sacrifice of Isaac described in Genesis 22.  Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-84)Western Wall plaza and Dome of the Rock with snow.  The Temple Mount,  specifically the rock enshrined by Islam's Dome of the Rock, is the traditional location of Abraham's near-sacrifice of Isaac described in Genesis 22.  Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>

## _Hebrew Quest_ Qal Infinitves Lecture

View this 3-minute overview video from _Hebrew Quest_ on Hebrew Qal Infinitive Verbs. Izzy spends the bulk of the lecture discussing the Qal Infinitive Absolute form, which we will study in Lesson 21.


<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
hfu4gjNo2K4?start=3505&end=3664&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/hfu4gjNo2K4?start=3505){target="_blank"}

## Two types of Infinitives

* Infinitive Construct - Parsing Code: ∞
* Infinitive Absolute (Lesson 21) - Parsing Code: A
* The Infinitives do NOT inflect for person, number, or gender
* Parsing is straightforward - Stem + Conjugation
    * Q∞
    * QA (Lesson 21)
* Prefixes
    * The ∞ can also take prepositional prefixes (which we will discuss a little bit later) or pronominal suffix
    * The A NEVER takes a prefix or suffix


## Q∞ Spelling

* For most verbs: <span class="he">קְתֹל</span>
    * 1G reduces as expected: <span class="he">אֱמֹר</span>
    * 3ח/ע can take a furtive patach, which is ignored when parsing: <span class="he">שְׁלֹחַ</span>

::: {.box .info}
"uh-oh" is the sound a Q∞ (or QM2ms) strong verb makes
:::

## 3ה Endings

* As expected, when a 3ה verb has no sufformative, a vowel is added
* For the ∞, this ending is <span class="he">וֹת</span>
    * The <span class="he">וֹת</span> remains when a pronominal suffix is added
    * Note: in this use, <span class="he">וֹת</span> is not the FP ending - it would be incorrect to say "Q∞fp." ∞ verbs are never inflected for person, gender, or number
* Remember, ∞ verbs never inflect, so there will never be a sufformative; in other words, all 3ה ∞ verbs will have the <span class="he">וֹת</span> ending
* We can continue building our 3ה ending table:

| Conj | Hebrew | Vowel
| :- | :- | :-
| P | <span class="he">בָּנָה</span> | Qamets+Hei
| I | <span class="he">יִבְנֶה</span> | Seghol+Hei
| M | <span class="he">בְּנֵה</span> | Tsere+Hei
| ∞ | <span class="he">בְּנוֹת</span> | Holem+Vav Tav

::: {.box .light}
Memorize the 3ה endings as they will make parsing easier
:::

::: {.box .caution}
LOOK-ALIKE WORDS

* <span class="he">ּבָנוֹת</span> is spelled with a Qamets and means "daughters"
* <span class="he">בְּנוֹת</span> is reduced and means "to build, building"
:::

## 1י and 1נ Spelling

* Usually, but not always, drop the 1-yod/nun
* When dropped, add a final <span class="he">ת</span>, and change the vowels so that it looks like a Segholate noun

* <span class="he">הלך</span> as always thinks it's a 1-yod

| Root | Keep | Drop
| :- | :- | :-
| <span class="he">נסע</span> | <span class="he">נְסֹעַ</span> | <span class="he">סַ֫עַת</span>
| <span class="he">נגע</span> | <span class="he">נְגֹת</span> | <span class="he">גַּ֫עַת</span>
| <span class="he">נתן</span> | <span class="he">נְתֹן</span> | <span class="he">תֵּת</span>
| <span class="he">הלך</span> | $\nexists$ | <span class="he">לֶ֫כֶת</span>

::: {.box .light}
<span class="he">נתנ</span> is tricky _and common_

Memorize <span class="he">תֵּת</span> as Q∞ of נתן
:::

## Biconsonantal

* An easy one, as long as you've memorized your vocab!
* The Q∞ of biconsonantal verbs is simply the lexical form
    * <span class="he">שׁוּב</span>
    * <span class="he">מוּת</span>
    * <span class="he">בּוֹא</span>
    * <span class="he">בּוֹשׁ</span>
    * <span class="he">דִּין</span>
    * <span class="he">בִּין</span>

## Q∞ often is identical to QM2ms

* As one is finite and the other is non-finite, the context should be obvious as to whether one person is giving a command to another person
* Some verbs that lose the Imperfect $V_S = O$ in the QM, RETAIN $V_S = O$ in the Q∞
* 3ה verbs have different word-final ה vowels as mentioned previously

## ∞ take Type 1 Pronominal Suffixes

* Q∞ and QM2ms with pronominal suffix are usually the same
* Both shift vowels with $V_1 \ =$ Qamets Hatuf when there is a pronominal suffix
* Nun-type suffixes ONLY occur with imperfects and imperatives


| No suffix | With Suffix
| :- | :-
| <span class="he">קְטֹל</span> | <span class="he">קָטְל</span>


| Suffix PGN | With Suffix
| :- | :-
| 3ms | <span class="he">קָטְלוֹ</span>
| 1cs | <span class="he">קָטְלִי</span>
| 3mp | <span class="he">קָטְלָם</span>
| 1cp | <span class="he">קָתְלֵ֫נוּ</span>

::: {.box .caution}
When affixed to an ∞ verb, the suffix can be the SUBJECT as well as the object.
:::

## Most ∞ have a prefixed preposition

* There are 6595 ∞ in the Bible
    * Only 896 do not have a prefixed preposition
    * 68% have <span class="he">ל</span>

::: {.box .info}
Since only ∞ and Participle can have a prefixed preposition, identifying and parsing the ∞ is usually easy!
:::


## Meaning of ∞

* Often used as a verbal noun - "to hear" or "hearing"
    * In English, "to hear", "to speak", or "to be" are examples of "infinitive" verbs.
* ∞ plus prefix <span class="he">ל</span> 
    * Try "to x" or "by x-ing"
    * Sometimes indicates purpose or result: IN ORDER TO SEE the nakedness of the land = <span class="he">לִרְאוֹת</span> 
    * Something imminent: The sun was ABOUT TO SET = <span class="he">לָבוֹא</span>
    * Verbal noun: It is good TO PRAISE Adonai = <span class="he">לְהֹדוֹת</span>
    * Verbal Noun: Obey BY WALKING in His ways = <span class="he">לָלֶכֶת</span>
* ∞ plus prefix <span class="he">ב</span> or <span class="he">כ</span> is often temporal
    * Often included with <span class="he">וַיְהִי</span> or <span class="he">וְהָיָה</span>
    * Past time: WHEN Israel DWELT = <span class="he">וַיְהִי בִּשְׁכֹּן יִשְֹרָאֵל</span>
    * Future time: WHEN YOU CROSS = <span class="he">וְהָיָה בְּעָבְרְכֶם</span>

## Negating the Infinitive

* The negative particles <span class="he">אַל </span> and <span class="he">לֹא </span> are not used to negate the ∞
* <span class="he">בִּלְתִּי </span> and <span class="he">לְבִלְתִּי</span> are used
* There is no difference in meaning between the two words, but <span class="he">לְבִלְתִּי</span>  is more frequent
* Not to do all my commandments (Lev 26:15) = <span class="he">לְבִלְתִּי עֲשׂוֹת אֶת־כָּל־מִצְוֺתַי</span>

## Word Warm-up {-}


<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/wrlzC0OAxoc" frameborder="0"></iframe>
</div>


[Click to open `Word Warm-up` video in a new tab](https://youtu.be/wrlzC0OAxoc){target="_blank"}

## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/9eYgruFN7bM" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/9eYgruFN7bM){target="_blank"}


## Ruth Pursuit {-}   

::: {.box .map} 
YOUR QUEST

1. Identify, parse, and translate the eleven Q∞
    * Identify pronominal suffixes in the parsing when present
    * All but two of these have prepositional prefixes
2. Identify the Lesson 20 vocabulary word that negates an Infinitive (blue)
:::

* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/copy){target="_blank"}
* [Ruth Pursuit Answer Key #20](./images/20_Ruth_Pursuit_KEY.pdf){target="_blank"}




## OPTIONAL _Hebrew Quest_ Study Passage: Genesis 22:1-19 {-}

::: {.box .map}
YOUR HEBREW QUEST:

1. Read through the passage - [Blank copy of Genesis 22:1-19](https://docs.google.com/document/d/1zpIOg9zyDv_qPK9f69QexbIlBhH6wKO74YkPz3xpurI/copy){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"}), and translating (you will need to parse verbs to translate)
3.[Watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/genesis-22.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?

:::

<!--chapter:end:20-Qal_Infinitive_Construct.Rmd-->

# Qal Infinitive Absolute {.QA}


The Qal Infinitive Absolute (abbreviated QA) is relatively infrequent, occurring 872 times.  It has a unique function, with no direct equivalent in English.  It generally adds emphasis to, or sometimes replaces another Hebrew verb entirely.  We will study a few of these different uses in this lesson.  We will also look at the functions of two articles,  יֵשׁ and אֵין.

::: {.box .map}
__LESSON ITINERARY__

1. Strong and weak verb spelling
1. Meaning
1. Compare Infinitive Construct with Infinitive absolute
1. The articles יֵשׁ and אֵין
:::

::: {.box .stop}
__EQUIPMENT CHECK__

Before continuing, be sure you understand the spelling and meaning of Qal Infinitive Construct.

:::

## First Thought {-}

### <span class="he">אָנֹכִ֗י אֵרֵ֤ד עִמְּךָ֙ מִצְרַ֔יְמָה וְאָנֹכִ֖י אַֽעַלְךָ֣ גַם־עָלֹ֑ה</span> {-}

*"I will go down with you to Egypt, and I will also surely bring you up again (Genesis 46:4)*

Our _Hebrew Quest_ Study Passage for this Lesson is the Priestly Blessing from Numbers 6, which begins, "the LORD bless you and keep you...". The LORD kept his promises to keep Israel when the nation was in Egypt.  This Lesson's grammar subject is the Infinitive Absolute.  In Hebrew, the Infinitive Absolute is often used to emphasize another verb. When this happens, the verb being emphasized will be repeated, but in the Infinitive Absolute form. 

In, <span class="he">אַעַלְךָ גַם־עָלֹה</span>, the literal translation might be, "I will bring you up again bringing up."
The _meaning_ of the phrase is, "I will SURELY bring you up again," as if to say, "Don't worry! I am definitely bringing up out of Egypt. In fact, there is zero chance I will not bring you up!"  

This is an excellent picture of what the LORD means when He says He will "keep" us!

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/21-5.Gen 46.4.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/21_Ketef Hinnom with Gabriel Barkay, tb042705895.jpg" alt="Ketef Hinnom with archeologist Gabriel Barkay. In 1979, Barkay's team found two tiny silver scrolls, inscribed with portions of the Priestly Blessing from Numbers 6 and apparently once used as amulets, in this burial chamber in Jerusalem. They contain what may be the oldest surviving texts from the Hebrew Bible, dating from the First Temple period, making the find one of the most significant Biblical discoveries ever made. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-85)Ketef Hinnom with archeologist Gabriel Barkay. In 1979, Barkay's team found two tiny silver scrolls, inscribed with portions of the Priestly Blessing from Numbers 6 and apparently once used as amulets, in this burial chamber in Jerusalem. They contain what may be the oldest surviving texts from the Hebrew Bible, dating from the First Temple period, making the find one of the most significant Biblical discoveries ever made. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>

## _Hebrew Quest_ Qal Infinitives Lecture

As needed, review this 3-minute overview video from _Hebrew Quest_ on Hebrew Qal Infinitive Verbs.


<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
hfu4gjNo2K4?start=3505&end=3664&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/hfu4gjNo2K4?start=3505){target="_blank"}


## QA Spelling

* The QA has a distinctive $V_2 = \hat O$ (Holem+Vav)
    * <span class="he">קָטוֹל</span> or <span class="he">קָטֹל</span> (defective spelling)
* If the Q∞ was "uh-oh", then the QA is "ah-oh"
    * Most weak verbs follow the "ah-oh" pattern
    * 3ע/ח verbs will take a Furtive Patach under $R_3$ but this affects pronunciation only (not parsing or translation)
    * 3ה verbs can appear in two forms
        * Holem+Hei = <span class="he">עָשׂה </span>
        * Holem+Vav with no Hei = <span class="he">עָשׂוֹ</span>
    * Biconsonantal verbs, including I- and U-class usually take the Holem+Vav/Holem $V_S$
        * <span class="he">קוֹם </span> or <span class="he">שׂוֹם</span>
        * O-class look the same in QA/Q∞/QM2ms = <span class="he">בּוֹא </span>
            * Sometimes QA is defective = <span class="he">בֹּא</span>
    * Geminate verbs retain all three letters with $V_2 = \hat O$ - <span class="he">סָבוֹב</span>
* Parsing (parsing code: A)
    * Never inflects for person, number, or gender
    * Never has a pronominal suffix
    * Never has a prefixed preposition

## 3ה Comparison Table

| Conj | Hebrew | Vowel
| :- | :- | :-
| P | <span class="he">בָּנָה</span> | Qamets+Hei
| I | <span class="he">יִבְנֶה</span> | Seghol+Hei
| M | <span class="he">בְּנֵה</span> | Tsere+Hei
| ∞ | <span class="he">בְּנוֹת</span> | Holem+Vav Tav
| A | <span class="he">בָנֹה</span> or <span class="he">בָנוֹ</span> | Holem+Hei or Holem+Vav

## Meaning of Infinitive Absolute

* Frequently, the absolute serves to emphasize a finite verb from the same root
* The Infinitive Absolute form may appear before or after the finite verb
* The Absolute can emphasize the _CERTAINTY_
    * 2 Kings 1:16: <span class="he">מוֹת תָּמוּת</span> =
    * You will surely die (lit: dying you will die)
    * There is zero chance you will NOT die
    * A mnemonic might be: "there is ABSOLUTE certainty" that the verb's action will occur
* The Absolute can emphasize the _EXTENT_
    * Judges 1:28: <span class="he">וְהוֹרֵישׁ לֹא הוֹרִישׁוֹ</span>
    * He did not completely drive him out (note these verbs are Hiphil stem)
* The Absolute may _substitute_ for another verb conjugation
    * Often, the absolute substitutes for an Imperative verb
        * Deuteronomy 5:12: <span class="he">שָׁמוֹר אֶת־יוֹם הַשַּׁבָּת</span> 
        * Observe Shabbat!
* The Absolute can denote _ongoing action_ that is often contemporaneous with another action
    * 2 Sam 15:30: <span class="he">וְעָלוּ עָלֹה וּבָכֹה</span> 
    * They went up, weeping as they went (lit: they went up, going up and weeping)

## Comparison of Infinitive Construct and Infinitive Absolute

| | ∞ | A
| :- | :- | :-
PGN | No PGN | No PGN
Paradigm | <span class="he">קְטֹל</span> | <span class="he">קָטוֹל</span>
Sound | uh-oh | ah-oh
1י and 1נ | Drop | Never Drop
3ה | use <span class="he">וֹת</span> | 3ה use <span class="he">ה ֹ </span> or <span class="he">וֹ</span>
Bicons | use Lexical $V_S$ | use $\hat O$ (<span class="he">וֹ</span>)
Pron. suffix | Yes | Never
Preposition prefix | Usually | Never
Meaning | purpose/result | emphasize certainty
English equivalent | Verbal noun "to do" or "doing" | No direct equivalent

## יֵשׁ and אֵין 

* These are particles that assert the existence or non-existence of something or someone
* Mnemonics: 
    * יֵשׁ sounds like "yes" as in "yes there are"
    * אֵין sounds like the English slang word "ain't," as in "ain't nothing or nobody"
* These do not inflect for gender or number 
    * אֵין could mean "there is not" or "there are not"
* When prefixed with <span class="he">לְ</span>, indicates possession or non-possession
    * We saw this way back in the Lesson 3 `Study Verses`
    * Genesis 44:20 - <span class="he">יֶשׁ־לָנוּ אָב זָקֵן</span> = we have an elderly father (lit: there is to us a father old)
* Pronominal suffixes occur on יֵשׁ only 9 times, compared with 104 times on אֵין 
    * 2 Kings 17:34: <span class="he">אֵינָם יְרֵאִים</span> = they do not fear


## Word Warm-up {-}


<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/UWb_3JSv-mk" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/UWb_3JSv-mk){target="_blank"}


## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/4-EL_lcP2xU" frameborder="0"></iframe>
</div>


[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/4-EL_lcP2xU){target="_blank"}



## Ruth Pursuit {-}   

There are no Qal Infinitive Absolutes in Ruth 1 (if you find one, let us know!), but we do have a few words for you to identify

::: {.box .map} 
YOUR QUEST:

1. Identify the particle affirming the existence of someone or something (yellow)
2. Identify the Lesson 21 vocabulary word for "famine" (green)
3. A vocabulary verb for this lesson was <span class="he">נוּחַ</span>.  Identify the FS noun in Ruth 1 that is derived from this verb. (blue)

:::

* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/copy){target="_blank"}
* [Ruth Pursuit Answer Key #21](./images/21_Ruth_Pursuit_KEY.pdf){target="_blank"}



## OPTIONAL _Hebrew Quest_ Study Passage: Aaronic/Priestly Blessing {-}

::: {.box .map}
YOUR HEBREW QUEST:

1. Read through the passage - [Blank copy of Numbers 6](https://docs.google.com/document/d/159LEzKxPYHjxibJ3VZylYLbZ_It9zwYZyAg_iotZIwM/copy){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3.[Watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/numbers-6.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?

:::

<!--chapter:end:21-Qal_Infinitive_Absolute.Rmd-->

# Qal Participle {.QPt}


Participles are verbal adjectives.  For Hebrew, this means:

* Participles inflect like adjectives: MS, FS, MP, and FP
* Participles are used like adjectives: attributively, predicatively, and substantively


::: {.box .map}
__LESSON ITINERARY__

1. Meaning of the Qal Participle
1. Spelling of the Qal Participle

:::

::: {.box .stop}
__EQUIPMENT CHECK__

Before continuing, can you describe the following concepts?

* The three ways an adjective can be used
* The four ways adjectives can inflect for person and number

As needed, review [Lesson 7 on Adjectives](#adjectives) prior to beginning Lesson 22

:::

##  First Thought {-}

###  <span class="he">וְיִבְטְח֣וּ בְ֭ךָ יוֹדְעֵ֣י שְׁמֶ֑ךָ כִּ֤י לֹֽא־עָזַ֖בְתָּ דֹרְשֶׁ֣יךָ יְהוָֽה׃ </span> {-}

*And those who know Your name will put their trust in You, For You, O LORD, have not forsaken those who seek You. (Psalms 9:11)*

Our _Hebrew Quest_ study passage for this lesson is Matthew 13 and the parable of the sower. Yeshua clarifies that the "good soil" is someone who hears the word, understands it, and then does something with it.  In contrast, the soil among the thorns is someone who hears the word but doesn't fully trust in Adonai or his promises.  We see one of these promises in Psalms 9:11.

It's become a cliche for Bible teachers to ask, "which of the four soils are you?"  In truth, for most of us, our lives at some point have reflected each of four soils.  So the better question to ask might be:

> "Today, in the next 1440 minutes, how can I make sure that I am the 'good soil', trusting in Adonai, and producing a yield for the Kingdom?"

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/22-10.Psalms 9.11.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/22_Cove of the Sower from east, tb112000201.jpg" alt="Cove of the Sower from the east. This is the suggested location of Yeshua's teaching we call 'The Parable of the Sower' (Matthew 13). This region's acoustic properties have been analyzed.  Scientists found that a person could be in a boat a few feet from the shore and easily be heard without amplification by ‘large crowds’ scattered several hundred feet up the embankment.  Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-86)Cove of the Sower from the east. This is the suggested location of Yeshua's teaching we call 'The Parable of the Sower' (Matthew 13). This region's acoustic properties have been analyzed.  Scientists found that a person could be in a boat a few feet from the shore and easily be heard without amplification by ‘large crowds’ scattered several hundred feet up the embankment.  Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>

## _Hebrew Quest_ Qal Participles Lecture

View this 1-minute overview video from _Hebrew Quest_ on Hebrew Qal Participle Verbs. 

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
hfu4gjNo2K4?start=3664&end=3737&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/hfu4gjNo2K4?start=3664){target="_blank"}

## Participles are Verbal Adjectives

* Participles are non-finite because they do not have 1st, 2nd, or 3rd person
* Since Participles are adjectives, the DO inflect for gender and number
    * They use the same adjectival endings we learned many lessons ago: MS, FS, MP, FP
    * They are used as adjectives
        * Attributive: I saw running water
            * Match the noun in gender, number, and definiteness
            * Attributive Always After (the noun), Article Always Agrees (with definiteness of noun)
        * Predicative: The water is running
            * Matches the subject in gender and number, but not definiteness
            * Predicate dePrived of the Article, Perhaps Precedes (the noun)
        * Substantival: running is good exercise
            * Has the gender and number of the noun it is replacing

::: {.box .info}
Review [Lesson 7](#adjectives) if you need a review on adjectives
:::

## Qal Active and Passive Participles

* The Qal (and only the Qal) stem has both active and passive particles
* Active: 
    * Parsing code QPtms - Qal Participle masculine singular (no need to say "active")
    * "He who blesses"
* Passive: 
    * Parsing code QPpMS - Qal Passive Participle Masculine Singular (important to denote "passive")
    * "Blessed are you"

## Qal Participle Spelling


* Participles use adjective endings and can appear in Absolute or Construct forms
* Active
    * $V_1 = \bar O$ defective: Holem (more common than plene Holem+Vav)
      * Every form except biconsonantal (which has $V_1 = \bar A$ (Qamets))
    * $V_2$ 
      * Usually $\bar E$ for Masculine singular: <span class="he">קֹטֵל</span>
      * Reduces before adjective endings
        * MP - <span class="he">קֹטְלִים</span>
        * FP - <span class="he">קֹטְלוֹת</span>
    * Two Feminine Singular variations
      * Seghol+Tav - <span class="he">קֹטֶ֫לֶת</span> - MORE COMMON
      * Qamets+Hei - <span class="he">קֹטְלָה</span> - Less common
* Passive: 
    * Every QPp as $V_2 = \hat U$ plene: Shureq (more common than defective Qibbuts)
    * Since $V_2 = \hat U$ it can't reduce; therefore $V_1$ will reduce before adjective endings
    * No FS "T" form

 |Abs | Con
:- | :- | :-
QPtMS | <span class="he">קֹטֵל</span> | <span class="he">קֹטֵל</span>
QPtFS | <span class="he">קֹטֶ֫לֶת</span> or <span class="he">קֹטְלָה</span> | <span class="he">קֹטְלַת</span>
QPtMP | <span class="he">קֹטְלִים</span> | <span class="he">קֹטְלֵי</span>
QPtFp | <span class="he">קֹטְלוֹת</span> | <span class="he">קֹטְלוֹת</span>
| | |
QPpMS | <span class="he">קָטוּל</span> | <span class="he">קְטוּל</span> 
QPpFS | <span class="he">קְטוּלָה</span> | <span class="he">קְטוַּת</span> 
QPpMP | <span class="he">קְטוּלִים</span> | <span class="he">קְטוּלֵי</span> 
QPpFP | <span class="he">קְטוּלוֹת</span> | <span class="he">קְטוּלוֹת</span> 

## Prefixes and Suffixes

* Like any adjective, the conjunction, the definite article, the interrogative particle, and prepositions can be added to Participles
    * Infinitive constructs and participles are the only verb conjugations that can take a prefixed preposition
* Type 1 pronominal suffixes may be added to singular participles
* Type 2 pronominal suffixes may be added to plural participles



## Biconsonantal 

* QPt $V_1 = \bar A$ (Qamets) - always - DOES NOT REDUCE
    * Irregular: **מוּת*** becomes **מֵת*** in Qpt
* QPp $V_1 = \hat U$ or the lexical vowel $\hat I$ (Hireq+Yod)
* Ambiguities
    * **קָם*** - QP3ms, QPtMS
    * **בּוֹא*** - QM2ms, Q∞, QA
    * **קָמָה*** is QPtFS, but **קָ֫מָה*** (note accent) is QP3fs
    
## 3ה 

* The "consonantal" ה drops in all forms of the Qpt
  * In the MS, it is replaced by Seghol+Hei - <span class="he">בֹּנֶה</span>
    * Although the final vowel is shared with the Imperfect, the Pt will never have an imperfect preformative
    * Thus, there is little risk of confusing a 3ה Imperfect with a 3ה Participle
  * In the FS, it is replaced by $\hat A$ (Qamets+Hei) - <span class="he">בֹּנָה</span> (the Tsere+Tav form $\nexists$))
  * There is no vowel letter ה ִin the plural forms
* The Yod reappears as $R_3$ in all forms of the QPp (and the non "T" form of QPtFS)
  * <span class="he">בָּנוּי</span>

### We can now complete our 3ה $V_2$ table {-}


| Conj | Hebrew | Vowel
| :- | :- | :-
| P | <span class="he">בָּנָה</span> | Qamets+Hei
| I | <span class="he">יִבְנֶה</span> | Seghol+Hei
| M | <span class="he">בְּנֵה</span> | Tsere+Hei
| ∞ | <span class="he">בְּנוֹת</span> | Holem+Vav Tav
| A | <span class="he">בָנֹה</span> or <span class="he">בָנוֹ</span> | Holem+Hei or Holem+Vav
| Pt | <span class="he">בֹּנֶה</span> | Seghol+Hei

::: {.box .map}
MEMORIZE THE 3ה ENDINGS

* As we get ready to journey into Unit 4, this table will be your friend!
* These endings are the same throughout all the derived stems  
:::

## Stem Comparison Table

* Now that we have concluded our discussion on the Qal stem, take a moment to review this table.
* It currently shows the Perfect 3ms, the Imperfect 3ms, and the Participle ms strong verb forms for the Qal stem
  * We will add the additional stems as we work through Unit 4
* Take note of the $Pre$ patterns in red and the $V_S$ in blue
    * When you can work your way back to the $Pre$ pattern of the Strong verb means you will correctly identify the stem and conjugation most of the time
* The last column indicates the $V_S$ pattern for perfects on the left, and Imperfects/Imperatives/Infinitives on the right.


<img src="images/22_stemcomp.png" width="600pt" style="display: block; margin: auto;" />

## _Hebrew Quest_ Qal Summary Lecture

As a conclusion to our study of Qal verbs, view this 5-minute summary of the Qal stem from _Hebrew Quest_. 

<div class="container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/
hfu4gjNo2K4?start=3737&end=4069&rel=0&showinfo=0&autohide=1&autoplay=1" frameborder="0"></iframe>
</div>

[Click to open video in a new tab](https://youtu.be/hfu4gjNo2K4?start=3737){target="_blank"}

## Word Warm-up {-}


<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/6inZWylM5U8" frameborder="0"></iframe>
</div>


[Click to open `Word Warm-up` video in a new tab](https://youtu.be/6inZWylM5U8){target="_blank"}

## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/uCkJD0fhT74" frameborder="0"></iframe>
</div>


[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/uCkJD0fhT74){target="_blank"}

## Worksheet: All Qal Paradigms {-}

The attached worksheet has all of the Qal strong forms we have studied in Lessons 13-22. Side 1 has placeholders, while side 2 has the קטל paradigm verb.  Complete either side of the worksheet until you can complete one entire column without looking at the answer column on the right.  

[All Qal paradigms worksheet](22_qal_paradigms_strong_verbs.pdf){target="_blank"}

## Ruth Pursuit {-}        

:::  {.box .map}
YOUR QUEST

Identify the one Participle in Ruth 1.  You might recall that we discussed this word in the Lesson 4 `Ruth Pursuit`.

:::

* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/copy){target="_blank"}
* [Ruth Pursuit Answer Key #22](./images/22_Ruth_Pursuit_KEY.pdf){target="_blank"}


## Claim your next `Twelve Tribes Badge`! {-}

<!-- Lesson 22 Tribe Badge 8 = LEVI -->

Once you have completed all activities through this lesson, complete the form below to receive your next badge!

<div class="containerLtr">
<iframe class="responsive-iframe" src="https://forms.gle/ncXmf7QRuoYCL3hz8" frameborder="0"></iframe>
</div>


## OPTIONAL _Hebrew Quest_ Study Passage: Matthew 13 {-}

::: {.box .map}
YOUR HEBREW QUEST:

1. Read through the passage - [Blank copy of Matthew 13](https://docs.google.com/document/d/1rl--X01fxApzUiadlxg68F6qVcx_nEsYlJP5LCGSsxo/edit?usp=sharing){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3. Watch Izzy's _Hebrew Quest_ video (video opens in a new tab)
    * [Part 1](https://holylanguage.com/matthew-13.1.php){target="_blank"}
    * [Part 2](https://holylanguage.com/matthew-13.2.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?

:::

<!--chapter:end:22-Qal_Participle.Rmd-->

# Hebrew Syntax {.Syntax}


With this lesson, you will begin to put all that information you learned over the past 22 lessons to work in better understanding how the Bible communicates to us.  With this knowledge, we can begin to think critically in our evaluation of differences in translation and the validity of arguments we read in commentaries.  We will cover a lot of Scripture in this lesson.  For this reason, this lesson, including the Anki exercises, will be a bit longer than usual as you store 29 of these verses in your heart.  

::: {.box .map}
__LESSON ITINERARY__

1. Understand the significance of word order upon translation
1. Describe the nuances of translation based upon word order and whether or not a verb has the <span class="he">ו</span> prefix
1. Translate conditional and volitional phrases
:::

::: {.box .stop}
__EQUIPMENT CHECK__

Before continuing, make sure you have an understanding of the Qal conjugations.  Refer to the worksheet in Lesson 22 for a self-assessment of your Qal skills.

:::

## First Thought {-}

### <span class="he">עַתָּה יָדַעְתִּי כִּי־גָדוֹל יְהוָה מִכָּל־הָאֱלֹהִים</span> {-}

*Now I know that the LORD is greater than all the Gods (Exodus 18:11)*

Back in Unit 2, we touched on how מִן is quite flexible when it comes to meaning.  A literal reading of this verse might be, "now I know that great is Adonai from all the gods."  מִן changes this to a comparative or even a superlative use. Comparative would be, "Our God is GREATER THAN all the other gods."  A superlative translation might be, "out of all the gods, I know Adonai is THE GREATEST."

This lesson will provide some overarching tips on interpretation and translation based on what we have studied so far.


<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>


*****

<div class="figure" style="text-align: center">
<img src="images/23..Muhraqa statue of Elijah on Mount Carmel, tb011400103.jpg" alt="Statue of Elijah on Mount Carmel. This statue is at the traditional location of Elijah's showdown between our God and the priests of Baal.  At this location, our God proved He was greater than Baal! Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-88)Statue of Elijah on Mount Carmel. This statue is at the traditional location of Elijah's showdown between our God and the priests of Baal.  At this location, our God proved He was greater than Baal! Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>



## Clause versus Sentence

* A clause has a subject and a predicate.
    * The simplest clause in Scripture is "Yeshua (subject) wept (predicate)"
* An _independent_ clause, such as "Yeshua wept" can be a complete sentence
* A sentence can have more than one clause
    * Now after the death of His servant Moses, the LORD spoke to Joshua son of Nun, Moses’ assistant, saying, “Moses My servant is dead." (Joshua 1:1)
    * There are three clauses in the one sentence
* We've used the terms "word-initial" and "word-final" throughout this course.  Now we will use "clause-initial" to reference the first word in a clause
* <span class="he">ו</span> is frequently clause-initial



## Word Order

Normal Hebrew word order is Verb - Subject - Object.  We can abbreviate this V-S-O (of course, in Hebrew, this goes from right-to-left).

* <span class="he">וַיִּזְכֹּר אֱלֹהִים אֶת־נֹחַ </span>  
    * _And God Remembered Noah (Gen 8:1)_
* <span class="he">וַיַּחֲלֹם יוֹסֵף חֲלוֹם</span>
    * _And (Then) Joseph dreamed a dream (Gen 37:5)_
* <span class="he">וַיִּקְרָא מֹשֶׁה אֶל־כָּל־יִשְׂרָאֵל</span>
    * _Then (and) Moses summoned all Israel (Ex 24:16)_

Since we say that V-S-O is the "normal" word order, whenever we encounter a clause that is **NOT** V-S-O, we want to take note as to what is going on.  Below is an example of S-V-O used to emphasize the subject, Adonai.

* <span class="he">*יְהוָה* יִמְלֹךְ לְעֹלָם וָעֶד</span>
    * *Adonai* shall reign forever and ever (Ex 15:18)
    
 
Hebrew also can have O-V-S, particularly in poetry.   

::: {.box .light}
English standard word order is S-V-O, so this is the way we would translate regardless of the Hebrew word order.
:::

## Perfect Syntax

The Perfect _without_ the <span class="he">ו</span> consecutive is **NOT NORMALLY** the first word in a clause

* <span class="he">אַחַר הַדְּבָרִים הָאֵלֶּה *הָיָה* דְבַר־יְהוָה אֶל־אַבְרָם</span>
    * After these things, the word of the LORD _CAME_ to Abram (Gen 15:1)
* <span class="he">וְהִנֵּה *נָפְלוּ* אֲבוֹתֵינוּ בֶּחָרֶב</span>
    * For behold, our fathers _FELL_ by the sword (2 Chr 29:9)
* <span class="he">בְּרֵאשִׁית *בָּרָא* אֱלֹהִים אֵת הַשָּׁמַיִם וְאֵת הָאָרֶץ</span>
    * In the beginning, God _CREATED_ the heavens and the earth (Gen 1:1
    
However, the Perfect _WITH_ the <span class="he">ו</span> consecutive is **ALWAYS** the first word in a clause

* <span class="he">*וַיֹּאוְאָהַבְתָּ* אֵת יְהוָה אֱלֹהֶיךָ</span>
    * _And you will love_ Adonai your God (Deut 6:5)
* <span class="he">*וְזָכַרְתִּי* אֶת־בְּרִיתִי </span>
    * _And I will remember_ my covenant (Gen 9:15)

As we remember from Lesson 17, the Perfect conjugation with the Vav is translated as if it were an Imperfect.


## Imperfect Syntax

Like the Perfect, the Imperfect _without_ the <span class="he">ו</span> consecutive is **NOT NORMALLY** the first word in a clause.  Below is an "S-V-O" verse we looked at earlier


* <span class="he">יְהוָה *יִמְלֹךְ* לְעֹלָם וָעֶד</span>
    * Adonai _shall reign_ forever and ever (Ex 15:18)
    
The consecutive Imperfect is the first word in a clause.  This is the most common form in Hebrew narrative.

* <span class="he">*וַיֹּאמֶר* הַנָּחָשׁ אֶל־הָאִשָּׁה</span>
    * The serpent _said_ to the woman (Gen 3:4)
    
A volitional imperfect (Cohortative and Jussive, each without the Vav consecutive) is usually the first word in the clause.

* <span class="he">*נַעֲשֶׂה* אָדָם בְּצַלְמֵנוּ </span>
    * _Let us make_ man in our image

::: {.box .info}
Note these words all follow the Imperfect paradigm.  The key to accurate translation is word order and whether or not there is the <span class="he">ו</span> consecutive prefix.
:::

## Volitional Syntax

Hebrew likes to link multiple verbs together. Word order can be a big clue in translating volitional clauses. 

* Multiple Imperatives (M+M) in succession:
    * <span class="he">*עֲלֵה* *וּקְבֹר* אֶת־אָבִיךָ</span>
    * _Go up_ and bury your father (Gen 50:6)
    * This verse would be sequential - go up and (then you can) bury your father
    * The context may indicate a consequential translation - do this **so that** something else will happen
* An Imperative followed by Perfect with Vav Consecutive (M + Pwc)
    * <span class="he">*לֵךְ* *וְאָמַרְתָּ* אֶל־עַבְדִּי</span>
    * _Go and say_ to my servant (2 Sam 7:5)
    * The perfect verb acts as if it were a second imperative ("Go and say", not "go and you will say")
* Imperative followed by an Imperfect or Cohortative (M+I or M+C) to create a purpose or result. "So that..."
    * <span class="he"> *רְדוּ*־שָׁמָּה *וְשִׁבְרוּ*־לָנוּ מִשָּׁם *וְנִחְיֶה* </span>
    * _Go down_ there and *buy grain* for us from there _so that we might live_

## Conditional Phrases

A conditional phrase is made up of two clauses.  You might want to think of this as an "if-then" statement.  The first gives the "if" condition, and the second states the "then" consequence if the condition is met<small>^[<small>The technical term for the first statement is the _protasis_, and the second statement is called the _apodosis_.</small>]</small> 

* <span class="he">וַיֹּאמֶר אֵלֶיהָ בָּרָק *אִם*־תֵּלְכִי עִמִּי *וְהָלָכְתִּי* *וְאִם*־לֹא תֵלְכִי עִמִּי לֹא אֵלֵךְ</span>
    * Then Barak said to her, "*If* you will go with me, *then I will go*; but *if* you will not go with me, (*then*) I will not go." (Judg 4:8)
    
::: {.box .info}

* The Hebrew word <span class="he">אִם</span> is most frequently, but not always, used for the first clause.
* The second clause often, but not always, begins with <span class="he">וְ</span>

:::

## Disjunctive Vav

In this course, we have talked about the CONjunctive Vav.  This is a Vav that is prefixed to a verb and serves to link the narrative and move it forward in some fashion.

When a Vav is prefixed to a non-verb, it is called a _DISjunctive_ Vav.  As the name implies, it indicates some kind of break or tangent in the narrative.  There are four primary ways a disjunctive Vav is used, as illustrated by the verses below.

* <span class="he">*וְהֵם* לֹא יָדְעוּ כִּי שֹׁמֵעַ יוֹסֵף כִּי הַמֵּלִיץ בֵּינֹתָם</span>
    * _(Now) They_ did not know, however, that Joseph understood, for there was an interpreter between them (Gen 42:23)
    * Parenthetical use: <span class="he">וְהֵם</span>
    * A parenthetical comment to explain why Joseph's brothers believed they could speak freely
* <span class="he">וַיְהִי כְּהַיּוֹם הַזֶּה וַיָּבֹא הַבַּיְתָה לַעֲשׂוֹת מְלַאכְתּוֹ *וְאֵין* אִישׁ מֵאַנְשֵׁי הַבַּיִת שָׁם בַּבָּיִת</span>
    * Now it happened one day that he went into the house to do his work, *and none* of the men of the household was there inside (Gen 39:11)
    * Circumstantial use: <span class="he">וְאֵין</span>
    * A break in the narrative, in this case, to provide vital information to set up the circumstances of the attempted seduction and subsequent imprisonment of Joseph
* <span class="he">וַיִּשַׁע יְהוָה אֶל־הֶבֶל וְאֶל־מִנְחָתוֹ׃  *וְאֶל*־קַיִן וְאֶל־מִנְחָתוֹ לֹא שָׁעָה</span>
    * And Adonai had regard for Abel and for his offering; *but for* Cain and for his offering He had no regard (Gen 4:4b-5a)
    * Contrastive use: <span class="he">וְאֶל</span>
    * Often translated "but"
    * This contrasts Adonai's reponse to the two men's offerings
* <span class="he">*וְהַנָּחָשׁ* הָיָה עָרוּם מִכֹּל חַיַּת הַשָּׂדֶה אֲשֶׁר עָשָׂה יְהוָה אֱלֹהִים</span>
    * _Now the serpent_ was more crafty than any beast of the field which the LORD God had made (Gen 3:11)
    * Introductory use: <span class="he">וְהַנָּחָשׁ</span>
    * A new theme or idea; sometimes an entirely new narrative
    * In this example, we move from the creation narrative to the temptation narrative

## Adverbs

* <span class="he">*עַתָּה* יָדַעְתִּי כִּי־יְרֵא אֱלֹהִים אַתָּה</span>
    * _Now_ I know that you fear God (Gen 22:12)
    * Adverb of Time: <span class="he">עַתָּה</span>
* <span class="he">*וַיָּשֶׂם* שָׁם אֶת־הָאָדָם אֲשֶׁר יָצָר</span>
    * *and there *He placed the man whom He had formed (Gen 2:8)
    * Adverb of Place: <span class="he">שָׁם</span>
* <span class="he">עֵינַי *תָּמִיד* אֶל־יְהוָה</span>
    * My eyes are *continually* toward the LORD (Ps 25:15)
    * Adverb of Degree: <span class="he">תָּמִיד</span>
* <span class="he">וַיָּבֹא אֲלֵיהֶם יְהוֹשֻׁעַ *פִּתְאֹם*</span>
    * So Joshua came upon them *suddenly* (Josh 10:9)
        * Adverb of Manner: <span class="he">פִּתְאֹם</span>

::: {.box .info}
* Adverbs are most frequently at the end of a clause.
* As the above examples illustrate, this is not a hard-and-fast-rule
:::

## Word Warm-up {-}


<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/" frameborder="0"></iframe>
</div>


[Click to open `Word Warm-up` video in a new tab](){target="_blank"}


## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/" frameborder="0"></iframe>
</div>


[Click to open `Verses Warm-up` video in a new tab](){target="_blank"}

## Ruth Pursuit Syntax Study {-}        

::: {.box .map} 

There is no formal quest for this lesson but consider the following points based on the material in Lesson 23<small>^[<small>These concepts are contained in the book, [_A Workbook for Intermediate Hebrew: Grammar, Exegesis, and Commentary on Jonah and Ruth_](https://www.amazon.com/gp/product/0825423902/&tag=holylanginst-20), by Robert B. Chisolm</small>]</small> :

* Note the Disjunctive Vav in Ruth 1:2.  Note how the main narrative does not continue but pauses to let us know the names of the people involved.  This is providing supplemental background information. 
* The Conjunctive Vav in Ruth 1:7 serves to begin a more detailed, focused narrative account of Naomi's return
* Note how the Disjunctive Vav in the final clause of 1:14 - Vav + non-verb (subject) + predicate - introduces a CONTRAST of Ruth's attitude of clinging, signaling deep loyalty and attachment to Naomi (see the דבק + בְּ note in Lesson 13 answer key), compared to Orpah's goodbye kiss
* In 1:16, כִּי introduces a subordinate clause that has an explanatory function.  "Ruth tells Naomi to stop urging her to go back because she has determined that she will follow Naomi wherever her mother-in-law goes."<small>^[<small>Chisholm. _A Workbook for Intermediate Hebrew_, page 286.</small>]</small>
* 1:17 has what some scholars refer to as an "oath formula".  <span class="he">כֹּה</span> gives the punishment for breaking the promise, and <span class="he">כִּי</span> gives the condition. The specifics appear to be implied rather than stated. This makes a literal translation awkward.  At the same time, any other translation becomes somewhat speculative and dependent on what the translator believes is the context.  NET renders the first clause as "The LORD will punish me severely."
    * Other oaths of this type appear in 1 Samuel 14:44, 1 Samuel 20:13, 2 Samuel 3:9, 1 Kings 2:23, and 1 Kings 19:2
* In 1:20, כִּי introduces a subordinate clause that has an explanatory function. Naomi is elaborating on why she wants a new name.
* We have noted that most Hebrew clauses begin with a verb, but 1:21 begins with "I".  Naomi is drawing attention to her condition: full when she left, but now returning empty.  Curiously, Ruth evidently counts for nothing.  Naomi's attitude will definitely change by the end of the book!
    * Also, note in 1:21 the Disjunctive Vav clauses, "And Adonai" followed by "And Shaddai."  Chisholm notes that the use may be "semi-poetic": "Adonai has testified about me; Shaddai has afflicted me"<small>^[<small>ibid. p. 133</small>]</small>.
* Finally, the Iwc in 1:22 begins a summarizing, concluding statement bringing the "first act" of the drama to a close.

:::

## Claim your Unit 3 Completion Certificate! {-}

If you have completed **all activities** in Lessons 1-23, you may claim the third `Unit Completion Certificate`.

<div class="containerLet">
<iframe class ="responsive-iframe" src="https://forms.gle/hkHMebEtNi61waidA" frameborder="0"></iframe>
</div>

## OPTIONAL _Hebrew Quest_ Study Passage: Psalm 19 {-}


::: {.box .map}
YOUR HEBREW QUEST:

1. Read through the passage - [Blank copy of Psalm 19](https://docs.google.com/document/d/1jyLXPdhaGYbyBmc6dZ2XJX1QrYDGgRpWtE6Yuho8B1k/edit?usp=sharing){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3. [Watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/psalm-19.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?

:::



<!--chapter:end:23-Hebrew_Syntax.Rmd-->

# (PART) Derived Binyanim {-}

# Introduction to Unit 4 {-}

Congratulations!  You now have the hardest work of a first-year Hebrew grammar course behind you.  From here on out, we will be studying the six major derived Hebrew Verb stems Niphal, Piel, Pual, Hiphil, Hophal, and Hitpael.

The reason we spent so much time on the Qal stem is not only because it's the most frequently occurring stem, but everything from this point forward is based on what you learned in Unit 3.  This means, for the most part, the lessons that follow will be shorter and much more methodical.

If you remember our introduction to Unit 3, we drew the comparison to a math formula.  If we know $a^2 + b^2 = c^2$, we do not need to memorize the dimensions of every triangle (assuming that were possible).  Instead, we can take the metaphorical triangle in front of us and use the formula to get what we need.  In Unit 3, you learned all the formulas.  All Unit 4 is going to do is present you with triangles of different sizes.  

Summaries of each of the derived stems will consist of the overall diagnostic features.  It is THESE features that should be memorized, not the numerous paradigms.

## Structure of Lessons 24-35 {-}

* You will note that 12 lessons remain in the course
* Each of the six derived stems will have two lessons: a lesson "A" and a lesson "B"
* Lesson A (even number) will cover the "Strong" Verb paradigm
    * The meaning of the stem
    * The spelling of the stem
        * Word-initial Prefix/Preformative combinations
        * $V_S$ formulas to help you "diagnose" the stem when you encounter it in the Bible
    * Complete forms of each conjugation using the קטל paradigm verb
        * The Perfect and Imperfect forms will have the Audio from Chapter 15 of _Hebrew Quest_
        * The Anki deck will have exercises to help you with paradigm identification
        * Each lesson will have a worksheet for you to practice the paradigm
        * As we have said, __identification of patterns is more important than memorization of paradigms__
* Lesson B (odd number) will address weak verb deviations
    * The b-side will cover spelling changes within caused by the behaviors of gutturals and other weak letters, Geminate verbs, Biconsonantal verbs, and other irregular verbs
    * Most of the time, you will already know the concepts
        * For example, in some forms of the Niphal Strong paradigm, $R_1$ takes a Dagesh Forte
        * You already know that if $R_1$ is a guttural or Resh, $R_1$ will reject the Dagesh Forte and often (but not always), there will be Compensatory Lengthening
        
## Ruth Pursuits {-}

There are only a handful of non-Qal verbs in Ruth 1, so you will only see the `Ruth Pursuit` activities in the following Lessons:

* Lesson 25 - Niphal
* Lesson 27 - Piel
* Lesson 31 - Hiphil
* Lesson 35 - Hitpael

In Lesson 26, we will start to do a `Ruth Pursuit Analysis`.  

* Here, we will start to use your `Ruth Pursuit Translation Worksheet` and your knowledge of grammar rules to begin to compose a paraphrase
* We will take a few verses at a time
* You will compose your own paraphrase translation and then compare it to published Bible versions of your choice
* This exercise is for your edification
    * You do not have to turn this in and, it will not be graded as a part of this course (as you know, no grades are ever recorded in this course)
    * We would encourage you to share your passage with the Holy Language Institute Tribe for their edification

## Stem Vowel Pattern Nomenclature {-}

* The derived stems tend to be much more consistent with their application of stem vowels
* We will use a code to memorize the stem vowels for non-Qal Strong verbs
* For example, the stem vowel code for Niphal is 

$$V_{S} = A \sim \bar E (A)$$

* $V_{S}$ means the <u>S</u>tem <u>V</u>owel
* Everything to the LEFT of the tilde $\sim$ is the stem vowel in the PERFECT conjugation
* Everything to the RIGHT of the tilde is the stem vowel in the IMPERFECT and related forms, Jussive, Cohortative, Imperative and Infinitive Construct
* Any exceptions are inside ()
    * Imperfect form exceptions apply to the Feminine Plural
        * Therefore $(A)$ in the formula means the Stem Vowel in the Imperfect FP, the Jussive FP, and the Imperative FP is Short A - Patach
        * There are no Cohortative (1st person) feminine forms
    * Perfect exceptions will tend to apply to the 2nd and 1st person forms
    * Niphal does not have any Perfect exceptions so there is nothing next to the first $A$
* What about Infinitive Absolute and Participles?
    * It turns out that for stems besides the Qal the Infinitive Absolute like $\bar E$ (Tsere)
    * Participles, again other than Qal, tend to like the _PERFECT_ $V_S$, _LENGTHENED_ if possible
        * So for the Niphal Participle, since the Perfect $V_S = A$, the Participle $V_S = \bar A$ (Qamets)
    
<img src="images/23b.stemvowelformula.png" width="300pt" style="display: block; margin: auto;" />

## What to memorize for all Derived Stems {-}
* Meaning of $V_S$ pattern

$$V_S = Perfect[2/1 person] \sim Imperfect (Imperfect FP)$$

* Always a Sheva before finite verb endings (unless $\bar E$ (Tsere))
* Participle $V_S$ = P3ms $V_S$ lengthened if possible (unless $\bar E$ (Tsere))
* Infinitive Absolute $V_S = \bar E$
    * Except: $V_S = \hat O$ for QA and some NA
* Everything else uses Imperfect $V_S$
    * Imperative, Jussive, Cohortative, ∞
    
## Review: Sheva before Finite Verb Endings {-}

* Finite Verbs have Person (1st, 2nd, 3rd)
    * Thus the Finite verb conjugations are: Perfect, Imperfect, Imperative, Jussive, Cohortative
    * The non-Finite conjugations are: Infinitive Construct, Infinitive Absolute, Participle
* A Sheva goes before a Finite Verb ending
    * This means the $V_S$ will REDUCE if the sufformative begins with a VOWEL
    * An exception to the above is that Unchangeable vowel letters do not reduce, so they do NOT take a Sheva
* The Adjective Endings do NOT take a Sheva - since Participles use adjective endings, they do not take a Sheva
    * One exception: if the Participle $V_S = \bar E$, then it REDUCES
        * Qal Active: <span class="he">קֹטֵל</span> (QPTms) becomes <span class="he">קֹטְלִים</span> (QPTmp)
        * Piel: <span class="he">מְקַתֵּל</span> (DPtms) becomes <span class="he">מְקַטְּלוֹת</span> (DPtfp)
        

<!--chapter:end:23b-Unit4_Intro.Rmd-->

# The Niphal Stem - Strong Verbs

The Niphal stem occurs 4,138 times in the Bible. 

* P - 1,426
* I - 1,544
* M - 118
* I∞ - 205 
* A - 37 
* Pt - 808

::: {.box .map}
LESSON ITINERARY

1. The meaning of the Niphal stem
1. $Pre$ combinations diagnostic of the Niphal stem
1. Niphal Stem Vowels
1. What to Memorize
:::

::: {.box .stop}
EQUIPMENT CHECK

* You must have all of the Qal strong verb paradigms committed to memory: Perfect, Imperfect, Imperative, Infinitive Construct, Infinitive Absolute, and Particle
* Review the $V_S =$ nomenclature from the Unit 4 Introduction
* Review the $Pre =$ nomenclature from the Unit 3 Introduction
:::

## First Thought {-}

### <span class="he"> וּמִן־הַגָּדִ֡י נִבְדְּל֣וּ אֶל־דָּוִיד֩ לַמְצַ֨ד מִדְבָּ֜רָה</span> {-}

*From the Gadites there came over to David in the stronghold in the wilderness (1 Chronicles 12:9)*

En Gedi, pictured below, is a well-watered oasis in an otherwise dry and dusty part of Israel adjacent to the Dead Sea.  Similarly, our walk with Yeshua (and indeed, our study of Hebrew!) can sometimes leave us feeling dry and dehydrated.  Just as David had a retreat at En Gedi, we need to remain connected to our source of Living Water as we go through life's journeys.


<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/24-8.1Chronicles 12.9.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="./images/24.Ibex drinking from Nahal David at En Gedi, tb100503600.jpg" alt="Ibex drinking from Nahal David at En Gedi.  En Gedi is the suggested location of the 'desert stronghold' referenced in 1 Chronicles. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-90)Ibex drinking from Nahal David at En Gedi.  En Gedi is the suggested location of the 'desert stronghold' referenced in 1 Chronicles. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>




## Niphal Verb Stem Table

| |Active Voice| Passive Voice | Reflexive Voice
|:- |:- |:- |:-
Simple Action	| Qal | _NIPHAL_ | _NIPHAL_
Cause a State	| Piel | Pual | Hitpael
Cause an Action	| Hiphil | Hophal

* Reminders:
    * The table gives broad generalization; many verbs do not fit neatly into the table's definitions
    * Use a lexicon/dictionary to check the meanings in different stems
    * Few verbs occur in all stems - many Niphal verbs NEVER occur in Qal
* Lesson 25 will have a list of the most frequent Niphal verbs

## Niphal Meanings

* Simple action with either a passive or reflexive voice
* <span class="he">שָׁמַע </span>
    * Qal - He heard
    * Niphal - He was heard (passive), or he heard himself (reflexive)
* Some English translations do not overtly seem passive or reflexive
    * <span class="he">אמן</span> - Niphal - to be reliable, faithful, trustworthy
    * <span class="he">לחם</span> - Niphal - to fight, do battle with

## Parsing Clues - _Pre_:  the נ prefix is added to EVERY conjugation

* Remember, we use the label $Pre$ for any diagnostic combination of word-initial consonants (prefix or root letters), vowels, and Dagesh Fortes (as applicable)
    * ק is used as a placeholder to represent $R_1% of any strong verb
    * For the Imperfect forms, י represents any of the Imprefect preformatives (note that 1cs א often usually takes a different $V_P$)

:::{.box .light}
Memorize these three $Pre$ formulas and the conjugations in which they are used
:::

* NP, NPt, some NA: $Pre =$ <span class="he">נִקְ</span>        
* NI: $Pre =$ <span class="he">יִקָּ</span> - and so forth for the other Imperfect forms
    * NI1cs: $Pre =$ <span class="he">אֶקָּ</span> (like the Qal) OR <span class="he">אִקָּ</span>
* NM, N∞, some NA:$Pre=$ <span class="he">הִקָּ</span>

::: {.box .info}      
* The נ prefix is added to <u>every</u> form of <u>every</u> conjugation
    * In the NP, NPt and in one form of the NA, the נ appears
    * In the NI, NM, N∞, and the other form of the NA, the נ is _assimilated into a Daghesh Forte_ in $R_1$
* Niphal Strong $V_P = I$ ALWAYS

:::

## Parsing Clues - $V_S = A \sim \bar E(A)$

::: {.box .light}
Memorize the $V_S$ formulas for each stem
:::
* $V_S = A \sim \bar E(A)$
* Left of $\sim$:
    * NP = $A$
        * Other stems will have a vowel in brackets, indicating a different $V_S$ for 1st and 2nd person
    * NPt (and Pt for all derived stems) = the P3ms $V_S$, _lengthened if possible_
        * Npt $V_S = \bar A$
* Right of $\sim$:
    *  NP/NI/N∞ = $\bar E$ 
        * ($A$ for Feminine Plural forms)
*  Absolute is not listed in the formula because for all derived stems, Absolute $V_S = \bar E$ (except $\hat O$ for QA and some NA)
:::

* Perfect $V_S=A$, so NP3ms = <span class="he">נִקְתַל</span>
* Imperfect/Imperative/∞ (except FP) $V_S= \bar E$, so <span class="he">יִקָּטֵל</span>
* Imperfect/Imperative/∞ FP $V_S=(A)$, so <span class="he">תִּקָּטַ֫לְנָה</span>
* Infinitive Absolute $V_S = \bar E$ (usually)
    * In the QA, $V_S = \hat O$ - ALWAYS
    * Some forms of Niphal also have $V_S = \hat O$ - <span class="he">וֹ</span>-  can be written defectively
    * The Niphal absolute only occurs 37 times total
* Niphal Participle $V_S =$ Lengthened P3ms
    * If $V_S$ is already long, the Participle is the same as the Perfect 3ms
    * Since the Niphal Perfect 3ms $V_S = A$, the Niphal Participle $V_S = \bar A$
        * NP3ms = <span class="he">נִקְטַל</span>
        * NptMS = <span class="he">נִקְטָל</span>
    * $V_S$ does NOT reduce in the NPt, which distinguishes Np3fs from NPtfs
        * <span class="he">נִקְטָלָה</span> is NPtfs because $V_S$ is long
        * <span class="he">נִקְתְלָה</span> is NP3fs because $V_S$ is reduced
    * Other stems reduce only if $V_S$ is $\bar E$ (Tsere)
        * Qal Active, Piel and Hitpael
    


## What to memorize for Niphal 

* The Three $Pre$ Sequences
    * NP/NPt/One form of NA: $Pre =$ <span class="he">נִקְ</span>        
    * NI: $Pre =$ <span class="he">יִקָּ</span> - and so forth for the other Imperfect forms
    * NM/N∞/One form of NA: $Pre =$ <span class="he">הִקָּ</span>
* The Niphal $V_S$ formula and what it means
    * $V_{S} = A \sim \bar E(A)$



## Paradigm: Niphal Perfect Strong

::: {.box .stop}
YOU DO NOT NEED TO MEMORIZE THE NON-QAL PARADIGMS

* The paradigms are presented so that you may see and hear each form
* With your knowledge of the Qal paradigms, you should be able to write the non-Qal paradigms from principles listed in the previous sections
:::

* In the Perfect, the נ of the Niphal is WRITTEN
* $Pre$ - $V_P = I$ and $V_1 = \ :$
* $V_S = A$ (unless reduced)

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">נִקְטַל</span>  | 3cp | <span class="he">נִקְטְלוּ</span> 
| 3fs | <span class="he">נִקְטְלָה</span> | 
| 2ms | <span class="he">נִקְטַ֫לְתָּ</span> | 2mp | <span class="he">נִקְטַלְתֶּם</span>
| 2fs | <span class="he">נִקְטַלְתְּ</span> | 2fp | <span class="he">נִקְטַלְתֶּן</span>
| 1cs | <span class="he">נִקְטַ֫לְתִּי</span> | 1cp | <span class="he">נִקְטַ֫לְנוּ</span>

<figure>
    <figcaption>Perfect Strong from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/24.Niphal_Perfect.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>


## Paradigm: Niphal Imperfect Strong

* In the Imperfect, the נ of the Niphal is ASSIMILATED
* $Pre$ - $V_P = I$, Dagesh Forte in $R_1$, and $V_1 = \bar A$ = <span class="he">יִקָּ</span>
* $V_S = \bar E$ (unless reduced)
    * For FP forms, $V_S = A$

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">יִקָּטֵל</span>  | 3mp | <span class="he">יִקָּֽטְלוּ</span> 
| 3fs | <span class="he">תִּקָּטֵל</span> | 3fp | <span class="he">תִּקָּטַ֫לְנָה</span>
| 2ms | <span class="he">תִּקָּטֵל</span> | 2mp | <span class="he">תִּקָּֽטְלוּ</span>
| 2fs | <span class="he">תִּקָּטְלִי</span> | 2fp | <span class="he">תִּקָּטַ֫לְנָה</span>
| 1cs | <span class="he">אֶקָּטֵל</span> | 1cp | <span class="he">נִקָּטֵל</span>

<figure>
    <figcaption>Imperfect Strong from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/24.Niphal Imperfect.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>

## Paradigm: Niphal Imperative Strong

* In the Imperative, the נ of the Niphal is ASSIMILATED
* You can tell an Imperative from an Imperfect by the <span class="he">הִ</span>, which is not an Imperfect preformative
* $Pre$ - $V_P = I$, Dagesh Forte in $R_1$, and $V_1 = \bar A$ = <span class="he">הִקָּ</span>
* $V_S = \bar E$ (unless reduced)
    * For 2FP form, $V_S = A$

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 2ms | <span class="he">הִקָּטֵל</span> | 2mp | <span class="he">הִקָּֽטְלוּ</span>
| 2fs | <span class="he">הִקָּֽטְלִי</span> | 2fp | <span class="he">הִקָּטַ֫לְנָה</span>

* The translation value of the Niphal Imperative will often lose the passive nuance as in הִשָּׁמֶר לְךָ פֶּן־תִּשְׁכַּח אֶת־יְהוָה “take heed to yourself lest you forget the Lord” (Deut 6:12).
* Frequently, the 2ms Imperative appears with an ה ָ ending

::: {.box .caution}
ADVANCE NOTICE

Hiphil Perfect verbs also have $Pre =$ <span class="he">הִקְ</span>, but Hiphil non-Perfect verbs have $Pre =$ <span class="he">הַקְ</span>. As long as you can distinguish a perfect from a non-perfect form, the <span class="he">הִ</span> prefix will pose little difficulty.
:::

## Paradigm: Niphal Infinitives Strong

* In one form of the Infinitive Absolute, the נ of the Niphal is WRITTEN
* In the other form of the Infinitive Absolute, the נ of the Niphal is ASSIMILATED
* The Niphal Infinitive Construct is identical to the NM2ms

| Type | Paradigm 
| :-  | :- 
| ∞ | <span class="he">הִקָּטֵל</span>  
| A | <span class="he">נִקְטוֹל</span>
| A | <span class="he">הִקָּטוֹל</span>

* There is no specific pattern regarding when one of the two absolute forms is used versus the other

### Derived Stem Infinitive Absolute $V_S = \bar E$ (usually) {-}

* In the QA, $V_S = \hat O$ - ALWAYS
* Some forms of Niphal also have $V_S = \hat O$
    * $\hat O$ <span class="he">וֹ</span> can be written defectively.

## Paradigm: Niphal Participle Strong

* In the Participle, the נ of the Niphal is WRITTEN

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| ms | <span class="he">נִקְטָל</span> | mp | <span class="he">נִקְטָלִים</span>
| fs | <span class="he">נִקְטֶ֫לֶת</span> | fp | <span class="he">נִקְטָלוֹת</span>

* Note $V_S = \bar A$, which is the lengthened $V_S$ of NP3ms


### Derived Stem Participle $V_S =$ the P3ms Vowel, lengthened if possible (usually) {-}

* In Niphal, the Perfect 3ms $V_S = A$ - using the above rule, the Niphal Participle $V_S = \bar A$
* For the Piel, the Perfect 3ms $V_S = \bar E$. Since $\bar E$ is already long, the Piel Participle is also $\bar E$

Three Exceptions:

* QPt = $\bar E$
* QPp = $\bar U$
* The Alternate FS "T-form" = <span class="he">נִקְטֶ֫לֶת</span>

## Participle Prefixes in the Derived Stems

All of the Participles besides Qal have a distinctive prefix.  Being able to identify this prefix will make identifying the various Participle stems straightforward.

Stem | Prefix 
:- | :-: 
NIPHAL | <span class="he">נִ</span>
Piel | מְ
Pual | מְ
Hiphil | ַמ
Hophal (u-class) | מֻ
Hophal (o-class) | ָמ
Hithpael | תִמְ


## Forms with Identical Spelling

* NP3fs and NPtfs - <span class="he">נִקְטְלָה</span>
* NI2ms and N∞ - <span class="he">הִקָּטֵל</span>
* As one form is finite and the other is non-finite, the context should immediately resolve any potential ambiguity

## Easily Confused Forms

* <span class="he">נִקְטַל</span> - NP3ms
* <span class="he">נִקְטֹל</span> - QI1cp (only biconsonantal forms would ever take a holem stem vowel (defective of Holem Vav) in the Niphal )
* <span class="he">נִקְטָל</span> - NPtms

## Niphal Parsing Examples

* Word: <span class="he">נִכְרָֽת</span>
    * Context: <span class="he"> וְזֶ֖רַע רְשָׁעִ֣ים נִכְרָֽת</span>
    * $Pre =$ נִכְ
    * $Suf =$ n/a
    * $Root =$ <span class="he">כרת</span>
    * $V_S = \bar A$ - 
        * The $V_S$ lengthening is unusual, but we have seen this with other Perfect and Imperfect verbs in the Qal section<small>^[<small>When in doubt, CHALOT provides a spelling of each word used.  P. 165 includes נִכְרָֽת as Niphal Perfect.</small> ]</small>
        * When the $Pre$ and $Suf$ are unambiguous, you can ignore the $V_S$
    * Result: NP3ms, he will be cut off

* Word: <span class="he">וְאִכָּבְדָ֤ה </span>
    * Context: <span class="he">וְאִכָּבְדָ֤ה בְּפַרְעֹה֙ </span>
    * $Pre =$ <span class="he">אִכָּ</span>- Niphal Imperfect 1cs + ו
    * $Suf =$ <span class="he">דָה</span>
        * Our first thought might P3fs or 3fs pronominal suffix, but neither of these fit the context
        * Remember from Lesson 18 that often, the Cohortative appears with an ה ָ ending.  In this passage, "I will be honored in/through Pharaoh" seems to fit better than "Let me be honored through Pharaoh."  This is likely just a spelling variant<small>^[<small>See CHALOT p. 150</small>]</small
        * External references tend to parse this as NI1cs
    * $Root =$ <span class="he">כבד</span>  to be heavy/weighty/glorified
    * $V_S = \ :$  (Silent Sheva)
    * Result: N(I/C)1cs; Imperative: I will be honored or Cohortative: let me be honored

* Word: <span class="he">נִגְרַזְתִּי֮ </span>
    * Context: <span class="he">נִגְרַזְתִּי֮ מִנֶּ֪גֶד עֵ֫ינֶ֥יךָ</span>
    * $Pre =$ <span class="he">נִגְ</span>
    * $Suf =$ <span class="he">תִי</span>
    * $Root =$ <span class="he">גרז</span>
    * $V_S =$ <span class="he">רַ</span>
    * Result: NP1cs - I am cut off (from before your eyes)
    * More than anything else, this word highlights the importance of differentiating the root from the Prefix and Suffix.  For example, if one thought the root was נגר, the translation would be very much incorrect.  גרז only appears once, here in Psalms 31:23
    
## Stem Comparison Table

* We can now update our Stem Comparison table to include Niphal
* Take note of the $Pre$ patterns in red and the $V_S$ in blue
    * When you can work your way back to the $Pre$ pattern of the Strong verb means you will correctly identify the stem and conjugation most of the time


<img src="images/24_stemcomp.png" width="600pt" style="display: block; margin: auto;" />

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/WYDdz_zrwSw" frameborder="0"></iframe>
</div>
 
[Click to open `Word Warm-up` video in a new tab](https://youtu.be/WYDdz_zrwSw){target="_blank"}




## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/jEQ6P2xIDEo" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/jEQ6P2xIDEo){target="_blank"}


## Worksheets: Niphal Strong Paradigm {-}

Use your knowledge of the $Pre$ and $V_S$ of the Niphal, complete the worksheet until you can do it once through correctly.

Again, you do NOT need to have the Niphal paradigms memorized (although that may eventually happen naturally!).

[Niphal Strong Paradigm](24_niphal_strong_paradigms.pdf){target="_blank"}


## Optional _Hebrew Quest_ Study Passage: Numbers 15 {-}

::: {.box .map}
YOUR HEBREW QUEST:

1. Read the passage - [Blank copy of Numbers 15](https://docs.google.com/document/d/19Tug4LR7twlNvMA0Gad_JKFsQNm5qugtzEqP_ET8_78/copy){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3.[Watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/numbers-15.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
    * You may wish to check your parsing and translation [here](https://scholarsgateway.com/search/WLC-ESV/Numbers/15){target="_blank"}
    * Check the "verbs" box to highlight all of the verbs in the passage, then hover over each verb for parsing information
5. How did the Ruach HaKodesh speak to you through the passage?
:::










<!--chapter:end:24-Niphal_Strong.Rmd-->

# The Niphal Stem - Weak Verbs {.N-w}


Now that we have learned the basic ground rules for the Niphal stem in Lesson 24, we now turn our attention to the spelling changes caused by verbs with one or more weak letters.  

In all stems, weak verbs tend to be much more prevalent.   We start by learning the strong verb patterns, then we can "manage by exception" to diagnose the corresponding weak verbs.

::: {.box .map}
__LESSON ITINERARY__

1. 1-Guttural Take Hateph Vowels, which changes $V_P$
1. 1-Guttural/Resh Compensatory Lengthening
1. 1-Yod Becomes וֹ or וָּ
1. 1-Nun with Silent Sheva Assimilates
1. 3-Aleph Changes $V_S$
1. 3-Hei Endings
:::

::: {.box .stop}
__EQUIPMENT CHECK__

Before continuing, can you describe the following concepts from Lesson 24?

* The Niphal $Pre$ sequences
* The Niphal $V_S$ formula
:::

## First Thought {-}

###  <span class="he">וְקָרְא֥וּ לָהֶ֛ם עַם־הַקֹּ֖דֶשׁ גְּאוּלֵ֣י יְהוָ֑ה וְלָךְ֙ יִקָּרֵ֣א דְרוּשָׁ֔ה עִ֖יר לֹ֥א נֶעֱזָֽבָה׃</span> {-}

*And they will call them, "The holy people, The redeemed of Adonai"; And you will be called, "Sought out, a city not forsaken." (Isaiah 62:12)*

We are called "Redeemed of Adonai."  Let that sink in.  Each new day offers us a chance to reflect on what it means to be redeemed and live our lives accordingly.

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/25-13.Isaiah65.19.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/25.Sunrise over Mount of Olives, tb031605564.jpg" alt="Sunrise over Mount of Olives. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-92)Sunrise over Mount of Olives. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>


## A weak consonant affects the vowels that touch it

* A weak $R_1$ affects $V_P$ and $V_1$ (but NOT $V_S$)
* A weak $R_2$ affects $V_S$ and $V_1$ (but NOT $V_P$)
* A weak $R_3$ affects $V_S$ and sufformative (but NOT $V_1$ or $V_P$)


## 1-Guttural 

* Guttural takes Hateph Vowel instead of Sheva
    * Remember the Rule of Sheva - "Hateph Copy Cat"
    * Whichever Hateph vowel is under the guttural, the Niphal prefix will take the corresponding short vowel
        * Strong - <span class="he">נִקְ</span>
        * 1G - <span class="he">נַעֲ</span> or <span class="he">נֶאֱ</span>
    * If $R_2$ has a Sheva, then $R_1$ lengthens from Hateph to its corresponding short vowel
        * 1G -<span class="he">נֶאֶמְ</span>
* Guttural and Resh reject Dagesh Forte
    * Strong - <span class="he">הִקָּ</span>
    * 1G/1R - <span class="he">יֵעָ</span>

## 1י

::: {.box .info}
* Historically, in the evolution of the language, most 1-Yod verbs used to begin with a Vav
* In some forms, that "original Vav" reappears
:::

* 1-Yod shifts to Holem Vav when $Pre$ = <span class="he">נִקְ</span>
    * Perfect - NOT *<span class="he">נִיְשַׁב</span>, but <span class="he">נוֹשַׁב</span>
    * Participle - NOT *<span class="he">נִיְשָׁב</span>, but <span class="he">נוֹשָׁב</span>
* 1-Yod shifts to consonantal Vav when $Pre =$ <span class="he">יִקָּ</span> (or similar)
    * Imperfect - NOT *<span class="he">יִיָּשֶׁב</span>, but <span class="he">יִוָּשֶׁב</span>
        * Imperfect 1C is ALWAYS <span class="he">אִ</span>, NOT *<span class="he">אֶ</span> if 1-Yod 
    * Imperative - NOT *<span class="he">הִיָּשֵׁב</span>, but <span class="he">הִוָּשֵׁב</span>

::: {.box .light}
If you see what looks like a "1-Vav" verb, parse it as 1-Yod
:::


## 1נ with Silent Sheva Assimilates

* When Niphal $Pre =$ <span class="he">נִקְ</span>:
    * NP3ms - NOT *<span class="he">נִנְצַל</span> but <span class="he">נִצַּל</span>
    * NPtMS - NOT *<span class="he">נִנְטָל</span> but <span class="he">נִצָּל</span>

## 3א Changes $V_S$

::: {.map .light}
You can usually parse a 3-Aleph verb based on the preformative alone
:::

* For 3-Aleph, there is a unique Niphal $V_S$ formula

$$V_S = \bar A(\bar E) \sim \bar E(E)$$

* You do not need to memorize the changed pattern since you can still parse based on the preformative
* $\bar A(\bar E)$ means:
    * $\bar A$ (Qamets) in the NP <u>3rd person</u> reduced (except in 3ms)
    * $(\bar E)$ (Tsere) in the NP <u>1st and 2nd person</u>
* NPt is still the P3ms $V_S$ lengthened
    * $\bar A$ is already a long vowel
    * So 3-Aleph NP3ms and NPtMS have the same spelling
    * <span class="he">נִמְצָא</span> is NP3ms or NPtMS
    
## 3ה Verbs Follow the same general principles

::: {.map .info}
To review: 

* 3-ה verbs have two root consonants, not three
* 3-ה verbs add a vowel after $R_2$
:::

1. If the sufformative begins with a vowel, the sufformative vowel goes after $R_2$
    * NP3cp - NOT *<span class="he">נִבְנָהוּ</span>, but <span class="he">נִבְנוּ</span>
    * Ni2fs - NOT *<span class="he">תִּבָּנָהִי</span>, but <span class="he">תִּבָּנִי</span>
2. If the sufformative begins with a consonant, (vowel)+Yod goes between $R_2$ and the sufformative
    * NP2ms - NOT *<span class="he">נִבְנָהתָ</span>, but <span class="he">נִבְנֵ֫יתַ</span> (Tsere+Yod for Perfect in the PASSIVE stems: Niphal, Pual, Hophal)
    * NI3fp - NOT *<span class="he">תִּבָּנָהנָה</span>, but <span class="he">תִּבָּנֶ֫ינָה</span> (Seghol+Yod for Imperfect and IMperative)
    * Hireq+Yod for Perfect in the NON-PASSIVE stems: Qal, Piel, Hiphil, Hitpael)
3. If NO sufformative or pronominal suffix, add 3-Hei ending after $R_2$
    * NP3ms <span class="he">נִבְנָה</span> (Qamets-Hei for Perfect)
    * QI3ms <span class="he">יִבְנֶה</span> (Seghol+Hei for Imperfect, Participle)
    * NI3ms <span class="he">יִבָּנֶה</span> (note the Dagesh Forte in $R_1$ is how you distinguish from QI3ms)
    * NM2ms <span class="he">הִבָּנֵה</span> (Tsere+Hei for Imperative, some Absolute)
    * QJ3ms <span class="he">יִ֫בֶן</span> (No ending for Iwc or Jussive)
4. Perfect 3fs uses sufformative <span class="he">תָה</span> to distinguish from P3ms
    * NP3ms - <span class="he">נִבְנָה</span>
    * NP3fs - <span class="he">נִבְנְתָה</span>

Review 3ה endings by Conjugation:

| Conj | Hebrew | Vowel when no sufformative
| :- | :- | :-
| P | <span class="he">בָּנָה</span> | Qamets+Hei
| I | <span class="he">יִבְנֶה</span> | Seghol+Hei
| M | <span class="he">בְּנֵה</span> | Tsere+Hei
| ∞ | <span class="he">בְּנוֹת</span> | Holem+Vav Tav
| A | <span class="he">בָנֹה</span> or <span class="he">בָנוֹ</span> | Holem+Hei or Holem+Vav
| Pt | <span class="he">בֹּנֶה</span> | Seghol+Hei


## What to Memorize for Niphal Weak

::: {.box .light}
Think your way through the weak verb $Pre$ to get back to the Niphal Strong $Pre$
:::

* 1G - $Pre$ <span class="he">נַעֲ</span> or <span class="he">נֶאֱ </span> or <span class="he">נֶאֶמְ</span> is the same as strong $Pre$ <span class="he">נִקְ</span>
* 1G/R - $Pre =$ <span class="he">הֵרָ</span> is the same as strong $Pre =$ <span class="he">הִקָּ</span>
* 1Y - $Pre =$ <span class="he">נוֹ</span> is the same as strong $Pre =$ <span class="he">נִקְ</span>
* 1N - $Pre =$ <span class="he">ָנִתּ</span> is the same as strong $Pre =$ <span class="he">נִקְתַ</span>

Also:

* Verbs that look "1-Vav" are actually 1-Yod - <span class="he">יִוָּשֵׁב</span>
* Memorize the list of 3-ה verb endings:

| Conj | Hebrew | Vowel
| :- | :- | :-
| P | <span class="he">בָּנָה</span> | Qamets+Hei
| I | <span class="he">יִבְנֶה</span> | Seghol+Hei
| M | <span class="he">בְּנֵה</span> | Tsere+Hei
| ∞ | <span class="he">בְּנוֹת</span> | Holem+Vav Tav
| A | <span class="he">בָנֹה</span> or <span class="he">בָנוֹ</span> | Holem+Hei or Holem+Vav
| Pt | <span class="he">בֹּנֶה</span> | Seghol+Hei

## Top 10 Niphal Verbs 

1. <span class="he">לָחַם</span> - (Q, N) to fight, do battle with (167x in Niphal Stem)
1. <span class="he">שָׁבַע</span> - (N) to swear, swear (take) an oath, adjure (154x)
1. <span class="he">מָצָא</span> - (Q) to find (out), reach, obtain, achieve; (N) be found, be found sufficient (142x)
1. <span class="he">רָאָה</span> - (Q) to see, perceive, understand; (N) appear, become visible (101x)
1. <span class="he">עָשָֹה</span> - (Q) to do, make, create, acquire, prepare, carry out; (N) be done, be made (99x)
1. <span class="he">שָׁאַר</span> - (N) to remain, be left over, survive (94x)
1. <span class="he">נָבָא</span> - (N) to prophesy, be in a state of prophetic ecstasy (87x)
1. <span class="he">נָתַן</span> - (Q) to give, put, set; (N) be given (83x)
1. <span class="he">אָסַף</span> - (Q) to gather (in), take in, take away; (N) be gathered, be taken away (81x)
1. <span class="he">יָתַר</span> - (N) to be left over, remain (81x)

## Word Warm-up {-}


<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/Pq3PWd41uQE" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/Pq3PWd41uQE){target="_blank"}


## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/hgbj52voNtw" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/hgbj52voNtw){target="_blank"}


## Ruth Pursuit {-}        

:::  {.box .map}
YOUR QUEST

Identify, parse, and translate the five Niphal verbs in Ruth 1.

You are likely unfamiliar with the meanings of at least two of these.  Identify the Niphal forms by their diagnostics, then identify and look-up the root's meaning.

By now, if you have been completing your `Ruth Pursuit` table along with each lesson, you may have noted that there aren't that many words left in the passage that we haven't translated.  This may make it easier for you to identify the remaining verbs by process of elimination, but make sure you understand WHY the words you select are Niphal.
:::

* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/copy){target="_blank"}
* [Ruth Pursuit Answer Key #25](./images/25_Ruth_Pursuit_KEY.pdf){target="_blank"}

## Claim your next `Twelve Tribes Badge`! {-}

<!-- Lesson 25 Tribe Badge 9 = Naftali -->

Once you have completed all activities through this lesson, complete the form below to receive your next badge!

<div class="containerLtr">
<iframe class="responsive-iframe" src="https://forms.gle/ScmbVPvSFGLW9P9p8" frameborder="0"></iframe>
</div>


## OPTIONAL _Hebrew Quest_ Study Passage: John 1 {-}

::: {.box .map}
YOUR HEBREW QUEST:

1. Read the passage - [Blank copy of John 1 in Hebrew](https://docs.google.com/document/d/1jWt3rS5Z5az2X_gCRO4Wg9mS4svUIHa5CrjUoqg-xnk/view?usp=sharing){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3.[Watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/john-1.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?
:::

<!--chapter:end:25-Niphal_Weak.Rmd-->

# The Piel Stem - Strong Verbs {.D-s}

The Piel stem occurs 6,473 times in the Hebrew Bible. It appears in the Perfect 2,120 times, Imperfect 2,446 times, Imperative 436 times, Infinitive Construct 708 times, Infinitive Absolute 84 times, and Participle 679 times

Many students find the Piel is one of the easier stems to identify.  It is one of only three Verb stems (along with the Pual and Hitpael) that has a Dagesh Forte in $R_2$. The Piel is easily distinguished from the Pual, which has a steady U-class vowel.  The Piel is also easily distinguished from the Hitpael, which has a unique prefix.

In addition to the Dagesh Forte, the Piel has a $Pre$ combination that (in the strong form) is relatively free from confusion with any other Hebrew Verb Stem.

::: {.box .map}
__LESSON ITINERARY__

1. Understand the meaning of the Piel Stem
1. Identify the distinctive diagnostics of the Piel Strong conjugations
:::



## First Thought {-}

### <span class="he">בִּשְׂפָתַ֥י סִפַּ֑רְתִּי כֹּ֝֗ל מִשְׁפְּטֵי־פִֽיךָ׃</span> {-}

*With my lips, I have told of All the ordinances of Your mouth (Psalms 119:13)*

With our study of Hebrew, we can get closer to the original intent of God's ordinances.  However, if we are not already keeping His words, worshiping and serving Him, and serving others in our native language, then nothing about learning Hebrew by itself will transform our lives.  

We must practice the disciplines of worship, service, and study (and teaching if that is our calling) so that these traits become hard-wired habits.  If that is already in place then we can use Hebrew to reach new depths in our relationships.

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/26-18.Psalms119.13.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="./images/26_Man with arms upraised at Western Wall, tb092603064.jpg" alt="Man with arms upraised at Western Wall. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-93)Man with arms upraised at Western Wall. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>




<!-- FOR STRONG VERB CHAPTERS -->

## Piel Verb Stem Table 

| |Active Voice| Passive Voice | Reflexive Voice
|:- |:- |:- |:-
Simple Action	| Qal | Niphal | Niphal
Cause a State	| _PIEL_ | Pual | Hitpael
Cause an Action	| Hiphil | Hophal

* Reminders:
    * The table gives broad generalization; many verbs do not fit neatly into the table's definitions
    * Use a lexicon/dictionary to check the meanings in different stems
    * Many references like this one will label the 2nd row as "Intensive Action," but this is a controversial topic in the academic community


## Piel Meanings

* Cause a state ('factitive')
    * <span class="he">מִלֵּא </span>
        * Q - He filled
        * D (Piel) - He caused (something) to be full
    <span class="he">אָנַשף </span>
        * Q - He was angry
        * D - He made (someone) angry
* Do something repeatedly ('iterative')
    * <span class="he">הָלַךְ</span>
        * Q - He walked
        * D - He walked around
* Declarative - he declared (someone) innocent
* Denominative (a verb made from a noun) - He acted as a priest (<span class="he">כִּהֵן</span> from <span class="he">כֹּהֵן</span> "priest")
* Intensive?
    * <span class="he">שִׁבֵּר </span>
        * Q - He broke
        * D - He smashed
            * This is hotly debated
            * Perhaps he caused it to be in a state of brokenness?
            * Perhaps he broke it repeatedly?

## Piel is the "D" stem because $R_2$ takes a Doubling Dagesh Forte

* In fact, when you see a Dagesh in $R_2$, it's more than likely either a Piel form or a 1-נ verb that has assimilated.  If you see three root letters, it's probably a Piel
    * Two other Stems take a Dagesh in $R_2$ - Pual (Lesson 28) and Hitpael (Lesson 34).  As we will learn in those lessons, both forms are easily distinguished from Piel.
* Gutturals, Resh, SQiN eM LeVY letters reject the Daghesh Forte
    * SQiN eM LeVY will be discussed later in this lesson
    * Gutturals/Resh will be discussed in Lesson 27

## Memorize Piēl - Paēl

::: {.box .info}
The Piel is remarkably consistent.  
While there are distinctive $Pre$ and $V_S$ combinations, it's easiest to remember the stem by the mnemonic "Piēl - Paēl"
:::

* Piēl in PERFECT
    * $V_1 = I$
    * $V_S = \bar E$ in the 3rd person
        * <span class="he">קִטֵּל</span> - DP3ms
    * $V_S = A in the 2nd/1st person
        * <span class="he">קִטַּ֫לְתָּ</span> - DP2ms
* Paēl in ALL OTHER CONJUGATIONS
    * $V_1 = A$
    * $V_P = :$ (or Hateph Patach in DI1cs), where applicable
    * $V_S = \bar E$
    * <span class="he">יְקַטֵּל</span> - DI3ms
    * <span class="he">קַטֵּל</span> - DM2ms/D∞/DA
    * <span class="he">מְקַטֵּל</span> - DPtMS

* For completeness, the Piel $V_S$ formula is below
    * This is the first time seeing $\bar E[A] \sim$
    * This means that while the 3rd person takes $\bar E$, the 1st and 2nd perfect forms take $V_S = A$
    * Do not confuse a vowel in brackets to the left of the $\sim$ with a vowel in parenthesis to the RIGHT
        * A vowel in brackets to the left means the 1st and 2nd person forms in the PERFECT take that vowel
        * A vowel in parenthesis to the right means the Feminine plural forms in the NON-PERFECT take that vowel

$$V_{S} = \bar E[A] \sim \bar E$$


## Pay attention when $R_2$ is a SQiN eM LeVY consonant

* As we have mentioned previously, SQiN eM LeVY is a mnemonic for a group of letters that can reject a Dagesh Forte when the letter has a Sheva
    * S - סצשׁסֹ
    * Q - ק
    * N - נ
    * M - מ
    * L - ל
    * V - ו
    * Y - י

* If you see a SQiN eM LeVY consonant with a Sheva, it might have a "hidden" Daghesh Forte

## DIwc

* The Iwc has a Dagesh in the Imperfect Preformative
* the DI preformative has a Sheva
* Therefore, DIwc3ms and DIwc3mp lose Dagesh
* DIwc3ms - Not *<span class="he">וַיְּקַטֵּל</span>, but <span class="he">וַיְקַטֵּל</span>
* DIwc3mp - Not *<span class="he">וַיְּקַטְּלוּ</span>, but <span class="he">וַיְקַטְּלוּ</span>
* Forms with reduced $V_2$
    * Example DP3cp - Not *<span class="he">שִׁמְּרוּ</span>, but <span class="he">שִׁמְרוּ</span>
    
## Piel: what to memorize

* Parsing code D - Dagesh Forte in $R_2$
* "Piēl - Paēl"
    * This is easier than remembering the $Pre$ and $V_S$ combinations separately
    * Piēl - Perfect $V_1 = I$
    * Paēl - everywhere else: $V_1 = A$
    * $V_S = E$ everywhere except Perfect 1st/2nd person (where $V_S = A$)
* $V_P = :$ in all Strong Conjugations with preformatives
    * This compares to $V_P = I$ in the Qal
* Participle preformative <span class="he">מ</span> (all stems except Qal and Niphal)
* The SQiN eM LeVY exceptions
    * $R_2$ and $DIwc$

## Piel Perfect Strong Paradigm

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">קִטֵּל</span>  | 3cp | <span class="he">קִטְּלוּ</span> 
| 3fs | <span class="he">קִטְּלָה</span> | 
| 2ms | <span class="he">קִטַּ֫לְתָּ</span> | 2mp | <span class="he">קִטַּלְתֶּם</span>
| 2fs | <span class="he">קִטַּלְתְּ</span> | 2fp | <span class="he">קִטַּלְתֶּן</span>
| 1cs | <span class="he">קִטַּ֫לְתִּי</span> | 1cp | <span class="he">קִטַּ֫לְנוּ</span>

* 3rd person $Pre$ is distinctive Hireq+Dagesh+Tsere
* 1st/2nd person $Pre$ is Hireq+Dagesh+Patach

<figure>
    <figcaption>Piel Perfect Strong from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/26_Piel_Perfect_Izzy.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>

## Piel Imperfect Strong Paradigm

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">יְקַטֵּל</span>  | 3mp | <span class="he">יְקַטְּלוּ</span> 
| 3fs | <span class="he">תְּקַטֵּל</span> | 3fp | <span class="he">תְּקַטֵּ֫לְנָה</span>
| 2ms | <span class="he">תְּקַטֵּל</span> | 2mp | <span class="he">תְּקַטְּלוּ</span>
| 2fs | <span class="he">תְּקַטְּלִי</span> | 2fp | <span class="he">תְּקַטֵּ֫לְנָה</span>
| 1cs | <span class="he">אֲקַטֵּל</span> | 1cp | <span class="he">נְקַטֵּל</span>

* Piel Imperfect is consistent: <span class="he">יְקַטֵּל</span> 
    * Remember $V_1 = A$ in all non-Perfect forms
    * $V_P = ə$ (Vocal Sheva) - DI1cs will take $V_P = \breve A$ (Hateph Patach)
    * Compare to Qal Imperfect $Pre$ of Hireq+Sheva+Holem
    
<figure>
    <figcaption>Piel Imperfect Strong from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/26_Piel_Imperfect.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>

## Piel Imperative Strong Paradigm

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 2ms | <span class="he">קַטֵּל</span> | 2mp | <span class="he">קַטְּלוּ</span>
| 2fs | <span class="he">קַטְּלִי</span> | 2fp | <span class="he">קַטֵּ֫לְנָה</span>

<figure>
    <figcaption>Piel Imperative Strong from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/26_Piel_Imperative.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




## Piel Infinitives Strong Paradigm


| Type | Paradigm 
| :-  | :- 
| ∞ | <span class="he">קַטֵּל</span>  
| A | <span class="he">קַטֵּל</span>

* Same as DM2ms

<figure>
    <figcaption>Piel Infinitives Strong from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/26_Piel_infinitive.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>


## Piel Participle Strong Paradigm

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| ms | <span class="he">מְקַטֵּל</span> | mp | <span class="he">מְקַטְּלִים</span>
| fs | <span class="he">מְקַטֶּ֫לֶת</span> | fp | <span class="he">מְקַטְּלוֹת</span>

* Distinctive <span class="he">מְ</span> prefix

### Participle Prefixes in the Derived Stems {-}

Again we present this table for review:

Stem | Prefix 
:- | :-: 
Niphal | נִ |
PIEL | <span class="he">מְ</span>
Pual | מְ
Hiphil | ַמ
Hophal (u-class) | מֻ
Hophal (o-class) | ָמ
Hithpael | תִמְ

## Piel Parsing Examples

* Word: <span class="he">גדַּ֫לְנוּ </span>
    * The Dagesh in the Gimmel is a Lene (not preceded by a vowel), but the Dagesh in the Dalet is preceded by a vowel that is not a Sheva, so this must be a forte.
        * A Forte in what appears to be $R_2$ Should get your attention 
        * The two questions you should start asking when you see a Forte in $R_2$:
            * "Is this Piel?"
            * "Is this an assimilated נ1" - if you clearly see $R_1$ you can rule out this option
    * $Pre =$ גִּדַּ, distinctly Piel Perfect
    * $Sufformative =$ נוּ, Perfect 1cp
    * $Root =$ <span class="he">גדל</span>
    * $V_S = A$ - We might expect Tsere in the Piel, but then we remember that Piel Perfect takes Patach in 1st/2nd person
    * Result: Piel Perfect 1cp, we made great

* Word: <span class="he">אֲדַבֶּר</span>
    * Immediately, note the Daghesh in $R_2$
        * Your mind should immeadetly be asking, "is this Piel?"
        * Potentially, this could be an assimilated 1-nun verb, but we already have what appear to be three-root letters visible
    * Then remember "Piel-Pael" and note this rhymes with Pael.  So without doing much analysis, we're already pretty sure this is a Piel, non-Perfect.
    * $Pre =$ אֲדַבּ, 
        * We expect $V_P = ə$ in the Piel; but, as we know, the Aleph takes the Hateph vowel instead of Sheva
        * The Patach+Dagesh+Tsere combination is consistent with Piel non-Perfect
    * $Sufformative =$ None. With the Aleph preformative, this is I1cs
    * $Root =$ <span class="he">דבר</span>
    * $V_S = \bar E$, consistent with Piel (except DP1/2 person)
    * Result: Piel Imperfect 1cs I will speak

* Word: <span class="he">לַמֵּד</span>
    * The Dagesh Forte in $R_2$ suggests Piel or assimilated 1-Nun
        * Of the verb examples on this page, this is the only one where a 1-nun might be plausible
            * We have the ל, which is a common prefix to an infinitive construct
            * If there was a verb נמד, we might want to probe this further as a possible ∞, but we don't know a verb נמד
            * Even if this were a 1נ verb,, the vowels don't match up
        * We DO know a verb למד though
            * Like in other areas of life, when we have a set of multiple possibilities, the most direct path is often the correct one
        * You also note that the word rhymes with "Pael", suggesting a "working hypothesis" of Piel, non-perfect
    * $Pre =$ לַמּ,
    * $Sufformative =$ none.  No preformative, no sufformative could be QP, but the vowels don't match Qal at all. The vowels do match Piel.
        * This can't be DP because $V_1 \not = I$
        * This can't be DI because all Imperfects have a preformative
        * This can't be DPt because DPt begins with <span class="he">מְ</span>
        * DM2ms, D∞, and DA each work
    * $Root =$ <span class="he">למד</span>
    * $V_S = \bar E$, consistent with Piel (except Piel Perfect 1/2 person)
    * Result: D(M2ms/∞/A) - Teach! or to teach

## Stem Comparison Table

* Here is the Stem Comparison Table showing Qal, Niphal, and now Piel


<img src="images/26_stemcomp.png" width="600pt" style="display: block; margin: auto;" />

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/6A3f3WemMmE" frameborder="0"></iframe>
</div>


[Click to open `Word Warm-up` video in a new tab](https://youtu.be/6A3f3WemMmE){target="_blank"}



## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/NGT8fiuGGp0" frameborder="0"></iframe>
</div>


[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/NGT8fiuGGp0){target="_blank"}


## Worksheets: Piel Strong Paradigms {-}

Use your knowledge of the diagnostics Piel stem to complete the Piel worksheet.

Strive for pattern recognition over rote memorization.

[Piel Strong Worksheet](26_piel_strong_paradigms.pdf){target="_blank"}

## Ruth Pursuit Analysis

We are now at the exciting stage where we can begin to stitch together an analysis of Ruth 1.  This will be much the same as you have done with the `Hebrew Quest Study Passages`.  The main difference is you will not have Izzy's video explanation.  In that sense, you will now be wading a little deeper into the Hebrew pool! 

We're going to do this in small chunks over the next several lessons.  

If Ruth 1 is "Act 1" of the drama, we'll start with what is "scene 1": Ruth 1:1-6.

::: {.box .map}
YOUR QUEST

1. Read Ruth 1:1-6 in the Hebrew text and underline any words or forms do you not recognize
    * For the first time, try doing this without any study aids, including your `Ruth Pursuit Translation Worksheet`
    * Then as needed, look up the words you don't recognize
2. Using what you have learned about syntax/phrase constructions and context, compose your own interpretative translation (this time, using whatever resources you'd like!)
    * You may wish to compose a structural outline of "mini-scenes" identified by conjunctive or disjunctive clauses, quotations, or other constructions
3. Compare your version with translations of your choice.  These may include JPS, KJV, ESV, NASB, NIV, or NLT.  
    * At what points do you agree and disagree with translation decisions made by these publications? 

This exercise is for you.  You do not have to turn this in, and it will not be graded as a part of this course.  We would encourage you to share your passage with the Holy Language Institute Tribe for their feedback and encouragement.

:::

## OPTIONAL _Hebrew Quest_ Study Passage: Exodus 31 {-}


::: {.box .map}
YOUR HEBREW QUEST

1. Read the passage - [Blank copy of Exodus 31](https://docs.google.com/document/d/1uRkk2MNy6-8CqSzXQAadDqhnHqUTI6i7Bd6OOxCbYjQ/edit?usp=sharing){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3.[Watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/exodus-31.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
    * You may wish to check your parsing and translation [here](https://scholarsgateway.com/search/WLC-ESV/Exodus/31){target="_blank"}
5. How did the Ruach HaKodesh speak to you through the passage?
:::

<!--chapter:end:26-Piel_Strong.Rmd-->

# The Piel Stem - Weak Verbs {.D-w}

This lesson will continue our overview of the Piel stem by looking at the week verbs.

::: {.box .map}
__LESSON ITINERARY__

1. Understand how the Piel diagnostics change in weak verb forms
1. Learn the 10 most frequent verbs in the Piel stem
:::

::: {.box .stop)  
EQUIPMENT CHECK

Before continuing, be sure you are familiar with the diagnostics of the Piel strong forms across the six primary conjugations

:::

## First Thought {-}

### <span class="he">בֹּ֤אוּ שְׁעָרָ֨יו ׀ בְּתוֹדָ֗ה חֲצֵרֹתָ֥יו בִּתְהִלָּ֑ה הֽוֹדוּ־ל֝֗וֹ בָּרֲכ֥וּ שְׁמֽוֹ׃</span> {-}

*Enter His gates with thanksgiving And His courts with praise. Give thanks to Him, bless His name. (Psalms 100:4)*

We pray that you are still enthusiastically looking forward to each new Lesson of Hebrew GRAMMAR Quest.  We realize it's a long road that you have traveled, yet at this stage, it might seem like you still have a long ways to go before reaching your destination.  Be of good cheer and do not lose heart!  

God is working within you through these lessons!  Throughout your life, you have likely had many journeys and many destinations.  Each lesson you finish and each day you complete your `Anki` reviews is a small destination: an arrival of sorts that should be celebrated.

Many people who travel to Israel rightly look back on Jerusalem as the pinnacle of their trip. And in a sense, many "first-timer" tours are structured so that Jerusalem is the "grand finale".  However, if those tourists were focused ONLY on getting to Jerusalem, they could miss the blessings of the many other places they visited and the lessons learned along the way.

You are nearing the end of your journey! Keep focusing on Him!  Make sure each day you are entering into His presence with thanksgiving and praise!

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/27-16.Psalms100.4.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="./images/27_Golden menorah for third temple, tb123199206.jpg" alt="Golden menorah for The Third Temple in Jerusalem. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-95)Golden menorah for The Third Temple in Jerusalem. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>




## Third Guttural (all variants)

::: {.box .light}
* All third guttural verbs will change the Stem Vowel
* In the Piel, we can determine the Stem by the $Pre$ and sufformatives, so we can effectively ignore what happens to the $V_S$
* You do not need to memorize the $V_S$ formulas below; just understand that the vowels change with these weak letters
:::

* Strong - $V_S = \bar E[A] \sim \bar E$
* 3-ע/ח - $V_S = A \sim A$
* 3-א - $V_S = \bar E \sim \bar E(A)$
* 3-ה - The same as 3-ה in other stems:

| Conj | Hebrew | Vowel when no sufformative
| :- | :- | :-
| P | <span class="he">בָּנָה</span> | Qamets+Hei
| I | <span class="he">יִבְנֶה</span> | Seghol+Hei
| M | <span class="he">בְּנֵה</span> | Tsere+Hei
| ∞ | <span class="he">בְּנוֹת</span> | Holem+Vav Tav
| A | <span class="he">בָנֹה</span> or <span class="he">בָנוֹ</span> | Holem+Hei or Holem+Vav
| Pt | <span class="he">בֹּנֶה</span> | Seghol+Hei



## 2-Guttural Reject Sheva 


* Going way back to the very first lessons of Hebrew GRAMMAR Course, we studied the different behavior of Gutturals and Resh
* 2-G verbs will take Hateph vowel instead of Vocal Sheva
* Whenever you see a Hateph vowel, substitute a Sheva to get back to the Strong paradigm
    * DP3cp - <span class="he">קִטְּלוּ</span> (strong) is <span class="he">נִחֲלוּ</span> 
    * Review Lesson 26 Paradigms for the forms where $V_2 = ə$

## 2-Guttural and 2ר Reject Dagesh Forte

* As we learned in Lesson 26, the Dagesh Forte in $R_2$ is a key distinctive of the Piel (as well as the Pual and Hitpael) stems
* 2-G and 2-ר will reject that Dagesh Forte
    * 2-ר/א will almost always have Compensatory Lengthening
        * DP2ms, Not <span class="he">בִרַּ֫כְתָּ</span>*, but <span class="he">יְבֶרַ֫כְתָּ</span> (Hireq lengthens to Tsere)
        * DI3ms, Not <span class="he">תְּבַרֵךְ</span>*, but <span class="he">תְּבָרֵךְ</span>(Patach lengthens to Qamets) 
    * 2-ה/ח/ע usually do NOT have compensatory lengthening in Piel
        * DP3cp - Not <span class="he">נִחֲּמוּ</span>*, but <span class="he">נִחֲמוּ</span>
        * Often $V_2$ changes, but do not be concerned about this; the Diagnostic Piel $Pre$ (minus the Dagesh Forte) is still intact

::: {.box .caution}  
Most Piel verbs exhibit either Compensatory Lengthening, or Virtual Doubling (i.e., either all one or all the other).

However, some verbs may exhibit either pattern.
:::

## 1נ

* As we know, what makes a 1-nun verb weak is the tendency to assimilate when the nun has a Sheva
* $V_1$ is NEVER a Sheva in the Piel<small>^[<small>To "connect the dots", if $V_2$ MUST be a Dagesh Forte, than $V_1$ MUST be a vowel that is not a Sheva.</small>]</small> so 1-Nuns are actually strong in the Piel (meaning there are no spelling changes compared to the Piel Strong Verb Paradigms)
* The challenge is that the $Pre$ of a 1-nun Piel Perfect verb is identical to the $Pre$ of a Niphal Perfect verb
* To demonstrate, consider <span class="he">נִגַּ֫שְׁתָּ</span>, which is either DP2ms or NP2ms:
    * We do not know whether the <span class="he">נִ</span> is the nun of the Niphal prefix, or whether it is the 1-nun of the root in the Piel
    * We also do not know whether the Dagesh in <span class="he">גּ</span> represents the assimilated 1-Nun in the Niphal, or the Doubled $R_2$ in Piel
    * The $V_S = A$ in both the perfect 1st and 2nd person
        * and $V_S$ is reduced in the P3fs and P3cp in both stems
    * The context may help if the voice is clearly active or passive, but remember many Niphal meanings are active
    * You may need to consult a reference for these
    
::: {.box .info}
The good news is that the P3ms $V_S$ are not the same in Piel ($\bar E$, as in <span class="he">נִצֵּל</span>) and Niphal ($A$, as in <span class="he">נִַצָּל</span>), so the far more common P3ms forms can be differentiated.
:::

## Biconsonantal: the Polel minor stem

* Biconsonantal verbs lack $R_2$ so there will be no Dagesh
* What happens is that $R_3$ is doubled (as if it were a Geminate) and there is a Holem Vav (sometimes written as a defective Holem) at $V_1$
* Example <span class="he">רוּם</span>
    * DP3ms <span class="he">רוֹמֵם</span> - this is also the same as DM2ms and D∞
    * DP2ms <span class="he">רוֹמַ֫מְתָּ</span>

::: {.box .info}
* Because of the vowel sequence, Biconsonantal Piel is sometimes referred to by the mnemonic, pôlēl
    * While there are seven major Hebrew verb stems, many grammars classify many additional minor stems
    * Polel would be considered a minor stem
* Take note that pôlēl is also the vowel sequence for the QPt 
:::

## Geminate

* Geminate verbs are sometimes strong
    * <span class="he">הִלֵּל</span> or <span class="he">יְהַלֵּל</span>
* Sometimes they are like pôlēl
    * <span class="he">פּוֹרֵר</span> or <span class="he">יְפוֹלֵל</span>

## Other weak $R_1$ forms

Generally, these are not a problem because we are not trying to reduce $R_1$ or put a Dagesh Forte in $R_1$

## What to Memorize for Piel Weak

* 3-ה verb endings in all stems
* 2-G/2-ר verbs lack the Dagesh in $R_2$ - may have Compensatory Lengthening
* 1-נ verbs in DP = NP (except for 3ms)
* The mnemonic, pôlēl, to remind you of Biconsonantal or Gemininate

::: {.box .info}
For most weak verbs, the strong diagnostics of the Piel are retained: 

1. Dagesh Forte in $R_2$
2. "Piel-Pael" ($V_1 = I$ in the Perfect, and $V_1 = A$ everywhere else)
3. $V_P = \ :$ where applicable (Imperfect and Participle)
:::

## Piel Weak Parsing Examples

* Word: <span class="he">כַּלּוּ </span>
    * $Pre =$ כַּלּ 
        * The Dagesh in $R_2$ should have us thinking Piel
        * The Patach fits with a non-Perfect Piel beginning
        * There is no imperfect preformative, which indicates D(M/∞/A)
    * $Suf =$ וּ -
        * This could be P3cp, but we already ruled Perfect out above. 
        * This is also 3mp Imperfect or 2mp Imperative
        * Based only on $Pre$ and $Suf$, we have a strong suspicion this is likely DM2mp
    * $Root =$ <span class="he">כלה</span> - 
        * We might think כלו, but there is no such word, and we're already pretty sure the Shurek is the $Suf$
        * When a $Suf$ begins with a vowel, the ה of a 3-ה verb drops.  
        * From our vocabulary, we know כלה means "to finish"
    * $V_S$ has been erased as is common with 3-ה verbs
    * Result: DI2mp - Finish!

* Word: <span class="he">כִּלּוּ</span>
    * Use the same detective work as כַּלּוֹ above, only the Hireq+Daghesh now takes us down a Piel Perfect trail
    * Result: DP3cp

* Word: <span class="he">שֵׁרְתוּ </span>
    * $Pre$: $V_1 = \bar E$ might give you pause, but when you look at the next letter, you see a Resh, which rejects the Dagesh forte.
    * The first question to ask is, "I wonder whether this was Hireq+Dagesh originally? Given that there is no other prefix or preformative, this could be Piel Perfect."
    * $Suf=$ Shurek P3cp/I3mp/M2mp
        * The lack of preformative rules out this being an I3mp
        * There are no imperatives that have $V_1 = I / \bar E$
    * $Root =$ <span class="he">שׁרת</span>
    * $V_S = \ :$, The original $V_S$ (whatever it was) has been reduced by the Sheva of the finite sufformative.  As it is, we have enough to conclude that this is Piel Perfect.
    * Result: DP3cp - they served

## Top 10 Piel Verbs

1. <span class="he">דָּבַר</span> - (Q) to speak; (D) speak to, with or about (someone or something) (1,085x in the Piel)
1. <span class="he">צָוָה</span> - (D) to command, give an order, charge (487x)
1. <span class="he">שָׁלַח</span> - (Q) to send, stretch out; (D) send, stretch out, send away, expel, let go free (267x)
1. <span class="he">בָּרַךְ</span> - (QPp) blessed, praised, adored; (D) bless, praise (233x)
1. <span class="he">בָּקַשׁ</span> - (D) to seek (to find or obtain), search for, look for, discover, demand, require (222x)
1. <span class="he">כָּלָה</span> - (Q) to (be) complete, be finished, be at an end,come to an end; (D) complete, finish, bring to an end (141x)
1. <span class="he">כָּסָה</span> - (Q) to cover, conceal, hide; (D) cover (up), conceal, clothe (132x) 
1. <span class="he">הָלַל</span> - (D) to praise, sing hallelujah (113x)
1. <span class="he">מָלֵא</span> - (Q) to be full, fill (up); (D) fill, perform, carry out, consecrate as priest (111x)
1. <span class="he">שָׁרַת</span> - (D) to minister, serve, attend to the service of God (98x)

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/b_Iu9NXRQS8" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/b_Iu9NXRQS8){target="_blank"}



## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/nIcuyVOHIhw" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/nIcuyVOHIhw){target="_blank"}



## Ruth Pursuit {-}        

:::  {.box .map}

Identify, parse, and translate the two Piel verbs in Ruth 1

Make sure you can identify the Piel forms by their diagnostic indicators: $V_1 = I \sim A$ and a Daghesh Forte in $R_2$ that does not represent an assimilated letter in a non-Piel form.
:::

* [Blank copy of Ruth 1](https://drive.google.com/file/d/1qcfTKAlTJGChC2eYCMhSbY2w-ibzCcDV/copy){target="_blank"}
* [Ruth Pursuit Answer Key #27](./images/27_Ruth_Pursuit_KEY.pdf){target="_blank"}



## Hebrew Quest Study Passages: Psalms 1 and 27 {-}


::: {.box .map}
YOUR HEBREW QUEST

1. Read the passages
    * [Blank copy of Psalms 1](https://docs.google.com/document/d/16fIA7dWqvQ-0GFpcwTC-tKwAr1-GgxDxlQN09_kGX3o/copy){target="_blank"}
    * [Blank copy of Psalms 27](https://docs.google.com/document/d/13erJPTE91FuYRR8OZWlASBpwn_r_x2YSkS2ikFPcAHc/copy){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3. Watch Izzy's _Hebrew Quest_ videos
    * [Psalm 1](https://holylanguage.com/psalm-1.php){target="_blank"}
    * [Psalm 27](https://holylanguage.com/psalm-27.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?
:::

<!--chapter:end:27-Piel_Weak.Rmd-->

# The Pual Stem - Strong Verbs {.Dp-s}

The Pual stem has a diagnostic Qibbuts as $V_1$, making this stem easy to recognize. 

The Pual occurs 423 times in the Hebrew Bible: 

* Perfect 146
* Imperfect 85 
* Participle: 190
* The Pual never occurs in Imperative and occurs only once each in ∞ and Absolute.

::: {.box .map}
__LESSON ITINERARY__

1. Translate the Pual
1. Recognize the Pual
:::

::: {.box .stop}
__EQUIPMENT CHECK__

Before continuing, be sure you can describe the diagnostics of the Piel Strong Paradigm

:::

## First Thought {-}

### <span class="he">בְּחֶ֣סֶד וֶ֭אֱמֶת יְכֻפַּ֣ר עָוֺ֑ן וּבְיִרְאַ֥ת יְ֝הוָ֗ה ס֣וּר מֵרָֽע׃</span> {-}

*By lovingkindness and truth iniquity is atoned for, And by the fear of Adonai, one keeps away from evil. (Proverbs 16:6)*

This verse is interesting.  Our traditional beliefs would probably be closer to "the fear of" Yeshua is what gives us atonement."  Similarly we might say that it is our actions, lovingkindness and truth, that keep us away from evil.  While these beliefs are not incorrect, this verse flips things around. 

How can you apply Proverbs 16:6 today?  How do you think our lovingkindness and truth can cover (כפר) our sins? 

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/28-1.Proverbs16.6.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/28_Megiddo pass aerial from northeast, tbs1201400113.jpg" alt="Megiddo Pass aerial from the northeast.  This area was highly strategic throughout antiquity. Whoever held it could control all movement in the region.  Pharaoh Thutmose III once remarked, 'taking Megiddo is like taking 1000 cities.' This is also the suggested location of the staging area for the so-called 'Battle of Armageddon' described in the Book of Revelation. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-96)Megiddo Pass aerial from the northeast.  This area was highly strategic throughout antiquity. Whoever held it could control all movement in the region.  Pharaoh Thutmose III once remarked, 'taking Megiddo is like taking 1000 cities.' This is also the suggested location of the staging area for the so-called 'Battle of Armageddon' described in the Book of Revelation. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>



## Pual Verb Stem Table and Meaning

| |Active Voice| Passive Voice | Reflexive Voice
|:- |:- |:- |:-
Simple Action	| Qal | Niphal | Niphal
Cause a State	| Piel | _PUAL_ | Hitpael
Cause an Action	| Hiphil | Hophal

The Pual is the Passive of the Piel, or sometimes, the passive of the Qal

* <span class="he">שׁלם</span>
    * D: To repay
    * Dp: To be repaid
* <span class="he">הלל</span>
    * Q: To praise
    * Dp: to be praised
* <span class="he">ילד</span>
    * Q: To give birth
    * D: To cause to give birth (be a midwife)
    * Dp: To be born



## Parsing Clues - _Pre_: $V_1 = U$ - ALWAYS for strong verbs

* The Pual is very consistent, making it easily recognizable
    * $V_1 = U$ - ALWAYS for strong verbs
* Perfect: <span class="he">קֻטּ</span>
* Imperfect: <span class="he">יְקֻטּּ</span>
    * $V_P = ə$ (I1cs/I1cp never occurs)
* Participle: <span class="he">מְקֻטּ</span>

::: {.box .light}
The Qibbuts under the first root consonant distinguishes the Pual Form
:::

## Parsing Clues - $V_S = A$ and Dagesh Forte in $R_2$

* $V_S = A$ - ALWAYS for strong verbs (unless reduced by the Sheva of the Perfect Sufformative)
    * I.e. $V_S = A \sim A$
    * Pt lengthens as expected: $V_S = \bar A$
* The Pual retains the other diagnostics of the Piel:
    * Daghesh Forte in $R_2$




## Pual: what to memorize

* Parsing code: Dp
    * 'D' because $R_2$ is doubled
    * 'p' because passive
* $V_P = \ :$
* $V_1 = U$
* $V_S = A$
* Qibbuts ($R_1$)+Daghesh+Patach is diagnostic of Pual
* Like Piel, beware when $R_2$ is guttural, Resh, or SQiN eM LeVY

## Perfect  

Qibbuts in $V_1$ always

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">קֻטַּל</span>  | 3cp | <span class="he">קֻטְּלוּ</span> 
| 3fs | <span class="he">קֻטְּלָה</span> | 
| 2ms | <span class="he">קִטַּ֫לְתָּ</span> | 2mp | <span class="he">קֻטַּלְתֶּם</span>
| 2fs | <span class="he">קֻטַּלְתְּ</span> | 2fp | <span class="he">קֻטַּלְתֶּן</span>
| 1cs | <span class="he">קֻטַּ֫לְתִּי</span> | 1cp | <span class="he">קֻטַּ֫לְנוּ</span>

<figure>
    <figcaption>Perfect Strong from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/28_pual_perfect.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>


## Imperfect  

* Qibbuts in $V_1 = U$ always
* If there is a preformative, $V_P = \ :$ always

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">יְקֻטַּל</span>  | 3mp | <span class="he">יְקֻטְּלוּ</span> 
| 3fs | <span class="he">תְּקֻטַּל</span> | 3fp | <span class="he">תְּקֻטַּ֫לְנָה</span>
| 2ms | <span class="he">תְּקֻטַּל</span> | 2mp | <span class="he">תְּקֻטְּלוּ</span>
| 2fs | <span class="he">תְּקֻטְּלִי</span> | 2fp | <span class="he">תְּקֻטַּ֫לְנָה</span>
| 1cs | <span class="he">אֲקֻטַּל</span> | 1cp | <span class="he">נְקֻטַּל</span>

<figure>
    <figcaption>Imperfect Strong from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/28_pual_imperfect.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>


## Participle

* Qibbuts in $V_1$ always
* Mem+Sheva prefix always

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| ms | <span class="he">מְקֻטָּל</span> | mp | <span class="he">מְקֻטָּלִים</span>
| fs | <span class="he">מְקֻטֶּ֫לֶת</span> | fp | <span class="he">מְקֻטָּלוֹת</span>

### Participle Prefixes in the Derived Stems {-}

Again we present this table for review:

Stem | Prefix 
:- | :-: 
Niphal | נִ |
Piel | מְ
PUAL | <span class="he">מְ</span>
Hiphil | ַמ
Hophal (u-class) | מֻ
Hophal (o-class) | ָמ
Hithpael | תִמְ

## Pual Parsing Examples

* Qibbuts ($R_1$)+Daghesh+Patach is diagnostic of Pual

* Word: <span class="he">גִּדְּלוּ</span>
    * Result: DP3cp

* Word: <span class="he"> גֻּדְּלוּ</span>
    * Result: DpP3cp

## Stem Comparison Table

* Here is the Stem Comparison Table showing the stems we have studied thus far


<img src="images/28_stemcomp.png" width="600pt" style="display: block; margin: auto;" />

## Worksheet: Pual Paradigm {-}

After memorizing the information in the "what to memorize" section, see if you can reconstruct the Pual paradigm using this worksheet.  

[Pual Strong Paradigms](28_pual_strong_paradigms.pdf){target="_blank"}


## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/ujh7gojxD9Q" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/ujh7gojxD9Q){target="_blank"}



## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/x6Sg3_NbX3w" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/x6Sg3_NbX3w){target="_blank"}



## Ruth Pursuit Analysis {-}

It's time for the next segment of translating Ruth.  This time, we'll start with "Scene 2": Ruth 1:7-10.

::: {.box .map}
YOUR QUEST

1. Read Ruth 1:7-10 in the Hebrew text and underline any words or forms do you not recognize
    * For the first time, try doing this without any study aids
    * Then as needed, look up the words you don't recognize
2. Using what you have learned about syntax/phrase constructions and context, provide your own interpretative translation 
    * You may wish to compose a structural outline of "mini-scenes" identified by conjunctive or disjunctive clauses, quotations, or other constructions
3. Compare your version with translations such as JPS, KJV, ESV, NASB, NIV, or NLT.  
    * At what points do you agree and disagree with translation decisions made by these publications? 

:::



## Claim your next `Twelve Tribes Badge`! {-}

<!-- Lesson 28 Tribe Badge 10 = Reuben -->

Once you have completed all activities through this lesson, fill out the form below to receive your next Badge.

<div class="containerLtr">
<iframe class="responsive-iframe" src="https://forms.gle/QC5VgJExb9R89Yde8" frameborder="0"></iframe>
</div>


## OPTIONAL Hebrew Quest Study Passage: Revelation 1 {-}

::: {.box .map}
YOUR HEBREW QUEST

1. Read the passage - [Blank copy of Revelation 1](https://docs.google.com/document/d/1EfxyZpTDzP-eaXgVAx4nWcdETV_fActF8L3l-0QQvGA/copy){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3.[Watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/revelation-1.php){target="_blank"}
4. After the video, compare your translation with versions such as ESV, NASB, NIV and/or NLT. How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?
:::



<!--chapter:end:28-Pual_Strong.Rmd-->

# The Pual Stem - Weak Verbs {.Dp-w}

The distinctive $V_1 = U$ is maintained in nearly all Pual weak forms.  Regardless of other spelling changes, only the Pual has $V_1 = U$.  It is only when $R_2$ rejects the Dagesh Forte AND has Compensatory Lengthening that there is a potential ambiguity.

Enjoy this very brief lesson!


::: {.box .map}
__LESSON ITINERARY__

The Pual diagnostic $V_1 = U$ is maintained in almost every weak verb form
:::

::: {.box .stop}
__EQUIPMENT CHECK__

Before continuing, can you describe the following concepts?

* The Piel weak forms (Lesson 27)
* Pual strong diagnostics (Lesson 28)
:::

## First Thought {-}

### <span class="he">גִּבּ֣וֹר בָּ֭אָרֶץ יִהְיֶ֣ה זַרְע֑וֹ דּ֭וֹר יְשָׁרִ֣ים יְבֹרָֽךְ׃</span> {-}

*His descendants will be mighty on earth; The generation of the upright will be blessed. (Psalms 112:2)*

As we are approaching the conclusion of the Hebrew GRAMMAR Quest course, an excellent question to start asking yourself is, "what next?" Or, as Yeshua might ask, what are you going to do with this "light" you have been given?  How can you enrich the lives of your family, friends, and other people in your circle of influence?  How can your descendants (whoever that might be in your situation) be blessed by your greater knowledge of Hebrew?

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/29-3.Psalms112.2.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>


<div class="figure" style="text-align: center">
<img src="images/29_Man with hands on sons for priestly blessing, tb092302202.jpg" alt="Man with his hands on his sons for the priestly blessing. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-98)Man with his hands on his sons for the priestly blessing. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>




## The Pual diagnostic $V_1 = U$ is maintained in almost all weak verbs

* $V_1 = U$ is unique to the Pual stem
* Regardless of other changes that may occur, you will be able to identify the Pual stem in every case, with one exception
* You will still need to know the general weak verb concepts, particularly 3-ה behavior, to make sure you get to the correct Pual conjugation



## 2-Gutturals Reject Dagesh Forte

* When there is NO compensatory lengthening, $V_1 = U$, so we can quickly identify Pual
* When there IS Compensatory Lengthening, $V_1 = \bar O$ (Holem)
    * DpP3ms - NOT *<span class="he">בֻּרַּךְ</span>, but <span class="he">בֹּרַךְ</span>
* Ambiguity arises because Qal Participle is also $V_1 = \bar O$ but only the QPtFS and DpP3FS of a 2-G verb are identical
* Because the Qal stem is much more frequent than the Pual, a correct first guess whenever $V_1 = \bar O$ is Qal Participle.  If you notice that $R_2$ is a guttural, you may need to do some more detective work


## Biconsonantal: the Polal minor stem

* In every respect the same as Pual except for $V_S = A$
* This is identical to the Polel stem for the Piel discussed in Lesson 27
    * Polel $V_S = \bar E$



## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/OO2Hy6apXlg" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/OO2Hy6apXlg){target="_blank"}



## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/YiO_gyPz-nM" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/YiO_gyPz-nM){target="_blank"}

## Ruth Pursuit 

Not surprisingly, there are no Pual verbs in Ruth 1.  We'll skip the `Ruth Pursuit` for this lesson.

## OPTIONAL _Hebrew Quest_ Study Passage: Psalms 145 {-}


::: {.box .map}
YOUR HEBREW QUEST

1. Read the passage - [Blank copy of Psalms 145](https://docs.google.com/document/d/1PjBUYB3ws2mdtdbHZsRz3Ji1W2dwyAvon3wJCrsP6qo/copy){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3.[Watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/psalm-145.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?
:::

<!--chapter:end:29-Pual_Weak.Rmd-->

# The Hiphil Stem - Strong Verbs {.H-s}

With the Hiphil stem, we move into the bottom row of our verb table.  There are approximately 10,000 occurrences of the Hiphil stem in the Bible. The Hiphil stem has the nuance of causing an action, entering into a state, or declaring a state.  Activities for this lesson include identifying Hiphil verbs in Ruth chapter one and, for those doing the _Hebrew Quest_ Study Passage track, reading verse by verse through Exodus 19.


::: {.box .map}
LESSON ITINERARY

1. Understand the meaning of the Hiphil Stem to understand our Bible
1. Identify the Hiphil $Pre$ sequence
1. Identify the $V_S$ pattern for when we can't rely on the $Pre$ sequence
1. Understand the Hiphal Strong paradigms
:::


## First Thought {-}

### <span class="he">לְכוּ־נָ֛א וְנִוָּֽכְחָ֖ה יֹאמַ֣ר יְהוָ֑ה אִם־יִֽהְי֨וּ חֲטָאֵיכֶ֤ם כַּשָּׁנִים֙ כַּשֶּׁ֣לֶג יַלְבִּ֔ינוּ אִם־יַאְדִּ֥ימוּ כַתּוֹלָ֖ע כַּצֶּ֥מֶר יִהְיֽוּ׃</span> {-}

*"Come now, and let us reason together," Says Adonai, "Though your sins are as scarlet, They will be as white as snow; Though they are red like crimson, They will be like wool. (Isaiah 1:18)*

This is a famous memory verse for traditional Jews and Christians/Believers in Messiah alike.  How beautiful to be able to read and hear in the original Hebrew!  Meditate on it!

<span class="he">יַאְדִּ֥ימוּ</span> is Hiphil Imperfect 3ms

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/30-10.Isaiah1.18.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/30.Western Wall with chairs and snow, tb022503206.jpg" alt="Western Wall with Chairs and Snow. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-99)Western Wall with Chairs and Snow. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>





## Meaning of the Hiphil

| |Active Voice| Passive Voice | Reflexive Voice
|:- |:- |:- |:-
Simple Action	| Qal | Niphal | (Niphal)
Cause a State	| Piel | Pual | Hitpael
Cause an Action	| __HIPHIL__ | Hophal

Meanings:

* Cause an action
    * <span class="he">יצא</span>
        * Q - to go out
        * H - to cause something to go out, i.e., to bring out
    * Sometimes passive of Qal - <span class="he">אכל</span>
        * Q - to eat
        * H - to cause to eat, i.e., to feed 
* Enter into or declare the state expressed by Qal
    * <span class="he">זקן</span>
        * Q - to be old
        * H - to grow old
    * <span class="he">רשׁע</span>
        * Q - to be guilty/wicked
        * H - to declare guilty
* Simple action, like the Qal

Parsing Code: H (`H`iphil)

## Hiphil Strong Word Initial Combinations - Think "HIphil-HAphil"

* Preformatives
    * Hiphil verbs have preformative ה
    * Imperfects and Participles have the usual preformatives
* $V_P$
    * Remember "Hiphil-Haphil" (like "Piel-Pael")
    * $V_P = I$ in the PERFECT ("Hiphil")
    * $V_P = A$ EVERYWHERE ELSE ("Haphil")
* $V_1 = :$ 
* $Pre$ combinations are:
    * <span class="he">הִקְ</span> - HP
    * <span class="he">יַקְ</span> - HI, and so forth for the other Imperfect forms
    * <span class="he">הַקְ</span> - HM/H∞/HA
    * <span class="he">מַקְ</span> - Pt

::: {.box .light}
* In most cases, the "H<u>i</u>phil-H<u>a</u>phil" mnemonic is sufficient to identify the Hiphil stem
* Exceptions are when $R_1$ is a weak consonant - we will study these scenarios in Lesson 31
:::

## Hiphil $V_S = Î[A] \sim Î(Ē)$

* $V_S(HPt) = \hat I$ 
    * The Participle is usually the Perfect $V_S$ lengthened. In this case, Hireq+Yod is already long, so there is no change from the Perfect
* $V_S(HA) = \bar E$ as expected.

::: {.box .caution}
Note when $V_S = \hat I$, it may be written defectively as Hireq.  It never reduces because it is an unchangeable long vowel, even when it is written as Hireq.
:::

### Exception to $V_S$ pattern {-}

* HM2ms: $V_S = \bar E$
* Hiwc---: $V_S$ is often $\bar E$ instead of $\hat I$ (Hireq+Yod) when there is no pronominal suffix
    * <span class="he">הַקְטֵל</span>
    * <span class="he">וַיַּקְטֵל</span>


## Don’t confuse  <span class="he">ְ הִ</span> with Niphal Preformative  <span class="he">ָּּ הִ</span>

* Hiphil  - <span class="he">הִקְטִיל</span>
    * No Daghesh Forte in $R_1$
* Niphal - <span class="he">הִקָּטֵל</span>
    * Daghesh Forte in $R_1$
    * $V_1$ = Qamets

## Don't confuse Hiphil Imperfect  <span class="he">ְ יַ</span> with Qal Imperfect  <span class="he">ְ יִ</span>

* Remember "Hiphil" = Perfect; "Haphil" everywhere else
* Imperfect $V_P$ of Hireq is NOT Hiphil
* Ambiguity arises with 1G verbs because of the Rule of Sheva ("Hateph copy-cat")
* As we've discussed, in 1G situations, we can't necessarily rely on the stem's $Pre$ sequence to determine the stem
    * $V_P$ and $V_1$ will be Patach and Hateph Patach in both Hiphil and Qal
    * The Hiphil $V_S$ will be Hireq+Yod
        * HI3ms - <span class="he">יַעֲמִיד</span>
        * QI3ms <span class="he">יַעֲמֹד</span>
* 3ה lose their stem vowel, so 1G+3ה are truly ambiguous
    * (Q/H)I3ms - <span class="he">יַעֲלֶה</span>
    * Context will determine whether he "went up" (Qal) or whether he "brought (something) up" (Hiphil)

## Hiphil Perfect Strong Paradigm

As with the other stems, we list these paradigms to aid in your recognition of these forms.  It is not necessary to memorize these like you had to do with the Qal paradigms.

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">הִקְטִיל</span>  | 3cp | <span class="he">הִקְטִ֫ילוּ</span> 
| 3fs | <span class="he">הִקְטִ֫ילָה</span> | 
| 2ms | <span class="he">הִקְטַ֫לְתָּ</span> | 2mp | <span class="he">הִקְטַלְתֶּם</span>
| 2fs | <span class="he">הִקְטַלְתְּ</span> | 2fp | <span class="he">הִקְטַלְתֶּן</span>
| 1cs | <span class="he">הִקְטַ֫לְתִּי</span> | 1cp | <span class="he">הִקְטַ֫לְנוּ</span>

<figure>
    <figcaption>Hiphil Perfect Strong Paradigm from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/30.hiphil_perfect_paradigm.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




## Hiphil Imperfect Strong Paradigm

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">יַקְטִיל</span>  | 3mp | <span class="he">יַקְטִ֫ילוּ</span> 
| 3fs | <span class="he">תַּקְטִיל</span> | 3fp | <span class="he">תַּקְטֵ֫לְנָה</span>
| 2ms | <span class="he">תַּקְטִיל</span> | 2mp | <span class="he">תַּקְטִ֫ילוּ</span>
| 2fs | <span class="he">תַּקְטִ֫ילִי</span> | 2fp | <span class="he">תַּקְטֵ֫לְנָה</span>
| 1cs | <span class="he">אַקְטִיל</span> | 1cp | <span class="he">נַקְטִיל</span>

<figure>
    <figcaption>Hiphil Imperfect Strong Paradigm from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/30.hiphil_imperfect_paradigm.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>

## Hiphil Imperative Strong Paradigm

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 2ms | <span class="he">הַקְטֵל</span> | 2mp | <span class="he">הַקְטִ֫ילוּ</span>
| 2fs | <span class="he">הַקְטִ֫ילִי</span> | 2fp | <span class="he">הַקְטֵ֫לְנָה</span>

<figure>
    <figcaption>Hiphil Perfect Strong Paradigm from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/30.hiphil_imperative_paradigm.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>



## Hiphil Infinitives Strong


| Type | Paradigm 
| :-  | :- 
| ∞ | <span class="he">הַקְטִיל</span>  
| A | <span class="he">הַקְטֵל</span>

* $V_S$ will distinguish the two Infinitive forms.  HA has a Tsere.
* Note that HM2ms and HA are identical (the context will distinguish)

## Participle Strong

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| ms | <span class="he">מַקְטִיל</span> | mp | <span class="he">מַקְטִילִים</span>
| fs | <span class="he">מַקְטֶ֫לֶת</span> or <span class="he">מַקְטִילָה</span> | fp | <span class="he">מַקְטִילוֹת</span>


* The מ prefix, which characterizes the Participle in the Piel, Pual, Hiphil, and Hophal stems
* $V_S$ = Hireq+Yod throughout (except for one of the FS forms)

### Participle Prefixes in the Derived Stems {-}

Stem | Prefix 
:- | :-: 
Niphal | נִ |
Piel | מְ
Pual | מְ
HIPHIL | <span class="he">ַמ</span>
Hophal (u-class) | מֻ
Hophal (o-class) | ָמ
Hithpael | תִמְ


## Strong Summary

* In most cases, the "H<u>i</u>phil-H<u>a</u>phil" mnemonic for $V_P$ is sufficient to identify the Hiphil stem - $V_P = I$ (Hireq) in the PERFECT, and $V_P= A$ (Pathach) in ALL OTHER CONJUGATIONS
* The exceptions come when $R_1$ is a weak letter (discussed in Lesson 31)
* Hiphil Beginning Combination:
    * <span class="he">ְ הִ</span> - HP
    * <span class="he">ְ יַ</span> - (etc.) HI
    * <span class="he">ְ הַ</span> - HM/H∞/HA
    * <span class="he">ְ מַ</span> - HPt
* $V_S = Î[A] \sim Î(Ē)$
    * It's essential to memorize the $V_S$ formula for each derived stem for those times when we can't rely on the beginning combination
    
## Stem Comparison Table

* Here is the Stem Comparison Table showing the stems we have studied thus far


<img src="images/30_stemcomp.png" width="600pt" style="display: block; margin: auto;" />

## Hiphil Strong Paradigm Worksheet {-}

Our focus is on recognition, not repetition.  As we stated, in most cases, the "H<u>i</u>phil-H<u>a</u>phil" mnemonic for $V_P$ is sufficient to identify the Hiphil stem.

After you have reviewed the Anki material for this lesson, test yourself by completing the [Hiphil Paradigm Worksheet](./images/30_hiphil_strong_paradigms.pdf){target="_blank"} using the $Pre$ and $V_S$ patterns you have learned.  Repeat until you can complete a column without referring to the answers.

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/mBTsk07nIwQ" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/mBTsk07nIwQ){target="_blank"}



## Verses Warm-up {-}

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/-WjxwqdN5UQ){target="_blank"}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/-WjxwqdN5UQ" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/-WjxwqdN5UQ){target="_blank"}

## Ruth Pursuit Analysis {-}

It's time for the next segment of translating Ruth.  We'll continue with "Scene 2": Ruth 1:11-14.

::: {.box .map}
YOUR QUEST

1. Read Ruth 1:11-14 in the Hebrew text and underline any words or forms do you not recognize
    * As needed, look up any words you don't recognize
2. Using what you have learned about syntax/phrase constructions and context, provide your own interpretative translation 
    * You may wish to compose a structural outline of "mini-scenes" identified by conjunctive or disjunctive clauses, quotations, or other constructions
3. Compare your version with one or more published translations such as JPS, KJV, ESV, NASB, NIV, or NLT.  
    * On which points do you agree and disagree with translation decisions made by these publications? 

:::




## OPTIONAL _Hebrew Quest_ Study Passage: Exodus 19 {-}


::: {.box .map}
YOUR HEBREW QUEST

1. Read the passage - [Blank copy of Exodus 19](https://docs.google.com/document/d/1OGYrVxUGGPbwi8ioGi1bnt_vwA4YCNE2XZ2l3GQ8rQM/copy){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3. Now, using your marked-up copy of the passage, [watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/lesson-33.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
    * You may wish to check your parsing [here](https://scholarsgateway.com/search/WLC-ESV/Exocus/19){target="_blank"}
    * Check the "verbs" box to highlight all of the verbs in the passage, then hover over each verb for parsing information
5. How did the Ruach HaKodesh speak to you through the passage?
:::


<!--chapter:end:30-Hiphil-Strong.Rmd-->

# The Hiphil Stem - Weak Verbs {.H-w}


The Hiphil stem is relatively common in Scripture, occurring 9,496.  In fact, it is the most frequently occurring of the derived stems.

Primarily, the Hiphil stem has a causative action.  For example, the root זכר means "he remembered" in the Qal Perfect 3ms.  That root would mean "he caused to remember," i.e., "he reminded" in the Hiphil Perfect 3ms. 

Hiphil has a distinctive prefix (remember, "Hiphil-Haphil"), and a distinctive $\hat I$ in the 3rd person Perfect as well as most non-Perfect forms.  For the most part, these diagnostic features are retained in weak verbs.  This lesson will review some of the major exceptions to the Hiphil strong verb paradigm.

::: {.box .map}
**LESSON ITINERARY**

Hiphil weak verb principles as they related to the following:

1. 1-Guttural
1. 2-Guttural
1. 3א and 3עח
1. 3ה
1. 1נ
1. 1י
1. Biconsonantal
:::

::: {.box .stop}
**EQUIPMENT CHECK**

Before continuing, can you describe the following concepts?

* Parsing code H
* Hiphîl-Haphîl
* $V_S = \hat I(A) \sim \hat I(\bar E)$
:::

## First Thought {-}

### <span class="he">תּ֘וֹרַ֤ת יְהוָ֣ה תְּ֭מִימָה מְשִׁ֣יבַת נָ֑פֶשׁ עֵד֥וּת יְהוָ֥ה נֶ֝אֱמָנָ֗ה מַחְכִּ֥ימַת פֶּֽתִי׃</span> {-}

*The precepts of Adonai are right, rejoicing the heart; The commandment of Adonai is pure, enlightening the eyes. (Psalms 19:8)*

The _Hebrew Quest_ Study Passage for this lesson will continue with Exodus 20, the 10 commandments. Let us delight in the Law of Adonai!

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/31-1.Psalms19.8.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/31_Men touching Torah Scroll at Western Wall, tb092302203.jpg" alt="Men touching Torah Scroll at Western Wall. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-101)Men touching Torah Scroll at Western Wall. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>



## Weak Verbs Review: 

* A weak consonant affects the vowels that touch it
    * A weak $R_1$ affects $V_P$ and $V_1$ (but NOT $V_S$)
    * A weak $R_2$ affects $V_S$ and $V_1$ (but NOT $V_P$)
    * A weak $R_3$ affects $V_S$ and sufformative (but NOT $V_1$ or $V_P$)
* Biconsonantals and Geminates affect everything
* Gutturals take Hateph, not Sheva
    * In Hiphil Strong, $V_1$ always takes Sheva
    
::: {.box .light}
Distrust vowels on or immediately before weak letters
:::

## Strong Summary

* In most cases, the "H<u>i</u>phil-H<u>a</u>phil" mnemonic for $V_P$ is sufficient to identify the Hiphil stem - $V_P = I$ (Hireq) in the PERFECT, and $V_P= A$ (Pathach) in ALL OTHER CONJUGATIONS
    * The exceptions come when $R_1$ is a weak letter (discussed in this lesson)
* Hiphil $Pre$ sequences:
    * <span class="he">ְ הִ</span> - HP
    * <span class="he">ְ יַ</span> - (etc.) HI
    * <span class="he">ְ הַ</span> - HM/H∞/HA
    * <span class="he">ְ מַ</span> - HPt
* $V_S = Î[A] \sim Î(Ē)$
    * It's important to memorize the $V_S$ formula for each derived stem for those times when we can't rely on the beginning combination
    

## 1-Guttural

The changes below **ONLY** apply to 1G Imperfect Verbs

* When Hiphil 1G $V_1$ takes Hateph vowel, this means $V_P$ is affected by the Rule of Sheva
* The same thing occurs in the Qal Imperfect
* Therefore, the $Pre$ for the Hiphil and the Qal will be identical: <span class="he">יֶעֱ</span> or <span class="he">יַעֲ</span>
* But (good news!), Hiphil has $V_S = \hat I$ which never reduces, so this is how we can distinguish
* All others:<span class="he">יַעֲמִיד</span>
    * <span class="he">יַעֲמִיד</span> is HI3ms because $V_S = \hat I$, which is diagnostic of Hiphil
    * <span class="he">יַעֲמֹד</span> is QI3ms because $V_S = O$, which is diagnostic of Qal Imperfect

::: {.box .caution}
AMBIGUITIES

1G verbs that are also 3ה lose the stem vowel and are ambiguous   
<span class="he">יַעֲלֶה</span> - (Q/H)I3ms

:::

## 2-Guttural

* No changes
* 2G reject Dagesh Forte, but this is not applicable for Hiphil<small>^[<small>Potentially, we could have a verb that is both 1נ and 2G.  We would think the Nun with $V_1 = \ :$ would assimilate into a Dagesh Forte that is ultimately rejected. In our vocab, we only have one such verb: נחם (to be sorry, regret).  What ends up happening is the ח's rejection of the Dagesh causes Compensatory Lengthening in $V_1$ of the נ.  Since the נ only assimilates when it has a Sheva, the Nun no longer wants assimilate.  The end result is that all three root letters of נחם are visible with the Hiphil $Pre$ and $V_S$ intact.</small>]</small>
* 2G rejects Vocal Sheva but the $V_S = \hat I$ will never reduce to a Sheva

## 3א and 3עח

* 3-Guttural can tweak the $V_S$, so we can't use $V_S$ for parsing
* Parse based on the word's $Pre$ sequence
* With 3עח, $V_S = A$
    * The Furtive Patach is hit or miss, but we can ignore it<small>^[<small>There is logic.  It appears if the 3עח is word-final and $V_2 \not = A \ or \ \bar A$</small>]</small>
    * $V_S = A$ for FP Imperfect and Imperative with 3עח
* With 3א, the א usually quiesces
    * The sufformative will lose its Dagesh Lene
    * The $V_S$ often switches, so we do not rely on it for parsing

## 3ה

* The usual changes
* If no sufformative, add final vowel letter (see table below)
* If sufformative begins with a vowel, that sufformative replaces $V_2$
* If sufformative begins with a consonant, add the applicable (vowel)+Yod

| Conj | Hebrew | Vowel when no sufformative
| :- | :- | :-
| P | <span class="he">בָּנָה</span> | Qamets+Hei
| I | <span class="he">יִבְנֶה</span> | Seghol+Hei
| M | <span class="he">בְּנֵה</span> | Tsere+Hei
| ∞ | <span class="he">בְּנוֹת</span> | Holem+Vav Tav
| A | <span class="he">בָנֹה</span> or <span class="he">בָנוֹ</span> | Holem+Hei or Holem+Vav
| Pt | <span class="he">בֹּנֶה</span> | Seghol+Hei


## 1נ always assimilates in Hiphil

* Always $V_1 = \ :$ in Hiphil
* When $R_1 =$ נ, and $V_1 = \ :$, the נ will always assimilate
* Therefore, 1נ always assimilates in Hiphil

::: {.box .caution}
POTENTIAL LOOK-ALIKES

Need to watch $R_1$ vs $R_2$ to avoid confusion with Niphil<small>^[<small>Dr. Beckman also notes a potential for ambiguity if a 1נ and a 1ה verb shared the same $R_2$ and $R_3$.  When you saw the ּ הַ , you would not know whether you are looking at the ה of the Hiphil prefix with an assimilated Nun or the first ה of a Piel verb.  In our first year Hebrew course, we do not have any vocabulary verbs where this potential could occur, so we will save this discussion for Intermediate Hebrew.</small>]</small>

    * <span class="he">הִצִּילוּ</span> is Hiphil with 1נ assimilated
    * <span class="he">הִנָּצְלוּ</span> is Niphal with נ prefix assimilated

:::

## 1י 

* 1י were originally 1ו
* In the Hiphil, 1י becomes $V_P = \hat O \ or \ O$:
    * <span class="he">הוֹשִׁיב</span>
    * <span class="he">יוֹשִׁיט</span>
    * <span class="he">הוֹשֵׁב</span>

::: {.box .caution}
POTENTIAL LOOK-ALIKES

* QPtms (Strong): <span class="he">קֹטֵל</span>
* DP3ms (2G): <span class="he">בֹּרַךְ</span>
* HP3ms (1י): <span class="he">הֹדִיע</span>

The $\hat O$ may be written defectively or plene in any of the above forms  
:::

## Biconsonantal Hiphil

* Biconsonantal verbs tweak $V_P$ so we can't rely on it
* Good news: $V_S = \hat I$, except in FP imperfect and FP imperative, where $V_S = \bar E$
    * Contrast this aspect with other stems where $V_S =$ the lexical vowel

::: {.box .caution}
POTENTIAL LOOK-ALIKES

* $V_P = ə$ could be either Piel non-Perfect or Hiphil Biconsonantal
* $V_P = \bar A$ could be either Hiphil Imperfect Biconsonantal or Qal Imperfect Biconsonantal
    * In Hiphil, $V_S = \hat I$
    * Only verbs where the lexical vowel is also $\hat I$ are ambiguous
    * <span class="he">יָשִֹים</span> could either be QI3ms or HI3ms
:::

## Top 10 Hiphil Verbs

1. <span class="he">בּוֺא</span> - (Q) to go in, enter, come to; (H) bring (in), come (in) (557x in the Hiphil)
1. <span class="he">נָכָה</span> - (H) to strike, smite, beat, strike dead, destroy, injure (482x)
1. <span class="he">שׁוּב</span> - (Q) to turn back, return, go back; (H) cause to return, bring back, give back (364x)
1. <span class="he">נָגַד</span> - (H) to tell, announce, report, declare, inform (336x)
1. <span class="he">יָצָא</span> - (Q) to go (come) out, go (come) forth; (H) cause to go (come) out, bring forth (282x)
1. <span class="he">עָלָה</span> - (Q) to go up, ascend; (H) bring or lead up or out, offer up (sacrifice); (260x)
1. <span class="he">נָצַל</span> - (H) tear from, take away, deliver from (191x)
1. <span class="he">יָשַׁע</span> - (H) help, save, deliver, rescue, come to the aid of (184x)
1. <span class="he">קָרַב</span> - (Q) to approach, draw near; (H) bring (near), present, offer a sacrifice (177x)
1. <span class="he">יָלַד</span> - (Q) to bear (children), give birth, beget; (H) beget, become the father of (176x)


## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/1R3dK5gr8pA" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/1R3dK5gr8pA){target="_blank"}



## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/Y7p9lMZ79FY" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/Y7p9lMZ79FY){target="_blank"}



## Ruth Pursuit {-}        

:::  {.box .map}
YOUR QUEST

Identify, parse, and translate the five Hiphil Verbs in Ruth 1.

Make sure you can identify the diagnostic indicators of these Hiphil verbs.

:::

* [Blank copy of Ruth 1](https://docs.google.com/document/d/1bcT1J-fcVmD1Zn5Jk2nj0560tEddcgtbYZLkwaVVuyE/copy){target="_blank"}
* [Ruth Pursuit Answer Key #31](./images/31_Ruth_Pursuit_KEY.pdf){target="_blank"}


## Claim your next Twelve Tribes Badge! {-}

<!-- Lesson 31 Tribe Badge 11 = SIMEON -->

Once you have completed all activities through this lesson, fill out the form below to receive your next `12 Tribes Badge`.

<div class="containerLtr">
<iframe class="responsive-iframe" src="https://forms.gle/gD1doxWveXuijHUF6" frameborder="0"></iframe>
</div>

## OPTIONAL _Hebrew Quest_ Study Passage: Exodus 20 {-}

::: {.box .map}
YOUR HEBREW QUEST

1. Read the passage - [Blank copy of Exodus 20](https://docs.google.com/document/d/1GSOQ432ytSqqvBEBOU2jI55cAiVWqzW9nmC-HRGWJvs/copy){target="_blank"}
2. Now re-read the passage critically, highlighting ([lexicon here](https://holylanguage.com/resources-dictionaries.php){target="_blank"} and translating (you will need to parse verbs to translate)
3.[Watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/lesson-34.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
5. How did the Ruach HaKodesh speak to you through the passage?

:::

<!--chapter:end:31-Hiphil-Weak.Rmd-->

# The Hophal Stem - Strong Verbs {.Hp-s}

Of the seven major stems, the Hophal occurs with the least frequency (396 times, roughly split between the Perfect, Imperfect, and Participle). Like the Pual, the Hophal has some distinctive characteristics making it straightforward to identify.

::: {.box .map}
<span class="he">LESSON ITINERARY<span class="he">

1. Meaning of the Hophal Stem
1. Hophal Strong paradigms
:::

::: {.box .stop}
<span class="he">EQUIPMENT CHECK<span class="he">

Before continuing, make sure you understand the meaning of the Hiphil stem

:::

## First Thought {-}

### <span class="he">וְהָ֣אֲנָשִׁ֔ים טֹבִ֥ים לָ֖נוּ מְאֹ֑ד וְלֹ֤א הָכְלַ֙מְנוּ֙ וְלֹֽא־פָקַ֣דְנוּ מְא֔וּמָה כָּל־יְמֵי֙ הִתְהַלַּ֣כְנוּ אִתָּ֔ם בִּֽהְיוֹתֵ֖נוּ בַּשָּׂדֶֽה׃</span> {-}

*Yet the men were very good to us, and we were not insulted, nor did we miss anything as long as we went about with them, while we were in the fields. (1 Samuel 25:15)*

The _Hebrew Quest_ Study Passage for this lesson is David and Goliath from 1st Samuel 17.  The passage's geographic detail reminds us that the events involved real people and real places.  This is true even though these events took place thousands of years ago and thousands of miles away. 

HaShem had these details recorded for a reason. Through our study of Hebrew, we can connect with these great stories in a more intimate way.  Praise Him for that!

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/32-8.1Samuel 25.15.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/32-Elah brook with students picking smooth stones, tbs75039303.jpg" alt="Elah brook with students picking smooth stones. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-102)Elah brook with students picking smooth stones. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>




## Meaning of the Hophal

| |Active Voice| Passive Voice | Reflexive Voice
|:- |:- |:- |:-
Simple Action	| Qal | Niphal | (Niphal)
Intensive	| Piel | Pual | Hitpael
Cause an Action	|Hiphil | __HOPHAL__

Meanings:

* Being Caused to Do Something
* Passive of Hiphil -  <span class="he">יצא</span>
    * Q - he went out
    * H - he brought out
    * Hp - he was brought out
* Sometimes passive of Qal - <span class="he">נתן</span>
    * Q - to give
    * Hp - to be given

Parsing Code: Hp (`p`assive of `H`iphil)

## Hophal Strong Parsing Clues - $Pre$: Think "Houûphal"

* Preformatives
    * Hophal verbs have preformative ה like the Hiphil
    * Imperfects and Participles have the usual preformatives
* $V_P = \ O, \ U, \ or \ \hat U $, indicates Hophal 
    * So a mnemonic for this stem might be: "<u>houûphal</u>"
    * The Hophal occurs with either u-class or o-class
    * O - Qamets Hatuf <span class="he">הָקְטַל</span>  
    * U - Qibbuts <span class="he">הֻקְטַל</span>
    * Û - Shureq 
        * <span class="he">הוּרַד</span> (Iי)
        * <span class="he">הוּשַׁט</span> (Biconsonantal)
        * <span class="he">הוּחַל</span> (Geminate)
    * HŌ or HȎ almost always HIPHIL 1-Yod
* Hophal Strong $Pre$ sequences are:
    * <span class="he">הָקְ</span> or <span class="he">הֻקְ</span> - HpP
    * <span class="he">יָקְ</span> or <span class="he">יֻקְ</span> - (etc.) HpI
    * <span class="he">מָקְ</span> or <span class="he">מֻקְ</span> - HpPt<small>^[<small>The remaining conjugations are rare in the Hebrew Bible, so we will skip them.</small>]</small>
* Given that $V_1 = ə$, we expect 1נ to assimilate (as it does in QI and NP)

::: {.box .caution}
QAMETS HATUF OR QAMETS?

* We learned many lessons ago that Qamets or Qamets Hatuf, <span class="he">ָ</span>, followed by a Sheva is potentially ambiguous
    * QAMETS followed by VOCAL Sheva _or_ QAMETS HATUF followed by SILENT Sheva?
* When $V_P$ is <span class="he">ָ</span> followed by $V_1$ of Sheva or Hateph Qamets Hatuf, $V_P$ is ALWAYS QAMETS HATUF
    * This is not necessarily the case when the positions are $V_1$ and $V_2$
* Therefore, in the Hophal Stem, <span class="he">הָקְטַל</span> is pronounced "hoq-TAL" (rhymes with "Hophal").
:::

## Hophal Strong Parsing Clues - $V_S$ = A

* P,I,M,∞ is $A$, just like the Pual stem
* Particle stem is lengthened P3ms as expected - HpP3ms uses $A$, so HpPt use $\bar A$ 
* Infinitive Absolute is $\bar E$ as expected (but there are only 6 HpA in the Bible)

## Hophal Perfect Strong

* The standard Perfect sufformatives
* $V_S = A$
* $V_P$ is variable between Qibbuts and Qamets Hatuf.  Only the O-class is listed below and in the audio. 


| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">הָקְטַל</span>  | 3cp | <span class="he">הָקְטְלוּ</span> 
| 3fs | <span class="he">הָקְטְלָה</span> | 
| 2ms | <span class="he">הָקְטַ֫לְתָּ</span> | 2mp | <span class="he">הָקְטַלְתֶּם</span>
| 2fs | <span class="he">הָקְטַלְתְּ</span> | 2fp | </span><span class="he">
| 1cs | <span class="he">הָקְטַ֫לְתִּי</span> | 1cp | <span class="he">הָקְטַ֫לְנוּ</span>

<figure>
    <figcaption>Hophal Perfect Strong from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/32-Hp-perfect-strong.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>


## Hophal Imperfect Strong

* The standard Imperfect preformatives and sufformatives
* $V_S = A$
* $V_P$ is variable between Qibbuts and Qamets Hatuf.  Only the O-class is listed below and in the audio. 

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">יָקְטַל</span>  | 3mp | <span class="he">יָקְטְלוּ</span> 
| 3fs | <span class="he">תָּקְטַל</span> | 3fp | <span class="he">תָּקְטַ֫לְנָה</span>
| 2ms | <span class="he">תָּקְטַל</span> | 2mp | <span class="he">תָּקְטְלוּ</span>
| 2fs | <span class="he">תָּקְטְלִי</span> | 2fp | <span class="he">תָּקְטַ֫לְנָה</span>
| 1cs | <span class="he">אָקְטַל</span> | 1cp | <span class="he">נָקְטַל</span>

<figure>
    <figcaption>Hophal Imperfect Strong from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/32-Hp-imperfect-strong.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>


## Hophal Participle Strong

* The standard Participle prefix (מ)
* The standard $V_S = \bar A$ - lengthening of P3ms
* The standard inflectional endings of the Participle
* Again, both Qibbuts and Qamets Hatuf are used interchangeably

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| ms | <span class="he">מָקְטָל</span> | mp | <span class="he">מָקְטָלִים</span>
| fs | <span class="he">מָקְטֶ֫לֶת</span> | fp | <span class="he">מָקְטָלוֹת</span>

### Participle Prefixes in the Derived Stems {-}

Again we present this table for review:

Stem | Prefix 
:- | :-: 
Niphal | נִ |
Piel | מְ
Pual | מְ
Hiphil | ַמ
HOPHAL (u-class) | <span class="he">מֻ</span>
HOPHAL (o-class) | ָ<span class="he">מ</span>
Hithpael | תִמְ


## Hophal Strong Summary

* Like $V_1$ in the Pual, the Hophal has a distinguishing O or U class $V_P$
* $V_S$ is almost always Patach
    * There is expected lengthening to Qamets in the Participle
    * The rare Infinitive Absolute has the expected Tsere (see `Ruth Pursuit` below)

## Stem Comparison Table

* Here is the Stem Comparison Table showing the stems we have studied thus far


<img src="images/32_stemcomp.png" width="600pt" style="display: block; margin: auto;" />

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/MdXXlMyr4Lg" frameborder="0"></iframe>
</div>


[Click to open `Word Warm-up` video in a new tab](https://youtu.be/MdXXlMyr4Lg){target="_blank"}


## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/O5CU62O94Cw" frameborder="0"></iframe>
</div>


[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/O5CU62O94Cw){target="_blank"}

## Hophal Strong Worksheet {-}

Complete this [Hophal parsing worksheet](./images/32_hophal_strong_paradigms.pdf){target="_blank"} using the concepts discussed in this lesson.  Paradigm memorization should not be necessary.

     
## Ruth Pursuit {-}

There are no Hophal verbs in Ruth 1, so there will be no `Ruth Pursuit` for Lessons 32 or 33.

* There ARE two Hophal verbs in 2:11.  Can you find them?
    * <span class="he"> וַיַּ֤עַן בֹּ֙עַז֙ וַיֹּ֣אמֶר לָ֔הּ הֻגֵּ֨ד הֻגַּ֜ד לִ֗י כֹּ֤ל אֲשֶׁר־עָשִׂית֙ אֶת־חֲמוֹתֵ֔ךְ אַחֲרֵ֖י מ֣וֹת אִישֵׁ֑ךְ וַתַּֽעַזְבִ֞י אָּבִ֣יךְ וְאִמֵּ֗ךְ וְאֶ֙רֶץ֙ מֽוֹלַדְתֵּ֔ךְ וַתֵּ֣לְכִ֔י אֶל־עַ֕ם אֲשֶׁ֥ר לֹא־יָדַ֖עַתְּ תְּמ֥וֹל שִׁלְשֽׁוֹם׃</span>
    * There are only six HpA forms in all of the Hebrew Bible (and some sources say there are only five).  One of those forms is in Ruth 2:11.  Note how $V_S$ is Tsere for the HpA verb, and how $V_S$ is Qamets in the HpP3ms verb that follows.
    * The verb root is נגד
    * The Daghesh Forte in the Gimmel represents the assimilated 1נ
* Dr. Beckman explains, "Infinitive Absolutes typically underscore the certainty of something. But in this past tense context where Boaz uses the word <span class="he">כֹּל</span>, it seems more likely that he is referring to the completeness of the report that he has received."<small>^[<small>Beckman. "Notes on Ruth" p. 27.  https://hebrewsyntax.org/bbh2new/00_Ruth_notes.pdf </small>]</small>


## Ruth Pursuit Analysis {-}

It's time for the next segment of translating Ruth.  We'll continue with "Scene 2": Ruth 1:15-19a.

::: {.box .map}
YOUR QUEST

1. Read Ruth 1:15-19a (the first וַיְהִי marks the start of 19b) in the Hebrew text and underline any words or forms do you not recognize
    * There is one Hitpael form in this passage in verse 18 that we have not yet studied
2. Using what you have learned about syntax/phrase constructions and context, provide your own interpretative translation 
3. Compare your version with translations such as JPS, KJV, ESV, NASB, NIV, or NLT.  
    * At what points do you agree and disagree with translation decisions made by these publications? 

:::




## OPTIONAL Hebrew Quest Study Passage: 1 Samuel 17 {-}


::: {.box .map}
YOUR HEBREW QUEST

1. Read the passage - [Blank copy of 1 Samuel 17](https://docs.google.com/document/d/1jX0OyJq3--vHWysXkZfXKNDCUFvOf04TalAEQInX6C8/copy){target="_blank"}
2. Now re-read the passage critically
    1. Highlight any words you do not know and look them up in a [lexicon](https://holylanguage.com/resources-dictionaries.php){target="_blank"}
    2. Parse as many verbs as you can
    3. Sketch out a translation - there is a blank line between each verse
3. Now, using your marked-up copy of the passage, watch Izzy's _Hebrew Quest_ video (video opens in a new tab)
    * [part 1](https://holylanguage.com/samuel-17.1.php){target="_blank"}
    * [part 2](https://holylanguage.com/samuel-17.2.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
    * You may wish to check your parsing and translation [here](https://scholarsgateway.com/search/WLC-ESV/1%20Samuel/17){target="_blank"}
    * Check the "verbs" box to highlight all of the verbs in the passage, then hover over each verb for parsing information
5. How did the Ruach HaKodesh speak to you through the passage?
:::



<!--chapter:end:32-Hophal_Strong.Rmd-->

# The Hophal Stem - Weak Verbs {.Hp-w}

Most of the Hopal verbs in the Bible are weak.  As with all the forms, we start with the strong verb diagnostics.  This makes it easier to understand the spelling changes that occur with weak verbs.  By now, you should be well-acquainted with the concepts discussed in this lesson.

::: {.box .map}
**LESSON ITINERARY**

1. 1G and 3ה Verbs prefer Qamets Hatuf as $V_P$
1. 1נ assimilates with $R_2$ as expected
1. Geminate/Biconsonantal Verbs prefer Shureq as $V_P$
:::

::: {.box .stop}
**EQUIPMENT CHECK**

Before continuing, be sure you can identify Hophal Perfect, Imperfect, and Participle Strong verbs

:::

## First Thought {-}

### <span class="he">נִשְׁאַ֥ר בָּעִ֖יר שַׁמָּ֑ה וּשְׁאִיָּ֖ה יֻכַּת־שָֽׁעַר׃ </span> {-}

*Desolation is left in the city; and the gate is battered to ruins. (Isaiah 24:12)*

As people of God, we are sometimes faced with situations where we are tempted to ask, "How could He let this happen?" The people of Isaiah's time who witnessed the destruction of Jerusalem indeed had similar questions. Most of the time, we can not provide a satisfactory answer. The only right choice is to relinquish any notion that we can control the situation and, like Job, trust in Him no matter what the outcome.

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/33-7.Isaiah24.12.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/33.Zion Gate from south, tb010910185.jpg" alt="Zion Gate from the south.  The pockmarks in the walls are remnants of the 1967 war to liberate the Old City.  This time, the gate was battered but held! Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-104)Zion Gate from the south.  The pockmarks in the walls are remnants of the 1967 war to liberate the Old City.  This time, the gate was battered but held! Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>






## 1G and 3ה Verbs prefer Qamets Hatuf as $V_P$

* $V_P = O$ 
* $V_1 = \breve O$ (Hateph Qamets Hatuf)
* $V_S = A$, which follows the strong paradigm



## 1נ assimilates as expected

* Since $V_1$ is a Sheva, 1נ assimilates just as it does with QI and NP
* $R_2$ will take a Daghesh Forte, if allowed
* We saw this in the `Ruth Pursuit` of Lesson 32
    * <span class="he">הֻגֵּ֨ד הֻגַּ֜ד לִ֗י</span> - "it has thoroughly been declared to me"
        * The verb root is נגד - to tell
        * The Daghesh Forte in the Gimmel represents the assimilated 1נ



## Geminate/Biconsonant prefer Shureq as $V_P$

* The medial letter of the biconsonantal verb is dropped
* Only one geminate consonant is preserved - where possible, a Daghesh Forte will appear in the remaining consonant
* The Holem+Vav as connecting vowel in some forms of the Perfect is another indicator of the geminate verb

## Top 10 Hophal Verbs

1. <span class="he">מוּת</span> - (Q) to die; (H) kill, put to death; (Hp) be killed, suffer death (69x in the Hp)
1. <span class="he">נגד</span> - (H) to tell, announce, report; (Hp) be told, be announced, be reported (35x)
1. <span class="he">בוֺא</span> - (Q) to go in, enter, come to; (H) bring (in), come (in); (Hp) be brought (24x)
1. <span class="he">שׁזר</span> - (HpPt) twisted; always spelled <span class="he"></span> (21x all in Exod 26–39)
1. <span class="he">נכה</span> - (H) to strike, smite, strike dead, destroy; (Hp) be struck down dead, be beaten (16x)
1. <span class="he">שׁלך</span> - (H) to throw (down, into or away), cast; (Hp) be thrown, be cast (13x)
1. <span class="he">יבל</span> - (H) to bring (as gift or tribute), lead; (Hp) be brought, be led (11x)
1. <span class="he">יצק</span> - (Q) to pour (out); (Hp) be cast, be poured out, be emptied out (8x)
1. <span class="he">פקד</span> - (Q)to attend, number, appoint, visit; (H) appoint, entrust; (Hp) be appointed (8x)
1. <span class="he">גלה</span> - (Q) to uncover, reveal, disclose; (H) take into exile; (Hp) be deported (7x)

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/DDh5Oy485WU" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/DDh5Oy485WU){target="_blank"}



## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/sTvLGMtaSpw" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/sTvLGMtaSpw){target="_blank"}



## OPTIONAL _Hebrew Quest_ Study Passage: Psalms 45 {-}


::: {.box .map}
YOUR HEBREW QUEST

1. Read through the passage - [Blank copy of Psalms 45](https://docs.google.com/document/d/1Wt1c4OYlK0y2EZnqczRG2U3BhTEzklbHIVg4eNyFhhs/copy){target="_blank"}
2. Now re-read the passage critically
    1. Highlight any words you do not know and look them up in a [lexicon](https://holylanguage.com/resources-dictionaries.php){target="_blank"}
    2. Parse as many verbs as you can
    3. Sketch out a translation - there is a blank line between each verse
3. Now, using your marked-up copy of the passage, [watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/psalm-45.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
    * You may wish to check your parsing [here](https://scholarsgateway.com/search/WLC-ESV/Psalms/45){target="_blank"}
    * Check the "verbs" box to highlight all of the verbs in the passage, then hover over each verb for parsing information
5. How did the Ruach HaKodesh speak to you through the passage?
6. Complete Memrise [here](https://app.memrise.com/course/5406435/hebrew-quest-lessons-1-to-40/37/garden/learn/?source_element=level_details_session&source_screen=level_details){target="_blank}.

:::

<!--chapter:end:33-Hophal_weak.Rmd-->

# The Hithpael Stem - Strong Verbs {.HT-s}


This is one of the shortest and easiest chapters in Hebrew GRAMMAR Quest.

If you've made it this far, you've earned it!

There are just under 1000 instances of the Hitpael stem:

* tDP - 161
* tDI - 491
* tDM - 78
* tD∞ - 104
* tDA - 3
* tDPt - 147


##  First Thought {-}

###  <span class="he"> וַיַּסֵּ֧ב חִזְקִיָּ֛הוּ פָּנָ֖יו אֶל־הַקִּ֑יר וַיִּתְפַּלֵּ֖ל אֶל־יְהוָֽה׃ </span> {-}

*Then Hezekiah turned his face to the wall and prayed to Adonai (Isaiah 38:2)*

Today in Jerusalem, the Western Wall is considered the holiest spot in Judaism.  It is said to be the closest spot one can get to the Holy of Holies.  While this wall was built in King Herod's time (well after Hezekiah), modern Jews and God-fearing gentiles consider it an honor to be able to follow in the tradition of Hezekiah and pray at the wall. 

Many of us may be physically removed from Jerusalem and the Western Wall.  Like Daniel who was also hundreds of miles away, we can still turn towards Jerusalem and bring our petitions to HaShem just as Hezekiah did centuries ago.  

Why don't you stop what you're doing and pray towards Jerusalem right now?

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/34-7.Isaiah38.2.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/34.Men praying at Western Wall, tb090705000.jpg" alt="Men Praying at Western Wall. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-105)Men Praying at Western Wall. Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>




## Meaning of Hitpael

| |Active Voice| Passive Voice | Reflexive Voice
|:- |:- |:- |:-
Simple Action	| Qal | Niphal | (Niphal)
Intensive	| Piel | Pual | __HITPAEL__
Cause an Action	|Hiphil | Hophal

Meanings:

* Reflexive of the Piel - <span class="he">קדשׁ</span>
    * Q - to be holy
    * D - to be sanctified
    * tD - to sanctify oneself
        * Because this is the most common use, the parsing code is tD - t because a Hitpael preformative always contains ת, and D because like the Piel, $R_2$ takes a Doubling Daghesh Forte (if possible)
* Reciprocal - <span class="he">ראה</span>
    * Q - to see
    * tD - to look at one another
* Iterative - <span class="he">הלך</span>
    * Q - to walk
    * tD - to walk back and forth, or to walk (as a way of life)
* Simple active - <span class="he">פלל</span>
    * tD - to pray

## Parsing Clues - _Pre_: a distinctive "_h_IT" prefix

The Hitpael is probably the easiest stem to identify:

* All conjugations have a distinctive prefix:
    * <span class="he">הִתְקַטֶּל</span> - tDP3ms, tDM2ms, tD∞, or tDA
    * <span class="he">יִתְקַטֶּל</span> - tDI3ms, and so forth for the remaining imperfect stems. 
        * tDI1cs preformative is <span class="he">אֶתְ</span>
    * <span class="he">מִתְקַטֶּל</span> - tDPtms
    * The preformative always has <span class="he"> תְ ִ </span> (except for I1cs)
        * So, if a verb begins with "hIT", "yIT", "mIT", etc., (and $R_1$ is not ת or ט) it's probably Hitpael
        
Also:

* $R_2$ takes Daghesh Forte
* $V_1$ is Patach


## Parsing Clues - $V_S = \bar E[A] \sim \bar E$



* tDP2ms and tDP1cs have $V_S = A$, otherwise it's very consistent

::: {.box .light}
The preformative alone is sufficient to identify the Hitpael stem  
:::

## Perfect Strong

* The standard Perfect sufformatives
* $V_S =$ Patach
* "Signature" tD Prefix: <span class="he">הִתְ</span>

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">הִתְקַטֵּל</span>  | 3cp | <span class="he"> הִתְקַטְּלוּ</span
| 3fs | <span class="he">הִתְקַטְּלָה</span> | |
| 2ms | <span class="he">הִתְקַטַּ֫לְתָּ</span> | 2ms | <span class="he">הִתְקַטַּלְתֶּם</span>
| 2fs | <span class="he">הִתְקַטַּלְתְּ</span> | 2fs | <span class="he">הִתְקַטַּלְתֶּן</span>
| 1cs | <span class="he">הִתְקַטַּ֫לְתִּי</span> | 1cs | <span class="he">הִתְקַטַּ֫לְנוּ</span>

<figure>
    <figcaption>Hitpael Perfect Strong from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/34-tD-perfect-strong.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>


## Imperfect Strong

* The standard Imperfect preformatives and sufformatives
* $V_S =$ Patach
* "Signature" tD Prefix: <span class="he">יִתְ</span> (or the applicable Imperfect preformative)

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 3ms | <span class="he">יִתְקַטֵּל</span>  | 3mp | <span class="he"> יִתְקַטְּלוּ</span>
| 3fs | <span class="he">תִּתְקַטֵּל</span> | 3fp | <span class="he">תִּתְקַטֵּ֫לְנָה</span>
| 2ms | <span class="he">תִּתְקַטֵּל</span> | 2mp | <span class="he">תִּתְקַטְּלוּ</span>
| 2fs | <span class="he">תִּתְקַטְּלִי</span> | 2fp | <span class="he">תִּתְקַטֵּ֫לְנָה</span>
| 1cs | <span class="he">אֶתְקַטֵּל</span> | 1cp | <span class="he">נִתְקַטֵּל</span>

* Note the standard Imperfect preformatives followed by a תְ

<figure>
    <figcaption>Hitpael Imperfect Strong from _Hebrew Quest_ Chapter 15</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/34-tD-imperfect-strong.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>

## Imperative Strong

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| 2ms | <span class="he">הִתְקַטֵּל</span> | 2mp | <span class="he">הִתְקַטְּלוּ</span>
| 2fs | <span class="he">הִתְקַטְּלִי</span> | 2fp | <span class="he">הִתְקַטֵּ֫לְנָה</span>

## Infinitives Strong


| Type | Paradigm 
| :-  | :- 
| ∞ | <span class="he">הִתְקַטֵּל</span>  
| A | <span class="he">הִתְקַטֵּל</span>

Although these forms are identical to tDP3ms and tDM2ms, the infinitive forms are infrequent.  The tDA only appears three times in the Hebrew Bible.

## Participle Strong

| Sing | Paradigm | Plural | Paradigm
| :-  | :- | :-  | :-
| ms | <span class="he">מִתְקַטֵּל</span> | ms | <span class="he">מִתְקַטְּלִים</span>
| fs | <span class="he">מִתְקַטֶּ֫לֶת</span> | fs | <span class="he">מִתְקַטְּלוֹת</span>

Note the <span class="he">מִתְ </span> prefix in every form, with the characteristic מ of the Participle.

### Participle Prefixes in the Derived Stems {-}

We are now able to complete this table.

Stem | Prefix 
:- | :-: 
Niphal | נִ |
Piel | מְ
Pual | מְ
Hiphil | ַמ
Hophal (u-class) | מֻ
Hophal (o-class) | ָמ
HITPAEL | <span class="he">תִמְ</span>


## Stem Comparison Table

* Here is the complete Stem Comparison Table listing $Pre$ and $V_S$ for each stem and the three major conjugations:

<img src="images/34_stemcomp.png" width="600pt" style="display: block; margin: auto;" />

## Word Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/U7bGSrESfco" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/U7bGSrESfco){target="_blank"}



## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/unjNAqluDpk" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/unjNAqluDpk){target="_blank"}

## Hitpael Parsing Worksheet {-}

If you desire additional paradigm practice, you may use this [Hitpael parsing worksheet](./images/34_hithpael_strong_paradigms.pdf){target="_blank"}

## Ruth Pursuit Analysis

It's time for the Final segment of translating Ruth.  We'll move on to "Scene 3" which concludes "Act 1": Ruth 1:19b-22

::: {.box .map}
YOUR QUEST

1. Read Ruth 1:19b-22 (the first וַיְהִי marks the start of 19b) in the Hebrew text and underline any words or forms do you not recognize
2. Using what you have learned about syntax/phrase constructions and context, provide your own interpretative translation 
3. Compare your version with translations such as JPS, KJV, ESV, NASB, NIV, or NLT.  
    * At what points do you agree and disagree with translation decisions made by these publications? 

:::


## Claim your next `Twelve Tribes Badge`! {-}

<!-- Lesson 34 Tribe Badge 12 = ZEBULUN -->

Once you have completed <span class="he">all activities<span class="he"> through this lesson, fill out the form below, and receive your next badge!

<div class="containerLtr">
<iframe class="responsive-iframe" src="https://forms.gle/ejQEQDRGZJT1v8jE6" frameborder="0"></iframe>
</div>


## OPTIONAL _Hebrew Quest_ Study Passage: Leviticus 23 {-}


::: {.box .map}
YOUR HEBREW QUEST

1. Read through the passage - [Blank copy of Leviticus 23](https://docs.google.com/document/d/1QlmWYqkD6NNOM0VcJCrJbB_ntpuXnoCCdpqJ0m6xcqU/copy){target="_blank"}
2. Now re-read the passage critically
    1. Highlight any words you do not know and look them up in a [lexicon](https://holylanguage.com/resources-dictionaries.php){target="_blank"}
    2. Parse as many verbs as you can
    3. Sketch out a translation - there is a blank line between each verse
3. Now, using your marked-up copy of the passage, [watch Izzy's _Hebrew Quest_ video (video opens in a new tab)]
    * [Part 1](https://holylanguage.com/leviticus-23.1.php){target="_blank"}
    * [Part 2](https://holylanguage.com/leviticus-23.2.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
    * You may wish to check your parsing and translation [here](https://scholarsgateway.com/search/WLC-ESV/1%20Samuel/17){target="_blank"}
    * Check the "verbs" box to highlight all of the verbs in the passage, then hover over each verb for parsing information
5. How did the Ruach HaKodesh speak to you through the passage?
6. Complete the passage memorization in Memrise [here](https://app.memrise.com/course/5406435/hebrew-quest-lessons-1-to-40/38/garden/learn/?source_element=level_details_session&source_screen=level_details){target="_blank}.

:::

<!--chapter:end:34-Hitpael_Strong.Rmd-->

# The Hitpael Stem - Weak Verbs {.Ht-w}

> CONGRATULATIONS ON REACHING THE FINAL CHAPTER OF HEBREW GRAMMAR QUEST!

In this lesson, we will briefly look at the spelling changes of the Hitpael weak verbs, a minor stem called the Hitpolel, and a second minor stem called Hishtapel that only has one word (but it's a very important word).

::: {.box .map}
**LESSON ITINERARY**

1. Understand fundamental spelling changes in the Hitpael stem
1. Describe the Hitpolel minor stem
1. Identify the Hishtapel minor stem in the Bible
:::

::: {.box .stop}
**EQUIPMENT CHECK**

Before continuing, be sure you can identify the Hitpael preformatives in all conjugations.

:::

## First Thought {-}

###  <span class="he">וְנָמַ֤סּוּ הֶֽהָרִים֙ תַּחְתָּ֔יו וְהָעֲמָקִ֖ים יִתְבַּקָּ֑עוּ כַּדּוֹנַג֙ מִפְּנֵ֣י הָאֵ֔שׁ כְּמַ֖יִם מֻגָּרִ֥ים בְּמוֹרָֽד׃ </span> {-}

*The mountains will melt under Him, and the valleys will be split, like wax before the fire (Micah 1:4)*

Our prayer at Holy Language Institute is that you have drawn closer to HaShem through Hebrew, His Holy Language.  We are extremely proud of you and excited that you have completed the course.  With that said, we know that, unless checked by the Spirit, we have an all-too-human tendency to boast in our success.  Let us give glory to Him who alone has the power to call down fire from heaven!

The Hebrew Quest Study Passage for this Lesson is Elijah's story on Mount Carmel in 1 Kings 18. HaShem did precisely that. May we always be reminded that we do all things through Yeshua, who gives us strength.

<figure>
    <figcaption>Listen to the verse in Hebrew:</figcaption>
    <audio
        controls controlsList="nodownload"
        src="./images/35-4.Micah1.4.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>




<div class="figure" style="text-align: center">
<img src="images/35.Muhraqa statue of Elijah on Mount Carmel, tb011400103.jpg" alt="Muhraqa statue of Elijah on Mount Carmel (1 Kings 18). Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-107)Muhraqa statue of Elijah on Mount Carmel (1 Kings 18). Courtesy of the [Pictorial Library of Bible Lands](https://www.bibleplaces.com)</p>
</div>




## $R_2$ can lose Daghesh Forte

* By now, you are very familiar with this concept
* The Hitpael verb MAY lose if  $R_2$ is SQiN eM LeVY consonant with a Sheva
* The Hitpael verb WILL lose if $R_2$ is Guttural or Resh
    * With ע, ה,  and ח there is usually no compensatory lengthening
    * With א and ר $V_1$ will lengthen from Patach to Qamets
        * <span>הִתְבָּרֵךְ</span> tDP3ms of ברך, "he blessed himself"


## Transposition of ת and $R_1$ when $R_1$ is sibilant

* The sibilants are the same letters as the "S" SQiN eM LeVY letters
* The ancients found it easier to pronounce <span>הִשְׁתַּמֵּר</span>* instead of <span class="he">הִתְשַׁמֵּר</span>
    * English has this too: we find it more "comfterble" to pronounce "comfortable" as "comfterble" - we transpose the "r" and "t"
    * Hebrew transposes the "ת" of the Hitpael preformative with the s-sound of $R_1$
* This can be an initial challenge since the <span class="he">ְ הִ</span> looks like Hiphil
    * If you think the root is שׁתם, then you have a stray ר that doesn't fit anywhere
    * Four-letter roots do exist but are exceptionally rare in the Hebrew bible - there is no root = שׁתמר
* The vowels of the Hitpael strong are the same
* Examples:
    * <span class="he">הִסְתַּתֵּר</span> - he hid himself
    * <span class="he">הִשְׂתַּכֵּר</span> - he earned wages for (hired) himself<small>^[<small>BBH mentions that there are three times n the Bible when $R_1$ = <span class="he">צ</span>, not only will the <span class="he">ת</span> switch places, it will change to <span class="he">ט</span>.</small>]</small>


## Preformative תְ assimilates when $R_1$ is ז ד ט ת,

* If $R_1$ is ז ד ט ת (i.e., the "dental" letters) the ת of the Hithpael preformative will assimilate into $R_1$ and remain as a Daghesh Forte
* This can present a potential ambiguity with Niphal; however, note $V_1$ is _QAMETS_ in Niphal compared to _PATACH_ in Hitpael, and $R_2$ will have a Daghesh Forte in Hitpael:
    * <span class="he">הִדַּבֵּר</span> - tDP3ms
    * <span class="he">הִדָּבֵר</span> -NM2ms 



## Hitpolel is tD of some Biconsonantal and Geminate Verbs

* $R_3$ is doubled
* $V_1$ is <span class="he">וֹ</span>
* This is an irregular form, but these words maintain diagnostic Hitpael preformative       
    * <span class="he">הִתְרוּמֵם</span> - Hitpolel (P3ms/M2ms/∞/A), רוּם
    * <span class="he">יִתְרוֹמֵם</span> - Hitpolel I3ms, רוּם
* Same meaning as a normal Hitpael


## <span class="he">חָוָה </span> - Hishtapel Stem

*  <span class="he">חָוָה </span> gets its own stem: Hishtapel
*  <span class="he">חָוָה </span> occurs 173 times in the Bible, only in Hishtapel
*  <span class="he">חוה</span> means: to prostrate oneself in worship (as to God, or another deity) or submission (as to a king)

* Since <span class="he">חָוָה </span> is a 3ה verb, it will consistently exhibit the distinctive 3ה endings
    * <span class="he">הִשְׁתַּחֲוָה</span> - HstP3ms - he worshipped
    * <span class="he">תִּשְׁתַּחֲוֶה</span> - HstI2ms - you will worship
    * <span class="he">הִשְׁתַּחֲווּ</span> - HstM2mp/HstP3mp - (you all) worship!/they worshipped
    * <span class="he">הִשְׁתַּחֲוֹת</span> - Hst∞ - to worship, to bow down
    * <span class="he">מִשְׁתַּחֲוֶה</span> - HstPtms - worshiping, bowing down
    
* Bible Examples:
    * <span class="he">וְהִשְׁתַּחֲו֧וּ לַיהוָ֛ה</span>  - (and) they will worship Adonai (Isa 27:13)
    * <span class="he">וַיִּשְׁתַּחוּ אַבְרָהָם לִפְנֵי עַם הָאָרֶץ</span> - (and) Abraham bowed down before the people of the land (Gen 23:12)
    * <span class="he">וְנִשְׁתַּחֲוֶה וְנָשׁוּבָה אֲלֵיכֶם</span> - (and) we will worship, and we will return to you (Gen 22:5)


## Top 10 Hitpael Verbs

1. <span class="he">פלל</span> - (tD) to pray, make intercession (80x in the tD)
2. <span class="he">הלך</span> - (Q) to go, walk; (tD) walk about, move to and fro (64x)
3. <span class="he">יצב</span> - (tD) to take one’s stand, stand firm, station oneself, resist (48x)
4. <span class="he">נבא</span> - (tD) speak or behave as a prophet, be in a state of prophetic ecstasy (28x)
5. <span class="he">חזק</span> - (Q) to be strong, have courage; (tD) strengthen oneself (27x)
6. <span class="he">קדש</span> - (Q) to be holy, set apart or consecrated; (tD) show or keep oneself holy (24x)
7. <span class="he">הלל</span> - (D) to praise, sing hallelujah; (tD) boast (23x)
8. <span class="he">טהר</span> - (Q) to be clean, be pure; (tD) purify or cleanse oneself (20x)
9. <span class="he">יחשֹ</span> - (tD) to be enrolled in a genealogical list; (tD∞ as noun) genealogy (20x)
10 <span class="he">אבל</span> - (Q) to mourn, lament; (tD) observe mourning rites (19x)



## Word Warm-up {-}


<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/lCKxr4BLfmM" frameborder="0"></iframe>
</div>

[Click to open `Word Warm-up` video in a new tab](https://youtu.be/lCKxr4BLfmM){target="_blank"}


## Verses Warm-up {-}

<div class="container">
<iframe class="responsive-iframe" src="https://youtube.com/embed/G7286j0gy80" frameborder="0"></iframe>
</div>

[Click to open `Verses Warm-up` video in a new tab](https://youtu.be/G7286j0gy80){target="_blank"}



## Ruth Pursuit {-}        

::: {.box .map}
YOUR QUEST

Identify the lone Hitpael verb in Ruth 1.  In fact, there are no other Hitpael verbs in the remainder of Ruth.
:::

* [Blank copy of Ruth 1](https://docs.google.com/document/d/1bcT1J-fcVmD1Zn5Jk2nj0560tEddcgtbYZLkwaVVuyE/copy){target="_blank"}
* [Ruth Pursuit Answer Key #35](./images/35_Ruth_Pursuit_KEY.pdf){target="_blank"}


## You did it!  Claim your Diploma! {-}

Once all Anki cards are `Mature`, please complete the attached form to begin the Graduation process and earn your Hebrew GRAMMAR Quest Diploma!      

<div class="containerLet">
<iframe class ="responsive-iframe" src="https://forms.gle/eyX82mzkCjoh9oM56" frameborder="0"></iframe>
</div>
## OPTIONAL _Hebrew Quest_ Study Passage: 1 Kings 18 {-}


::: {.box .map}
YOUR HEBREW QUEST

1. Read through the passage - [Blank copy of 1 Kings 18](https://docs.google.com/document/d/1YmsEP2tiOf2qtI3xSM_HJ0sgTYUtV8Up86UIFotRtNY/copy){target="_blank"}
2. Now re-read the passage critically
    1. Highlight any words you do not know and look them up in a [lexicon](https://holylanguage.com/resources-dictionaries.php){target="_blank"}
    2. Parse as many verbs as you can
    3. Sketch out a translation - there is a blank line between each verse
3. Now, using your marked-up copy of the passage, [watch Izzy's _Hebrew Quest_ video (video opens in a new tab)](https://holylanguage.com/kings-18.php){target="_blank"}
4. After the video, assess your translation.  How close was it?
    * You may wish to check your parsing and translation [here](https://scholarsgateway.com/search/WLC-ESV/1%20Samuel/17){target="_blank"}
    * Check the "verbs" box to highlight all of the verbs in the passage, then hover over each verb for parsing information
5. How did the Ruach HaKodesh speak to you through the passage?
6. Complete the passage memorization in Memrise [here](https://app.memrise.com/course/5406435/hebrew-quest-lessons-1-to-40/40/garden/learn/?source_element=level_details_session&source_screen=level_details){target="_blank}.

:::

<!--chapter:end:35-Hitpael_Weak.Rmd-->

# Conclusion {-}

We would like to take a moment and recap all that you have accomplished in His strength.  Each section will also have tips and references on where you can go next.

* Vocabulary
    * What you have accomplished: 570 of the most common Biblical Hebrew words committed to memory!
    * Where you can go next: Continue to grow your vocabulary, both by isolated word memorization, such as by learning the top 1000 (or more) Biblical Hebrew words and, of course, by continuing to read your Hebrew Bible.  For word memorization, there are modules on Memrise and Anki that are free (these are not affiliated with Holy Language Institute)
* Bible Verses
    * _What you have accomplished_:
    * _Where you can go next_:
* Hebrew Quest Study Passages (optional track)
    * _What you have accomplished_: You have studied 20 distinct passages, most of which were full chapters of the Hebrew Bible or passages from the Delitsch Hebrew New Testament.  You have also completed the 17-lesson "Premium Proverbs" study.
    * _Where you can go next_:
        * Complete _Hebrew Quest_ if you have not already done so!
        * After _Hebrew Quest_, review Izzy's [Hebrew Verses](https://holylanguage.com/verses.html) studies.  Hebrew Verses picks up where Hebrew Quest left off.
* Ruth
    * _What you have accomplished_: You have skimmed, if not read entirely through, Ruth Chapter one at least 35 times and written your own translations.
    * _Where you can go next_: INTERMEDIATE HEBREW!
        * You can review [Dr. Beckman's Notes on Ruth](./images/00_Ruth_notes.pdf){target="_blank"}
    * We can recommend two Intermediate Hebrew books:
        * [A Workbook for Intermediate Hebrew](https://www.amazon.com/gp/product/0825423902/&tag=holylanginst-20){target="_blank"}, by Robert B. Chisholm, Jr., which contains a verse by verse expositional grammar study through the books of Ruth and Jonah
        * The same author has [From Exegesis to Exposition: A Practical Guide to Using Biblical Hebrew](https://www.amazon.com/gp/product/B009UOG4N4/&tag=holylanginst-20){target="_blank"}




**Next steps**: Continue with Intermediate Hebrew!





<!--chapter:end:36-Conclusion.Rmd-->

# (APPENDIX) Appendices {-} 

<!--chapter:end:40-Appendices.Rmd-->

# Hebrew Lexicon 

<img src="images/lexicon.jpg" width="600pt" style="display: block; margin: auto;" />
The authors of <u>Basics of Biblical Hebrew</u> have created an abridged Lexicon to accompany this course.  This document is beneficial       as vocabulary words are indexed to the Lesson #, and irregular plural forms and selected construct forms are also included.

[Open/download BBH Lexicon](./images/BBH_Lexicon.pdf){target="_blank"}

You are also encouraged to check out the Lexicon resources in the [Holy Language Heritage Library](https://holylanguage.com/resources-dictionaries.php){target="_blank"}.  They are much more exhaustive.  

<!--chapter:end:57-Lexicon.Rmd-->

# (PART\*) About us and this book {-}

# About Holy Language Institute {-}

<img src="images/following_yeshua.jpg" width="500pt" style="display: block; margin: auto;" />

***Jesus is Jewish.*** 

What if you could get closer to him through Hebrew?

Read on to see what "Following Yeshua, in a Hebrew way, together" means to us.

## Following Yeshua {-}

When the first disciples heard "follow me", they understood they were being invited into a relationship with this Rabbi from Nazareth. Through this journey of discipleship, they would become like him and go on to change the world with him. They knew that following Yeshua was all about knowing Yeshua. That's what our learning experiences are all about.

## In a Hebrew Way {-}

The disciples of Jesus joined him in reading the Hebrew Bible and praying the Hebrew prayers. That's why this isn't just a language - it's a way of following in the footsteps of the Master, a way of encountering the King of the Jews through the language of his people. 

## Together {-}

The men and women who followed Yeshua became a safe and loving community.  Same with us! As an organization, we're Holy Language "Institute".  As a community of disciples, we're the Holy Language "Tribe".  Together we're a movement, making disciples and changing the world.

***LEARN MORE:***

[Email sign-up](https://holylanguage.com/index.html)

[Become a member](https://holylanguage.com/subscribe.html) to access the full Hebrew GRAMMAR Quest course, as well as our complete library of teaching materials.

<!--chapter:end:60-About_HLI.Rmd-->

# About the designer of this book {-}

* Chris Flanagan has been a member of HLI since 2013 and joined as a ministry volunteer in 2015.
* He has completed Hebrew Quest as a student, which planted a desire to dig deeper into the original languages. He has completed both Hebrew and Greek courses at the seminary level.
* He has worked on several projects for HLI from an instructional design standpoint, including leading of "Hebrew Quest Memrise" and now "Hebrew Grammar Quest"
    * This work is simply a compilation of many various first-year Hebrew resources, which he has knitted together to present in an original and engaging format
    * For this reason, he likes to refer to himself as the "designer" or "compiler" of this dynamic Hebrew learning tool and not the "author" of a static book
* Professionally, Chris has worked in the healthcare compliance field for over 30 years
* Personally, Chris is married and has two men in college.  He and his wife, Sarah, love to travel, especially to Israel; (which, as you can tell, has inspired the format of each lesson in this book)

<div class="figure" style="text-align: center">
<img src="images/cf.jpg" alt="Chris Flanagan" width="400pt" />
<p class="caption">(\#fig:unnamed-chunk-110)Chris Flanagan</p>
</div>
## References {-}

<!--chapter:end:65-abouttheauthor.Rmd-->


# References {-}


<!--chapter:end:99-References.Rmd-->

