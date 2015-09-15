
PLACE
name TEXT
abbr TEXT
type SELECT [country,state/province/?,city/municipality/?]
sub-type of: SELECT [locations with higher type]
Legal: BOOL
Buy: BOOL
Grow: BOOL
Hemp: BOOL
Medical: BOOL
Important Dates:
  date: DATE
  name: TEXT
  related:
      changeTo: SELECT [Legal, Medical, Stores, Grow]
      becomes: BOOL
  urls
    title TEXT
    source URL
    publication: TEXT -> AUTO