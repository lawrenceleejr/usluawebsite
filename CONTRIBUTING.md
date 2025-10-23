# CONTRIBUTING

There are many ways to contribute, especially in the content of the pages. The main workflow, unless you're made a Collaborator on the main repo, is to fork this repository, commit your changes, and open a pull request to `main`.

### Workflow

You'd want to clone this repository to your local machine. Since it has a submodule, you'll need to clone with `--recursive`.

```
git clone --recursive {SSH_PATH_TO_YOUR_FORK}
```

You'll need to install `hugo`. See https://gohugo.io/installation/ for instructions on how to do that. 

Then you'll go into the repository and just run

```
hugo serve
```

which will launch a local web server that will let you see your changes live. Then you can edit the markdown files in the `content/` folder. Once you're happy with how your edits look, just commit, push, and submit a PR.

### Quick Fixes (small text additions or typos)

If there's something in the text that's very small and should be updated quickly, it's possible to use the built-in GitHub IDE (just hit `.`), make the change, commit, submit the PR. The CI will take care of running everything for you.

### Issues or Suggested Changes

Please report any issues or suggestions to the GitHub Issues of the main repository.
