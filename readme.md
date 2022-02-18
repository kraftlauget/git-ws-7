# Present your work with Git and Rebase

## Exercise 7 - Rebase and split a commit

Scenario:

- You've been working a little bit more on that menu.
- So far you've been putting the menu stuff into the basic layout commit.
- You're starting to feel that the layout and menu should be two separate commits.
  - Because you're quite happy with the basic layout but the actual menu is its own component contained within the layout.
- Also, teammates are quite eager to get the basic layout integrated into `main` branch as soon as possible.
  - There's no reason they need to wait for the menu to be finished.
- You realize your attention got split a bit and you're now working on two features: the awesome rolling rick + the menu.
  - Splitting the menu work off into its own commit will help putting that work on hold and keep focusing on Rick.
  - The menu work could even be moved out into its own branch, to be later picked up again by you or someone else.

Instructions for exercise:

- Checkout branch `start`.
- Create a new branch `exercise`.
- Have a look at the commits in `solution` branch.
- Rebase the `exercise` branch and choose to edit the layout commit.
- Soft reset the layout commit.
- Stage the basic layout parts and commit (need to type the commit message again).
- Stage the menu parts and commit with message as shown in `solution` branch.
- Continue rebase.
- Rebase and reorder menu commit as shown in `solution` branch.

Tips:

- [Rebase](https://git-scm.com/docs/rebase) the `exercise` branch and choose edit option.
- Use a GUI client such as [GitExtensions](http://gitextensions.github.io/) (Win), [Fork](https://git-fork.com/) (Mac + Win) or [GitKraken](https://www.gitkraken.com/) (Linux, Mac, Win) so that you don't have to figure out the git cli commands for doing the above.
- I've written a bit about editing commits using GitExtensions on [my blog](https://blomholm.no/posts/how-i-git-it-more-rebase/#pause-the-replay-and-make-changes-to-a-commit)

[Click here for next exercise](https://github.com/kraftlauget/git-ws-8)
