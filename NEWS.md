# ChangeLog
## Changes to version 1.2.1
* fix bug
  * column names are broken using non-standard name in tibble
  * makedummies() converts 'NA' to '0'

## Changes to version 1.2.0
* add S3 methods
  * `matrix` class data is automatically converted to `data.frame` class
  * return tibble class when data is tibble
* fix several bugs
  * return rownames of input data

## Changes to version 1.1.2
* fix several bugs
  * the column names are inappropriate.
  * the columns are droped when they contain only one level.

## Changes to version 1.1.1
* Pull Request #1
  "add column name when when columns has binary value"
  (https://github.com/toshi-ara/makedummies/pull/1)
  Thanks to Kohki YAMAGIWA for the contribution.

## Changes to version 1.1
* makedummies() accepts a tbl class data.
* fixed bug when "POSIXt" class is included.

