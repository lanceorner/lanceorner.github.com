---
layout: page
title: Lance Orner 
tagline: Home Page
---
{% include JB/setup %}

## Professional

I'm currently a Software Engineer at [IGT](http://www.igt.com) for
Ignite Studio, developing high-end slot machine software using Unity 3D
and C#.  I have also been a Project Manager and a Product Manager for
global software platforms, and work with both internal and external
customers to create the best software foundation which allow the games
to work with the hardware, networks, and graphic tools. 

## Technical

I am a Computer Engineer and Software Developer, and I've lead
software development teams and have worked with many different
software development teams over the years.  I've worked with C++, C#,
Python, database development, networking, protocol development, and
lots of other technologies that have come and gone.

I'm still primarily a Linux user at home, since that's just how I
work.  This web page is developed with Vim and Jekyll, and have 
also experimented with Audrino projects. 

I've documented a few of my personal projects here:

* [Github:Cribbage](https://github.com/lanceorner/Cribbage.cpp)
* [Roby the Costerbot](http://orner.net/robycosterbot)

## Family

Posting public pictures on the web is a tricky thing, but I've been
posting more and more.  I have posted a [web photo
album](http://orner.ent/albums) with pictures for people to
browse.

If you're looking for genealogical information, I've been out of it
for a while, but there is another [web
site](http://www.kinfolks.info/) which has a lot of Orner/Arner/Erner
family information. I have no affiliation with them.

## Emergency Management

Dad was a volunteer fire chief, and I try to do what I can to help the
community.  Washoe County has a [very active CERT
Team](http://wcsovolunteer.org), and I have been on the advisory
board, and I have been a team leader for the Sparks team which meets
monthly at Sheels.  I previously ran the webpage also.

* [Washoe County Sheriff Volunteers](http://wcsovolunteer.org)
* [National Citizen Corps (FEMA)](http://www.citizencorps.gov/)
* [Broken Wing Disaster Exercise 2011](http://wcsovolunteer.org/archives/157)
    
## Posts

Thoughts I want to publish from time to time:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


