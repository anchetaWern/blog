---
date: 2015-07-18
title: Things I learned while writing for SitePoint
excerpt: Sharing some of the things I learned as an article contributor for SitePoint
---

It’s been more than a year since I started writing articles for [SitePoint](http://www.sitepoint.com/) . For those who don’t know, SitePoint is a provider of awesome content for web professionals. Anything web which you can think of, they have it. They have tutorials on HTML & CSS, JavaScript, PHP, Ruby, Mobile, Design & UX, Wordpress and even for web entrepreneurs. And they’ve been doing it since the year 2000, I believe.

Going back to the main topic of this article, the things I learned while writing for SitePoint. There’s a lot that I’ve learned especially on my writing skills. When I first started, I thought my grammar was already perfect. But I’ve never been so wrong. Here’s a list of things that I wish I knew when I first started:

-   When using PHP libraries, always install it via Composer whenever possible.

-   When installing a single PHP library, it should be done via the command line using the composer require instead of adding the configuration in the `composer.json` file. Here’s an example when installing the guzzle http library:

```
composer require guzzle/guzzle
```

If you’re using [packagist](https://packagist.org) , you can easily install the package by using the command they have provided if you open a link to a specific library.

-   Sharing files that are used in articles (SQL files, project files) should be done with [GitHub](https://github.com/) if it’s a whole project or [Gist](https://gist.github.com/) if it’s just a single file. I made a mistake of uploading it to the public folder in my Dropbox before.

-   Use shorthand echo when outputting something with PHP. So instead of using `<?php echo 'hello world!'; ?>`, it should be done with `<?= 'hello world!' ?>`.

-   Always use a framework when the examples gets too big so that the readers can easily try out the demo.

-   When using a framework, exercise separation of concerns. All routes should be in the routes file, and the routes file shouldn’t contain anything else. I made a mistake of using a closure in the routes to respond to HTTP requests. This shouldn’t be. Best practices should always be used even the code isn’t used for a real project. So the routes should use a controller which will return the view or execute a specific function.

-   When making HTTP requests, such as when the article talks about a specific API. Guzzle should be used or some other HTTP library instead of Curl. Some readers might not have Curl installed.

-   In every article, the convenience of the readers should always be the priority. This means that it should be easy to read. If the article includes a sample project, it should be hosted using GitHub or Bitbucket. Some authors prefer having a single repository for each article. But for me I prefer having everything inside a [single repository](https://github.com/anchetaWern/sitepoint_codes) . This is because the projects or sample codes that I host in there aren’t really updated that much. I think there’s no point having each one in it’s own repository. My main purpose in hosting with GitHub is to give the readers a place to examine the code with syntax highlighting and the way each files relates to all the other files. So that they can easily setup a demo which they could play on in there local machine.

-   Write your article as if the reader is a beginner. Don’t make assumptions on the skills of the reader. But this doesn’t mean to say that you have to walk the reader through the installation of PHP or talk about the basics when you’re writing an article about a specific API that uses PHP to make HTTP requests. Every PHP developer would already know that. In the first place, the reader shouldn’t be reading your article while not knowing anything about PHP. There’s always a minimum amount of requisite knowledge. Another example is when telling a reader to install a specific library using Composer. Not all PHP developer knows about Composer. I can’t point you out to a statistic but always assume that there’s someone out there who still installs libraries using Pear or zip files. In those cases you don’t have to walk the reader through how to install Composer. Simply pointing the website out or linking to the page which shows how to install Composer should suffice.

-   Always try to include a demo as a supplement to the article. This is not something I’ve personally done. Because most of the articles I write is about PHP, which runs on the server. With client-side articles (HTML, CSS and JavaScript) this is easy since there’s Codepen, jsFiddle, jsbin, and many others which allows you to easily create a demo which the reader can use to have an idea what the output would be like.

-   Always give some time for the title of the article and the introduction. These are really important, this is what the readers sees the first when they come across your article in social media sites like Twitter. It’s the first selling point of the article so it’s important that it’s catchy.

-   Include screenshots to supplement a specific instruction or to show the readers the output.

-   Don’t just paste big blocks of code and explain it in a really long paragraph. Break down the block into parts and explain each part. Then you can paste the big block of code so the reader sees how it all comes together. Often times I do the alternate, so I paste the big block of code first and do a summary of what it does and then I break it down into multiple parts.

-   Always participate in the comments. It’s not just about writing the article, and having it published. If readers comments on your article or asks a question, you should try to answer the best way possible even if you don’t know the answer. Even if it’s not a direct question or it’s just an opinion by the reader. You should try to participate and include your own opinions as well. Honestly this is a part that I need to improve on. I don’t always participate in the comments.

-   [Common grammatical errors](https://medium.com/@hayley_mullen/beyond-youre-vs-your-a-grammar-cheat-sheet-even-the-pros-can-use-c2b90dae85ef) . The common one’s for me were the use of were vs. we’re, its vs. it’s. Everyday vs. every day. And where to place the comma or if it’s even needed. I think I’ve improved when it comes to this. But it’s always nice to have a second pair of eyes looking at your work. For this I use the [hemmingway editor](http://www.hemingwayapp.com/) . It grades the readability of an article, marks potential errors, and provides some really good tips about your article.

-   Use a bullet list instead of saying ‘next’ or ‘and then’ all the time. If a bullet list doesn’t feel right, connect sentences with commas.

-   Property casing. Use all-caps when referring to an acronym. One of those acronyms is ID. It should be ID instead of id.

-   Needless words should always be ommitted. Common offenders include the words: ‘always’, ‘just’, ‘basically’, and ‘simply’.

-   Be consistent with the use of ‘we’ or ‘you’ when referring to the reader. You will often see these 2 words in tutorials. But if you have started using ‘you’ to refer to the reader or ‘we’ if you’re a merry person who wants to include yourself while telling something to the reader. It’s important that you stick with whatever you started using. I prefer to use ‘we’ in most cases since ‘you’ sounds really lonely. Whereas if you use ‘we’, it has the connotation that you have gone through the same process that the reader is going through when you were writing the article.

-   Proofread your article 3 or more times to ensure that common grammatical errors were caught and the wording is easy in the eyes or comfortable to read. This means that the article should be readable without having to exert much mental effort or having to go back to a sentence you’ve just read because it didn’t make sense.

-   When referring to a specific library such as jQuery, always be mindful of how it’s written on the website of that specific library. For jQuery, the ‘j’ is a small letter and the ‘Q’ is a capital letter.

-   Always be mindful of the word count. If an article is meant to be a series then each part should have a word count of not greater than 3000 words.

-   Always strive to make the work of the editor easier so that they will be more motivated to review your work.

-   Recently, SitePoint implemented the peer reviews which utilizes Github. How this works is that all the articles are stored in a Github repository. Every new article is a separate branch that’s going to be merged in the main branch. A pull request is created for each new article which is then reviewed by the other authors. The other authors will comment on your work or make the changes on their end. The original author can then make use of these comments to improve the original article. This kind of workflow has levelled up my Git skills. And through the help of the other authors, I’ve learned how to improve my articles by altering the wording, providing screenshots and using Frameworks when presenting code. The next step that I’m looking into is to also review the works of other authors. As a means of giving back and learning how the other authors construct their articles as well.

That’s it! I won’t treat this section as the conclusion as there will always be new things to learn. I’ll update this article in the future once I learn some more. Be sure to check out the resources below if you also want to level up your writing skills. And if you’re a web professional, you’re welcome to [join SitePoint](http://www.sitepoint.com/write-for-us/). They’re always looking for new authors. It doesn’t matter if you’re new to the industry or an experienced one. As long as you have something to share, you’re welcome to write for SitePoint. Oh and articles are paid really well so it’s worth the time investment.

### Resources

-   [How to Write Great Web Development Articles and Tutorials](http://www.impressivewebs.com/how-to-write-great-web-development-articles-tutorials/)

-   [SitePoint Writing Guidelines](http://www.sitepoint.com/writing-guidelines/)

-   [Introduction to SitePoint Peer Review](http://www.sitepoint.com/introduction-to-sitepoints-peer-review/)

-   [Beyond You’re vs. Your: A Grammar Cheat Sheet Even the Pros Can Use](https://medium.com/@hayley_mullen/beyond-youre-vs-your-a-grammar-cheat-sheet-even-the-pros-can-use-c2b90dae85ef)
