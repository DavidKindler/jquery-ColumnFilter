jquery-ColumnFilter
===================

jquery Table Column Filter

This jquery plugin takes ideas from several others that I have used but is built from scratch. This is a no-fills plugin that is fast and small. It is only 4K when minimized.

To use your table should have a thead and a tbody. The plugin will create a new table heading row for the filters. By default each column will have a text filter.

If you want a drop down list add “filter-type” attribute to th cell and set to ddl. eg. <th filter-type=”ddl”>
If you do not want column to be filtered add “filter-type” attribute to th cell and set to none. eg. <th filter-type=”none”>

Plugin options:
alternateRowClassNames : Alternating class names for each row after filtering. Maximum of two items.