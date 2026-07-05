# Decor My Nest — Live Site Measurement

A mobile-friendly painting measurement app that runs directly in the browser.

## Run

Double-click `Start Decor My Nest.bat`. It opens the app in Microsoft Edge through
localhost so Leica DISTO X3 Bluetooth can work.

Opening `index.html` directly supports manual measurements, but browser security
may block the Leica Bluetooth chooser.

## Painting system rate sheet

Double-click `Open Painting Rate Sheet.bat` to edit the live CSV in Excel. Use
these columns exactly: Product, Painting Type, Painting System, Surface /
Substrate, Rate per Sq Ft, Active, and Last Updated.

Save the CSV in place. When the app is running through `Start Decor My Nest.bat`,
it checks the sheet every 15 seconds and automatically updates matching rates.
You can alternatively paste a published Google Sheet CSV URL in the app.

## Included

- Multiple room measurements
- Itemised estimate table with area description, substrate, L/W/H, deductions, rate, and line total
- Leica DISTO X3 Bluetooth Smart measurement capture
- Automatic wall area and opening deductions
- Paint quantity with coats, coverage, and wastage
- Paint and labour estimate for the complete project
- Site notes and photo capture
- Printable site report
- Automatic local saving
