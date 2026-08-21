---
description: >-
  Tool Description : Interactive global public-transport map showing scheduled
  and, where available, real-time positions of trains and other public-transport
  vehicles.
---

# Live Train Tracker

| **Live Train Tracker** | **Quick Overview**                                                                                                                      |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| URL                    | [https://mobility.portal.geops.io/world.geops.transit](https://mobility.portal.geops.io/world.geops.transit)                            |
| What it does           | Maps public-transport routes, stops and vehicle movements worldwide, including trains where data is available.                          |
| How to use it          | Navigate to an area, select the relevant transport layer and inspect routes, stops and vehicle positions.                               |
| Cost                   | Free.                                                                                                                                   |
| Account required       | No.                                                                                                                                     |
| Cookies                | Matomo analytics cookies.                                                                                                               |
| Ownership              | geOps; a German and Swiss software company led and managed by CEO and co-founder [Uli Müller.](https://www.linkedin.com/in/ulimueller/) |
| Use in Reporting       | Useful for checking transport movements, routes, schedules, locations and potential timelines.                                          |

### What does Live Train Tracker do?

Live Train Tracker visualises transport data on an interactive map. Its tracker combines static timetable data with available real-time data and can display trains, buses, trams and boats, and it uses GTFS feeds from transport providers around the world.

Where genuine real-time data is unavailable, the system can instead display interpolated positions based on timetable and delay information.&#x20;

**The lowdown:** It’s a useful transport-location and timeline verification tool.&#x20;

**Important Note:** A vehicle shown moving on the map isn't automatically proof that a specific physical train was at that exact location at that exact time. Some areas use real-time feeds while others rely on timetable-based interpolation.

### How to Use:

**1. Open the tracker and navigate/zoom to the country, city, railway line or station relevant to the investigation.**&#x20;

<img src="../.gitbook/assets/unknown (493).png" alt="" height="352" width="602">

**2. Enable the appropriate transport layers and inspect the displayed routes, stops and vehicle movements. Where available, examine current positions and delays.**&#x20;

<img src="../.gitbook/assets/unknown (494).png" alt="" height="248" width="602">

**3. Record the date/time, location, route, service and relevant map information, then corroborate important findings against the relevant transport operator, timetable, journey information or another independent source.**&#x20;

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

The site uses first-party Matomo analytics cookies, including \_pk\_id, \_pk\_ref and \_pk\_ses. These are used to identify returning browsers, maintain analytics sessions and record referral sources. They relate to website usage analytics and do not represent train-location data.

### Use in Reporting

Live Train Tracker can be used to:

* Establish the location and route of public-transport services relevant to an investigation.
* Check scheduled or apparent vehicle movements around a particular time and location.
* Investigate transport-related timelines, including whether a reported journey is consistent with available data.
* Corroborate information obtained from railway operators, timetables, photographs, videos or other OSINT sources.
* Identify railway stations, routes, stops and transport connections relevant to an investigation.
* Document service names, routes, locations, timestamps and observed movements as part of an evidential record.
* Support geolocation and movement analysis where transport infrastructure is visible or relevant.
* Inform investigations involving travel, transport disruption, incidents or movements through a particular area.

**Important reporting caveat:** Where possible, record whether the information represented real-time data or timetable/interpolated data. geOps explicitly states that its tracker falls back to interpolated schedule positions where real-time feeds are unavailable.&#x20;

| **Capabilities**                                                                                            | **Limitations**                                                                                          |
| ----------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| Displays public-transport routes and vehicle movements across many parts of the world.                      | Real-time coverage varies by location and operator.                                                      |
| Combines timetable information with available real-time feeds.                                              | Some displayed positions are interpolated from schedules rather than live GPS positions.                 |
| Can display trains as well as buses, trams and boats where data is available.                               | Coverage and data quality depend on the underlying transport provider's feed.                            |
| Provides an interactive geographic view useful for location and route analysis.                             | A displayed vehicle position should not automatically be treated as precise physical-location evidence.  |
| Can help establish transport timelines and identify relevant routes/stations.                               | Historical data may not be readily available through the public interface.                               |
| Uses standardised transport data such as GTFS, making data integration possible across multiple operators.  | Service cancellations, feed outages, delays or stale data can affect accuracy.                           |

### Summary

Live Train Tracker’s strongest OSINT application is transport and movement verification. It can help investigators understand railway networks, locate stations and routes, examine scheduled services and, where real-time feeds exist, observe apparent vehicle movements.&#x20;

However, the distinction between live data and estimated/interpolated positions is critical.

### Ownership

geOps; a German and Swiss software company specialising in web applications for public transport, mobility, and geodata. It is led and managed by its long-time CEO and co-founder [Uli Müller.](https://www.linkedin.com/in/ulimueller/)

### Ethical Considerations

* Treat displayed positions as OSINT indicators, not automatically as definitive proof of a vehicle's physical location.
* Establish whether the data is real-time, delayed or timetable-derived.
* Record the date and time of observation, including the relevant time zone.
* Corroborate important findings with the relevant railway/operator or another independent source.
* Consider whether publishing a particular train movement could expose sensitive information about individuals.
* Be careful with historical claims because the public tracker may not provide a complete historical record.

### Related Tools:

* geOps Maps
* OpenStreetMap
* OpenRailwayMap

#### Sources

[https://mobility.portal.geops.io/world.geops.transit](https://mobility.portal.geops.io/world.geops.transit)&#x20;

[https://geops.com/en/about](https://geops.com/en/about)&#x20;

[https://www.linkedin.com/in/ulimueller/](https://www.linkedin.com/in/ulimueller/)
