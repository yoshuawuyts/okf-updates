# What did you do last week?
- General setup.
- Created github org.
- Read up on DASH vs HLS.
- Met with Louis from Hypervision.
- Call with Caio from NYT about live streaming / collaborating (went real well!)
- Call with former Heroku people to see if we can get more people involved with
  Datrs.
- Multiple chats with Magnus (leveldb maintainer) - he's now helping out on
  Datrs too.
- Created `pretty-hash` module.
- Worked on `sparse-bitfield`.
- Worked on `bit-tree` module.
- Started work on `hypercore`.
- Completed DLR paperwork.
- Hung out with Tyler (@spacejam) to talk more about database reliability -
  offered to help out one day a week.

# What are you working on this week?
- From conversations with Caio from NYT's live streaming group, we found that
  using HLS is probably the right way to go. Also `hls.js` offers all we need,
  so that opens up time in the schedule.
- Going to work more on porting hypercore to Rust. This will allow us to use the
  protocol on mobile, which is a huge win. Feeling we're building up some
  momentum here.
  - Want to port the `bitfield` submodule.
  - Want to port the `tree-index` submodule.
  - Want to port the `storage` module inside hypercore.
- Picking up on `quicktest` on the side to make sure we can ensure our previous
  work actually works.
- Hopefully going to be hacking on Wednesday with Tyler.

# What's blocking you?
- Nothing right now! - things are going well :D
