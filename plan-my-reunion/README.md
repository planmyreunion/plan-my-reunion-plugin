# Plan My Reunion

Plan My Reunion is a free tool for the person organizing a high school class reunion. This plugin lets you run your reunion from Claude. Venue partners can run their venue from Claude too.

## What you can do

- Start a reunion for your school and class year. You get a public class page that collects RSVPs.
- Build the class list from names you already have and from public pages.
- Pick the date, look at partner venues and request one.
- Set the ticket price and open ticket sales on the class page.
- Preview an update to your class, then send it after you approve it.
- Ask how the reunion is going: RSVPs, tickets sold and the next step.
- Check people in on the night.
- Venue partners can answer booking requests and leads, keep their calendar and update their listing.

Try "Help me plan my 10-year high school reunion" or "How are ticket sales for my reunion going?".

## What is in the plugin

The plugin has five skills and one connection to the Plan My Reunion server.

- `plan-a-reunion` starts a reunion.
- `run-my-reunion` covers the date, the venue, tickets, messages, the budget, settings and reunion day.
- `check-on-my-reunion` reports how a reunion is going and shares its class page.
- `find-my-classmates` builds the class list.
- `run-my-venue` is for venue partners.

The plugin contains no code. It runs nothing on your computer and has no hooks.

## What it connects to

The plugin connects to one remote MCP server, `https://www.planmyreunionnow.com/mcp`, run by PLAN MY REUNION LLC. Tool calls send what you ask Claude to do with your reunion to that server, and the server answers with your reunion's data. The plugin contacts no other service.

Searching schools works signed out. Everything else asks you to sign in to your Plan My Reunion account in the browser and approve access on a consent screen (OAuth 2.1). If you have no account, you can make one there for free. You can disconnect Claude at any time at https://www.planmyreunionnow.com/app/connected-apps.

## What it will not do

- It never moves money. Payouts and refunds stay in the Plan My Reunion app.
- It never gives out a classmate's email, phone number or address. The class list tools save names and public profile links only.
- It asks you to confirm before anything is sent to your class or made public.

## Links

- Documentation: https://www.planmyreunionnow.com/assistant
- Privacy: https://www.planmyreunionnow.com/privacy
- Terms: https://www.planmyreunionnow.com/terms
- Support: hello@planmyreunionnow.com

## Install in Claude Code

```
/plugin install plan-my-reunion --marketplace planmyreunion/plan-my-reunion-plugin
```
