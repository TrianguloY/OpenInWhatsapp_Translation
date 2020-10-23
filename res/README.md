# Resources folder

App's strings.

'values' and 'raw' folders correspond to english version, used as default.

[Github] If you want to add a translation create a copy of the 'values' and 'raw' folders named 'values-[country code]' and 'raw-[country code]' respectively (example 'values-es' and 'raw-es') and translate the files inside.

Note: the 'raw/countries_name.txt' file can be very time-consuming to translate. If you remove that file from the translation the english names will be used.

Note: Each entry from 'raw/countries_name.txt' will be joined with the entry on the same line on 'raw/countries_ext.txt'. IMPORTANT!: Make sure the ordering of the countries is kept when translating, and don't remove/add/reorder any entry/line! otherwise the country code displayed will be wrong. (If you find a missing country just tell me).

Note: The changelog from 'raw/changelog.txt' is also used on the Play Store if there is a corresponding translation. You don't need to translate old versions if you don't want, and new versions without translations will use the english until provided.