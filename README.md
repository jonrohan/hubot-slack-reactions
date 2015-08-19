# hubot-slack-reactions

A hubot script like /star me except for slack reactions.

See [`src/slack-reactions.coffee`](src/slack-reactions.coffee) for full documentation.

## Configuration

You'll need to get your [Slack API Auth token](https://api.slack.com/web#authentication). Once you've gotten it for your org, set it as an environment variable.

```sh
export SLACK_ACCESS_TOKEN=xxxxxxxx
```

## Installation

In hubot project repo, run:

`npm install hubot-slack-reactions --save`

Then add **hubot-slack-reactions** to your `external-scripts.json`:

```json
[
  "hubot-slack-reactions"
]
```

## Sample Interaction

```
user1>> hubot react me -1year
hubot>> https://chat.slack.com/archives/general/p1d39f3463d000068
```
