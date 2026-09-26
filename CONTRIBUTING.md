# Contribution terms

These terms apply to every contribution to a Next Web Working Group repository. A repository's own
`CONTRIBUTING.md` explains how to work in it; these terms still apply.

## Sign off every commit

Add a `Signed-off-by` trailer to each commit to certify the
[Developer Certificate of Origin 1.1](https://developercertificate.org/): that you wrote the
change, or otherwise have the right to submit it under these terms.

```sh
git commit -s                 # sign off a new commit
git rebase --signoff main     # sign off the commits already on your branch
```

Pull requests with unsigned commits fail the `DCO` check.

## What you agree to

By signing off, you make your contribution under the
[W3C Community Contributor License Agreement](https://www.w3.org/community/about/agreements/cla/),
reading the Next Web Working Group in place of the Community Group, and each specification the
group develops as "the Specification". That means you grant:

- a perpetual, worldwide, royalty-free copyright license to your contribution; and
- a royalty-free license, on the W3C royalty-free terms, to any patent claims of yours that are
  essential to implementing the specification your contribution is part of.

These commitments continue if the work moves to a W3C Community Group, the Web Incubator Community
Group, or a W3C Working Group, so a proposal can move without asking past contributors again.

Specification text is published under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
and code under the MIT license, as each repository's license files state.

## Conduct

Participants follow the [Code of Conduct](CODE_OF_CONDUCT.md). How the group makes decisions and
how contributors gain roles is in [GOVERNANCE.md](GOVERNANCE.md).
