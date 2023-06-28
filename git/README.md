## Lets Fix Git

I need issues of git and then we will fix them

---

## Concepts

- Conflicts
- Rebasing
- Force Pushing
- Fast-Forward
- Submodules
- Precommit hooks
- Cherry-pick
- Git prune
- Merge vs rebase arguments
- Git UIs
- Documentation
- Git flow
- Commit messages
    - merge commit messages
- .gitignore
- git blame / praise

## Things that suck for Everyone

renaming files losing history
    - "use git mv"

fighting to be the first person who pushes to a branch

Having to listen to merge vs rebase arguments

Can't handle binary or JDSL or PDFs etc.

## Jokes

I want the opposite of a .gitignore
    - .gittrackme
    - you add tmp/ or node_modules/ here

All merge conflicts will be resolved by just taking the developer with the older Twitter account's changes

Cherry-picking apparently means:
    "suppressing evidence, or the fallacy of incomplete evidence
     is the act of pointing to individual cases"
Which doesn't make any sense, so we are going to instead rename this:
    - yoink

Git Flow is banned, and if you talk about it ever, you have handle all major feature branching merges on your own.

The default editor will now be a fully configured neovim, with telescope, treesitter, harpoon etc. all up and running.

Commit Messages are now entered in the form of madlibs:
    - It checks the number of files changes and has you fill in:
        - I really needed to change 100+ files because: _____________

If you call --force when trying to push to master, and a call with HR is automatically scheduled.

We need to unify theme, half is trees, with branches and trunks and pruning, and other parts are toliet themed. So I think we make it all bathroom themed.

submodules are banned from use. if you suggest using submodules your name will appear exclusively in Git Blame until the next mention of submodules.

the only precommit hook allowed is one that tweets "I'm coding!"

No more git blame or git praise. I want `git who`, once I know who wrote it, then I'll decide if I'm gonna praise or blame.

Branches have to all be named, with the original, author and date
    - This isn't funny, need a joke

