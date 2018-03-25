# CSUN 2018 Documents

by Jamal Mazrui\
2018-03-24

The content of this repository is mainly contained in its wiki:\
<http://GitHub.com/JamalMazrui/CSUNATC18docs/wiki>

Note that this is not an official project of the [CSUN Assistive Technology Conference](http://www.csunconference.org).  The project name, CSUNATC18docs, includes the [#csunatc18 hashtag](https://twitter.com/hashtag/csunatc18) from Twitter.

## Background

As a blind attendee of the 2018 CSUN conference, I regularly experienced an inability to gain value from a slide presentation of keen interest to me.  Even if the speaker gave a URL for a digital copy of the presentation, it was usually not accessible to me, either because it was just displayed on the final slide without verbalization or because the verbalized URL was too difficult to memorize by listening just once.  Often, simultaneous sessions were of interest to me, so I also missed a chance to learn of other slide presentations that would be accessible if I only knew their public URLs.

This project is an attempt to make the conference slides or handouts available in a manner that is easy for speakers to share accessibly.  I investigated various alternatives for a free, reliable, and self-service system for sharing such documents.  In the past, dedicated individuals have collected links to slides after the CSUN conference and updated a web page as often as volunteer time would allow.  This approach tries to be less dependent on a single individual and more direct in the path for speakers to share their documents.

I found that some collaboration sites require individual authorization for adding content to a project.  Others with fewer barriers to entry enable users to post links but not to upload files.  Still others support uploading images such as `.jpg`, but not documents such as `.pdf`.

On balance, an approach using some GitHub features seem to work best.  Given the popularity of the `GitHub.com` site .com in the tech world, many CSUN conference participants are familiar with it as users.  Moreover, since speakers there are often developers as well, they are likely to have an account already, so uploading a document or posting a link there should be a relatively straightforward way of sharing.

## Sharing Steps

A CSUN speaker may share a conference document as a link on the wiki of the *CSUNATC18docs* repository, which is configured to permit contributions by anyone with a GitHub account.  If the speaker does not have use of another website for hosting the document, it may be uploaded in the issue queue of the same repository.  The following steps may be taken:

- Sign into the web site <http://www.github.com>.

- Go to the repository at <http://GitHub.com/JamalMazrui/CSUNATC18docs> (either a mixed case or lower case URL will work).

- Choose the `Wiki` link and then the `New Page` link.  Alternatively, open the page <http://GitHub.com/JamalMazrui/CSUNATC18docs/wiki/new>.

- In the web form for creating a new page, use the `Title` field for inputting the title of the document to be shared.  Use the multi-line `Page content` field for a description that at least contains a link to the document.  By default, the wiki accepts Markdown syntax as input, so the link may be entered like this:

  `[Link name](Link URL)`

  It is recommended that each document include explicit licensing terms within its content, e.g., by referencing [Creative Commons — Attribution-NonCommercial-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nc-nd/4.0/).

- If the document is not already hosted elsewhere, it may first be uploaded to the issue queue of the `CSUNATC18docs` repository before creating a wiki page that links to the document.  To create an issue, open the page <http://GitHub.com/JamalMazrui/CSUNATC18docs/issues/new>.

- In the web form for creating a new issue, use the `Title` field for inputting the title of the document to be shared.  Use the multi-line `Comment` field for any description.  Invoke the button for uploading a document as an attachment to the comment.

- After creating the issue, move focus to the attachment link and copy its full URL to the clipboard using the context menu (e.g., invoked via a right click or Shift+F10).

- On a wiki page for sharing the document, as described above, paste the URL when adding the link.

- This repository contains a test example of a wiki page that links to an issue attachment.

## Miscellaneous

If CSUN speakers participate by sharing in this manner, then their digital learning aids will be available to benefit more people.  Undoubtedly, there were more interested in their sessions than who could attend, given scheduling or financial limitations, so this makes knowledge available more broadly.  It spreads education about accessibility and furthers its implementation.

This project is an experiment in a self-service system based on professional trust.  Please post document links only if you were a speaker at the 2018 [CSUN Assistive Technology Conference](http://csunconference.org).

Feel free to use (responsibly) other collaboration features of the `CSUNATC18docs` repository, e.g., by adding related content or cloning the wiki.
