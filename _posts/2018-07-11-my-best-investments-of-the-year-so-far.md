MY BEST INVESTMENTS OF THE YEAR... SO FAR
=======================================

Posted on [July 11, 2018](https://iooikos.co/blog-post/my-best-investments-of-the-year-so-far/) by [Yann Tromeur](https://iooikos.co/author/gmailyatr/)

[![](https://i1.wp.com/iooikos.co/wp-content/uploads/2018/08/6.png?fit=538%2C411&ssl=1)](https://iooikos.co/blog-post/my-best-investments-of-the-year-so-far/)

In this new regular series, I will give you my best investments, tips, tricks that gave me the best results to achieve goals. If you thought I was going to give you away the latest cryptocurrency whale (maybe next time) or some Wall Street type advice, well...

![](https://static.wixstatic.com/media/6205f7c76ec4497ea3543cb9ecf7db56.png/v1/fill/w_484,h_484,al_c,q_80,usm_0.66_1.00_0.01/6205f7c76ec4497ea3543cb9ecf7db56.webp)

Sorry we have been really busy, so the blog has been a bit left on the side.

An ode to the cloud... Amazon Web Services, you shine so bright.

We migrated part of our infrastructure to a Public Cloud: our private file sharing. We have office 365 as well, but honestly, OneDrive is not Microsoft at its best.

At first, we hosted the service on a private Cloud. Budget around 900€ a year. Simple Windows VM.

Service was there, very happy customer of this private cloud, best team, good price, but there comes the Public Cloud and especially AWS.

From reading my past articles, [serverless does not mean brainless](http://www.iooikos.com/single-post/2018/04/25/Serverless-does-not-mean-Brainless---Part-1), you begin to understand iooikos is mainly about innovation and begin smart and sustainable.

![](https://static.wixstatic.com/media/aedf3dceccd24a0ca6c446113a3c127b.jpg/v1/fill/w_484,h_272,al_c,q_80,usm_0.66_1.00_0.01/aedf3dceccd24a0ca6c446113a3c127b.webp)

About being smart, I mean especially two questions arise.

1.  What if you can get the same thing but cheaper? What is smarter: stay with a good provider or deal yourself with IT management (if you can)?
2.  Oh yeah big word. What do we talk about every day? What is iooikos soul? How can we preach what we do not practice?

For one, of course, it is a business. It is about how you re-invest the money and what you produce to your customers' benefits. No hard feelings but we have to think about our bank account as well! For a year, I have been a happy customer.

AWS provides the same software as a service, and you know what: it is free tier eligible. FREE TIER. How we use file sharing: we upload them to the service, instead of attaching files to emails, and they are dumped after a couple of days.

DONE. FREE. SMART. SAFE. SUSTAINABLE.

We just deployed the AWS INSTANCE, no VM setup and boom we are live. More, we migrated user database and licenses in a couple of clicks, copy and paste. So yeah, it is a Linux VM, but even with basic knowledge, you can do the trick.

So yes, sorry but I prefer free tier to 70 € a month. My bad, I apologize, my budget is now 0 € a month.

Accountant says: "0 € is a Good Investment".

Who would disagree?

For two, our Church is the Cloud. Innovation in / with the Cloud. I cannot stay stuck to one thing, especially if a new / better / faster / more efficient service exists.

Also, we believe in innovative CHANGE.

We stick to it.

I know: sticking and change in the same sentence feels weird!

Let me be clear. Free is a state of mind as well. It feels good having something for "free", almost seems like you stole something and nobody to catch you!

Do not forget, free has this other meaning, it means always you can do whatever you like, whenever you feel it. No bounds. FREE. Almost.

So now, we have file sharing live on AWS EC2, as a private Service on a Public Cloud in a European Datacenter.

Best is it took us less than four hours to migrate with no downtime. The service runs smoothly on a t2.micro instance (see below).

We chose AWS because they provided the same product we used as an instance, so it felt easy. We could have done the same with Google Cloud or Microsoft Azure or any Cloud provider.

![](https://static.wixstatic.com/media/2223f083ac395d233dbf0d745b39eef2.jpg/v1/fill/w_484,h_323,al_c,q_80,usm_0.66_1.00_0.01/2223f083ac395d233dbf0d745b39eef2.webp)

MORE CONSIDERATIONS (almost nothing is free)

A new business model clearly emerges there. No more heavy fixed costs, just pay as you go.

The only costs we will have now are, so the customers will get a nice discount:

-   Our management time
-   Extra storage if needed to extend
-   Software License

We can also invoice the customers from their usage, with an elastic invoicing. Service guaranteed but you would only pay what you use as well. SMART. AGAIN.

Disruption is here.

About AWS FREE TIER: "The free tier for these services provides you with a monthly allotment of hours for the first 12 months. For example, the free tier for Amazon EC2 provides you with 750 hours usage of Linux (any combination of t2.micro and t1.micro instances), plus 750 hours usage of Windows (any combination of t2.micro and t1.micro instances)".

750 hours that is about 31 days. For t2.micro or t1.micro. Just being a smart Small Business!

![](https://static.wixstatic.com/media/e77fd1ddd12e4652b471fe86db43b889.jpg/v1/fill/w_484,h_277,al_c,q_80,usm_0.66_1.00_0.01/e77fd1ddd12e4652b471fe86db43b889.webp)

Also a little extra about SUSTAINABILITY. Our former VM was on almost 24/7. Very bad for the ecology. Therefore, we do what we preach: AWS allows through LAMBDA and CLOUDWATCH easy autostart and stop of VMs with small python coding.

We do not share files at night so the filesharing is working only 9 hours per day on working days only: smart and sustainable! Then, next year we will pay for those 9 hours

More tips and experiences coming soon, stay tuned!

More info on AWS EC2 pricing:

<https://aws.amazon.com/ec2/pricing/>

If you need technical advises: ring us or email us!

I hope you enjoyed my little tips and tricks of the day! Please do not hesitate to post comments or share your own. Have a nice week!