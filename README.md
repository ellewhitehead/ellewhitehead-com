# ellewhitehead.com

The code for [ellewhitehead.com](ellewhitehead.com). Static HTML served by Cloudflare Workers.

## Requirements
See https://developers.cloudflare.com/workers/platform/sites/start-from-scratch for reference.

* Node 15+
* Wrangler

## Making local changes

Edit the files in `/public` and save changes.
Run `wrangler preview --watch` in Terminal. This will open a page in your browser.
Test out your changes.
When you're done, switch to your Terminal and press `Ctrl-C` to stop the preview.

## Publishing changes

Commits to `main` are automatically published by a Github Action. 

If you need to publish separately, run `wrangler publish` in Terminal.