+++

title = "Plausible Review | A Google Analytics Alternative?"
date = "2021-03-13"
description = "Plausible is a cookie-free website tracking solution, but can it replace Google Analytics?"
draft = false
tags = ["review", "analytics"]
showtoc = true
tocopen = true
[cover]
image = "/uploads/plausible_header.png"
alt = "Plausible Review"

+++

## What is Plausible Analytics?
[Plausible](https://plausible.io) is a fully GDPR compliant website analytics platform, made and hosted in the EU. The script adds less than 1 KB so it's lightweight, lightning fast, and privacy-focused. 

![Plausible Analytics](/uploads/Plausible.png)

Plausible takes a progressive approach to web tracking:
* cookie-free
* does not collect personal data
* no persistent identifiers
* user count is based on unique IP addresses and is cleared every 24 hours
* open source

But how does Plausible stand up to Google Analytics?

## Why Should You Trust Me?
I'm a [professional digital marketer](/consulting/) at [Mailgun](https://www.mailgun.com), an email api service for developers. I've spent millions of dollars on Google Ads and consulted for multi-million dollar SaaS companies.

My job requires me to live and breathe Google Analytics, often abbreviated as just **GA**. Google Analytics is used by [84% of websites](https://w3techs.com/technologies/details/ta-googleanalytics) known by W3Techs, and for two good reasons:
* It's free
* It's made and maintained by Google

But Google Analytics has some major downsides, including that it's made by the largest digital advertising company in the world. It's not privacy-focused by default because it places tracking cookies that persist for years.

I was looking for a Google Analytics alternative for this website because I don't want to use cookies at all, **and that's how I found Plausible.**

## Plausible Review
For the last two weeks I've had both the Plausible and the Google Analytics code firing on all pages of my website. 

Both tags are placed through Google Tag Manager with the same firing trigger.

I get about 5,000 visitors each month so I wanted to compare the data both tools collect. 

Here's what happened.

![Plausible vs Google Analytics](/uploads/GA_Plausible_Graph.png)

The orange line in the above chart is Google Analytics and the purple line is Plausible.

Plausible **tracked 3% more users** on average than Google Analytics.

The main reason for this is that Plausible resets sessions every 24 hours. Because there's no cookie stored, Plausible has no idea if the same person is coming back multiple days in a row.

The Google Analytics can persist for up to two years, so Google has a more accurate (and invasive) way of measuring return visitors for periods greater than 24 hours. 

That's a strong plus for Plausible if you're seeking a privacy-first and open source website analytics tool. 

### Plausible Features
* Aggregate data collection only
* No cross-device tracking
* Built in the EU
* GDPR & CCPA compliant
* No cookies
* Simple and easy to understand, all reports fit on one page
* Lightweight script, < 1 KB

### Plausible vs Google Analytics
![Plausible Stats](/uploads/plausible_stats.png)

The above chart is from my Plausible dashboard. My favorite plausible feature is that their reports are **simple**.

All of the Plausible reports and charts fit on a single page.

In contrast, Google Analaytics is complicated and tracks hundreds of different metrics. There are many pages and folders you have to sift through to find the report you want.

There are Google Analytics certifications you can get to prove you know the tool well. Plausible doesn't need any certifications because of its simplicity. 

| Feature | Plausible | Google Analytics |
| ------ | ------ | ------ | 
| Price | $6/month | Free |
| Uses Cookies | No | Yes |
| GDPR Complaint | Yes, by default | Yes, with heavy configuration | 
| Privacy-Focused | Yes | No |
| Traffic Source Reporting | Yes | Yes |
| Location Reporting | Yes | Yes |

Plausible has a free 30 day trial with unlimited page views, but after 30 days you'll need to pay for it. 

The cost is small, starting at $6/month or $4/month paid annually. 

It's really a minimal cost and it supports the two developers. Because they're not backed by a mega corporation they need to charge, which is totally understandable. 

If you want an open source google analytics alternative then Plausible is easily worth the cost. 

## Open Source Analytics Tools

1. [Matomo](https://matomo.org/) 
2. [Plausible](https://plausible.io)
3. [Open Web Analytics](http://www.openwebanalytics.com/)
4. [Cloudflare Web Analytics](https://www.cloudflare.com/web-analytics/)

Formerly Piwik, Matomo is another GA alternative. But it's more expensive than Plausible: their cheapest plan starts at $29/month for 50,000 users. 

Open Web Analytics is a tool I have not personally used, but I immediately distrust it for one reason: their site doesn't use https. An https website is tablestakes in 2021, so I won't be testing this tool. 

Cloudflare's web analytics tool also came out of beta recently with another privacy-focused, lightweight Google Analytics alternative. You can use CloudFlare analytics in two ways:
* Install their javascript snippet
* Host your website behind Cloudflare (requires a paid plan)

## Do You Need Google Analytics?
No. There are several alternatives to Google Analytics these days. If you're concerned about Google rankings and SEO, [Google does not use GA data](https://www.searchenginejournal.com/does-google-use-analytics-for-ranking-purposes/375988/#:~:text=Does%20Google%20Use%20Google%20Analytics,sites%20or%20ranking%20sites%20better.) for their ranking algorithms.

{{< tweet 1288220268155076611 >}}

Google Analytics is great if you want a free, widely used web analytics platform. If your goal is to learn digital marketing then you need to know Google Analytics.

But if you're looking for an analytics tool that respects your users privacy, does not use cookies, and only shows you the most essential data, checkout [Plausible](https://plausible.io).