# Portfolio entries

Generally '' is uses over "", "" inside ''.

## Math studies entries

```
---
title: [name of studies]
page: portfolio
type: math
anchor: [anchor for HTML]
startyear:
endyear:
loc: [uni]
published: true
---
```

## Exhibition entries

```
---
title: [title of exhibition]
page: portfolio
type: exhibit
exhibittype: [solo/group]
anchor: [anchor for HTML and for general reference]
endyear: [used for sorting]
endmonth: [used for sorting]
loc: [location of the exhibition, name and city]
dates: [date range of exhibition, sorting is done on endyear then endmonth]
works:
  - [work1, anchor name]
  - [work2, anchor name]
  - [work3, anchor name]
press: [press release, flyer, poster]
extralink: [e.g. link to gallery website]
published: [true/false, false for loc not to be include in exhibition lists]
---
```

## Work entries

```
---
title: [title of the work]
page: portfolio
type: art
anchor: [anchor for the HTML and for general reference]
startyear: [when the work starting]
endyear: [when the work was completed, used for sorting, endyear then endmonth]
endmonth: [month it was complete, for sorting]
range: [true/false, to show range in list]
loc: [anchor name of location of original installation/exhibition, if any]
exhibitlist: [list of others exhibitions beyond the original, if any]
  - [exhibit1, anchor name]
  - [exhibit2, anchor name]
  - [exhibit3, anchor name]
imgdir: [directory for images]
published: true
---
```

[content is the materials, size, text, further description, curator, etc. plus photos]


# Praxis entries

## Talk entries

```
---
title: [title]
page: praxis
type: math
anchor: [anchor for HTML]
startyear:
endyear:
endmonth:
loc: [location of lecture]
dates: [semester]
extralink: [link to notes]
published: true
---
```

## Art entries

```
---
title: [name of the exhibition]
page: praxis
type: art
anchor: [anchor for HTML and for general reference]
endyear: [for sorting, endyear then endmonth]
endmonth: [for sorting]
loc: [location, not referencing exhibit entry]
dates: [date range]
press: [poster, etc.]
extralink: [website]
imgdir: [directory for the images]
published: true
---
```
