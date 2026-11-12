---
name: plan-a-reunion
description: "Start planning a high school class reunion with Plan My Reunion, from \"I said yes to planning it\" to a reunion with a class page link."
---

# Plan a reunion

Use this when someone is organizing (or about to organize) their high school
class reunion. Not for family reunions, college reunions, weddings or
corporate events.

1. **Find the school.** Ask for the school's name and city if you don't have
   them, then call `search_schools`. Show the matches and confirm the right
   one; keep its `schoolId`. If nothing matches, the reunion can still be
   started with the name, city and two-letter state (or the country, outside
   the US).
2. **Confirm the class.** The graduating year, and which reunion it is (10th,
   20th…) if they've said. Rough timing (spring, summer, fall,
   Thanksgiving, winter) and the year are optional.
3. **Ask one question:** should our team find the class (build the class list
   from the yearbook and public sources)? The default is yes.
4. **Start it** with `start_reunion`. If they aren't connected yet, the tool
   asks them to connect their Plan My Reunion account; that's expected.
5. **Tell them what happens next**, using the tool's answer:
   - New planners are reviewed, usually within a business day; the class page
     goes live after that, and we email them.
   - Otherwise the class page is live: offer `get_share_kit` for the link and
     ready-to-post text, and `find_partner_venues` when they're thinking about
     where to hold it.
   - Outside Alabama, say plainly that partner venues are in Alabama for now
     and our team's help can take longer, while the class page, RSVPs and
     tickets work anywhere.
6. **Offer the next step.** The organizer can keep going right here: build
   the class list (find-my-classmates), pick the date, pick a venue,
   set up tickets and messages (run-my-reunion). Link them to their reunion's
   Home (`homeUrl`) for the rest.

Never look up or save classmates' emails, phone numbers or home addresses.
To build the class list, use find-my-classmates: names and public profile
links only. Classmates add their own contact details on the class page.
