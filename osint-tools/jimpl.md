---
description: >-
  Tool Description : Jimpl is a free EXIF viewer used to uncover hidden info
  from any photo and to find when & where it was taken.
---

# Jimpl

| **Jimpl**        | **Quick Overview**                                                                                     |
| ---------------- | ------------------------------------------------------------------------------------------------------ |
| URL              | [https://jimpl.com/](https://jimpl.com/)                                                               |
| What it does     | Allows users to view and remove metadata in photos.                                                    |
| How to use it    | Upload photo, view metadata and/or remove metadata.                                                    |
| Cost             | Free                                                                                                   |
| Account required | No                                                                                                     |
| Cookies          | A mix of Google analytics cookies, advertising/consent cookies, and Jimpl’s own session cookie.        |
| Ownership        | An individual developer named [Toni](https://x.com/ToniTheMaker), based in Romania.                    |
| Use in Reporting | Useful for extracting image metadata to support verification and geolocation in OSINT investigations.  |

### What does Jimpl do?

Jimpl is a browser-based EXIF metadata tool that allows investigators to upload images and extract embedded data that may not be visible in the image itself. This can include camera make and model, creation date, editing software, and GPS coordinates if location services were enabled when the photo was taken.

It can also be used to strip metadata from images, which is useful for privacy protection or preparing evidence for publication.

**The lowdown:** It’s most used for verifying the authenticity of images, checking when and where a photo was taken, and identifying whether an image has been edited or manipulated.&#x20;

### How to Use:

**1. Upload an image file (drag and drop or select from device) into Jimpl:**

<img src="../.gitbook/assets/unknown (230).png" alt="" height="301" width="602">

**2. Review extracted EXIF metadata including camera model, timestamp, GPS coordinates (if available), and software used for editing:**

<img src="../.gitbook/assets/unknown (231).png" alt="" height="297" width="602">

<img src="../.gitbook/assets/unknown (232).png" alt="" height="309" width="602">

**3. Use the metadata to verify image authenticity, support geolocation efforts, or remove metadata if needed for privacy or publication.**&#x20;

**Note:** Be careful not to subscribe to Clarity Check who have been cited as taking illegal payments through PayPal.

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

The site uses a mix of Google analytics cookies, advertising/consent cookies, and Jimpl’s own session cookie.

### Use in Reporting

Jimpl is used by amateur and professional investigators to find more information from photos (device, location, etc).

It’s particularly useful to:

* Extract image metadata to support OSINT verification.
* Identify when and where a photo was taken (if GPS data is present).
* Detect image editing software used to modify images.
* Corroborate visual evidence in investigations.
* Support geolocation and timeline reconstruction.
* Help verify authenticity of user-generated or leaked images.

| **Capabilities**                                      | **Limitations**                                                           |
| ----------------------------------------------------- | ------------------------------------------------------------------------- |
| Extracts EXIF metadata from images.                   | Requires metadata to still be embedded in the image.                      |
| Displays camera, timestamp, and software information. | Many platforms strip EXIF data automatically (e.g. social media uploads). |
| Reveals GPS coordinates when available.               | GPS location data is often missing/disabled.                              |
| Helps detect image manipulation or editing.           | Cannot verify authenticity beyond metadata presence.                      |
| Supports privacy-focused metadata removal.            | Does not analyse image content, only embedded data.                       |

### Summary

Jimpl is a free tool, running since 2010, used by more than 750,000 users every month. It’s best used during the analysis and verification stages of the OSINT workflow for verifying the origin, time, and potential location of images during early-stage analysis and evidence validation. However, its effectiveness depends entirely on whether metadata has been preserved in the image file.

### Ownership

Jimpl is an independently operated web tool created by an individual developer named [Toni](https://x.com/ToniTheMaker), based in Romania.

### Ethical Considerations

* Only analyse images you are authorised to examine.
* Be cautious when handling images containing personal or sensitive data.
* Avoid misinterpreting metadata without cross-verification.
* Respect privacy when reporting geolocation or timestamp data.
* Be aware metadata can be removed or altered easily.
* Use findings as supporting evidence, not standalone proof.

### Related Tools:

* FotoForensics
* [Forensically](forensically.md)
* ExifTool
* Metapicz

#### Sources

[https://jimpl.com/](https://jimpl.com/)&#x20;

[https://x.com/ToniTheMaker](https://x.com/ToniTheMaker)&#x20;



_With thanks to Toni for submitting this tool to the OSINT Tool Library._

<br>
