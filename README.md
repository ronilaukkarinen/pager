# Pager for irssi

An irssi script that sends out an away message for people who try to private message you when `/away` is set.

    -- I'm currently afk (out to lunch). (last seen in IRC: 1 hour, 43 minutes, and 59 seconds ago ago)"

Extremely useful for example when used with [Pushover](https://pushover.net/), [BitlBee](https://www.bitlbee.org) or [Slack](https://slack.com).

## Commands

`/set page_command` - a shell command to run if someone sends you the private message 'page' while you are away
`/set away_notice` - a notice to send to someone sending you a private message while you are away
`/set paged_notice` - a notice to send to someone who has just paged you
`/set dcc_notice` - a notice to send to someone who has just sent you a DCC chat offer (this automatically pages you)