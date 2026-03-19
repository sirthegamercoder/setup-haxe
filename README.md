# About this Fork
In the original repository, the workflow action runs on Node.js 20, which has been deprecated by GitHub; therefore, this fork allows the workflow to run on Node.js 24, as recommended by GitHub.
>[!IMPORTANT]
>If you want to use this fork in your Haxe-based project and run a workflow, you may need to add `FORCE_JAVASCRIPT_ACTIONS_TO_NODE24: true` as an environment variable on `env` in your workflow file.

See the original of (README)[README-OG.md]
