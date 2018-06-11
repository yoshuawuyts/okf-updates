# Week 5
## What did you do last week?
- Fixed flat-tree iterator logic. Third pass on this module, but we're now
  mimicking the original behavior, so it should be stable.
- Fixed 3 regressions in `memory-pager`. Fixed all known bugs in
  `hypercore/bitfield`, adding tests in the process.
- Met up with Tyler; patched a bug together in tree-index. Added a full property
  test suite in the process, so regressions will probably no longer pop up.
- Worked on storage backend. Struggled a bit with Rust's lifetime system, but
  figured out how specializations work and now it's all exactly like planned.
- Livestreamed hypercore development on Twitch. Interacted with folks from the
  community.
- Created a [design doc](https://github.com/datrs/hypercore/issues/2) to rework
  Hypercore's internals.
- Performed half of the planned rework.
- Started work on the [peer-to-peer day](https://peer-to-peer-web.com/) talk for
  next week.

## Which goals didn't you meet last week?
- Actually met most of what I said I would!
- We didn't make a lot of progress with hypercore's feed, but got 3 methods
  done, with a 4th one coming up!

## What are you planning to work on this week?
- Planning to get at least one method in hypercore done.
- Want to do a good job at the peer-to-peer day talk; so might spend a day or
  two on that.
- Forthnightly Rust hacking at Mozilla is coming up again on Wednesday, so will
  probably check that out.
- Tuesday is a national holiday, so not working.

## What's blocking you?
- I'm not sure how to invoice for national holidays.
- Also: I'm not sure how sick days / vacations work - given we're contractors I
  guess we wouldn't invoice then. But can we then work for extra time after the
  deadline?
- Hypercore is still tricky to decypher. Feel like I'm refactoring quite a lot.
  We're making progress, but because we're not getting things right the first
  time, it feels like we're moving slower than expected. It still feels okay
  though, the code does end up feeling super reliable!
