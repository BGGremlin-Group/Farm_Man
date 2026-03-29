Farm Manager v1
======================================

Files
-----
- Farm_ManagerV1.html
- README.md

What was changed
----------------
This clean V1 build was made from the uploaded original ranch tracker.
The following cleanup changes were applied:

- Removed bundled demo/preloaded ranch records
- Removed demo reset/reload behavior
- Changed startup to a blank ranch tracker
- Changed the local IndexedDB name so old saved demo data does not auto-load into this build
- Removed user-facing meta/build/demo wording from the interface
- Kept the main V1 ranch tracking modules intact

What in the app
---------------------
- Herd profiles
- Health logs and doctor/triage records
- Feed and inventory tracking
- Breeding and birth logs
- Finance and transaction tracking
- Land, asset, and maintenance tracking
- Media vault
- Reports and import/export tools
- Field guide content
- JSON, YML/YAML, CSV, and PDF export/import support already present in V1

How to use
----------
1. Open Farm_ManagerV1.html in a modern browser.
2. Start entering your own ranch data.
3. Use Save Now to persist changes locally.
4. Use the Reports + Import/Export section for backups and report output.
5. Use Clear All Data only if you want to wipe the current local ranch book for this clean build.

Storage note
------------
This clean V1 build uses a separate browser database from the original demo-loaded file,
so it should not auto-populate with the old sample ranch records.

Recommended backup workflow
---------------------------
- Use JSON for the most complete backup format
- Use YML/YAML for readable structured backups
- Use CSV for table-style exports
- Use PDF for a printable ranch report with visuals and charts

