# Description of the data
All dates in these tables are in YYYY-MM-DD format.

## The visits table (server logs with data on website visits):
- [x] Uid — user's unique identifier
    - This is fine the way it is. No changes
- [x] Device — user's device
    - There's only two different values, so I'll change the type to category
- [x] Start Ts — session start date and time
    - Looks like the seconds aren't included in this, I'll convert to datetime
- [x] End Ts — session end date and time
    - change to datetime type also
- [x] Source Id — identifier of the ad source the user came from
    - There's only 10 unique values, so I changed this to category type. I'll come back and undo if I need to.

## The orders table (data on orders):
- [x] Uid — unique identifier of the user making an order
    - No Changes
- [x] Buy Ts — order date and time
    - Convert to datetime type
- [x] Revenue — Yandex.Afisha's revenue from the order
    - No changes needed

## The costs table (data on marketing expenses):
- [x] source_id — ad source identifier
    - There's only 7 unique values. Convert to category type
- [x] dt — date
    - It only has dates, and no times. Convert to datetime type accordingly
- [x] costs — expenses on this ad source on this day
    - This looks fine unchanged