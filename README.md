# 17 單車趣

GitHub Pages compiled assets. Source repository is private.

Version and SHA-256 inventory: version.json.

Visitors can browse sample routes and page introductions. My account, ride creation and personal actions require Google sign-in; first sign-in creates an account. Routes and riding records stay private. Legacy browser records are retained without automatic upload. Firebase stays on the Spark plan; cloud operations require a network connection.

Together rides (一起約騎) and private rides (私人約騎) share one creation form and integrated registration, capacity limits, waitlists, cancellation, promotion, host management and in-app updates. New rides default to private; visibility is fixed after creation. Signed-in members can discover and join together rides. Private rides require an expiring, revocable invitation; participant identities remain visible only to the host or that participant. Refresh to see updates; no external push notifications.

Legacy activities remain available. Hosts can explicitly enable registration; source mapping prevents duplicate conversions and freezes old write paths without deleting records or automatically making private activities public. Existing group IDs and invitations are preserved.

Hosts can click the registered count on a ride card or activity details to view the host, confirmed participants and ordered waitlist, with refresh and retry controls. Full rosters remain host-only.

Members can switch between all rides, their upcoming registrations (including waitlist positions) and hosted rides. My account and successful signup provide a shortcut; the next-ride reminder includes confirmed participation or hosted rides. Past and withdrawn registrations are excluded.

[Product Roadmap](https://qqjameqq1.github.io/17-cycling-pages/roadmap.html) is public, mobile friendly and readable without JavaScript. The website footer links to it. Planned features have no promised release dates.

Imported GPX routes can be viewed over surrounding MapTiler streets with Leaflet after explicitly opening the map. GPX files are not sent to the map provider. Failed tiles retain the local track preview; this is not navigation. Existing Google sign-in and private member storage remain in place.

Application source: `6bcfa6b524eaae801df4959e097952de9de685dd`.

Hosts can soft-delete rides with no past registrations, or cancel then archive rides that have participants. Completed rides can be archived. Activity history retains minimal name/time/status summaries for former participants without sharing meeting details or other identities. Deletion and archival are not reversible in this version. Refresh existing tabs after this update.
