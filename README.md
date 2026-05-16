# OpenClaw SDLC Pipeline Demo

Static demo page for a simulated OpenClaw SDLC pipeline dashboard.

The demo includes an optional [TweetClaw](https://github.com/Xquik-dev/tweetclaw) public follow-up stage after production. It waits for human approval, searches launch context, posts the approved X/Twitter update, and monitors replies.

Install TweetClaw with `openclaw plugins install @xquik/tweetclaw`. npm is the canonical install source, and the [ClawHub page](https://clawhub.ai/plugins/@xquik/tweetclaw) is useful for browsing the plugin.

## Run locally

Open `index.html` in a browser.

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` to the repository root.
3. Go to Settings > Pages.
4. Set source to deploy from the main branch root.
5. Open the GitHub Pages URL after deployment.

## Note

This is a static demo. It does not connect to a real OpenClaw backend yet.
