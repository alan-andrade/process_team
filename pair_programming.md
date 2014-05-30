# Pair programming

This guide assumes that you accept pair programming as a practice that
yields code with relatively higher quality and that is beneficial for
the company.

If you aren't committed to pair programming because you don't believe on
the gains you can get, then stop reading and do something else. Don't
waste your time.

If you aren't committed because previous experiences were frustrating,
please keep reading. After you finish, you'll have a better idea of
_how_ to pair with somebody else successfully and have a good time doing
so.

## Testing is fundamental

You need feedback from the system you're building. The fastest the
better.
Discussion is good, but code has better arguments than words.

## Take small steps

> Divide and conquer

Describe the face of some potential symptoms.

- When testing becomes harder that the problem itself
- Dependecies start to itch
- After 30 minutes, you haven't accomplished anything.

## Styles of pair programming

__ EDIT __
He has been facilitating coderetreat workshops for 5 years and has
paired with all sort of developers: Newbies, experienced pair
programmers, rockstars with no pair programming notion, and so forth.
According to his observations, there are pair programming styles that fit
different type of programmers. Let's review those styles.

### Driver - Navigator

This is the traditional approach and very often fails to succeed.
Unless the developers have a very strong communicative skills and they
keep a _constant_ process of sharing thoughts, the Navigator role is
easy to get distracted.

If you have seen a "pair programming" session where one of the pair is
checking facebook or twitter, then you know what a failed session looks
like. When you pair, beware of this symptom and try to communicate more,
or switch the style.

### Ping-Pong

This style relies strongly on having descent _testing skills_ since the
fundament of this style is to make red tests go green. These are the
roles you can play:

- __Test redder__ : Write a test that contains missing functionality,
  run it, shouldn't pass.
- __Test greener__ : Make the red test go green by writting the missing
  implementation.

There are two variations of this style and the difference relies on the
right time for each member to switch roles. For example, you could always
be the test redder and your partner the test greener. If that starts to
feel monotonous, you could try being the test redder and test greener.
Your partner would play both roles as well when you finish being both.

> Taken from this [article](http://articles.coreyhaines.com/posts/thoughts-on-pair-programming/)
> from [Corey Haines](https://twitter.com/coreyhaines).
> He has more than 10 years of experience with pair programming.


### Which one should I choose?

There's no perfect answer to this question because it depends on the
developer's skills and objectives. However, there are a couple
guidelines you can follow to make a decision.

1. If one member has experience with tdd, but the other doesn't,
   Driver-Navigator might be a good fit.
2. If both members have experience with tdd, Ping-Pong is highly
   recommended.

# Not all the time is pair programming time

As surprisingly as it sounds, there has been some research about the
[cost and benefit of pair programming](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.67.4205&rep=rep1&type=pdf).
We don't need to dive into the internals of the study, you can do that
yourself in your free time, but basically the point is that pair
programming won't always pay off. It depends on external variables.
Is a fact that pair progamming (done correctly) increases the speed of
developement yielding much higher code quality. However, we need to take into
consideration the "market pressure" to make a decision.

> Factors such as the development time, development cost, and net present
> value of the project are some examples of market pressure.
> Pair Programming __only pays off__ under strong market pressure

If you're interested in a case study of pair programming, read this
[paper](http://www.inf.fu-berlin.de/inst/ag-se/teaching/V-SWT2-2008/doc/MulTic01.pdf)
which shares the experience of using extreme programming (therefore
constant pairing) in a university's project. It was tough and frustrating
at the beginning, but afterwards software got delivered on time and with
small bug rates. Moreover, the developers found it "enjoyable".

Since TDD is an overlapping concept with this guide but not the main
interest, you can find another case study
[here](http://research.microsoft.com/en-us/groups/ese/nagappan_tdd.pdf),
which explains how Microsoft and IBM were able to ship new products in
less time with 60% less errors than previous projects that were using
conventional software development techniques.

# Conclusion

TODO
