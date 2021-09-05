## Project Proposal 


### Personal Info:
 * Name: Lubna Almuammar.
 * Email: LubnaIbrahim@outlook.sa.
 * Github:lluban.

### Background:

#### About the company:	
Scooter  rentals application, the applaction provides a
shared vehicle the app provides the ability to share the devices
using a short-term rental business model.  To begin a rental,
users unlock a scooter through the company’s smartphone app. the Scooters will be distributed across the city, to make the most benefit of the application the scooters will distributed near the station especially the most crowded stations.

- problem is where to put the scooters in which station.

- value for the compnay to make more profite we have to study the places where the scooters will be distributed.

### Data Description:

#### What is MTA ?
The Metropolitan Transportation Authority is North America's largest transportation network, serving a population of 15.3 million people across a 5,000-square-mile travel area surrounding New York City through Long Island, southeastern New York State, and Connecticut.

The MTA network comprises the nation’s largest bus fleet and more subway and commuter rail cars than all other U.S. transit systems combined. The MTA's operating agencies are MTA New York City Transit, MTA Bus, Long Island Rail Road, Metro-North Railroad, and MTA Bridges and Tunnels.

#### MTA Turnstile Data:
Data sourse from http://web.mta.info/developers/turnstile.html

#### Description of the dataset MTA


#### Field Description:

| Field Name | Description                                                                     |
|------------|---------------------------------------------------------------------------------|
| C/A        | Control Area (A002)                                                             |
| UNIT       | Remote Unit for a station (R051)                                                |
| SCP        | Subunit Channel Position represents an specific address for a device (02-00-00) |
| STATION    | Represents the station name the device is located at                            |
| LINENAME   | Represents all train lines that can be boarded at this station                  |
| DIVISION   | Represents the Line originally the station belonged to BMT, IRT, or IND         |
| DATE       | Represents the date (MM-DD-YY)                                                  |
| TIME       | Represents the time (hh:mm:ss) for a scheduled audit event                      |
| DESC       | Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours)   |
| ENTRIES    | The comulative entry register value for a device                                |
| EXITS      | The cumulative exit register value for a device                                 |

* the Sample size is recent three months from Jun to Sept 2021, because it will be the most useful to use since we need a new data.
* the dataset has 2932345 rows and 11 columns

 


#### Tools:
* technologies: SQL,SQLite,python,jupyter notebook.
* libraries: Numpy,Pandas, matplotlib.

#### MVP Goal:
* The goals of an MVP are to validate the premise of a product, to test hypotheses about market needs, to make adjustments to the product vision, and to prioritize where to invest in future development. As such, MVPs are a profoundly powerful approach towards finding product-market fit.
