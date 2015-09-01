title: "Making 'index.html' more clickable"
date: 2015-08-31 15:28:13
tags:
- offline
- content-distribution
---

In my work recently I've been grappling with an unexpected problem when physically distributing offline web(apps|sites|files) to users of mobile phones using microSD cards or .zip files. What's the problem? The person receiving the files doesn't know that she is supposed to tap the `index.html` file to open the app/site. And if she received the files as a zipped file, she doesn't know how (or her phone doesn't offer) to extract the contents.

# An Example

Let's say you want to distribute ~4GB of various kinds of multimedia files on a microSD card to people in a developing nation. For this example, the actual content isn't important, but it is worth knowing that it includes dozens of videos (full-length films and shorter clips), audio files grouped into folders by album, as well as a myriad of text documents in various formats (PDF, HTML, ePub, etc.). Knowing that it will be difficult to indicate all of the important metadata related to the files (title, author, language, category, series, etc), you've put a whole lot of work into building an offline web site (a primitive web app, really) that beautifully gives access to the content and the extended information. And, like a good developer, you named the entry-point file `index.html`.

Now, you would expect that it would be _obvious_ that the user is supposed to tap on the `index.html` file. And if the multimedia content is in another language, you would expect them to tap the equivalent file in the local language - `memulakan.html` in Malay, for example). However, time and time again you're getting reports like:

> This might work, but all of the file and folder names are in English. No one here understands English!

Or

> It's really hard to understand the file structure to know where to go to open the file I want. And why is the folder structure so deep?

It hurts to hear that the well-crafted, painstakingly organized, functionally tested digital library is not being used because the recipient doesn't know how to use it the *right way*.

# A Solution?

In addition to the functional testing we've done, I think it's time we also do some usability testing with real users of our product. We need to get out and observe people struggling with that first step of accessing the content so we can better serve them. Now, this could be a bit difficult, as we are based in the US, and our primary users are geographically isolated, primarily offline, have low technology literacy, and usually live beyond the reach of the internet and mobile phone networks.

As for a technical solution to the question, what are some solutions to this problem that you've tried? Does simply renaming the `index.html` file help? What has worked in your context? Was something more drastic done in order to improve the usefulness of your offline content (such as building a mobile app)? Take part in the discussion and comment below.
