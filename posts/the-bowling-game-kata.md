---
title: "The Bowling Game Kata"
date: '2012-02-25'
description: The blog post that started a flood of writings.
categories: ['changeblog']
---

_Editor's Note: Many of my reposted works will have slight updates to the
writing, including grammar corrections and sometimes restructuring of the
sentences. If the originals are desired, I will post them separately. Without
further ado; The Bowling Game Kata, written, February 25th, 2012._

This was a difficult blog post for me. It started a few days ago, not too long
after my last post on the blog. As a sidebar, I feel like an idiot for not
working with the other blog more, yet. But that's neither here nor there,
because my focus in the last few days have been the katas.

The programming kata is nothing new at all. Sites such as Project Euler, Ruby
Quiz, Code Kata, Less Than Dot's Exercises, The Python Challenge and, more to
the point of this writing, Uncle Bob's Bowling Game Kata, advertise these
exercises and practices you can undertake, given certain levels of help or
assistance, or none. The problems are build to exercise all one's abilities as
a programmer, but with a strong focus on algorithms, abstraction and abstract
concepts, and in some cases learning a specific it language; of them all, the
Bowling Game is my favourite.

I won't sit here and write out the code patterns that are posted as a .ppt file
at Uncle Bob's site, because they're already there. I will, however, discuss
the rather detailed insanity that precluded finishing the kata for the first
time, in the language for which it was designed: Java.

It would be important to start by saying I wasted a lot of time wondering what
languages I could write this in, easily, and not see much of a conflict between
what the kata shows in Java and what I write in Language X. I tend to do this a
lot; I love trying to figure out what language might be perfect for the
situation. And while people might say that proting this to other languages, to
exemplify both clean code and tests in those languages might have been the
better idea, it wasn't the idea for this exercise. I had to finish the kata
once, a kata I've never done before.

It looked easy at first, the night before last. I sit down, I study the
material from end to end a few times. I go to sleep to see if I wake up and
still think it's a good idea. Still a good idea, we're go. So I sit down and...
grind to a halt. It's yesterday, now. I don't have any Java tools or
environments. Wait, yes I do, I just haven't used them in forever. Pull up the
command line, lose a couple hours googling for what should be obvious at this
point. Take a break, frustrated, mmove on to work that's actually moving and
progressing at a pace.

It took far longer than seemed necessary to end up at Eclipse with the Maven
and JUnit plugins to accomplish this simply and effectively, in a way I could
follow from start to finish. It didn't take terribly long to get started into
the test-driven design of the kata, however there were details in that
presentation that made a great difference, but also irritated me greatly.

The kata takes you through producing the simplest working solutions to the
tests, instead of the entire problem, and tends toward the quickest, if not the
cleanest or most optimal, answer to the problem. This is how TDD afficionados
like it, and while I feel their aim is merely a degree off, I agree with what
thy point out in their 'passes the test' code. It slowed down after the second
test. It became a little more focused, having to sit and see what I clearly
didn't like but does, in fact, pass the tests, stepping through and cleaning
these things out until I both pass the tests and match the commentaries in the
example of the kata.

I took a break between tests 3 and 4. It has been a long time since I've found
myself at this point of balance, focus and broad-view. But tests 4 and 5 when
remarkably well; they started so ugly.

I won't say that what I wrote came out exactly like the kata. For one, I hated
their taste in method/variable names. I also use a slightly more compact style
with my braces and parentheses. But I did learn what I was supposed to learn
from my first full walk through it. I'm going to, for a few more days, go
through the kata until I have it memorized. And then, on my professional blog,
I'll be posting the Bowling Game Kata in other languages; specifically C++,
Haskell, and Perl. I might do others.
