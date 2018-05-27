# NotifyMe

Execute command in bash and wait to send notification via slack.

## Setup

Define this environment variables on bash before execute command.

```bash
export NOTIFYME_SLACK=x35QCtUUQ*B376M2D8F.JntD801gqXwOMTYuZTdGhNQ0
export NOTIFYME_CHANNEL=alerts
```

## Usage

Is very easy to use:

```bash
./notifyme "ls -lah"
```

And work on something else until you wait for notification in slack. Maybe to not lost execution, run this command into `tmux` or `screen`.