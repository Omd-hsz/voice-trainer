# DECISIONS

2026-09-20 | Songs live in data.js, not inside the HTML | keeps every file under the 500-line limit
2026-09-20 | Videos embed from www.youtube.com, never nocookie | shares login cookies, avoids the bot check
2026-09-20 | Publish on GitHub Pages, public repo | free HTTPS; the microphone only works on https pages
2026-09-20 | No song downloader — synthesized guide tones + legal YouTube embeds | downloading copyrighted music is illegal
2026-09-20 | Pitch detection is hand-written autocorrelation | no new libraries without asking
2026-09-20 | data.js written two songs per line | 508 → 256 lines, back under the hard limit
2026-09-21 | Song-end detection via YouTube official player API, plain-iframe fallback | only way to know a song ended; fallback keeps old behavior
