# Information Bundle No.4: Data formats and standards
Having a strong technical underpinning to the data you release is key to maximising its use and reusability by others, and in turn helps more value to be generated from that.

## (Open) Data Formats
- **Tabular**: Structured as one or more data tables of rows and columns. (e.g. CSV)
- **Geospatial**: Mapping data containing coordinates and attributes for location - may be vector (points, lines, polygons - e.g. property boundaries and roads) or raster (images - e.g. aerial and satellite imagery). (e.g. KML, GeoJSON, Shapefile)
- **Rich Media**: One or a combination of images, audio, and video - typically used for cultural datasets. (e.g. JPEG, MP3, MP4)
- **And the rest**: Many domain-specific formats across niche areas (e.g. Seismology, Laser and satellite remote-sensing);

The common thread between all of the formats is that they’re machine-readable data.

> “Data is machine-readable when it is structured data that can be automatically read and processed by a computer.”

Not to be confused with the wider array of types of digital formats. Just because something is in a digital format does it mean it’s machine-readable.

Machine-readable data makes reuse easier, enables you or others to query and analyse the data with ease using standard tools, and reduces the risks of errors when people have to copy/transcribe data from a non-machine-readable format.

### (Non-open) Data Formats
PDF, Word Docs, and Excel may be commonly used, but they do not make for good open data formats. As formats PDFs and Word Docs are focussed on presentation and readability for people.

Digital material need not be machine-readable.

Consider a PDF document containing tables of data. These are digital, and anyone can open them, but are not machine-readable because a computer would struggle to access the tabular information - they’re intended to be readable by people. The tables in the PDF inherently lacks any structure beyond that which is needed to display it visually. It’s lost the meaning and structure it once had and just been reduced to text. By comparison, the equivalent tables in a format such as a CSV/Spreadsheet are very much machine-readable.

In practice, there are always shades of grey. Most published data formats for Aus, US, and UK include a mix of good machine-readable formats and these non-open formats.

Something is always better than nothing. Don’t let the perfect be the enemy of the good.

### Further Reading
- [The Open Data Handbook: File Formats](http://opendatahandbook.org/guide/en/appendices/file-formats/)
- [Open Definition: Open Format Definition](http://opendefinition.org/ofd/)
- [Clean sheet: how to release data or statistics in a spreadsheet](http://www.clean-sheet.org/)
- [CSV - Comma Separated Values](http://frictionlessdata.io/guides/csv/0)
- [Data Packages - An emerging standard for packaging data, data schemas, and metadata in a machine-readable way](http://frictionlessdata.io/data-packages/)
- [Choosing the right format for open data](https://www.europeandataportal.eu/elearning/en/module9/#/id/co-01) - Open Data Institute
- [5 Star Open Data](http://5stardata.info/en/)

## APIs & Web Services
APIs (Application Programming Interface) are the language of machines - they provide set of requirements and rules that govern how machines send data and information to each other. They power almost every website on the Internet, every app on your phone. Every website that uses Google Maps, or website that lets you login with your Facebook account, uses an API.

APIs are inherently machine-readable, are easier to integrate with to build new services and tools, and ensures access to up-to-date data. People use your data directly from the source (your organisation). No need to copy, manipulate, and re-upload data. Less risk of misinterpretation and stale data.

Examples of APIs in government abound - from [Transport for NSW's Real-time Data API](https://opendata.transport.nsw.gov.au/), the [Australian War Memorial](https://www.awm.gov.au/direct/api/, to [Western Australia’s Shark Hazard API](http://api.fish.wa.gov.au/webapi/Introduction).

All jurisdictional government data portals in Australia - data.gov.au, data.wa.gov.au, et al. - automatically provide an API for machine-readable CSV files published to their platforms. Easy way to deliver and try out delivering a simple API. Talk to your open data team.

### Further Reading
- [What APIs Are And Why They’re Important - ReadWrite](http://readwrite.com/2013/09/19/api-defined/)
- [API 101 - API Evangelist](http://101.apievangelist.com/)


## Data Standards
> “Standards make it easier to create, share, and integrate data by making sure that there is a clear understanding of how the data are represented, and that the data you receive are in a form that you expected.” - US Geological Survey

When we talk about standards in this context we’re considering the structure of the data itself (i.e. the rules the data follows, descriptions of what each element of the data means, possible values). Data standards represents the next level of data maturity and ensures data can be shared and integrated with confidence and provides a clear explanation of how the data are represented.

Don’t let the lack of a standard stop you from publishing it. The way you describe your data now is *probably* perfectly OK if it’s in an open format with a well written description.

Think carefully before embarking on developing a standard. Do other organisations collect the same data as you or are you unique? What about internationally? Is there value in it for your users? Beware of over-engineering it, involve your data users, and talk to other publishers.

What does a good standard look like? Lightweight, developed collaboratively with publishers and users. Has value to community and users of the data. The [Open Council Data Standards](http://standards.opencouncildata.org/) are a good example of this approach.

### Further Reading
- [Data Standards - US Geological Survey](https://www2.usgs.gov/datamanagement/plan/datastandards.php)
- [Open Council Data Standards](http://standards.opencouncildata.org/)

## Licensing
- [Creative Commons Australia](http://creativecommons.org.au/)
- [Australian Government Public Data Policy Statement](https://www.dpmc.gov.au/public-data/public-data-policy)
