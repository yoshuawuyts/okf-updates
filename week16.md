# Week
last week I've been tinkering around with the threading model in Rust, which has
been lots of fun. However, halfway through the week I came to the realization
that the existing threading model won't work with WASM, so I had to dig in
further.

## What did you do last week?
- merged varint patch
- reviewed C-FFI Code
- ran the rust meetup
- met up with Tyler Neeley
- realized the `from_pager()` method is a dead end for our bitfield modules
- dug into WASM, and realized the threads model is a dead end too
- tried out hyper / futures for TCP connection

## Which goals didn't you meet last week?
Worked on both goals extensively, but both of them turned out to be dead ends.

## What are you planning to work on this week?
- Get a future-based version of our connections working.
- Figure out what it takes to restore the memory layout to disk, and vice-versa.
- Investigate the networking stack.

## What's blocking you?
- Nothing much!

## This Week's Video Archives
- https://www.youtube.com/watch?v=kOhH1Igo6Ps
