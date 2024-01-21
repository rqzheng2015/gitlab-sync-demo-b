# gitlab-sync-demo-b

This is a demo project to show how to sync code between two gitlab repositories.

This repo is repo B.

Repo A can be found [here](https://github.com/rqzheng2015/gitlab-sync-demo-a).

## Prequisites

Run `pnpm install` to install dependencies.

## How to use

1. Make sure you are using gitlab.
2. Check the .gitlab-ci.yml file in this repo, and migrate it to your project with necessary changes.
   > Be sure to migrate repo A as well, which can be found [here](https://github.com/rqzheng2015/gitlab-sync-demo-a).
3. Run the ci on gitlab to see if the build and publish stages runs on repo B successfully.