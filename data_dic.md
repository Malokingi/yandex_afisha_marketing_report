# Description of the data
All dates in these tables are in YYYY-MM-DD format.

## The visits table (server logs with data on website visits):
- [x] uid — user's unique identifier
    - Change from 'Uid' to 'uid'
- [x] device — user's device
    - Change from 'Device' to 'device'
    - There's only two different values, so I'll change the type to category
- [x] start_time — session start date and time
    - Change name from 'Start Ts' to 'start_time'
    - Looks like the seconds aren't included in this, I'll convert to datetime
- [x] end_time — session end date and time
    - Change name from 'End Ts' to 'end_time'
    - Change to datetime type also
- [x] source_id — identifier of the ad source the user came from
    - Change name from 'Source Id' to 'source_id'
    - There's only 10 unique values, so I changed this to category type. I'll come back and undo if I need to.

## The orders table (data on orders):
- [x] uid — unique identifier of the user making an order
    - Change from 'Uid' to 'uid'
- [x] purchase_time — order date and time
    - Change from 'Buy Ts' to 'purchase_time'
    - Convert to datetime type
- [x] profit — Yandex.Afisha's revenue from the order
    - Change from 'Revenue' to 'profit'

## The costs table (data on marketing expenses):
- [x] source_id — ad source identifier
    - There's only 7 unique values. Convert to category type
- [x] dt — date
    - change from 'dt' to 'date'
    - It only has dates, and no times. Convert to datetime type accordingly
- [x] costs — expenses on this ad source on this day
    - This looks fine unchanged