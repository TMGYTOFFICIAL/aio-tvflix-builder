# aio-tvflix-builder
A configuration tool for Stremio AIO builds.
Availible on: **https://aio.tvflix.co.uk/**
🚀 Update v2: AutoPlay, Anime Catalogs & Logic Fixes
This major update refines the logic for both Debrid and Non-Debrid users, restores deep catalog customization, and adds highly requested playback features.

✨ New Features

AutoPlay Customization: Added a dropdown to select how AIOStreams determines the next episode:

Matching File (Default/Smartest)

Matching Index

First File

Anime Catalogs Restored: Brought back the deep categorization for Anime (Airing Now, By Studio, Decades, etc.).

Balanced Catalog Order: The default catalog layout is now interlaced (Streaming Services mixed with Anime) to prevent the home screen from feeling too "Anime-heavy" at the top.

TorBox Priority: Moved TorBox to the top of the Debrid selection list for easier access.

🛠️ Critical Fixes

Non-Debrid Formatter: Fixed an issue where P2P users saw "Cache" emojis. Non-Debrid setups now correctly display Seeders (👥) and disable complex group fetching to ensure instant loading without timeouts.

Debrid Group Logic: Refined the "Smart Fallback" logic. The builder now correctly skips the first group and applies strict resolution/time limits to all subsequent groups for Debrid users.

CAMs Logic: Ticking "Include CAMs" now correctly clears the excludedQualities array, allowing CAM/SCR sources to appear.

UI Polish: AutoPlay options now automatically hide when "AIOMetadata Only" is selected. Added a support button.

⬇️ How to update No manual file editing required. Just use the web builder to generate a fresh aiostreams-config.json or aiometadata-config.json.
