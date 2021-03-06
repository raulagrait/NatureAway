# NatuRentals

Mashup of iNaturalist and various rental sites that lets you use the iNaturalist API as well as the Zilyo API to find species observations and rentals near each other.

## Team Members
 - Chris Beale
 - Elaine Mao
 - Raul Agrait

## Features

#### Species overview and search view
- View species observations by top level categories (e.g. Plants, Animals, Vertebrates, etc)
- Display species in a collection view grid layout
- Search for specific species

#### Observations View and Rentals View
 - View recent observations for a given species in tabular format
 - Observations sorted by distance to current location
 - View rentals near a given observation in tabular format
 - Rentals sorted by distance to observation

#### Detailed view of a single observation
  - Display paginated control of observation images
  - Display common name, species name, and observation date
  - Display nearest available rental near the observation
  - Link to view list of multiple nearby rentals

#### Detailed view of a single rental
  - Display paginated control of rental images
  - Display number of bedrooms and bathrooms
  - Display cost to rent per night
  - Display rental description
  - Link to external rental site (AirBnb, etc)

#### Map view of observations
  - View observations near your current location
  - Search to a given location and view observations near it
  - Map annotations
  	 - Custom map icons depending on the species type
  	 - Map annotation has observation image and links to the detail view


### Walkthrough

![Video Walkthrough](naturentals.gif)


Credits
-------
* [iNaturalist API](http://www.inaturalist.org/pages/api+reference)
* [Zilyo API](https://www.mashape.com/zilyo/zilyo)
* [BDBOAuth1Manager](https://github.com/bdbergeron/BDBOAuth1Manager)
* [AFNetworking](https://github.com/AFNetworking/AFNetworking)
* Design Help: Mike Towber