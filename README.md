# mockups

Screenshots of UI mockups, kept here so each one has a stable public URL to embed in GitHub issues.

These images are produced by the `mockup` skill. Once a mockup is signed off, its screenshots are committed here and linked into the relevant project issue — so the issue's plan shows the design everyone actually agreed on.

## Why this repo is public

GitHub renders an embedded image by having the viewer's browser fetch its URL. A private repo's `raw.githubusercontent.com` URL needs an auth token the inline fetch can't supply, so the image shows up broken. Public is what makes these screenshots render inside an issue.

Only non-sensitive design mockups belong here. Keep anything confidential out of a public repo.

## Layout

One folder per project. Each file is named after the screen and state it shows:

​`
<project>/<screen>-<state>.png
<project>/<screen>-<state>-<breakpoint>.png   # when capturing more than one breakpoint
​`

Examples:

​`
chat-logbook/chat-list-default.png
chat-logbook/chat-list-popover-open.png
chat-logbook/chat-list-default-mobile.png
​`

## Embedding

Reference an image by its raw URL:

​`md
![Chat List — default](https://raw.githubusercontent.com/evaaaaawu/mockups/main/chat-logbook/chat-list-default.png)
​`
