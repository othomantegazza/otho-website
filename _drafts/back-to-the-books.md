---
title: Back to the books
date: 2017-06-01
---
+++
draft: true
+++


# Back To The Books

Recently, toward the end of my PhD, I was struggling to learn new
skills such as writing with LaTeX and R programming.
At that time I somehow rediscovered (duh!) books.

I also have been always fascinated by **Open source
Software** and by the **copyleft movement** (I also was not earning a
huge amount of money during my PhD and I did not know how long it would take to
find a job afterwards). It was at that time that I discovered
open books: such as *wikibooks*, *Git books* and any other kind of openly
licensed book.

## Communication in academia

As young scientist in plant biology, I feel strongly pushed toward writing
academics papers. This make sense, we communicate our research through peer
reviewed papers, and use this to make a career; but I often feel that we are
focusing too much on writing papers and that we neglect other forms of
communication.

Today we have a many communication media at hand, such as, indeed, the
**academic paper** or **review**, but also relatively new media such as **blogs**,
**wikis**, **videos** and **podcasts** and nevertheless **classes**, online
and not. Among those, for personal experience, **books** have a great impact when
somebody has to **learn something completely new** and when kept as reference.

Overall, books remain a practical **unit of knowledge** and since the role of
academics is to generate and redistribute knowledge, book writing should be highly
rated in an academic career.

## Git tracked books

I am impressed by the potential of **open Git tracked books**. people from statistics, programming and data analysis are already implementing this model.

For example Hadley Wickham's [Advanced R](https://github.com/hadley/adv-r),
R. Irizarry and M. Love [Biomedical data science](https://github.com/genomicsclass/book),
or R. Peng [R programming](https://github.com/rdpeng/rprogdatascience) are all
tracked on Git. (*all links point to the source code*)

This makes sense, since people in those fields are often very familiar with the
open source culture and Git. But I could also find a [book on journalism](https://www.gitbook.com/book/towcenter/curious-journalist-s-guide-to-data/details)
(I could not find the source for this one, even though it is free and it is
definitely tracked with Git).

### why git

Git was written by Linus Torvald's team in 2005 and it is a version control tool
that, while developing a program, it keeps track of the changes are inserted and
allows collaborative programming.

The trick here is that the source code of programs is a collection of text files,
so git essentially is designed to track text files, so it can be easily adapted
for book writing, especially text books.

## Technical details

I have to say that I never tried to write a book, and more important, I have never
tried to write using Git and Github.

So there is **Gitbook** that since 2014 provides and easy framework and it's free
for open source. I have to say that I did not understand where they store the
source of the book, Github?

As I understood, Hadley Wickham writes in **markdown** and uses a combination of
**Jekyll** and **bookdown** on [travis](https://travis-ci.org/) for compiling his
book and push it to his website.

Overall looks like the R package [Bookdown](https://bookdown.org/yihui/bookdown/)
might be the choice right now. It takes a **markdown** input and nicely converts it in:

- **HTML** through **pandoc**,
- **PDF** through LaTeX,
- **epub** (always through pandoc?) and also **mobi** through **Calibre**

Moreover Bookdown is very nicely documented and easy to use
and would be my choice if I would write a book.

## good for academics

Git traked open books might (but it is not sure) not bring as much profits as a
normal book. But on the other side a regular book could have much less impact.

And given that [Leanpub](https://leanpub.com/) allows to sell open books written in Git
with a very transparent process while leaving copyright to the author, and given that also
printers as [O'Reilly](https://www.oreilly.com/)
already publish some of its books under permissive licenses; it might be that open
book can also provide some monetary profit (I mean, somebody might buy them anyway,
I did).

But most of all, we, academics, want to get credit for our work, because this is
generally how we get our next contract in academia (and they never last long).

And writing a nice book, rich of content that introduces people to a topic that
we deal with in academia, that goes into the details and that serve as a reference,
might be a good thing to get credit for.

Github allows to get exact credit for your work, because every contribution is tracked.

Another thing is that we want is control on what we do, with Github we can control
contribution, and at the same time if somebody want anyway to introduce
contributions that we might reject, they can always fork our project and go on
on their own path, developing their own product.

In this I think that Books on Github are superior for us academics to wikibooks
We can get credit for it and control the content

While open books might not provide the same profit as static books published
through traditional publishers, they might have much higher impact. Think about a static and expensive book, against a book that people can get for free or for low price, but
moreover, that can be constantly updated and that anybody can edit.

## next

So, looks like the perfect modern tools for text book writing are already there;
right now I do not feel enough
an expert in any of my area of interest to write a book on it. But it sounds like
a good long term project, to identify an area in which I know enough about it
and then start writing an open book. As stated above the tools are all there.
