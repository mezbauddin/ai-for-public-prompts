# Draft a clean travel itinerary from booking emails

**For:** Executive support  
**Tool:** Copilot Chat  
**Task:** Extract

## Prompt

```text
Turn the booking confirmations below into a single clean itinerary. UK English. One row per leg in time order: date, time, what (train/hotel/meeting), from and to, reference number, and any note. Add total travel time per day. Flag any tight connection under 30 minutes with [TIGHT]. Do not invent times that are not in the confirmations.

Confirmations:
{paste}
```

## Why it works

A single time-ordered itinerary beats forwarding six confirmation emails. The [TIGHT] flag catches the connection that will cause a panicked call from a station.

## Watch out

Double-check the times against the original bookings, especially anything crossing midnight or a timezone.
