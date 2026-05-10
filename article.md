---
author: "Kyle Jones"
date_published: "January 8, 2025"
date_exported_from_medium: "November 10, 2025"
canonical_link: "https://medium.com/@kyle-t-jones/using-arrow-to-wrangle-dates-and-times-in-python-05f2e08de508"
---

# Using Arrow to wrangle dates and times in Python

Arrow simplifies the complex and tedious task of handling dates and times in Python by providing intuitive methods for creating...

### Using Arrow to wrangle dates and times in Python
#### Arrow simplifies the complex and tedious task of handling dates and times in Python by providing intuitive methods for creating, manipulating, and formatting time series data.
Raw data never has pristine dates and times. And fixing this with Pandas in a pain. **Arrow** simplifies handling, manipulating, and formatting dates and times. RIP `datetime.datetime.now()`.

Arrow improves Python\'s date and time handling by making it easy to create, manipulate, and format dates and times. It lets up change time zones and talk about time in a relative way, like "2 hours ago".

Install Arrow with:

``` 
pip install arrow
```

### Getting Started with Arrow
#### Creating Dates and Times
Arrow makes it easy to create date and time objects.

#### Converting Between Time Zones
Arrow makes time zone conversions simple.

#### You can also reference Time Zones
Arrow includes useful tools for converting between time zones.

#### Manipulating Dates and Times
Arrow lets you manipulate dates and times, by say adding or subtracting time.

``` 
2025-01-14T21:15:12.374752-06:00
2024-12-07T16:15:12.374752-06:00
```

#### Rounding and Flooring
You can round or floor dates to specific time units.

#### Formatting Dates and Times
Arrow lets you talk about time like a human and not in [Unix epoch time](https://en.wikipedia.org/wiki/Unix_time) (seconds since 1970).

#### Parsing and Converting Dates
Arrow makes it easy to parse and convert date strings.

#### Arrow and Pandas
Arrow integrates seamlessly with **Pandas** for working with time series data.

#### Time Zone Conversion in DataFrames

#### Handling Intervals
Arrow supports operations on time intervals, such as checking overlaps or durations. Let's calculate how long this call lasted.

The worst part of working with time series is formatting. Arrow makes this a lot (lot) easier. I will be using it for all my projects going forward.
