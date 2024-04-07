---
title: "The Daily Molecule: The Wonders of Chemistry - One Molecule at a Time"
published: "2008-05-14T00:00:00.000Z"
---

Chemistry is a big field judged by any standard, including the [proliferation of American Chemical Society (ACS) divisions](/articles/2008/05/07/1908-and-all-that-the-long-tail-and-chemistry). Each subdiscipline in chemistry is in turn so big, that once a chemist becomes 'differentiated' it's easy to lose touch even with neighboring subdisciplines. It doesn't have to be that way. This article introduces a new service, [*The Daily Molecule*](http://blog.chempedia.com) designed to make it just a little bit easier (and hopefully fun) to stay in the chemical loop.

# What Is It?

The idea is simple: every weekday, a new molecule will be featured on *The Daily Molecule* with a short write-up and some leading references. Although molecules in the news will get first priority, any molecule is fair game.

The material for *The Daily Molecule* will be drawn from [Chempedia](http://chempedia.com), which in turn gets some of its content from [Wikipedia](http://wikipedia.org). In other words, the entries on the Daily Molecule will be largeley written by my fellow chemists.

The process of creating a *Daily Molecule* entry is not time-consuming, but much of what is being done manually now could be automated in the future. The technology platform lends itself well to many forms of chemistry-specific modification (see below).

I hesitate to use the term 'blog' to describe *The Daily Molecule*, but the description may be helpful to an extent.

*The Daily Molecule* is unlike a blog in that most content will be generated by others, selected by some criteria, reformatted for consistency, and published. In that sense, *The Daily Molecule* is a something like a mini scientific journal, but it turns the process of acquiring content on its head.

If chemistry ever evolves beyond the [current model of publication](/articles/2007/07/16/go-west-young-man-does-open-access-really-matter-in-the-long-run), which seems inevitable at this point, the journals of the future may resemble *The Daily Molecule* in one or more ways.

# Technology

The software running *The Daily Molecule* is a modified version of [SimpleLog](http://simplelog.net/), a Web application based on [Ruby on Rails](http://www.rubyonrails.org/). Unlike most blogging engines, SimpleLog focuses on implementing only the most basic publication features, and doing them to perfection. If you know a little Ruby and can work with Rails, you can do a lot with SimpleLog.

One of the first items of business will be to implement [reCAPTCHA](/articles/2007/09/18/six-reasons-i-like-recaptcha-or-how-to-build-a-web-service-worth-talking-about) support and activate comments on articles.

Some ideas for chemically-enabling *The Daily Molecule* include a graphical abstract sidebar and (sub)structure search. Currently, the 2D chemical structure images posted to *The Daily Molecule* [have complete connection tables embedded as metadata](/articles/2007/08/08/never-draw-the-same-molecule-twice-viewing-image-metadata), a feature with some interesting possibilities.

# The Molecule of the Day/Week/Month

The basic idea behind *The Daily Molecule* is not new. Many other services have sprung up over the last ten years that operate, at least on the surface, similarly. Some examples:

-  [Molecule of the Day](http://www.moleculeoftheday.com/)
-  [ACS Molecule of the Week](http://portal.acs.org/portal/acs/corg/content?_nfpb=true&_pageLabel=PP_TRANSITIONMAIN&node_id=677&use_sec=false&sec_url_var=region1)
-  [Drugs and Poisons](http://www.drugsandpoisons.com/)
-  [Saturday Night Synthesis](http://the-half-decent-pharmaceutical-chemistry-blog.chemblogs.org/category/saturday-night-synthesis)
-  [The Molecule of the Month](http://www.chm.bris.ac.uk/motm/motm.htm) (may be the oldest continuously-operated MOTM site in existence)
-  [3dchem.com Molecule of the Month](http://www.3dchem.com/motm.asp)
-  [Protein Spotlight](http://www.expasy.org/spotlight/)
-  [PDB Molecule of the Month](http://mgl.scripps.edu/people/goodsell/illustration/pdb)
-  [Prous Molecule of the Month](http://www.prous.com/molecules/default.asp)

Quite a few others don't appear on this list.

The different idea behind the *The Daily Molecule* is that chemical content already exists in on the Web in machine-readable format with licenses that permit its re-use; all that's needed is a way to aggregate, format, and package that information in a form suitable for once-daily scanning and cheminformatics manipulation.

# Conclusions

Like no other medium, the Web blurs artificial distinctions: between work and play; between private and public; between on-topic and off-topic; between fame and obscurity; between mine and yours; between big and small; and between profit and non-profit. Chemistry may be late to the party, but is not immune to its call.