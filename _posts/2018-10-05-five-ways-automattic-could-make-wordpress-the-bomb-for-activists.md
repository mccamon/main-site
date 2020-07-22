---

title: "Five Ways Automattic Could Make WordPress the Bomb for Activists"
date: "2018-10-05"
author: Mike
image: /assets/post-images/protest.jpg

---

Every movement needs an online presence. A place to tell their story, their action plan, and how to connect and organize around the cause. Historically, the online world provided a safe haven to do all this, and recruit new supporters to your work. **But that all changed.** Activists are not technologists and without changes we’re in deep trouble.

<!-- more -->

Generally what we all do online in the US is governed and protected by the First Amendment. Just a few weeks ago the US Justice Department requested Dreamhost, an internet website hosting company, release “all records and information” relating to the site disruptj20.org and more specifically the IP addresses of those who visited the site. For those less technical, that would be like the Justice Department requiring Target to supply the CC# of every person who walked into the store even if they didn’t buy anything. At its most innocent, it’s a witch hunt. At its more sinister, its something out of the sci-fi movie Minority Report where police can arrest you before you even commit a crime.

WordPress is used by 29% of all websites online. My guess is a fair number of those sites are used by activists. This means Automattic, the company behind WordPress.com and the WordPress codebase, could make five simple changes that would make WordPress the bomb for activists online.

**1\. Never, ever keep log files.** One reason why the Justice Department can get so many juicy facts about visitors, etc is virtually every website on the web maintains, and saves log files. Think of it as list of every visitor, page visited, admin login, and on and on - all timestamped with the web location you were at when you connected, what browser you use, your screen size and so forth. I can’t speak for Automattic, but most places don’t have a tidy log file management policy meaning quite often log files are kept into perpetuity. Log files are handy for troubleshooting errors, but maybe the WordPress Admin could expose a setting on how long to keep log files - something like never, hourly, daily, monthly, etc.

**2\. Replace Google Analytics.** When it comes to knowing about your website traffic, there isn’t a super awesome replacement for Google Analytics. The team at Automattic could on their own, or maybe approach a partner, build a simple replacement for Google Analytics. Not only could it be more careful with data storage history, but it could also be an data island not connected the Google mainland of data sharing. If you have analytics installed on your site, Google knows a lot about your visitors - and could potentially be asked, like Dreamhost, to provide it to the government.

**3\. Encrypt user data.** Most all the data stored in a WordPress instance is stored in plain-text. Okay, except maybe some passwords. “Plain-text” simply means data is stored in a way that is human readable without any decryption. It’s like the number on the front of your credit card not the encrypted data in your chip on your credit card. Minimally WordPress should encrypt user data; especially email addresses of admins, authors and the like. And WordPress should include a library so plugin developers can encrypt data they collect as well before it get stored into the database.

**4\. Business, Personal or Activist.** When you first setup a WordPress blog, a step in the wizard to help you find the right theme is the choice of Business or Personal. WordPress should add an Activist option that would increase security posture of the site (like requiring 2-factor authentication), enable all the features above, and create elevated requirements for Automattic employee access to the site.

**5\. Curriculum and Mentoring.** WordPress provides a good deal of curriculum, FAQ, guides, and help files to help the world blog. Automattic could provide additional curriculum to advocates about the precautions they should take when administering an advocacy site online and with WordPress. As we’ve seen over the past several years, journalists are under increased threat by governments around the world. WordPress is a publishing platform, and therefore its users are amateur journalists.

I’ve been using WordPress for more than a decade to host my website. I have launched several corporate sites on the platform as well. It is a very approachable tool that improves the health of the web, our conversations online and our lives. There is a good chance I missed a few idea or perhaps some of it is in the works. My goal here is to help start the conversation.

WordPress is used around the world by folks living under oppressive regimes and cultural censorship. Automattic: Let’s help to protect the next generation of advocates as they find their way online.
