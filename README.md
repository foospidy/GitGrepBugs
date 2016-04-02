# GitGrepBugs
Grep Bugs with Git

The goal of this script is to be able to scan git repos with GrepBugs (http://www.grepbugs.com) rules and requiring little to no dependencies. Currently the only dependency is a `bash` shell and the `git` command. Git has some really good search capability, you can find a great introduction by @travisjeffery here http://travisjeffery.com/b/2012/02/search-a-git-repo-like-a-ninja/

### Usage

Examples below assume the GitGrepBugs script is in your PATH.

Example 1:
```
git clone https://github.com/<user>/<project>
cd <project>
GitGrepBugs
```

Example 2:
```
git clone https://github.com/<user>/<project>
GitGrepBugs <project>
```

### Output

Currently results are just printed to the console. You can redirect the output to a file, example:
`GitGrepBugs <project> > results.txt`
