# TZVIEW

Display in local time the moment in time in other timezones.

## Requirements

A date(1) command that supports "--date" argument. Busybox, binutils.

## Help

tzview

    Usage: tzview [-f FMT][-c LIST]
    
    Display in local time the moment in time in other timezones.
    
    Example "tzview.lst" file:
    
      America/New_York <tab> 08:00 <tab> New York Office Opening
      Europe/Berlin    <tab> 09:00 <tab> Berlin Office Opening
    
    The time format can be specified with the -f option, which is
    passed to the date command. The default format is "%H:%M".
    
    Default list: $TZVIEW_FILE, ~/.tzview.lst, /etc/tzview.lst

## Collaborating

For making bug reports, feature requests, support or consulting visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
