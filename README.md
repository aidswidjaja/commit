# ACC - Adrian's Commit Codes
## Version 1.0 - 8 November 2019

Commit codes can be used to identify what the purpose of a commit is. For larger commits you should still use proper descriptions. These are guidelines only and can be adapted for personal use under the Unlicense.

- `B-123/3-TEAM` - Bug fix, where `123` refers to the issue number
- `F-123/3-TEAM` - Feature update, where `123` refers to a number that identifies the feature (for example a number on a tasklist or sequential ordering of feature updates)
- `E-123/3-TEAM` - Enhancement (that isn't big enough to be a feature), where `123` refers to a number that identifies the enhancement (for example a number on a tasklist or sequential ordering of feature updates)
- `G-123/3-TEAM` - File management/Git management updates such as commit reverts and merges. See below for exceptions.
- `R-1.23AX/3-TEAM` - Ready for deploy/release – A commit that a release/package is based off, where `1.23` refers to the release/package number, and `A` refers to: Pre-Alpha/Prototype `P`; Alpha `A`; Beta `B`; Canary/Nightly `N`; Release candidate `S`; Final version `F`. In the situation of Releases, use `G-1.23` where `G` is the prefix.
- `O-123/3-TEAM` - Other

The `/5` in the above examples refer to a scale of importance. 

- `/1` is low importance (e.g minor bug fix like escaping characters)
- `/2` is medium importance (e.g project enhancement/code cleanup)
- `/3` is high importance (e.g major bug fix/product release)

The `-TEAM` refers to the team(s) that should be involved. For example, a bug fix might solicit a `-BUG` suffix, or a feature release a `-FEATURE`. Only use `-TEAM` if you need community interaction, otherwise leave blank.

The above commit codes can also be used for issues.

Last modified 8 Nov 2019 (AEST)
