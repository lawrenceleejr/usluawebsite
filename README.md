# Website for the US LHC Users Association (USLUA)

*Redesign by Lawrence Lee in May 2024*

## Background Information

This website uses the wonderful `hugo` package for creating static webpages. The theme is the very powerful `blowfish` theme. See https://blowfish.page/. 

The goal of these packages is to have it so that content is written in simple markdown files. Then the style and such is implemented separately. So adding new pages or editing content just takes some text file editing.

Then the continuous integration setup on this repo is set to take whenever is committed to the `main` branch, build it with `hugo`, and then deploy to GitHub pages automatically. So a simple typo could be fixed just in the web IDE setup on GitHub, a new PR being submitted, and then accepted. Then the CI will go build and deploy automatically.

## Contributing

See [CONTRIBUTING](CONTRIBUTING.md) for details on how to contribute to this website.
