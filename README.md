# sync-labels-milestones

Use the [github-sync-labels-milestones](https://github.com/Jimdo/github-sync-labels-milestones) `npm` module to synchronize Learners Guild milestones across different repos.

## Getting Started

See `package.json` and `config/learning-os-software.json` for example usage.

1. Get a [personal access token](https://github.com/settings/tokens) from GitHub with `repo` privileges and store it in a file called `.ghtoken`.
2. Create a file in the `config` folder with the synchronization you want to happen.
3. Add an `npm run` script to `package.json` that uses your config file to synchronize the repositories.
