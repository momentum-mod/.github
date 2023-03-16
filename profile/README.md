Hello!

This is the Github organization for all open-source parts of [Momentum Mod](https://momentum-mod.org)’s codebase, primarily our [website](https://github.com/momentum-mod/website) frontend and backend, [game UI](https://github.com/momentum-mod/panorama), [docs](https://github.com/momentum-mod/docs) and various tooling software. It does *not* contain our base game code, which due to licensing restrictions is closed-source and not on Github - though our game files prior to going closed-source in 2021 can be found in [game](https://github.com/momentum-mod/game), which we still use for an issue tracker.

We welcome contributions to all active repositories in the organization, but please either work on changes mentioned on issues boards, or first discuss other potential features with us in our [Discord](http://discord.gg/momentummod).

We request all contributions follow these guidelines in all repositories (besides docs):

 - Keep your branch up-to-date by rebasing, not using merge commits. We consider merge commits to be a major detriment to the quality of a Git repo, and will always ask you to remove any merge commits in code review, even if this means force-pushing.
 - Keep your commits clean and simple, splitting all changes into separate commits.
 - Don’t push commits specifically for addressing issues in earlier commits, including those brought up in code review. Instead, make those commits then `fixup` them into the original commit using an interactive rebase. Again, we have no problem with force-pushes; so long as you make sensible local backups, we feel that rewriting history of non-master branches is a necessary evil to avoid merge commits. For a general guide on this workflow, see here.
 - Name your commits using [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/#summary). If in doubt, just check the rest of the history of the repo and follow that.