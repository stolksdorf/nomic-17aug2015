# what is nomic

Nomic is a game in which changing the rules is a move. In that respect it differs from almost every other game. The primary activity of Nomic is proposing changes in the rules, debating the wisdom of changing them in that way, voting on the changes, deciding what can and cannot be done afterwards, and doing it. Even this core of the game, of course, can be changed.

# how to play

All you need is a github account. All rules will always be recorded in the [README.md] and all scores will be recorded in the [Scoreboard.md].

### propose a rule change

1. Click the `README.md` ![](http://i.imgur.com/gtWUHWd.jpg)
2. Click the lil' pencil icon to edit the file ![](http://i.imgur.com/rGYJ88i.jpg)
3. Write your proposed change in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Give a short title to your change, and an more in-depth reasoning behind it. Then click `propose file change`. ![](http://i.imgur.com/3rlMJVc.jpg)
4. Click `Create Pull Request` twice and you're done!

### comment and vote on changes

1. Click the Pull requests tab off to the left. ![](http://i.imgur.com/eP2OUwe.jpg)
2. Find the open pull request (there should usually only be one)
3. Write your comment or vote. For voting, start your comment with "AGREED" or "DECLINE", followed by X/Y, which stands for how many people are in favour / how many people have voted. This gives us a easily check-able state of voting at a glance. ![](http://i.imgur.com/F1j6NF0.jpg)

### what about randomness?

Some parts of the game may require randomness. We will be using a random number site that lets us set seeds. We will use the initial git commit of the pull request in question to generate the random number.

for example: `bca7e9b2476aa1d42c13196b358e847b388b3a6c` is the git commit hash of [Scott's first pull request](https://github.com/stolksdorf/nomic/pulls), so [https://www.random.org/integers/?num=1&min=1&max=6&col=5&base=10&format=plain&rnd=id.bca7e9b2476aa1d42c13196b358e847b388b3a6c](https://www.random.org/integers/?num=1&min=1&max=6&col=5&base=10&format=plain&rnd=id.bca7e9b2476aa1d42c13196b358e847b388b3a6c) will get a random number between 1 and 6, using this as the seed. Therefore it will always be 4.

### moderators

Each moderator will be set as a `collaborator` on the github repo, all other players will be `contributors`. Their job is to merge in approved pull requests, close disapproved ones, and update scores if need be. We will have **two moderators**: Jared and Scott. If we feel the need to appoint more, we can. Just let the mods know.
