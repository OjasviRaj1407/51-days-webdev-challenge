# Web Development Day‑03

## Nested lists

1) Nested list = a list inside another list.  
2) An ordered list `<ol>` can contain `<li>` items, and each `<li>` can have its own nested unordered list `<ul>` (or vice‑versa).  
3) In the “Countries List” example, the outer `<ol>` lists countries, while each country `<li>` contains a `<h2>` and an inner `<ul>` of cities.  
4) Proper indentation makes nested lists easier to read and maintain.

## Basic table structure

1) `<table>` defines the table; `border="1"` is a quick way to show borders (for practice only; in real projects use CSS).  
2) `<thead>` holds the header row with `<th>` cells.  
3) `<tbody>` contains the data rows with `<tr>` (table row) and `<td>` (table data) cells.  
4) `<tfoot>` is used for summary/total rows (e.g., “Total 15, $2.50” in the items table).

## Colspan

1) `colspan="n"` allows one cell to span **n columns** horizontally in that row.  
2) In the “Contact Info” table, the header cell “Contact Info” uses `colspan="2"` to cover both the phone and email columns under a single heading.  
3) Colspan is useful for section headers, totals, and combined cells in invoices or reports.

## Rowspan

1) `rowspan="n"` allows one cell to span **n rows** vertically in that column.  
2) In the “Row1 Cell 1” example, `rowspan="2"` makes one cell cover two stacked rows, while other columns still show separate cells.  
3) The more complex “System / System Apps / System Env” table uses multiple rowspans to show a hierarchy, where one high‑level category cell stretches across several detailed rows.

## Planning complex tables

1) Always calculate the total number of rows and columns before adding `rowspan` and `colspan`.  
2) For each row, make sure the total column span (including merged cells) matches the table’s column count.  
3) Start with a simple table using only `<tr>` and `<td>`, then gradually add `rowspan`/`colspan` once the structure is clear.
