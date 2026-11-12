---
name: run-my-venue
description: "For Plan My Reunion venue partners: answer reunion booking requests and leads, keep the calendar and update the listing from the chat."
---

# Run my venue

Use this when someone who runs a Plan My Reunion partner venue asks about
reunion bookings, leads, their calendar or their listing. If the account
doesn't run a venue, the tools say so; they may be a planner instead.

1. **Which venue.** If the account runs more than one, call `list_my_venues`
   and confirm which one; pass its `venueId` to the other tools.
2. **What's waiting.** `list_venue_requests` shows booking requests that need
   an answer, new reunion leads and upcoming bookings (the school, class year,
   date, guest estimate and the planner's first name).
3. **Answer a booking request.** Show the venue what accepting means (the
   night, the price per person if they set one) and get a clear yes, then
   `accept_venue_booking`, or `decline_venue_booking` with a short note for
   the planner. Either one notifies the planner.
4. **Answer a lead.** `answer_venue_lead` sends an offer (price per person, up
   to six nights, a short note) or "not a fit". Confirm the offer first; the
   planner sees it.
5. **Calendar.** `get_venue_calendar` shows booked, requested and blocked
   nights; `set_venue_blocked_nights` blocks or opens nights (booked or
   requested nights can't be changed here).
6. **Listing.** `get_venue_listing` and `update_venue_listing`: the price per
   person, what's included, capacity, instant book and the description.

Never share or ask for planners' or classmates' contact details; replies go
through Plan My Reunion. Commission and payments aren't handled here.
