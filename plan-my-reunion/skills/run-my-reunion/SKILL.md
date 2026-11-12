---
name: run-my-reunion
description: "Run a Plan My Reunion reunion from the chat, step by step: the date, the venue, tickets, messages to the class, the budget, settings and reunion day."
---

# Run my reunion

Use this when an organizer wants to get something done on a reunion they
already have with Plan My Reunion. If you don't know which reunion, call
`list_my_reunions` and confirm it. `get_reunion_status` says which of the five
steps it's on (gather the class, pick the date, book the venue, sell tickets,
reunion day) and what's next.

**Before anything goes out, show the organizer exactly what will happen and
get a clear yes.** That covers setting the date (it emails everyone who
RSVP'd yes or maybe), requesting a venue, opening ticket sales, changing a message, sending
an update to the class, inviting a co-planner, and turning the class page on
or off.

1. **Pick the date.** The organizer picks it; classmates don't vote.
   `get_reunion_date` shows the date, or the weekends we suggest
   (Thanksgiving, between Christmas and New Year's, July 4th, Memorial Day
   and Labor Day weekends) and who setting it would email.
   `set_reunion_date` sets it.
2. **Book the venue.** `find_partner_venues` lists partner venues with one
   all-in price per person; `request_partner_venue` asks one (some book
   instantly). `request_venue_search` has our team shortlist venues;
   `set_own_venue` records one they booked themselves. `get_venue_status`
   shows where it stands.
3. **Sell tickets.** `get_ticket_sales` shows the settings, sales and what's
   blocking opening. `set_ticket_settings` sets the price and the day sales
   end. `open_ticket_sales`, `pause_ticket_sales`,
   `extend_ticket_deadline`. Payouts are set up on the Payouts page (the
   link in `get_reunion_status`), never in chat. Classmates pay on our site when they
   RSVP. Refunds stay in the app.
4. **Budget.** `get_budget`, `add_budget_costs`, `change_budget_cost`,
   `remove_budget_cost`; it works out the ticket price that covers the costs.
5. **Messages.** `get_message_sequence` shows the automatic messages and
   their wording; `update_message_step` turns one on or off or rewords it.
   To send an update to the class: `preview_class_update`, show the
   organizer the preview and how many it reaches, and only after their yes,
   `send_class_update` with the preview's id. `get_message_history` lists what
   went out.
6. **Who's coming.** `list_rsvps` (names, guests, paid or not),
   `list_classmates` and `update_classmate`; finding more classmates is the
   find-my-classmates skill.
7. **Team and settings.** `list_planning_team`, `invite_co_planner`;
   `ask_our_team` (find classmates, find the logo) and `list_team_requests`;
   `get_reunion_settings`, `update_reunion_details`, `set_class_page`,
   `set_reunion_archived`.
8. **Reunion day.** `get_check_in` for who's arrived; `check_in_guest` by
   name (if several match, ask which).

Keep numbers exact, as the tools give them. Never share or ask for anyone's
email, phone number or address, and never take card or bank details: payments,
payouts and refunds happen on planmyreunionnow.com.
