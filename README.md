🧭 Ordinal Children JSON Generator
This is a lightweight web app that lets you input a parent Ordinal ID and generate a JSON array of its child inscriptions. You can optionally include metadata formatted for marketplaces like Magic Eden.

✨ Features
🔍 Fetches all child inscriptions from a given parent ID using the ordinals.com recursive end points.

🧩 Optional metadata support including asset naming and trait attributes.

📝 Generates JSON in the format used by marketplaces like Magic Eden.

📎 Copy or download the output instantly.

--------------------------------------------------------

🚀 How to Use
Open the tool in your browser (or host it on your own site).

Enter the Parent Ordinal ID in the first input box.

Choose whether to include metadata:

If "Include meta" is selected:

Enter a base Asset Name (e.g. Bitcoin Bandits) — this will append numbers like Bitcoin Bandits #1, #2, etc.

Add a single trait type and value (e.g. Clan: Aoi) to be applied to all.

Click Generate JSON.

--------------------------------------------------------

After generation:

View the total number of children.

Click Download JSON to save the file.

Or click Copy to Clipboard to paste it elsewhere.

--------------------------------------------------------

🛠 Developer Notes
Built with vanilla HTML, CSS, and JavaScript.

No frameworks or dependencies.

Uses the endpoint:
https://ordinals.com/r/children/{PARENT_ID}/{PAGE_INDEX}

🧡 Credits
Made with ❤️ by 9iNE
