This is the OpenSpending Registry of Datasets. It lists all officially
registered OpenSpending Data Packages.

It also acts as tracker for new datasets that we want to package and load into OpenSpending.

## The Registry

The Registry data is stored in a very simple way in a CSV file in the data directory.

```
data/catalog.csv
```

The structure of the registry file is as per [OSEP 6][osep6] (see OSEP for definitions):

```
url,name,owner,core
...
```

[osep6]: http://labs.openspending.org/osep/06-datastore/

----

## Tracking Data to Load

[![Stories in Ready](https://badge.waffle.io/openspending/datatoload.png?label=ready&title=Ready)](https://waffle.io/openspending/datatoload)

This is the **community tracker** for work to **load data** into [OpenSpending][]
(including tracking down, scraping, cleaning that data!). You can use it to:

- Register a data set for someone (maybe you!) to work on in the future
- Find new load you could contribute to
- Update on progress you are making working on data
- Discuss any of the above!

*A note on the technology: in theory this is some kind of git repo (don’t worry if you don’t know what that is). However, we’re just using the [issue tracker][issues] part of it -- there’s no code or any complex stuff.*

[OpenSpending]: http://openspending.org/
[issues]: https://github.com/openspending/datatoload/issues
[new]: https://github.com/openspending/datatoload/issues/new

### See what is happening

Take a look at the **[issues in the tracker &raquo;][issues]**

### Register data to work on

*Note: this can be data for someone else to work on :-)*

- Create a [new issue][new]

Add info like:

- The source & url of the source data to get into OpenSpending
- What does the data contain?
- what is the format of the data?
- Does it need data cleaning or data wrangling?

### Find data to work on

- Browse the [issue list][issues]
- Claim the dataset by assigning your self to the issue
- Ask for help from the community - see http://community.openspending.org/about/contact/
- When its done mark the issue as Closed

### Discuss stuff

Just comment on one of the [issues][] :-)
