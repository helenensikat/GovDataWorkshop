# Information Bundle No.4: Data formats and standards
Having a strong technical underpinning to the data you release is key to maximising its use and reusability by others, and in turn helps more value to be generated from that.

## (Open) Data Formats
- **Tabular**: Structured as one or more data tables of rows and columns. (e.g. CSV)
- **Geospatial**: Mapping data containing coordinates and attributes for location - may be vector (points, lines, polygons - e.g. property boundaries and roads) or raster (images - e.g. aerial and satellite imagery). (e.g. KML, GeoJSON, Shapefile)
- **Rich Media**: One or a combination of images, audio, and video - typically used for cultural datasets. (e.g. JPEG, MP3, MP4)
- **And the rest**: Many domain-specific formats across niche areas (e.g. Seismology, Laser and satellite remote-sensing).

### (Non-open) Data Formats
Digital material isn't necessarily machine-readable.

> "Non-digital material (for example printed or hand-written documents) is by its non-digital nature not machine-readable. But even digital material need not be machine-readable. For example, consider a PDF document containing tables of data. These are definitely digital but are not machine-readable because a computer would struggle to access the tabular information - even though they are very human readable. The equivalent tables in a format such as a spreadsheet would be machine readable." - The Open Data Handbook

In practice, there are always shades of grey. Most published data formats for Aus, US, and UK include a mix of good machine-readable formats and these non-open formats. Something is always better than nothing, so don't let the perfect be the enemy of the good.

### Further Reading
- [The Open Data Handbook: File Formats](http://opendatahandbook.org/guide/en/appendices/file-formats/)
- [Open Definition: Open Format Definition](http://opendefinition.org/ofd/)
- [Clean sheet: how to release data or statistics in a spreadsheet](http://www.clean-sheet.org/)
- [CSV - Comma Separated Values](http://frictionlessdata.io/guides/csv/0)
- [Data Packages - An emerging standard for packaging data, data schemas, and metadata in a machine-readable way](http://frictionlessdata.io/data-packages/)
- [Choosing the right format for open data](https://www.europeandataportal.eu/elearning/en/module9/#/id/co-01) - Open Data Institute
- [5 Star Open Data](http://5stardata.info/en/)
- [Creating machine readable data - DataWAGovAu](https://data.wa.gov.au/fact-sheets-and-toolkit/creating-machine-readable-data)
- [A Primer on Machine Readability for Online Documents and Data - DataGov US](https://www.data.gov/developers/blog/primer-machine-readability-online-documents-and-data)

## APIs & Web Services
APIs (Application Programming Interface) are the language of machines - they provide set of requirements and rules that govern how machines send data and information to each other. They power almost every application on the Internet, every app on your phone. Every website that uses Google Maps, or website that lets you login with your Facebook account, uses an API.

Examples of APIs in government abound - from [Transport for NSW's Real-time Data API](https://opendata.transport.nsw.gov.au/), the [Australian War Memorial](https://www.awm.gov.au/direct/api/), to [Western Australia’s Shark Hazard API](http://api.fish.wa.gov.au/webapi/Introduction).

All jurisdictional government data portals in Australia - data.gov.au, data.wa.gov.au, et al. - automatically provide an API for machine-readable CSV files published to their platforms. Easy way to deliver and try out delivering a simple API. Talk to your open data team.

### Further Reading
- [Publishing data for API acccess - DataGovAu](https://toolkit.data.gov.au/index.php?title=Publishing_Data)
- [What APIs Are And Why They’re Important - ReadWrite](http://readwrite.com/2013/09/19/api-defined/)
- [API 101 - API Evangelist](http://101.apievangelist.com/)


## Data Standards
> “Standards make it easier to create, share, and integrate data by making sure that there is a clear understanding of how the data are represented, and that the data you receive are in a form that you expected.” - US Geological Survey

Think carefully before embarking on developing a standard. Do other organisations collect the same data as you or are you unique? What about internationally? Is there value in it for your users? Beware of over-engineering it, involve your data users, and talk to other publishers.

What does a good standard look like? Lightweight, developed collaboratively with publishers and users. Has value to community and users of the data. The [Open Council Data Standards](http://standards.opencouncildata.org/) are a good example of this approach.

### Further Reading
- [Data Standards - US Geological Survey](https://www2.usgs.gov/datamanagement/plan/datastandards.php)
- [Open Council Data Standards](http://standards.opencouncildata.org/)

## Licensing
- [Creative Commons Australia](http://creativecommons.org.au/)
- [Australian Government Public Data Policy Statement](https://www.dpmc.gov.au/public-data/public-data-policy)
