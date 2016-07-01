## Differences from upstream [react-templates](https://github.com/wix/react-templates)

* [[PR]](https://github.com/igetgames/react-templates/pull/1) Upgrade to React [v15.1.0](https://github.com/facebook/react/releases/tag/v15.1.0)

Based off of this [pull request](https://github.com/nippur72/react-templates/pull/5), and I also updated the react and react-dom versions in package.json.

* [[PR]](https://github.com/igetgames/react-templates/pull/2) Update README.md for fork

I changed the Travis CI badge in README.md to point to my fork, to better test changes not present in upstream.
I also added this document to note all of my changes.

* [[PR]](https://github.com/igetgames/react-templates/pull/5) Cherry-pick [this commit](https://github.com/nippur72/react-templates/commit/696144b707fc530b1fc3e5baf4bcac1f2d9f577b) to nest functions generated by `rt-scope` into the template render function.

* [[PR]](https://github.com/igetgames/react-templates/pull/9) Cherry-pick [this commit](https://github.com/nippur72/react-templates/commit/b1b29c2cf088a94be6e22cbc6557b3b3263d28ba) to fix [wix/react-templates#162](https://github.com/wix/react-templates/issues/162).

* [[PR]](https://github.com/igetgames/react-templates/pull/10) Cherry-pick [nippur72/react-templates@3b288f0](https://github.com/nippur72/react-templates/commit/3b288f0bc6151a553a9542f438145534c1085ff5) and [nippur72/react-templates@40b46a9](https://github.com/nippur72/react-templates/commit/40b46a9ceecc93dd9e62be0b2e42a0460bba385c) while removing comment sanitization tests that will come in a later PR.

* [[PR]](https://github.com/igetgames/react-templates/pull/11) Cherry-pick [nippur72/react-templates@8955efa](https://github.com/nippur72/react-templates/commit/8955efad9207c00f929038640ef0d83bad4e2207) and restore the tests removed in PR 10 to fix [wix/react-templates#158](https://github.com/wix/react-templates/issues/158).

* [[PR]](https://github.com/igetgames/react-templates/pull/12) Cherry-pick [nippur72/react-templates@3b0e355](https://github.com/nippur72/react-templates/commit/3b0e3557541d181d20ff202a109a661fe285547d) to fix [wix/react-templates#144](https://github.com/wix/react-templates/issues/144).

* [[PR]](https://github.com/igetgames/react-templates/pull/13) Cherry-pick [nippur72/react-templates@86abe5f](https://github.com/nippur72/react-templates/commit/86abe5fb899b7a296e5f60dd1a949762a86e0107) to satisfy [wix/react-templates#146](https://github.com/wix/react-templates/issues/146).
  Rename the option from `normalize-whitespace` to `normalize-html-whitespace`.

* [[PR]](https://github.com/igetgames/react-templates/pull/15) Integrate [my fix](https://github.com/wix/react-templates/issues/164) for [wix/react-templates#163](https://github.com/wix/react-templates/issues/163).