---
description: >-
  Tool Description : A research demonstrator from TIB that uses deep learning to
  estimate where a photograph was taken based on visual and geographic features.
---

# Geolocation Estimation

| **Geolocation Estimation** | **Quick Overview**                                                                                               |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| URL                        | [https://labs.tib.eu/geoestimation/](https://labs.tib.eu/geoestimation/)                                         |
| What it does               | Estimates the likely geographic location of photographs using a deep-learning model.                             |
| How to use it              | Select a benchmark image and compare your location guess with the model's estimate.                              |
| Cost                       | Free.                                                                                                            |
| Account required           | No.                                                                                                              |
| Cookies                    | No cookies are used for TIB's web analytics, according to TIB's privacy information (and according to our test). |
| Ownership                  | Technische Informationsbibliothek (TIB), Germany.                                                                |
| Use in Reporting           | Useful for testing geolocation hypotheses and understanding AI-assisted image geolocation.                       |

### What does Geolocation Estimation do?

Geolocation Estimation uses deep-learning models to estimate the geographic location of photographs. The approach divides the world into geographical areas and uses visual features from an image to estimate where it was taken. It also considers the broader scene, such as whether an image is urban, natural or indoors.

The demo displays the model's estimated location as a heat map, showing areas considered more likely, and provides visualisations indicating which parts of the image contributed most to the model's decision.

**The lowdown:** It’s an AI-assisted image geolocation research/learning tool.&#x20;

**Important Note:** The current demo is primarily a research/benchmark demonstrator (similar to GeoHints). The ability to analyse your own uploaded photographs was discontinued in 2025.

### How to Use:

**1. Open the Geolocation Estimation demo and select one of the available benchmark photographs.**

<img src="../.gitbook/assets/unknown (465).png" alt="" height="617" width="602">

**2. Click on the world map to make your own location estimate, then select “Guess Location” to see the model's result.**

<img src="../.gitbook/assets/unknown (466).png" alt="" height="615" width="602">

<img src="../.gitbook/assets/unknown (467).png" alt="" height="536" width="602">

**3. Compare your estimate with the model's heat map, ground-truth location and scene classification. Use the result to understand how visual features can influence automated geolocation.**

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

No cookies are used for TIB's web analytics, according to TIB's privacy information. No cookies were used during our site session on 11 August 2026.

### Use in Reporting

Geoestimation is very much a background/learning tool with limited operational capability but it can be useful to:

* Test whether AI can support a difficult geolocation problem.
* Generate additional hypotheses about an image's likely location.
* Compare human and machine geolocation estimates.
* Support research into AI-assisted visual verification.
* Use as a methodological reference for automated geolocation.

| **Capabilities**                                                    | **Limitations**                                                      |
| ------------------------------------------------------------------- | -------------------------------------------------------------------- |
| Estimates geographic location from visual image content.            | The current demo doesn’t accept users’ own photographs.              |
| Uses scene context such as urban, natural, and indoor environments. | Results are estimates and can be geographically inaccurate.          |
| Produces a heat map of likely geographic areas.                     | Generic scenes can provide few reliable location clues.              |
| Shows image regions that influenced the model’s decision.           | Model performance can vary significantly between images and regions. |
| Provides comparison between human and machine estimates.            | The underlying research and demonstrator date from the late 2010s.   |
| Uses a research-backed deep-learning geolocation methodology.       | <p><br></p>                                                          |

### Summary

Geolocation Estimation conceptually fits at the geolocation hypothesis stage, between initial visual analysis and independent map-based verification.

However, it is operationally limited in that the current demo no longer allows investigators to upload their own images. It’s therefore better described as a learning tool, not dissimilar to GeoHints (although that platform is more comprehensive).&#x20;

### Ownership

Geoestimation was developed by researchers at the Technische Informationsbibliothek (TIB) and the L3S Research Center at Leibniz University Hannover. The underlying research was authored by Eric Müller-Budack, Kader Pustu-Iren and Ralph Ewerth and published at the European Conference on Computer Vision in 2018.

### Ethical Considerations

* Treat AI-generated locations as hypotheses rather than facts.
* Independently verify important geolocation findings.
* Be transparent when AI-assisted analysis contributes to a reporting conclusion.

### Related Tools:

* [Geohints](geohints.md)
* [Geoconfirmed](geoconfirmed.md)
* Google Earth Pro
* [OpenAerialMap](openaerialmap.md)
* [Mapillary](mapillary.md)

#### Sources

[https://labs.tib.eu/geoestimation/](https://labs.tib.eu/geoestimation/)&#x20;

[https://research.uni-hannover.de/en/publications/geolocation-estimation-of-photos-using-a-hierarchical-model-and-s/](https://research.uni-hannover.de/en/publications/geolocation-estimation-of-photos-using-a-hierarchical-model-and-s/)&#x20;
