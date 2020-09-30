## <a href=https://github.com/OfflineBay/TheOfflineBay>The Offline Bay</a>

The Offline Bay is a stand-alone searchable BitTorrent database containing over 31 million torrents.<br>
It requires nothing but a modern web browser - no installation, no admin privileges, and no network access.<br>
It works on Windows, Android, OS X, and Linux. 32 and 64-bit. <a href=https://raw.githubusercontent.com/OfflineBay/TheOfflineBay/master/docs/Search%20Results.png>Screenshot1</a> <a href=https://raw.githubusercontent.com/OfflineBay/TheOfflineBay/master/docs/Search%20Result%20Details.png>Screenshot2</a>

1. <a href="https://github.com/OfflineBay/TheOfflineBay/blob/master/docs/The%20Offline%20Bay.zip.torrent?raw=true">Download</a>
2. Extract
3. Search away!

Fake torrents are not removed from this database, but because of the in-depth information available, they are easy to spot.<br>
We are not affiliated with The Pirate Bay or <a href=https://github.com/techtacoriginal/offlinebay>OfflineBay by TechTac</a>.

The database is available in the following flavors:
- All (Everything - 31.1 million)
- All Alive (Everything alive - 5.3 million) (Recommended)
- TPB (The Pirate Bay only - 6.2 million) <a href="https://github.com/OfflineBay/TheOfflineBay/blob/master/docs/The%20Offline%20Bay.zip.torrent?raw=true">Download</a>
- TPB Alive (Alive from The Pirate Bay - 1.5 million)

Each torrent contains the following info (where available):<br>
Title, hash, age, size, seeders and leechers from 3 trackers, filelist, description, and trusted(TPB VIP+)/caution(large seed variance) tags.

Torrents are considered alive if they've been seeded within the last 3 months.<br>
Always use the alive variant unless you need dead torrents due to performance loss with the larger database.<br>
Torrents are sorted by seeders of the lowest tracker. This ensures torrents with fake seeds on one or two trackers do not appear high in the results. Tracker info is less than 2 weeks old. The age of the torrent is based on its first appearance in historic tracker scrapes. File lists are limited to the largest 32 files or (seed count + 1) files, whichever is smallest. Descriptions are limited to (seed count x 100) characters. Child exploitation torrents have been deleted.

Thanks to our torrent sources:
- The Pirate Bay
- Magnetico (DHT)
- Torrent-Paradise
- BTDB
 
Thanks to our tracker sources:
- Coppersurfer
- Leechers Paradise
- Cyberia

We get over 49.4 million unique hashes from the above sources.  Due to lack of searchable titles, only 31.1 million are available through The Offline Bay.

The Offline Bay is based on our to-be-released book.  This book will be released as an eBook and physical book.
This book promotes <a href=https://en.wikipedia.org/wiki/Evidence-based_policy>evidence informed policy</a> and <a href=https://en.wikipedia.org/wiki/Pirate_Party>pirate politics</a>, and <a href=https://kopimistsamfundet.se/english>Kopimism</a>, and contains a record of current and historical torrents shared over BitTorrent.
To prove our torrents are truthful, they can be verified by a <a href=https://qbittorrent.org>torrent client</a> using the magnet link.<br>
Copyright infringement is not authorised. We discourage it by including all fake torrents.<br>
The JavaScript is obfuscated to prevent theft and malicious modification. I would like to make it open source in the long term.<br>
Report bugs, request features, or talk to us at <a href=https://github.com/OfflineBay/TheOfflineBay/issues>GitHub</a>.

#### The future of this project will depend on its popularity. Priority of plans:
- An online version of this database.  Development complete - just need to buy a server. <a href=https://raw.githubusercontent.com/OfflineBay/TheOfflineBay/master/docs/basic.png>screenshot1</a> <a href=https://raw.githubusercontent.com/OfflineBay/TheOfflineBay/master/docs/detailed1.png>screenshot2</a> <a href=https://raw.githubusercontent.com/OfflineBay/TheOfflineBay/master/docs/detailed2.png>screenshot3</a>
- Another level of detail which adds detailed sources, historic tracking info, all TPB info(uploader/tpb_id/category/imdb/etc) (The same as the online version above)
- Release our Pirate Bay dump.  We made this after TPB stopped providing dumps.  It contains all the information of every torrent on TPB (no comments as per)
- Release a CSV/sqlite3 dump of our database (49.4 million torrents)
- WebTorrent/bitcoin integration for an updatable but serverless, domainless, and censorship resistant version (this is half developed, built around <a href=https://github.com/elendirx/web2web>web2web</a>).
- Options to sort by age/size (5x database size increase)
- Open source
- Python script so users can build their own database from available dumps/scrapes.

#### If you're good with CSS, unlike me, it would be great if you could help make it look pretty.
#### You can help pay towards hosting costs by donating BTC to bc1q5j808wvsqt9z0j6tyycarp0f306sxfug5xd3zh
We will never run pop-ups and will have no more than 1 ad per page on the online version.
