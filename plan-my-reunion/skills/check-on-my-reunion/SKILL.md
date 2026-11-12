---
name: check-on-my-reunion
description: "Check how a Plan My Reunion reunion is going, share its class page, and look at partner venues."
---

# Check on my reunion

Use this when an organizer asks about a reunion they already have with Plan My
Reunion: how it's going, ticket sales, who's coming, the link to share, or
where to hold it.

1. If you don't know which reunion, call `list_my_reunions` and confirm it.
2. Then, depending on the question:
   - **How's it going?** `get_reunion_status`: how much is planned (a
     percent), the one next small task with about how long it takes (and its
     link), the step it's on, classmates found and coming, and tickets sold.
     Lead with the percent and that one task, not the whole list. When
     `nextTask` is empty, say what it's waiting on (`waitingOn`). Offer
     `show_reunion_card` to see it as a card.
   - **Spread the word.** `get_share_kit`: the class page link, a short link,
     and text ready for a Facebook group, an Instagram story and a group chat.
     You don't post anything; they paste it.
   - **Where to hold it.** `find_partner_venues`: nearby partner venues, each
     with one all-in price per person and how many guests it holds. They
     request one from the Venue page link.
3. Keep numbers exact, as the tools give them. Don't estimate turnout or
   promise dates.
4. To change something (the date, the venue, tickets, messages), use the
   run-my-reunion skill.

Payments only happen on planmyreunionnow.com. Never reveal or look up
classmates' contact details.
