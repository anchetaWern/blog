---
date: 2015-12-05
title: Tools of trade
excerpt: In this article I’m going to share some of the tools and resources that I usually use in my day to day web development practice.
---

Every developer has their own set of “go to tools” when it comes to developing applications. Such as the stack, programming tools and libraries that would make specific tasks easier to implement.
In this article I’m going to share some of the tools and resources that I usually use in my day to day web development practice.

### LAMP

Since I’m running Ubuntu on my machine, I use the LAMP (Linux, Apache, MySQL, PHP) stack for all of my projects. Linux being the Operating System, Apache as the web server, MySQL for the database and PHP for the programming language.

### Composer

[Composer](https://getcomposer.org/) is a package manager for PHP. It handles the installation of various PHP libraries which can be found at [Packagist.org](https://packagist.org/) .

### Laravel

For medium-sized projects (takes about 2-5 months to build), I use the [Laravel](http://laravel.com/) framework. And for small-sized (takes about 2 days to 3 weeks to build), I use the [Lumen](http://lumen.laravel.com/) framework which is basically a lightweight version of Laravel. I chose it because of the sheer elegance of code that can be written when using the framework. It also comes with a lot features that I need in most of my projects. Such as database migrations, seeding, routing, templating and easy integration with third-party libraries.

### jQuery

They say jQuery is for sissies, but I don’t really mind. As long as the tool works, it doesn’t really matter. jQuery is basically the all in one solution for all my JavaScript needs. It makes it easy to select and manipulate the elements in the page, listen to events and make AJAX requests. I haven’t done a web project where I didn’t need jQuery.

### Sublime Text

My text-editor of choice, though I admit that I’m still using an unregistered copy. So I still see the purchase pop-up every now and then. Though I have plans to buy a license in the future. But as they say “someday I’ll buy a sublime text license but today isn’t that day”. What I liked with [Sublime Text](http://www.sublimetext.com/) is that it makes writing code faster. You can also install plugins which integrates with other programs such as JSHint or Git.

### Git

Most developers today are using [Git](http://git-scm.com/) , probably because of Github. But that doesn’t really matter. Git is an awesome software by itself, even without Github. For the uninitiated, Git is a version control software which allows you to make snapshots of your project so that you can easily revert later or share your changes to your team. Github on the other hand, is a web based Git repository hosting service with lots of other nice features. Go check it out yourself. But the key takeaway is that Github makes collaboration much easier with the set of tools that it provides.

### Cordova

Ocassionally I get mobile app development projects. This is where [Cordova](https://cordova.apache.org/) comes in handy. It basically makes it easier to develop apps for any of the platforms (Android, iOS, Windows, etc.) that it supports by making use of web technologies (HTML, CSS, JavaScript). Access to native device APIs are also provided by making use of plugins.

### Bootstrap

I admit, I’m not a designer and my CSS skills could certainly improve. Making things pretty isn’t really my forte. That’s why front-end frameworks such as [Bootstrap](http://getbootstrap.com/) really helps. It keeps my mind off making things pretty so I can just concentrate on the functionality.

### Chrome/Chromium

The main browser that I use for testing the web applications that I build. The developer tools is what really makes it shine. It’s interface is really intuitive and easy to use. Almost every aspect of your web application can be inspected and tested by using their developer tools.

### Skype

Since I’m mostly working remotely, there’s a need for exchanging messages and making calls. Skype helps me with that. It’s also cross-platform, so I can install it no matter what machine I’m using. Recently they also released [Skype for web](https://web.skype.com/en/) which makes things even more easier.

### Bitbucket

[Bitbucket](https://bitbucket.org/) is another Git repository hosting service. Well there’s already Github, but the thing is you can only have public repositories on Github. Bitbucket on the other hand allows you to have private repositories for free. That’s pretty much the only reason why I used Bitbucket. I need my projects to be private so I use it instead of Github.

### Node.js

If a project calls for real-time functionality such as chat applications, nothing beats [Node.js](https://nodejs.org/en/) . It provides an event-driven architecture and a non-blocking I/O API. This allows real-time applications to be built with ease.

### Socket.io

[Socket.io](http://socket.io/) is a library that makes it easy to build real-time applications. It’s often used in tandem with Node.js.

### Virtualbox

If a project requires me to test on a different platform and browser such as Internet Explorer or Safari on Windows. I usually use [Virtualbox](https://www.virtualbox.org/) . I guess I don’t really have much of a choice. Other than Virtualbox, I’m not really aware of any other software that can virtualize an OS.

### AWS

[Amazon Web Services](http://aws.amazon.com/) as the name suggests is a collection of Web Services offered by Amazon. I only use ec2 (elastic compute cloud), s3 (simple storage service) and cloudfront (CDN) though. The cool thing about their web services is that they’re tightly integrated with each other. Which means that you can easily use s3 within an ec2 instance without having to do much of the setup. They also provide an API which can be used to programatically upload files to their servers.

### DigitalOcean

Recently I also started using [Digitalocean](https://www.digitalocean.com/) for my personal projects. Mainly because its very affordable (only \$5 a month for the lowest tier) and easy to resize (I can upgrade or downgrade any time).

### Carbon

Carbon is a PHP library for working with dates.

### Moment

Basically the Carbon equivalent for JavaScript. The nice thing is that you can use it on both the client-side and server-side (node.js).

### Intervention Image

When there’s a need for image processing in a PHP application, I always grab [intervention image](http://image.intervention.io/) through Composer. Resizing, cropping, blurring, change orientation, optimizing, name it and intervention image has it. But what hit the jackpot is that it works nicely with Laravel without having to do much setup.

### Twig

Blade is the default templating engine used by Laravel so I use that without having second thoughts. But whenever I work outside Laravel, I have to use something like [Twig](http://twig.sensiolabs.org/) to handle my templating needs.

### Handlebars

My templating engine of choice when I’m using JavaScript.

### Mandrill

Whenever I need to send out emails from an application, [Mandrill](https://www.mandrill.com/) is the tool of choice. Its a no-brainer since Laravel makes it easy to send emails using services such as Mandrill.

### Faker

As programmers we all love automating things. [Faker](https://github.com/fzaninotto/Faker) does exactly that. It generates fake data for you so you don’t have to enter it manually through the application that you’re building.

### Dropzone

[Dropzone](http://www.dropzonejs.com/) is my file upload libary of choice. It’s easy to get started using it. But it also makes it easy for developers to customize.

### Stripe

Whenever a project needs to accept payments from its users, [Stripe](https://stripe.com/) is my service of choice. I’m not really confident enough that I’d be able to implement a payment system which is safe from every hacker. Just the thought of saving the hash of credit card numbers on a database sends shivers to my spine. Stripe takes that fear away. I know the guys at Stripe know their stuff.

### Paypal

For simple payment needs, [Paypal](https://www.paypal.com/) is the tool. And BTW, this is also how I receive payments. It integrates with almost every bank on the planet so you can easily withdraw your money using your bank of choice.

### Twilio

Whenever there’s a need for voice enabled apps or SMS verification, nothing beats [Twilio](https://www.twilio.com/) .

### Guzzle

“No man is an island”, the same is true with web applications. More often than not, you’ll find the need to integrate with third party services. That’s where [Guzzle](http://docs.guzzlephp.org/en/latest/) comes in, it’s a PHP library for making http requests. If the API that you’re working on doesn’t already come with a library for making requests, then Guzzle is for you.

### thujohn/pdf-l4

For applications that require printing of reports. [Thujohn’s pdf-l4](https://github.com/thujohn/pdf-l4) library does it.

### Datatables

If an application requires searching or paginating through a table of data, [datatables](https://www.datatables.net/) does the trick. What’s great is that there’s also a [datatable](https://github.com/Chumper/Datatable) library for Laravel 4 which makes it easy to integrate to a Laravel project.

### Beanstalk

[Beanstalk](http://kr.github.io/beanstalkd/) is a queue system. You basically use it for running time-consuming tasks such as sending out emails or processing images. There’s also a library called [Pheanstalk](https://github.com/pda/pheanstalk) which makes it easy to work with Beanstalk for queueing tasks.

### Elasticsearch

I use [Elasticsearch](https://www.elastic.co/) if there’s a need for fast searches. Elasticsearch if a full-text search server that is based on [Apache Lucene](https://lucene.apache.org/core/) . It works with

### schickling/laravel-backup

Any decent developer would implement a database backup and restore functionality for each of the applications that they build. For Laravel developers, the [laravel-backup](https://github.com/schickling/laravel-backup) library is one choice. It allows you to easily backup your database on a folder in the server or in an Amazon s3 bucket.

### Cron

We all know Cron. It’s the thing that we use whenever we need to execute something at specific intervals.

### Express

Express is a framework for Node.js. From their website itself: “Express: Fast, unopinionated, minimalist web framework for Node.js”. It handles routing and serving of static files. That’s all it really does but you can easily install third-party libraries for talking to the database or handling views and you wouldn’t have any problem. Its unopinionated so you can do whatever the fuck you want and it won’t complain.

### Picnic CSS

Recently for some of my personal projects, I used [picnic css](http://www.picnicss.com/) . Think of it as a lightweight bootstrap. It makes your UI beautiful without all the cruft that usually comes with bootstrap. It’s also modularized into a set of plugins. So you can just include the plugins that you need.

### Conclusion

In this article you’ve learned about some of the tools that I usually use in my projects. What about you? What are your “go to” tools when it comes to developing applications?
