---
title: Database properties window
outdated: true
---

# Database properties window

*Opened from the main window by selecting **File -&gt; Database properties***

The database properties window lets you set certain database-specific settings.

## Database encoding

This setting determines which character encoding JabRef will use when writing this database to disk. Changing this setting will override the setting made in Preferences dialog for this database. JabRef specifies the encoding near the top of the bib file, in order to be able to use the correct encoding next time you open the file.

## Override default file directories

These settings are used to specify which directory will be used to search for general file links (specified in the *file* field), and for legacy PDF/PS links (the *pdf* and *ps* fields were used in JabRef versions prior to 2.3, but should in current versions be replaced by general file links).

Relative directories can be specified. This means that the location of the files will be interpreted relative to the location of the bib file. Simply setting a directory to "." (without quotes) means that the files should reside in the same directory as the bib file.

These settings override the general file directories specified in the Preferences dialog. If no values are set, the general directories will be used.

## Database protection

This setting lets you enforce reviewing of external changes before the database can be saved. Without the protection enabled, users have the option to save even if other users have made changes to the file, without reviewing the changes - although they will be warned about the changes. When the protection is enabled, users will only be able to save after any external changes have been reviewed and merged (however, the user can disable individual changes in the course of reviewing them).

**Note:** this is not a security feature, merely a way to prevent users from overwriting other users' changes inadvertently. This feature does not protect your database against malicious users.
