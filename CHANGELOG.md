# v0.1.28

_Released 2026-10-30, changes since v0.1.27._

- fix(playback): file calendar days by the real local day, not one fixed offset
# v0.1.27

_Released 2026-10-30, changes since v0.1.26._

- feat(janitor): list the recordings missing from the index, without writing
- feat(admin): switch the janitor's delete permission from Settings
# v0.1.26

_Released 2026-10-30, changes since v0.1.25._

- fix(janitor): recover lost recording runs from their init segments
- fix(janitor): report how many recordings a run re-indexed
# v0.1.25

_Released 2026-10-30, changes since v0.1.24._

- fix(api): take a real camera password out of the Safire tests
- fix(web): keep the event list on screen while the next page loads
- feat(cloud): pair with Leviathan Cloud and publish cameras over a broker
- fix(storage): rebuild the index from disk, and stop deleting unasked
- style: apply rustfmt to files it had never been run on
- fix(live): stop view switches from restarting a warm stream
# v0.1.24

_Released 2026-09-30, changes since v0.1.23._

- feat(admin): bulk camera edits, pinnable display timezone, probe fix
# v0.1.23

_Released 2026-09-30, changes since v0.1.22._

- fix(discovery): ONVIF login and multicast discovery against real cameras
- feat(live): attention wall for sites with more cameras than a grid holds
- fix(web): show recording times on the server's clock, not the browser's
# v0.1.22

_Released 2026-09-30, changes since v0.1.21._

- fix(playback): keep main/sub in sync and give the timeline a real scale
# v0.1.21

_Released 2026-09-26, changes since v0.1.20._

- feat(native): edit the Safire camera's own settings from the UI
- fix(infer): safeguards so a Tier 2 failure can't silently jam the queue
# v0.1.20

_Released 2026-09-26, changes since v0.1.19._

- feat: release notes in apt and the UI, plus an update check
# v0.1.19

_Released 2026-09-26, changes since v0.1.18._

- fix(deploy): let recordings live anywhere instead of only /rec
# v0.1.18

_Released 2026-09-26, changes since v0.1.17._

- fix: feed reconnect gaps across go2rtc, recorders, live relay and tiles
# v0.1.17

_Released 2026-09-25, changes since v0.1.16._

- ci(apt-repo): per-version changelog + confirm Pages picked it up
- feat(web): mobile pass, playback calendar, health popover
- feat: two-factor authentication (TOTP)
- feat: automatic PTZ patrol/tour scheduling
- feat: inferred camera-to-camera movement graph (not a real floor plan)
- fix(janitor): auto-register paths.recordings so its health is actually watched
- feat(web): auto-load older events on scroll instead of a manual click
- feat: connection history, alert-enriched restarts, bitrate trend, RTSP failover
- feat(web): Alarm view — focus panel for active motion + all-camera grid
