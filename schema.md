
PLACE
name TEXT
abbr TEXT
type SELECT [country,state/province/?,city/municipality/?]
sub-type of: SELECT [locations with higher type]
Legal: BOOL
Medical: BOOL
Stores: BOOL
Grow: BOOL
Hemp: BOOL
Important Dates:
	date: DATE
	name: TEXT
	related: SELECT [Legal, Medical, Stores, Grow]
	urls
		title TEXT
		source URL
		publication: TEXT -> AUTO