---
description: >-
  Tool Description : An open platform for finding, viewing, and downloading
  openly licensed aerial imagery from satellites, UAVs/drones and other
  aircraft.
---

# OpenAerialMap

| **OpenAerialMap** | **Quick Overview**                                                                                                                         |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| URL               | [https://openaerialmap.org/](https://openaerialmap.org/)                                                                                   |
| What it does      | Finds and provides access to openly licensed aerial imagery by location, date, resolution and data type.                                   |
| How to use it     | Search an area, filter available imagery, inspect metadata, then view, download or use the imagery in GIS software.                        |
| Cost              | Free.                                                                                                                                      |
| Account required  | No account required to search and access imagery. An account may be required for contributing/uploading imagery.                           |
| Cookies           | A mixture of Google Analytics, Matomo analytics, and an OpenAerialMap map-state cookie.                                                    |
| Ownership         | It’s part of the Humanitarian OpenStreetMap Team (HOT) ecosystem and is built around the Open Imagery Network.                             |
| Use in Reporting  | Particularly useful for geospatial OSINT, historical imagery checks, site verification, change detection and corroborating visual claims.  |

### What does OpenAerialMap do?

OpenAerialMap brings together imagery from satellites, UAVs/drones and other aircraft so users can search for imagery covering a particular location.

You can search by location and filter imagery by factors including date, resolution and data type. Available imagery can be previewed and, where available, downloaded as GeoTIFF or accessed through map services such as TMS/WMTS for use in GIS applications.

OAM also exposes an API containing imagery metadata and map-layer information, making it potentially useful for more systematic or programmatic OSINT workflows.

**The lowdown:** The platform is essentially a searchable library of openly licensed aerial imagery, rather than a conventional satellite-imagery provider.&#x20;

### How to Use:

**1. Go to OpenAerialMap and search for a place, address, area or coordinates. Browse the imagery available for the area of interest.**

<img src="../.gitbook/assets/unknown (458).png" alt="" height="341" width="602">

**2. Use the filters to narrow results by date, resolution and data type. Select individual imagery to inspect its preview and associated metadata, including information about the imagery provider and capture details where available.**&#x20;

<img src="../.gitbook/assets/unknown (459).png" alt="" height="682" width="340">

**3. Download the imagery where appropriate, or use the available map-layer services in tools such as QGIS. Record the imagery date, provider, resolution, license and relevant metadata so the source can be properly documented in your investigation.**

<img src="../.gitbook/assets/unknown (460).png" alt="" height="481" width="602">



<img src="../.gitbook/assets/unknown (461).png" alt="" height="599" width="602">

**You can also** [**view this YouTube guide here.** ](https://www.youtube.com/watch?v=woDsyAQQMko)

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [x] Yes
* [x] No

Searching and accessing imagery through the browser does not require an account. An account is required for those uploading imagery.

### Cookies:&#x20;

OpenAerialMap uses Google Analytics and Matomo analytics cookies to measure visits and website activity. It also uses functional cookies such as oam-map-view to retain map state. No authentication/session cookie is evident in the supplied cookie set.

### Use in Reporting

OpenAerialMap can be used to:

* Verify locations and corroborate where an image or video was taken.
* Show change over time by comparing sites across different dates.
* Map events and place incidents or infrastructure geographically.
* Corroborate claims by testing visual and location-based assertions.
* Provide aerial context by showing the wider area around a subject.
* Support visual evidence with independent geospatial information.

[The platform](https://www.elrha.org/projects/openaerialmap) was specifically developed to make satellite and UAV imagery easier for humanitarian responders to find and access after disasters. Its original humanitarian project focused on coordinating imagery so responders could quickly identify what coverage existed and use it for response planning.&#x20;

| **Capabilities**                                                               | **Limitations**                                                                     |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------- |
| Search for aerial imagery covering specific locations and areas of interest.   | Coverage varies significantly by location and may be limited in some areas.         |
| Filter available imagery by factors such as date, resolution, and data type.   | Available imagery may not match the date or timeframe of an investigation.          |
| View imagery online and download available files for further analysis.         | Image quality and resolution vary depending on the imagery source.                  |
| Access useful metadata about imagery including source and capture information. | Metadata can be incomplete, inconsistent, or unavailable for some imagery.          |
| Compare imagery from different dates to identify changes at a location.        | OpenAerialMap does not independently guarantee the accuracy of contributed imagery. |
| Import imagery into GIS tools such as QGIS for further analysis.               | Detailed analysis often requires external GIS or image-analysis tools.              |

### Summary

OpenAerialMap fits best at the geospatial discovery and verification stage of the OSINT workflow, sitting between identifying an area of interest and conducting detailed geospatial analysis. It can also support corroboration and evidence presentation later in an investigation.

Its strongest use is not simply finding a picture of a location, but finding appropriately dated, geographically relevant imagery with usable metadata that can be compared against other evidence.

### Ownership

OpenAerialMap is part of the [Humanitarian OpenStreetMap Team (HOT)](https://www.hotosm.org/en/) ecosystem and is built on the Open Imagery Network (OIN).

### Ethical Considerations

* Verify imagery before using it as evidence.
* Check licensing and provide appropriate attribution.
* Consider privacy risks in high-resolution imagery.
* Avoid exposing sensitive or vulnerable individuals.
* Do not overstate what imagery can prove.
* Preserve source details and imagery provenance.

### Related Tools:

* Google Earth Pro
* OpenStreetMap
* [Copernicus](copernicus-browser.md)
* [Mapillary](mapillary.md)
* [Wikimapia](wikimapia.md)

#### Sources

[https://openaerialmap.org/](https://openaerialmap.org/)&#x20;

[https://openaerialmap.org/about/](https://openaerialmap.org/about/)&#x20;

[https://www.youtube.com/watch?v=woDsyAQQMko](https://www.youtube.com/watch?v=woDsyAQQMko)&#x20;

[https://www.kontur.io/blog/oam-software-development/](https://www.kontur.io/blog/oam-software-development/)&#x20;

[https://www.hotosm.org/en/](https://www.hotosm.org/en/)&#x20;

[https://www.elrha.org/projects/openaerialmap](https://www.elrha.org/projects/openaerialmap)
