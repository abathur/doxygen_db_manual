# doxy_db

Doxy_db (WIP) helps you compose sqlite3 databases generated by Doxygen into multi-section manuals that have a simple query API.

doxy_db leverages improvements to Doxygen's sqlite3 generator which were first available in Doxygen 1.8.15. Unfortunately, an issue cropped up in Doxygen 1.8.16 that causes junk data in some columns; a fix may be in 1.8.19, but for now 1.8.15 is the only "safe" major version. The current Nix build of doxy_db will use https://github.com/abathur/doxygen/tree/sqlite3_text_safety for now.
