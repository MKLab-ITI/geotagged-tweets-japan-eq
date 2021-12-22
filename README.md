# Geotagged tweets in English about earthquakes in Japan

Description TBA

## Data Organization

| Property Name | Property Type | Description |
| --------- | ----------- | ----------- |
| \_id | String | The unique identifier of a tweet, as provided by Twitter. |
| detected_locations | Array | An array of objects that contain information about the locations that have been extracted from a tweet’s text. |
| location_in_text | String | The word(s) in a tweet’s text that has/have been recognized as locations after analysis. |
| location_fullname | String | The full location name as retrieved by the OpenStreetMap API. |
| geometry | JSON Object | A JSON object that contains information about the coordinates of the location. |
| type | String<br> (predefined value: "Point") | A field that defines the type of the coordinates. |
| coordinates | Array<br> (format \[latitude,longitude\]) | An array of Double values that refer to the latitude and longitude coordinates of the location, as retrieved by the OpenStreetMap API. |

## Licensing

This dataset is licensed under the Creative Commons Attribution-NonCommercial International Public License ([CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)). When downloading tweets by the means of the distributed Tweet IDs, users have to be compliant with [Twitter’s Developer Agreement and Policy](https://developer.twitter.com/en/developer-terms/agreement-and-policy). By using this dataset, you agree to abide by the stipulations in the license, remain in compliance with Twitter’s Terms of Service, and cite the following manuscript.

## How to Cite

TBA

BibTeX:

    TBA

## Contact

If you have any further questions about the dataset or if you are interested in running some additional analyses on the data, please contact Stelios Andreadis at **[andreadisst@iti.gr](mailto:andreadisst@iti.gr)**.

## Team

Stelios Andreadis, Nick Pantelidis, Thanassis Mavropoulos, Ilias Gialampoukidis, Stefanos Vrochidis, Ioannis Kompatsiaris

Information Technologies Institute (ITI), Centre for Research and Technology Hellas (CERTH)
