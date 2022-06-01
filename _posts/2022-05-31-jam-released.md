---
layout: post
title: JAM! Released
subtitle: A tool you hopefully won't need much
cover-img: /assets/img/jam/jam-banner.png
gh-repo: TsimpDim/jam
gh-badge: [star, follow]
tags: [project]
---

{: .box-warning}
**Remember:** This project is in its early stages - a lot of polish & love is required before this can be described as a full-fledged product.


# Overview

Finding a job is a tedious process. You have to send a bunch of applications across different sites, platforms, emails. You have to keep tabs on which companies you have applied to, and for which roles - as well as their descriptions. Well, I don't know about you but I don't like the process a lot.

That's why I wrote [JAM!](https://jam.tsdim.net/), a **J**ob**A**pplication**M**anager to help you in this process, by providing a place where you can keep tabs on your job-finding journey. The platform works by providing the ability to create, and group, job applications that follow certain steps (which you define). You can then have a clear timeline of the process, add any comments you want, and make sure that you'll always have a place with a good overview of your current job-seeking.

JAM! can be found under this link: [https://jam.tsdim.net/](https://jam.tsdim.net/)

# Stack

For this project I used [Angular](https://angular.io/) together with [Clarity Design](https://angular.clarity.design/) to serve the frontend, and [Django](https://www.djangoproject.com/) w/ [DRF](https://www.django-rest-framework.org/) for the backend/API which is served using Gunicorn and its ASGI integration. The application is fully running on an AWS environment backed by EC2 & RDS - and is deployed with Terraform.