Know knows how the internals work
I don't have a trades degree
(I don't have a degree in plumbing)

## Categorizing Tweets

Don't Teach In College (3)
https://twitter.com/GrantStarkman/status/1671647980573855744

Irreversable Mistakes

Git (1)
 - https://twitter.com/oppliger/status/1671961523210559488
 - https://twitter.com/Enapiuz/status/1671618397249978376

Hub (4)
 - https://twitter.com/teej_dv/status/1671595187351572480

Master -> Main argument
 - https://twitter.com/shindashis/status/1671906718635155457



Conflicts (17)
 - (general) https://twitter.com/gyurisc/status/1671731749695397888
 - (rebase) https://twitter.com/trashh_dev/status/1671595776404000768
 - funny idea: https://twitter.com/wartabPSR/status/1671594473548140545

Rebase (19)
 - Terminology is confusing

Using a GUI (3)
 - https://twitter.com/OtterPy/status/1671609098675142657
 - being scared around the gui: https://twitter.com/khys_aman/status/1671893721699450882
 - more ui: https://twitter.com/pdesjardins90/status/1671597956196188161

People Who Don't Use It (5)
 - https://twitter.com/edwardoverthere/status/1671955099617296407
 - Teammates: https://twitter.com/rodohale/status/1671640618798583809

More AI
 - https://twitter.com/paulsancer/status/1671625542997508099

Most Offensive thing about git

Force Push

SubModules (2)

Rebase vs Merge argument (2)
 - https://twitter.com/Marcusjrc2/status/1671593659983093762

Long Lived Feature Branches (2)

Stash (1)
 - https://twitter.com/1mikegrn/status/1671628135568392192

When you need a Wizard (4)
 - https://twitter.com/sauhaarda/status/1671600129101676545
 - https://twitter.com/ScottLilly/status/1671721581465223170
 - https://twitter.com/ryanrwinchester/status/1671593683156705280
 - https://twitter.com/mannyistyping/status/1671657019344924673
 - https://twitter.com/pen__jelly/status/1671640875540045826

Commit Messages (1)
 - https://twitter.com/nicoorfi/status/1671734015689367552

Wat (1)
 - https://twitter.com/beginbotbot/status/1671638165491433472

Git Flow (1)

Pronounce It Correctly (1)
 - https://twitter.com/robzolkos/status/1671691820772753408

Deleting Folders via Symlink (1)
 - https://twitter.com/DrSammyD/status/1671613686287421443

.gitignore
 - https://twitter.com/KansaiGaijinEng/status/1671593879517425665

Honorable Mentions
 - https://twitter.com/shoeboxdnb/status/1671593389194899456
 - https://twitter.com/nosajio/status/1671620409425313795
 - https://twitter.com/ingwar_samestuf/status/1671595698331037696
 - https://twitter.com/DavidMeirLevy/status/1671615215236968450
 - https://twitter.com/hputzek/status/1671631537484312577

Just Use SVN (3)
 - https://twitter.com/brunolanevik/status/1671593487983075340
 - NOT SVN: https://twitter.com/MotoKris221/status/1671623130836611073

Detached Head (1)
 - https://twitter.com/devuxer/status/1671624619831205888

Window's Users
 - https://twitter.com/_rauldias_/status/1671661401507545091

## Outline

- Intro
I heard you, 500 responses on why everyon's favorite VCS sucks.
Merge vs Rebase
Submodules
Conflicts
Branching
Commit Messages
Hooks
Using a GUI vs CLI
Cherry-picking
Force Pushing
Rerere, Reflog, bisect?

- Jokes
    - The Name
        - Need a Joke
        - Jit -> Gif
        - First of all you've been saying wrong
        - Git is an insult
        - Jit is a version control system
    - no more debating merge VS rebasing
        - no rebasing on fridays or weekends, or major federal holidays
        - no rebasing or merging on mondays before 11AM montana time
            - I don't care Tom if you refactored the whole app into Rust this weekend
              we get it you're a genius
    - What about conflicts
        - simple:
            - when merging, you always take the developer with the older twitter account
            - when rebasing, "Since theirs as ours and ours as theirs,
            you will use the youngest github (or gitlab) account for merge"
        - So you never have to worry about that again.
        - It can be automated
    - if the conflict is within 10 mins, you can challenge the conflictee to typeracer,
       fastest merges first
        - marquees of queensbury rules
       - unless chara-chorded keyboard, in that case you flip a coin

    What about Force pushing?
    - --force calls HR
        (meet with karen)
       - if --force-with-lease is used, it calls the police
            (copilot wrote that joke)

    - Git Branching & naming Rules
        - You start the week with 5 branches, Juniors get 2
            - Every meeting you schedule, or time you suggest rewriting something in Rust
            you lose a branch
            When you're out of branches, you have to work off master.
        - Branches don't roll out week-to-week
        - if you don't use all your branches,
          - you can have to groom the Jira backlog for 1 hour per unused branch.
          - 1 day of on call support

    - We got to talk about commit message:
        - no more: "fixes bug" at midnight commit messages allowed.
        - All commit messages should rhyme
    - Commit Messages & Default Editor
        - fully configured neovim, to theprimeagans detailed speicfications,
          69.420 -> Copilot, telescope, treesitter, harpoon, undotree, fully configred LSP
        - a fully configured waifu in the background

    - submodules:
        - if you suggestion submodules, all changes will be in your name,
        until the next person suggests submodules

    - Git Flow BANNED - rant
        - David Farley
        - Git Flow is Scrum Courses for DevOps nerds
        - Git Flow -> is an MLM

    - The Internals + Degree Joke
        - and I don't have a plumbing degree, if you need to git bisect reflogs,
          new rule: don't mess up our entire git history
          just call the Wizard Tom.
        - Don't even try

    - Using GUI BANNED - rant
    - GUI VS CLI
        -> Lazy Git
        -> GUI in terminal


    - git blame/praise is now named git who
        - I'll praise it after I find out who wrote it. If it's that hotshot tom, then its blame.
    - git cherry-pick is now called git yoink

    - .gitignore + .gitwatch
        in addition to the gitignore theres a gitwatch.
        IF I WANT TO TRACK NODE_MODULE, I WILL TELL YOU I WANNT TRACK NODE_MODULES
        node_modules
        .env
        .DS_Store
        out
        tmp/
        build/

    - Precommit Hooks tweets
        - The only precommit hook we have, checks all repos for precommits,
          and if it finds one, you're on call for the next 24 days.
          if you are caught using -n, you're on call for all major WoW releases.
          all triple-AAA game launc

- Maybe: Final rule, now that we've laid out the plan to fix Git, no suggestion of VCSs,
conversation closed.

- Outro w/ C++ tweet

## Script

### Intro


/*
 * NONE OF THIS
But it how did it win the version control wars!

New programmers don't even know the difference between Github and Git

Yet everyday there are millions of juniors around the world struggling with merge conflicts.
Making repos that look like a game of Guitar Hero

Many have tried to fix Linus's Mad creation before:

Papers have been written
https://homes.cs.washington.edu/~rjust/courses/CSE403/gitless.pdf

People have tried making it more friendly: tig, gitless, cogito
all with little adoption!

New GUI clients pop-up everyday, so grifters can pump out: "Top 10 Git GUI clients for developers in 2023"

But it's time I lay down the law, and fix this mess Linus got us into.
*/

### Jokes

First Things First:
    The name git: it's an insult!

Next this themeing: it's half tree based and half toliet based

### Outro

Now I'm now going to implement any of this, that's left as an excercise for the viewer.

I started trying to do some of this in C++

...but now I'm trying to fix that language first.

Respond to the tweet here, here
