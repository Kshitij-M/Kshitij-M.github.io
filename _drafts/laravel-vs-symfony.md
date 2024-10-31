---
layout: post
title:  "Laravel vs Symfony"
author:  "Tahir R."
image: /assets/images/apache-kafka.png
time: 1
categories: [tech]
tags: [tech, symfony, laravel]
---

**Note: before publishing think of a funny, more energatic name for the artice**

Symfony vs Laravel? Which one do you prefer and why? For quite some time this question came up in discussions and till now I have not found a definitive answer regarding this topic. So I thought this would be a good topic to dig a bit deeper and see for myself and try to find the answer for this mysterious looking, long awaited and debated topic. I promise I will try to be unbiased, I said I will try! :P

Disclaimer: I am not a very popular and/or senior guy to talk about this. The comparison I am about to write is a combination of my personal experience and an outcome from various discussions which I have done with fellow software engineers around me. And this can be boring for some people as well! :D

In order to understand which one is better I will try to setup a criteria upon which we can judge the frameworks based on a scale.

Followings are some major categories about which we are goind to talk about.

- Framework's core values
- Documentation
- Stats regarding the current usage of frameworks and time over popularity index and github stars etc etc
- Database Layer
- Design Patterns used in the framework
- Conatiners
- Debug Options
	+ Symfony's Profiler vs Laravel Debug Toolbar


## Framework's core values
Laravel: According to a podcast by Taylor, the framework was created to scratch his own itch, solve a problem which he faced during his daily life. The core idea about inventing Laravel was to build web apps faster. That's why laravel is more expressive in terms of writting code and it does all the heavy lifting behind the scenes so you can just focus on building the real thing as mentioned by the basecamp guys in the book [Getting Real](https://basecamp.com/books/getting-real).
Symfony: figure out

## Documentation
When it comes to using a software created by someone else documentation is one of the most crutial aspect which decides if the software is going to be a big hit or just another wandereing pin in a haystack.
Laravel: To be honest, as far as I have discussed with people around me, everybody thinks Laravel has done a really great job at the documentation. Writing a badass software is one thing but then explaining all that rocket science in plain english is one heck of a job which I believe Laravel has done really great. The ui of documentation provides a distraction free environment which is perfectly aligned with user's sight which makes it a lot easier to read through it, pages after pages.

Symfony: The documentation is good at Symfony also and it's pretty well explained but there's always a feeling which tells you this can be done in a better way. There's always a feeling which tells you that it's a bit more clustered as compared to laravel's documentation. Probably doing less is more here also. I will try to explain what I am trying to say here with some pictures.

I beleive this documentation aspect is one of the reasons people beleive that Symfony's learning curve is more steep than Laravel's.

Laravel and symfony documentation photos go here.

## Database Layer


## Conatiners
As we all know what container is and if not probably it's best to know that first which you can do it [here](https://example.com).
As container is a very important part of any framework I think it is necessary to talk about this separately, even though this is just another PHP object.
Laravel: NOTE: TBD

Symfony: NOTE: TBD... All I can say for now is in Symfony 4 or greater every service is binded as singleton but in laravel it is different you can bind a service as singleton or differently but I don't know how it's binded by default in laravel :P

## Debug
Here I am not talking about doing `var_dump()` - I am gonna talk about the default options provided by the frameworks to debug your code. Because let's face it, debugging can be hard and it would really nice if the framework can make it easier.
Laravel: As far as I know, unlike Symfony, Laravel does not ship with a default debug toolbar but you can get one by typing `composer require barryvdh/laravel-debugbar --dev`. OK so this is not something which is actually backed up by laravel it's not even on the official website but this is good package maintained by [Barry](https://github.com/barryvdh). It recently a got a big ui update as well.

Symfony: When it comes to symfony it has a really powerful debug toolbar which is officialy backed up by the framework.

NOTE: we need more details on this...

