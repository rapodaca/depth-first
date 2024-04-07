---
title: JavaScript for Cheminformatics - Cross-Compiling Java to JavaScript with GWT
disqus: true
published: "2008-12-09T00:00:00.000Z"
---

A few months ago I wrote about some ways that [JavaScript could be used for cheminformatics](/articles/2008/07/15/javascript-for-cheminformatics). Although at the time I was considering mainly cheminformatics tools build from scratch with JavaScript, there is another possibility. Today, [Duan Lian](http://chemhack.com/) posted [this intriguing comment](/articles/2008/07/15/javascript-for-cheminformatics#comment-944):

>I think GWT(Google Web Toolkit) is a good starting point. It has the ability of running "Java code" as javascript generated by a special java2js complier.

If you've never heard of [Google Web Toolkit](http://code.google.com/webtoolkit/), it's a compiler for Java that instead of generating bytecode generates Javascript. It has the capability of producing highly-compact, obfuscated JavaScript that can be efficiently transmitted.

I feel a little dumb for not even considering this possibility. I remember grabbing a copy of GWT just days after it was initially released and compiling a simple 'hello world' application with it. But somehow the idea of using it to cross-compile full-blown Java libraries to JavaScript didn't occur to me. It seemed like something you'd use to build AJAX widgets with.

One problem with this approach could be the limited availability of Java APIs on GWT. Ease of cross-compilation is likely to turn on the dependencies the source code requires, both from core Java itself and externally.

Still I wonder how practical would it be to cross-compile a lightweight cheminformatics library like [MX](http://metamolecular.com/mx/) into pure JavaScript? If it worked, imagine the possibilities...
