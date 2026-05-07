# tkh-ai-hackathon-may-2026

A single-file, browser-based inventory system built for [Indigo
Wellness][stakeholder], by a team of 6 fellows at [TKH][tkh], during an AI
hackathon held in May 2026. No installation required, just open the HTML file,
enter data daily, and everything saves locally in your browser, even without an
internet connection (for most tasks).

Key capabilities delivered:

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

Authors
* [Channel][https://github.com/cblue718]
* [Haojie][https://github.com/aslhhhhj97]
* [Ian][https://github.com/ian-s-mcb]
* [Manuela][https://github.com/Mchalen21]
* [Mike][https://github.com/mikeadarkwah-beep]
* Ozor

[stakeholder]: https://www.indigowellnessgroup.com/
[tkh]: https://www.theknowledgehouse.org/
