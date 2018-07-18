# Resources folder

App's strings.

'values' and 'raw' folders correspond to english version, used as default.

If you want to add a translation create a copy of the 'values' and 'raw' folders named 'values-[country code]' and 'raw-[country code]' respectively (example 'values-es' and 'raw-es') and translate the files inside.

Note: the countries.txt file can be very time-consuming to translate. If you remove that file from the locale folder (simply by don't creating the 'raw-[country code]' copy) the english names will be used.

NEW: Using xml was a waste of size. Since version 1.12 countries are placed on a raw file with each newline an entry. Each entry from 'countries_name.txt' will be joined with the entry on the same line on 'countries_ext.txt'. IMPORTANT!: Make sure the ordering of the countries is kept when translating, and don't remove/add/reorder any entry/line! otherwise the country code displayed will be wrong.