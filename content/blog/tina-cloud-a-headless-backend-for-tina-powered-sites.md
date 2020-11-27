---
title: Introducing Tina Cloud
date: '2020-11-26T21:53:53-04:00'
author: Scott Gallant
last_edited: '2020-11-27T02:06:04.520Z'
---
Around this time last year, we [announced TinaCMS](https://www.youtube.com/watch?v=iPDCmbaEF0Y), an open-source toolkit to give your JAMstack sites a visual editing experience. At that time, we had a simple objective:

_Take the concept of "visual editing" used by tools like Wix, Squarespace, or Webflow and offer it to developers in the form of open-source Javascript libraries._

Tina has come a long way in the last year and we recently completed the [last feature](https://tina.io/blog/introducing-media-manager/) from our original plan.

## **Own your content, no lock-in**

To prevent vendor lock-in we designed Tina to read and write content from any API. This could be a Markdown file in GitHub, a Google Sheet, or a headless CMS. This way, you can give your site Wix-like visual editing powers but keep a separation of concerns between content and code.

Write content to any API  
![](/img/blog/tina-api-friendly.png)

Since Tina can talk to any API it becomes very versatile and prevents lock-in with any one vendor. But on the flip side, Tina is just Javascript that runs when your site is in _edit mode_ and therefore lacks some basic functionality that comes with other CMS solutions like user management, authentication, content storage, and more.  With Tina, you have to roll a lot of that stuff yourself and it can be a lot of work.  That’s why we’re happy to share our vision of Tina Cloud: a headless backend designed to power Tina sites.

## **Tina Cloud**

Initially, Tina Cloud will provide three essential components:

**Dashboard**

A dashboard to manage your users and Tina sites.

**Headless GraphQL API**

The headless API provides content storage backed by Git and a GraphQL API on top of it.

**User Management and Authentication**

Give editing access to any team member, even if they don’t have a GitHub account.

You’ll see us invest in the Tina plugin ecosystem soon to make it easier to get up and running with 3rd party backends. But we know some things just require a server which is why we’re excited to

We believe in using Tina with whatever stack you want. But in order to

![](/img/blog/tina-cloud-backend.png)

take visual editing to the next level, we’re creating the best-of-breed solution designed to support Tina sites.