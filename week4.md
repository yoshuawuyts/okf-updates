# Week 4
## What did you do last week?
- Went to Rust hack and learn on Wednesday.
- Met up with Tyler on Wednesday - helped out for a couple of hours on Rust
  based filesystem / socket testing. Really excited for this work to stabilize a
  few weeks from now! Will come in useful for our DB tests too.
- Met up with Karissa from Code for Science and Society (Dat Project
  Foundation).
- Worked on Hypercore's bitfield implmentation.
- Built the [Speedometer](https://github.com/datrs/speedometer) module.
- Talked to mafintosh how flat-trees work.
- Implemented several more tests on tree-index.
- Built, then re-built flat-tree's Iterator struct.
- Made some progress on
  [human-panic](https://github.com/yoshuawuyts/human-panic) on the side. Figured
  it'd be a useful thing in general, and also helped me brush up my Rust skills
  a bit further by collaborating with folks.
- Met up with some more Rust people in Berlin; will probably figure out a way to
  hang more regularly - fun, but also useful to become better at this!

## Which goals didn't you meet last week?
- Didn't finish hypercore (minus networking). Made progress, but woah did I
  underestimate how much refactoring would be needed on the past modules.

## What are you planning to work on this week?
- Make more progress on Hypercore!
- Still leaving out the networking bit.
- But hopefully I'll get both bitfield and persistence to a reasonable state.
- Peristence might be a stretch goal to be honest; but a start should be
  feasible!
- Start filling in some methods for the Hypercore feed.

## What's blocking you?
- Building Hypercore is tricky. Making progress, but moving at a slower pace
  than I started with. This is predictable, but still a bit disappointed by it.
- Feel this mostly comes because the further I move, the more I realize some of
  the previous mistakes I've maded. For example the week prior I also spent a
  good chunk of time on adding tests for modules whose API was done. But that's
  just projects I guess.
