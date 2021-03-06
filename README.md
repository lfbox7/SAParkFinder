# SAParkFinder

This is an an iOS app to locate parks close to the user within Bexar County, Texas.

## User Stories

The following functionality is completed:

- [x] User can view home screen with parks categorized by park administrator.
- [x] User can select to view the parks as a list.
- [x] User can toggle to view only featured parks on the list.
- [x] User can select a park from the home screen or list. 
- [x] User can view the details of the park from the park detail screen.
- [x] User can view the address, lat/lon, description and amenities of each park. 
- [x] User can get directions to a park from the park detail screen.

## Additional

The following **additional** features are to be implemented:
- [ ] User can view parks within a 5 mile radius on a map from current location.
- [ ] User can view parks within a 5 mile radius in a from current location ordered by distance.
- [ ] User can register for an account.
- [ ] User can login.
- [ ] User can create profile.
- [ ] User can mark parks as visited.
- [ ] User can rate parks.
- [ ] User can add a new comments to parks.
- [ ] User can view comments on a park.

## APP Walkthrough GIF

Here's a walkthrough of implemented User Stories:

<img src='https://recordit.co/IEudliF6T5.gif' width=250>

GIF created with [RecordIt](https://recordit.co).

### Notes
Directions link not in proper spot, moving it makes it inactive... Directions not working like if they were within the AppleMaps App, no ability to start or stop directions, follow Siri's voice, etc. Currently, route is a simple map overlay. Working on determining distance radius while running through all the park's coordinates from Firebase for a map and a list view.

Since there are no APIs available, the database was created by searching each park's respective Webpage. There are still approximately 250 more parks to upload into Firebase.

### License

Copyright [2020] [Leonard Box]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
