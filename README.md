# Cindrella SMP music pack

Source-of-truth notes for the server's custom music discs (Java, Minecraft 26.2 / Paper).

The zip that players actually download is served from:

https://cindrella-music-pack-gw1tbz-preview.freebuff.site/cind-music.zip

Rebuild the zip after changing any `.ogg` or `sounds.json` with `node build-pack.mjs`, then re-upload it and update `resource-pack-sha1` in `server.properties`.

`jukebox_song` is a load-time registry: new discs only appear after a server restart, not `/reload`.
