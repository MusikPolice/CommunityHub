Registering to join Community Hub should be relatively painless, but some friction is necessary to prevent bad behaviour.

The registration process should require new users to enter a valid email address and a display name. Users should also be encouraged to enter a phone number that can receive text messages, as well as their mailing address. 

The provided email address can be immediately verified through [standard means](Email). A text message [can be sent](SMS) to verify the phone number. [[Letter mail]] can be sent to verify the mailing address. Each level of verification will increase the user's [[Trust Score]].

The [City of Kitchener's Address Proximity Directory dataset](https://open-kitchenergis.opendata.arcgis.com/datasets/91b34c8560c04dcdbc262361e2995bad_0/explore?location=43.455898%2C-80.476219%2C16.64) gives the ward name, neighborhood name, neighborhood association, and other useful information about any address in the city.

The [City of Kitchener's Address dataset](https://data.waterloo.ca/datasets/KitchenerGIS::addresses/explore?location=43.450232%2C-80.461167%2C14.51) gives a list of all valid street addresses in the city, as well as some metadata about each.

It may also be possible to verify a user's address by asking them to upload a piece of government-issued identification, although that comes with PII concerns.

Another option could be to attempt to verify the application with open data sets. For instance, the City of Kitchener publishes [a dataset of all Building Permits](https://open-kitchenergis.opendata.arcgis.com/datasets/c486d37abe2948d884a159cba20bec8c_0/explore?location=43.449408%2C-80.466586%2C14.49). If a homeowner opened a building permit in their name, that dataset would correlate their name to their address.