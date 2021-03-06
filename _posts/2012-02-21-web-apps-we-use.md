---
layout: post
title: Webapps We Use
---

We work on a variety of products and with people. We work in a highly distributed environment,
with all of our clients working
remotely from us. And while we work out of the same office, we are frequently
working from other places as well. Here are the tools which help us stay productive,
sane and working. :)
 
*Code hosting: [Unfuddle](http://agiliq.unfuddle.com/) and [Github](http://github.com/agiliq).*

For our open source projects we use Github.  
For our client and non OS projects, we use Unfuddle.  

For our client code we need both SVN and Git, and we need tickets which can be
assigned to people. Both these features are missing from Github.  

For our open source projects, we use Github. It lacks the features above, but
its code browser, code diff and patch queue etc are much more advanced than
Unfuddle. Unfuddle doesn't have open access repositories, so they segment nicely
for us.  

For Unfuddle we pay 49$/Month. Since all our repositories at Github are open,
we don't have to pay anything for it.  

We also use [Bitbucket](http://bitbucket.org/agiliq), to keep
our code in a Mercurial repo. Additionally,
Bitbucket supports CNAMEs, so we can point [code.agiliq.com](http://code.agiliq.com),
to our bitbucket code.
(Github does not support Cnames for repositories.) This used to cost us USD 5/Month,
but after [Atlassion acquisition of Bitbucket](http://blogs.atlassian.com/news/2010/09/atlassian_acquires_bitbucketorg_distributed_version_control.html), this is free.

* Collaboration, docs and Mail: [Google apps for your domains](http://www.google.com/apps/intl/en/group/index.html).

At free, the price is right. And with Gmail like interface and searching which
is both best in class and familiar, using this is a no brainer. You can pay 50$/user/year,
to get extra space and ads. We never hit the free space limitation.


* Invoicing: [Freshbooks](http://agiliq.freshbooks.com/).

We use Freshbooks for invoicing and accounting. Freshbooks is fairly standard as
an invoicing tool, but its feature set leaves a bit to be desired. It only recently
got [multi currency invoicing](http://www.freshbooks.com/blog/2010/01/13/multi-currency-arrives-at-freshbooks/),
and still doesn't have multi currency expenses.  
(Which is sort of a deal breaker for us. We invoice is USD, AUD and Euro, our
expenses are in USD and INR). We get around this by having multiple accounts for tracking
the different currencies, but still have to account things by pen and paper.

Cost: 19$/Month.


* Voice Chat: [Skype](skype:shabda.raaj?call).

Skype is the (Afaik) only voice chat software which works reliably across Win/Mac/Linux.
We have a skype-in number and we use it to call out bound as well.

* Cost: Depends upon usage.

Hosting: [Webfaction](http://www.webfaction.com/),
[Slicehost](http://www.slicehost.com/), [Linode](http://www.linode.com/)
and [Ec2](http://aws.amazon.com/ec2).

It might be weird to see so many listed as webhosts. Webfaction is *really* easy as
a Django host. They have one click install of Django, and make using Django apps easy
without fiddling with Apache configs.
I started with Webfaction in 2008, and still have some sites from back then hosted with
them. But soon we needed a VPS for flexibility.

Our next host was Slicehost, and we have been very happy with them. Their
support and quality of support staff is phenomenal. However, they are weak when in comes
to price to server specs bang.

We recently got a Linode to test things out and have been happy with them as well. I havent
used their support yet, and they don't offer a easy backup like Slicehost, but are much more
powered for he same price.

Cost:

Webfaction: ~40$/Month.
Slicehost: 50$/Month, with backups.
Linode: 20$/Month.


* Backup: [S3](http://aws.amazon.com/s3)

We backup our media and Databases on S3,
[using a custom script](http://uswaretech.com/blog/2009/02/automatically-backup-mysql-database-to-amazon-s3-using-django-python-script/).

Cost: Depends on usage, but very less.


* Dns: [Dnsmadeeasy](http://www.dnsmadeeasy.com/)

A good, fast DNS can speed up your site, and its a good idea to keep this separate from rest of your hosting.
Dnsmadeeasy is straightforward DNS provider, which has proved very solid for us.

Cost: 30$/Year.

* Email sending: [Sendgrid](http://www.sendgrid.com/)

While it is easy to use a local SMTP to send emails from your servers, it is not easy to make
sure it will reach recipients. You will need to fiddle with SPF, and other email mumbo-jumbo.
It is easy to outsource it to a third party provider, which has expertise in email deliverability.

Cost: 10$/Month.

* CRM: [Highrise](http://agiliq.highrisehq.com/).

We use Highrise to keep track on leads and contacts. However I haven't found any actionable
insights to take actions from it, so I am looking for alternatives.

Cost: 49$/Month



----------

Also,

1. We used to use [Efax](http://www.efax.com/), but nobody sent us fax, so we don't use that anymore.
2. We used to use [Clicktale](http://www.clicktale.com/), but I could never figure out what to do with their data,
and at 100$/month they are costly to keep around.
3. We use [Crazyegg](http://www.crazyegg.com/), as needed.
4. I used [Basecamp](http://www.basecamphq.com) and [Assembla](http://assembla.com/) but I much prefer Unfuddle.
5. We also use Google Analytics, Google Adword, [Flickr](http://www.flickr.com/photos/agiliq),
[Twitter](http://twitter.com/agiliqdotcom), [Facebook](http://facebook.com/agiliq), Delicious ...

