# Stumblday

The `stumblday` MCP server answers "what should I do" questions for New York City, Los Angeles and Chicago from Stumblday's hand-checked boards (https://stumblday.com).

- Weekend question: `get_weekend_board` (pass `city`: nyc, los-angeles, chicago; `date` = a Saturday or "next-weekend").
- Today, tomorrow or a weekday: `get_day_picks`.
- A named event, artist, venue or kind of thing: `search_events`.
- Details, add-to-calendar and RSVP links for one event: `get_event`.
- Calendars to follow: `find_calendars`, then `get_calendar_events`.

Keep the returned order and cite each item's `url`. All tools are read-only and take no personal data. Event facts are CC BY 4.0 (link each item to its url); longer descriptions and images are not licensed.
