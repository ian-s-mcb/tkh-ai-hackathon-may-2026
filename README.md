# tkh-ai-hackathon-may-2026

A single-file, browser-based inventory system built for [Indigo
Wellness][stakeholder], by a team of 6 fellows at [TKH][tkh], during an AI
hackathon held in May 2026. No installation required, just open the HTML file,
enter data daily, and everything saves locally in your browser, even without an
internet connection (for most tasks).

## Key capabilities delivered:

* Per-location stock tracking across Stamford and Westport with live dashboard,
  status alerts (OK / Low / Critical), and donut charts.
* Smart reorder points auto-calculated from batch size × average supplier lead
  time. Overdue shipments auto-flip to Delayed.
* Shipment management with AI extraction — drop a PDF or Excel order and the
  system reads supplier, ETA, location, and products automatically.
* Inventory Update (Purchase/Sales) with AI extraction, manual entry, duplicate
  detection (content hash + PO number), and an editable review table before
  committing.
* Transfer log with reason tracking (committed sale, stock balancing, event) and
  full audit trail per location.
* Trends & Forecast — 7-day usage rates, per-location Stamford vs Westport
  consumption chart, stockout forecast, and reorder recommendations.

## [Demo - screencast][screencast]

## Demo - steps follow on your local computer

1. Download this repository and open the `app.html` file in your web browser
2. Under `Settings` > `Data Management`, press `Restore backup` and pick the
   .json file within the sample_data folder.
3. Under `Inventory Update`, click the `Purchase / Restock` button, and either
   save the Claude AI API and choose a purchase order PDF (from the sample_data
   folder) OR press `Enter items manually` and fill in the item details.
4. Under `Inventory Update`, click the `Sales / Usage` button and repeat the
   previous step with a service invoice PDF OR service details.
5. Under `Dashboard`, inspect a particular item of interest and take note of its
   stock level status
6. Under `Inventory`, inspect that same item of interest and take note of the
   quantity per location
7. Under `Transfers`, click the `New Transfer` button , choose an item from the
   drop down menu, set the FROM and TO locations, set the Quantity, and finally
   click the `Confirm transfer` button.
8. Revist `Inventory` and `Dashboard` and note the changes stock level status
   and quantity per location for the item of interest.

## Authors
* [Chanel](https://github.com/cblue718)
* [Haojie](https://github.com/aslhhhhj97)
* [Ian](https://github.com/ian-s-mcb)
* [Manuela](https://github.com/Mchalen21)
* [Mike](https://github.com/mikeadarkwah-beep)
* [Ozor](https://github.com/ozormoya1794-a11y)

[stakeholder]: https://www.indigowellnessgroup.com/
[tkh]: https://www.theknowledgehouse.org/
[screencast]: https://drive.google.com/drive/folders/1TZe7sHsX8q2bn-_J__NeaALvQmzdG70G
