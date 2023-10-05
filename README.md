# Moo1210's Adonis Fork
A fork of adonis for contributing various features upstream.

The following features are either planned or are in development in a branch to be merged upstream: 

- [x] [bug/fix-adonis-state-2023](https://github.com/moo1210/Adonis/tree/bug/fix-adonis-state-2023) Originally intended to just fix linting, this branch now adds a swift full of changes to help fix bugs, such as adding stack traces to error logs, and fixes the linter, as well as fixes a many different bugs too. ([Draft PR submitted, likely will be ready for review this week.](https://github.com/Epix-Incorporated/Adonis/pull/1216))
- [ ] [feat/improve-adonis-ui-ux-2023](https://github.com/moo1210/Adonis/tree/feat/improve-adonis-ui-ux-2023) Make Core UI elements (such as Window) work better with Gamepads, Consoles, and in VR, on the classic theme. Other cross-platform stuff such as scaling, and other changes. Fix changes made within the last year that harm UX for no reason. See https://github.com/moo1210/Adonis/issues/1 for more details.
- [ ] [feat/improve-github-actions](https://github.com/moo1210/Adonis/tree/feat/improve-github-actions) Reformat, improve, and refactor some of the GitHub actions, because they both make my eyes hurt trying to even look at them, and they're written kind of oddly in ways, such as the releases not adding the builds to the tags/releases.

Expect this to happen in a Adonis 2.0 fork instead, details to be found later, in a soon to be created Adonis_2.0 fork repo.
~~The following features are currently developed within this downstream fork and don't intend to be merged upstream, mainly due to Adonis's current buggy state and poor maintainership.
- [ ] Create the "Modern" Theme with Roact, essentially what was going to happen with Adonis 2.0's, but I guess since that's not happening, I'll make something for the current Adonis. Someone else seemed to have this idea, but it hasn't been touched for a long while, and it doesn't work and has basically no UIs.
- [ ] Create (Or remake, if you can even call the default GitHub pages template that exists currently a thing) an Adonis Website with a fancy homepage, and more importantly documentation pages that don't stink and don't confuse everyone.~~

I'm also working on an Adonis Plugin which I would like to make built-in (although I don't know if this will ever happen, you can definitely always install the plugin manually though, both on my fork and the normal Adonis), which is basically a revamp of F3X and Dex combined in a way, which can be seen at https://github.com/moo1210/Dex.
