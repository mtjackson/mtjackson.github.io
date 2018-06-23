---
layout: post
title:      "Bestsellers Scraping Gem "
date:       2018-06-23 13:37:23 +0000
permalink:  bestsellers_scraping_gem
---


I was terrified by the prospect of blank slate. No tests that would tell me exactly what was wrong and what my program *should*  be doing; No empty methods to flesh out with code.  Building something from scratch that, ideally, would relate to something I cared about.

This was challenging for a couple of reasons. One, I was starting completely from scratch, including deciding what I wanted it to do. Now that I've finished it, I have a lot of ideas of things that I could have made it do, but when faced with the prospect of a blank slate, my mind blanked. *How was I supposed to pick one website from the entire internet to scrape?*

Two, I had to determine (with out a step by step guide via tests) *how* my application would opperate and prioritize features. So much freedom!

Three, it was a demonstration of my own comprehension of the concepts I've learned so far, with no safety nets. *I've felt comfortable with my progress*, so I suppose there was an element of imposter syndrome at play.

Ultimately, I overcame the first challenge (what would it do) while shopping for toilet paper. I needed to add at least $5 to my cart to get free shipping, so I did what I always do and picked out a book from my running list. While clicking through product pages and reviews reminding myself why I had been interested in the book in the first place, it occured to me *this is something I do all the time*. How nice it would be to just have the information I'm looking for laid out in front of me without having to load and reload pages? (answer: very nice)

**Functionalities**

This CLI app scrapes the top five bestselling books in fiction and nonfiction from the New York Times list and then (optionally) returns more details on a given book from its IndieBound profile. Once starting up the application, the user is prompted to select a genre (fiction / nonfiction), at which point it will return the top five bestsellers in that genre, including the title, author, and a brief one line description. The user will then have the option to ask for more information on a specific book in the list, at which point they would receive the publication details, a lengthier synoposis, and a blurb about the author (if available). Then the user can navigate back to the begining and select another book from the list, or see the books in the other genre.

**Other Functionalities I Didn't Include**

There are many, many data points I could have pulled from, and for practical reasons (and them not being high priority for me) I scrapped the ideas. One was pulling the overall rating from IndieBound, which a) wasn't especially important to be to begin with because I'm more interested in what specific people are saying about a book, not the aggregate and b) ended up being more difficult than I anticipated because that data was stored in an iframe. I played around with it for a while before opting to move on and focus my energy on fixing exisiting bugs in the way my easy-to-scrape data was collected.

I also debated letting the user pull a given author's bibliography and see more information on those books, but a) that started to get beyond the very basic functionalities I was hoping for and b) that information by itself wasn't especially valuable to me unless I was familiar with the books already. Since I was not including ratings or reviews, I scrapped that as a possibility as well.

I also didn't include a "where to by" option. I toyed with the idea of including a functionality to pull information on local bookstores (contact information, address, hours of operation), but that in itself could have been it's own app and I thought I was straying too far from the initial progress.

**What I'd Have Loved**

In the process of building *this* application, it's given me an opportunity to think strategically of what functionalities I'd like in "Mary's perfect book app." The goal of this app would be to tell me the book I should consider reading next, based on new releases, my preferences, and a few other factors.  Similar things already exist in http://whatshouldireadnext.com/ and https://www.goodreads.com/, but I'm *my* dream world, after working its magic and getting to the top choice, it'd just automatically purchase and send to me, removing the possibility of agonizing over it.

The concept itself has an inherent flaw, however, because I (and I imagine other people, though I haven't done any research into this) actively enjoy reading about books through multiple sources before making purchases. I'm also skeptical of an application's ability to make these decisions for me and it's a bit lazy for me. Maybe it could start by telling me it's top five recommendations and I could have an option to automate the purchases. Or maybe I could just add books to a list on an ongoing basis (as I already do with my Amazon wishlists) and it would automatically select one to purchase every month (a book of the month club tailored specifically to me). 

**Conclusion**

Anyway, I did finally select a book (which ended up not being on my original "to read" list). Is this app the most practical way to collect the information I look for? Not really. There are so many unconnected factors that influence book buying purchases, including recommendations from trusted sources, what kind of read you're looking for, what else the author has published, and taste. It's hard to objectively say "this is a book I should read and will enjoy reading now."

![](https://images-na.ssl-images-amazon.com/images/I/41wP7sR5mBL.jpg)
*[Less](https://www.amazon.com/Less-Winner-Pulitzer-Prize-Novel/dp/0316316121) by Andrew Sean Greer*
