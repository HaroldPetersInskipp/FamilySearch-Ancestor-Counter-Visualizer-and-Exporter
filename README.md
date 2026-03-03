# FamilySearch-Ancestor-Counter-Visualizer-and-Exporter
Userscript to count the total unique ancestors found in the FamilySearch pedigree page allowing you to visualize and export the stored data.

Installation
------------
First, install an extension that enables UserScripts. There are several extensions for each web browser:

- Chrome or Firefox: [Tampermonkey](https://www.tampermonkey.net/)
- Firefox: [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)

Then, [click here to install](https://gist.github.com/HaroldPetersInskipp/3fb1733305d78531b111c0f78dda8d40/raw/familysearch-ancestor-counter-visualizer-and-exporter.user.js).


Usage
------------
Just navigate to [FamilySearch.org](https://www.familysearch.org/en/tree/pedigree/portrait/) and press the `Start` button seen in the below screenshot (you may need to refresh the page once for the tool to appear).

This tool can take a lot of time if your family tree is very large (10,000+), so there is a manual `Stop` button, just press start again to continue. If you leave the page this tool will stop.

The `Clear` button will clear all data stored in your web-browsers local storage.

After scanning your tree press the `Visualize` button to view a visualization of all the found ancestors color coded by generation.

You can search the stored data using names or PIDs.

Click on any of the found ansectors to pull up their FamilySearch page.

You can also export the stored data to a JSON file for further use or record keeping.

You can also drag the tool to another location or minimize it so it doesn't block any existing functions of the website.

Screenshots
------------
### Ancestor Counter:
<img alt="screenshot-1" width="1024px" src="screenshot-1.png" />

### Visualizer and Exporter:
<img alt="screenshot-2" width="1024px" src="screenshot-2.png" />
