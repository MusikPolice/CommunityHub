The most straightforward way to verify a user's mailing address is to [send them physical mail](<Letter Mail>) containing a verification code that they can enter into their user profile. 

The [City of Kitchener's Address dataset](https://data.waterloo.ca/datasets/KitchenerGIS::addresses/explore?location=43.450232%2C-80.461167%2C14.51) gives a list of all valid street addresses in the city, as well as some metadata about each. This could be used to ensure that an address is valid.

The [City of Kitchener's Address Proximity Directory dataset](https://open-kitchenergis.opendata.arcgis.com/datasets/91b34c8560c04dcdbc262361e2995bad_0/explore?location=43.455898%2C-80.476219%2C16.64) gives the ward name, neighborhood name, neighborhood association, and other useful information about any address in the city. This could be used to populate the user's profile with information about their neighborhood and to determine which sections of the platform they are allowed to post in.

Another option could be to attempt to verify the application with open data sets. For instance, the City of Kitchener publishes [a dataset of all Building Permits](https://open-kitchenergis.opendata.arcgis.com/datasets/c486d37abe2948d884a159cba20bec8c_0/explore?location=43.449408%2C-80.466586%2C14.49). If a homeowner opened a building permit in their name, that dataset would correlate their name to their address.

It may also be possible to verify a user's address by asking them to upload a piece of government-issued identification, although that comes with [[Personally Identifiable Information (PII)]] concerns.

Any system that attempts to verify a user's mailing address must account for users who have moved and users who live in multi-unit dwellings.