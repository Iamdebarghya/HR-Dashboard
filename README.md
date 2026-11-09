# HR Analytics Dashboard | Advanced Excel

An Excel-based workforce reporting project. The repository contains the original workbook, a visual reference and documentation. A separate browser demo lets reviewers upload an Excel or CSV file and explore basic workforce summaries locally.

## Business questions
1. How is the workforce distributed across departments?
2. How do employee counts vary across available workforce categories?
3. What do salary distribution and summary measures show when salary data is present?
4. How can performance categories be compared when the source includes a rating field?

## Project components
- `HR_Dashboard .xlsx`: original Excel workbook.
- `DATA_DICTIONARY.md`: suggested field definitions and validation checks. Confirm every field against the workbook before use.
- `Updated_README.md`: earlier project notes.
- `Screenshot 2025-01-05 221120.png`: visual reference.
- Live browser demo: accepts an Excel or CSV upload, counts records, fields and missing cells, and calculates grouped totals/averages for a selected numeric field.

## How to review the workbook
1. Download `HR_Dashboard .xlsx`.
2. Open it in Microsoft Excel desktop.
3. Review the workbook sheets, PivotTables, charts and slicers that are present in the file.
4. Refresh PivotTables if you replace or extend the underlying source data.
5. Validate the source column meanings before interpreting any KPI.

## Browser demo
Open the live demo and choose an Excel or CSV file. The file is processed in the browser; it is not sent to a server. Select a category field and a numeric measure to see grouped row counts, totals and averages. This is a generic data exploration view, not a replacement for the Excel workbook's PivotTable functionality.

## Data quality and privacy
- Check duplicate and blank employee identifiers.
- Confirm salary units and pay frequency.
- Preserve the source's category labels and rating scale.
- Do not publish identifiable employee records or upload confidential HR data to a public demo.
- Workforce metrics should support, not replace, informed HR decisions.

## Limitations
The browser demo calculates grouped summaries from the uploaded file. It does not infer attrition, tenure, employee sentiment or performance outcomes unless the source contains the relevant fields and definitions. The data dictionary is a validation template, not a guarantee that every listed field exists in the workbook.

## Author
Debarghya Hajra | Advanced Excel, Data Analysis & Reporting
