> :Hero src=https://images.unsplash.com/photo-1466454617340-f7e55c03ecfd?w=1900&h=600&fit=crop,
>       mode=light,
>       target=desktop,
>       leak=156px

> :Hero src=https://images.unsplash.com/photo-1466454617340-f7e55c03ecfd?w=1200&h=600&fit=crop,
>       mode=light,
>       target=mobile,
>       leak=96px

> :Hero src=https://images.unsplash.com/photo-1466454617340-f7e55c03ecfd?w=1900&h=600&fit=crop,
>       mode=dark,
>       target=desktop,
>       leak=156px

> :Hero src=https://images.unsplash.com/photo-1466454617340-f7e55c03ecfd?w=1200&h=600&fit=crop,
>       mode=dark,
>       target=mobile,
>       leak=96px

> :Title shadow=0 0 8px black, color=white
>
> Learning JS While Crawling

> :Author src=github

<br>

I've recently started a new role. We've decided to work with full stack JavaScript for both front and back end. See our 
[stack share](https://stackshare.io/mind-gym/mind-gym) if you want more details. This presents a challenge for me if I 
want to stay close to the code as it's been years since I've worked full stack and I've never worked with JavaScript in 
any detail. 

As I'm not a day-in day-out engineer this means I need a hobby project

## What to do? 

I have a guilty pleasure. I like browsing ebay for old bargains or looking for random things on gumtree. This has led to
me buying the following over the past few years

* A WWII artillery shell found near Fontenay-le-Pesnel (£25 on Gumtree)
* 10 bullets around 100 to 200 years old (£2.70 on ebay)
* One good condition Roman coin (£14.50 on ebay)
* Three mid condition Roman coins (£5 on ebay)
* A fake of a $10,000 US coin (£1.27 on ebay)

The last one was worth a gamble. Despite being ugly, ebay has quite effective UX for getting alerts on the things I'm 
interested in. Gumtree on the other hand is full of crap and has no way to filter it out. 

Therefore my headline requirements are

1. Grab all adverts within a given radius of my house (using a list of categories)
2. Store key metadata for all (add new or update with a `last seen` for existing)
3. Using a dictionary of keywords I'm not interested in flag all non-interesting adverts
4. Set this up on a schedule somewhere that's not my laptop
4. Implement the above in JavaScript so that I pick up some new skills

There are a bunch of other things I could do to make this more convenient but this is my minimum

## Crawling technology

This is the sort of thing I've done in Python heaps of time before and would result in me leaning on tools I know. Time 
to start from fresh in a new ecosystem. 

From a quick look around the crawling tool options that stand out in JS are:

* https://github.com/cheeriojs/cheerio
* https://github.com/puppeteer/puppeteer  
* https://sdk.apify.com/docs/api/apify



---

> :DarkLight
> > :InDark
> >
> > _Hero image by [Yoal Desurmont](https://unsplash.com/@yoal_des) from [Unsplash](https://unsplash.com)_
>
> > :InLight
> >
> > _Hero image by [Yoal Desurmont](https://unsplash.com/@yoal_des) from [Unsplash](https://unsplash.com)_