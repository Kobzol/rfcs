- Feature Name: N/A
- Start Date: 2026-07-20
- RFC PR: [rust-lang/rfcs#0000](https://github.com/rust-lang/rfcs/pull/0000)
- Rust Issue: N/A

## Summary
[summary]: #summary

Adopt [guidelines] for using AI tools and other Project-wide AI policy items.

## Motivation
[motivation]: #motivation

In the Rust Project, we've seen an increase in unhelpful contributions, particularly where contributors used AI tools.  These are frustrating and costly to reviewers.  We need to find ways to reduce the number of these and to lower the cost of handling them.

We hope that by providing [guidelines] with clear expectations that fewer contributors will send us unhelpful things and more contributors will send us helpful ones.  We hope that this will make decisions and communication less costly for reviewers and moderators.

At the same time, the *process* of agreeing on an AI policy has been costly.  Project members have many reasonable and diverse views about AI tools and their appropriate role in society, in open source communities, and in the Project.

This RFC seeks to adopt an intersection of agreement to mitigate the most acute harms in front of us.

## Reference-level and guide-level explanation
[reference-level explanation]: #reference-level-explanation

The [guidelines] below are Rust's policy on the use of AI tools when making contributions to the Rust Project.  Teams may extend the guidelines within their own spaces, and they may relax restrictions in the guidelines except those concerning [comments].

Teams may not alter the policies in this section.

The guidelines may be cited in or copied to all places where we guide contributors on our expectations.

Repeatedly falling short of the normative part of the guidelines (the *do* and *do not* items), after being notified of them, is disruptive and a form of "other attention-stealing behavior" described in our [Code of Conduct].  When this causes conflict or tension, consider raising it to the moderation team.

A maintainer may decline to review a contribution for any reason, including that it appears to have been produced using an AI tool and the maintainer does not want to review such work; no team may require otherwise.

No policy or procedure of any team in the Project may require the use of an AI tool; teams must ensure that it's possible to perform all processes manually.

[Code of Conduct]: https://rust-lang.org/policies/code-of-conduct/

## Guidelines for using AI tools
[guidelines]: #guidelines-for-using-ai-tools

### Be in the loop
[be in the loop]: #be-in-the-loop

As the author, you're fully responsible for anything you send us (e.g., code, documentation, descriptions, reports, proposals, comments).  Before submitting, *do* review, understand, and be able to explain it.  *Do* be the human in the loop.  We *do not* accept fully autonomous contributions.  Consider describing how the work was produced; this helps reviewers give better feedback.

### Comments
[comments]: #comments

In comments (and messages, posts, etc.), we want to hear from *you*.  *Do not* simply copy AI output when commenting or replying.

It's OK to use AI tools for translation.  Consider including your original message or mentioning that automated translation was used.

Including raw AI output in an attachment, such as for a security report, is OK, but *do* discuss it and how it was produced in your own words.  Consider speaking to why it's useful and the degree to which you've reviewed it.

## Drawbacks
[drawbacks]: #drawbacks

In adopting any policy for contributions, we'll be asking more of our contributors.  On the other hand, this policy might help those contributors by providing clarity on what we expect.

Some may view the adoption of a policy that does not ban the use of AI tools as an implicit endorsement.  That's not what this is, but it's not always possible to prevent people from getting the wrong idea.

## Rationale and alternatives
[rationale and alternatives]: #rationale-and-alternatives

This policy encourages but does not *demand* disclosure of use.  Some feel strongly this should be demanded.  Others feel strongly this causes [harms].  This RFC adopts the intersection of agreement.

This policy reduces the autonomy of teams in some places and preserves it in others.  Where it preserves autonomy, that lets teams fit their practices to their unique work and circumstances but can make the Project feel more uneven.  Where it restricts autonomy, this promotes homogeneity but may interfere with teams that have unique needs.  This RFC tries to strike a balance.

[harms]: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5205850

## Prior art
[prior art]: #prior-art

Python adopted a [similar policy][Python AI policy] in [python/devguide#1778].  The Crates.io team adopted the Python policy in [rust-lang/crates.io#13726].  This RFC also draws ideas from the [Astral AI policy], [LC#273], [RFC 3936], [RFC 3950], and from the discussion in [rust-lang/rust-forge#1040].

Many other open-source projects have adopted various policies, and within the Project, various policies have been proposed or adopted.  In the interest of keeping this brief, we declined to attempt to exhaustively survey those here.

[Astral AI policy]: https://github.com/astral-sh/.github/blob/main/AI_POLICY.md
[Python AI policy]: https://devguide.python.org/getting-started/ai-tools/
[python/devguide#1778]: https://github.com/python/devguide/pull/1778
[rust-lang/crates.io#13726]: https://github.com/rust-lang/crates.io/pull/13726
[rust-lang/rust-forge#1040]: https://github.com/rust-lang/rust-forge/pull/1040
[LC#273]: https://github.com/rust-lang/leadership-council/issues/273
[RFC 3936]: https://github.com/rust-lang/rfcs/issues/3936
[RFC 3950]: https://github.com/rust-lang/rfcs/pull/3950

## Unresolved questions
[unresolved questions]: #unresolved-questions

None.

## Future possibilities
[future possibilities]: #future-possibilities

This RFC seeks to mitigate the harms in front of us.  In the future, we may decide other things.  The world is moving quickly.  Let's adopt an intersection of agreement today and then see what happens later.

## Acknowledgments

@Kobzol coauthored this policy with me; thanks to him for that fruitful collaboration.  Thanks to the authors of the [Python AI policy] and the [Astral AI policy] for helpful ideas.  Thanks to all those who left useful feedback on the earlier policy drafts.

All errors remain mine alone.
