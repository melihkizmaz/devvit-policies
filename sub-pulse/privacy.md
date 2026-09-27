# Sub Pulse — Privacy Policy

_Last updated: 2026-09-27_

This policy explains what the **Sub Pulse** app ("the App") for the Reddit Developer Platform stores, who can see it and how to delete it. Reddit's own [Privacy Policy](https://www.reddit.com/policies/privacy-policy) continues to apply to your use of Reddit.

## What we store

Sub Pulse stores counts, not content: it never stores the text of posts, comments or modmail.

Per community where the App is installed, in Reddit-hosted storage (Devvit Redis) that only that installation can access:

| Data | Purpose | Retention |
|---|---|---|
| Daily counts: posts, comments, reports, AutoMod filters, modmail received, mod actions by type, removals, approvals, bans, unbans, mutes, admin actions, queue wait times | Weekly digest and dashboard | 400 days |
| Moderator usernames with their action counts per day | "Per moderator" list (hidden when "Show usernames" is off) | 400 days |
| Usernames of posters and commenters with their post/comment counts per day | "Top contributors" lists | 35 days; not recorded while "Show usernames" is off |
| Ids and first-seen times of items in the modqueue; 5-minute queue size samples | Queue size, oldest item, wait time, alerts | Until the item leaves the queue (max 30 days); samples 35 days |
| Ids of processed events (posts, comments, mod actions, modmail messages, reports) | Counting each event once | 8 days |
| Subscriber count once a day | Growth and milestone | 400 days |
| Admin action ids and types | Admin-action alert | 35 days |
| Alert states, digest delivery status, moderator list cache, mod log import progress | Operating the App | While installed |
| Dashboard cache (may include top post titles and names, as shown to moderators) | Fast dashboard | Replaced hourly |
| Weekly archive (counts only, no names or titles) | History | 400 days |

We do **not** store the text of posts, comments or modmail messages, reporter identities (Reddit does not provide them), email addresses, location, device data or cookies. We do not use analytics or advertising trackers.

## Who sees it

Only moderators of the community: in modmail notifications, in the moderator-only dashboard post, and in the Discord/Telegram destinations the moderators configured. Private "preview" messages go only to the moderator who requested them.

## Sharing

We do not sell or share data. The App contacts two external services, and only when moderators configure them: `discord.com` (a webhook the moderators created) and `api.telegram.org` (a bot the moderators created). Those requests contain the digest or alert text — community statistics and, if "Show usernames" is on, the moderator and top-contributor names shown in the digest.

## Deletion and choices

- **Show usernames = off**: stops recording poster/commenter names and removes all names from digests, alerts and the dashboard.
- **Wipe all data** (subreddit mod menu → *Sub Pulse: wipe all data*, type `WIPE`): deletes everything the App stored for the community.
- **Uninstall**: stops all collection. Run *Wipe all data* first if you want the stored data deleted immediately.
- Users may ask the moderators, or the developer (see Contact), to remove their name from a community's lists.

## Children

Reddit requires users to be at least 13. The App does not knowingly collect additional data from anyone.

## Changes and contact

We may update this policy; the date above shows the latest version. Questions or requests: send a Reddit message to the developer account listed on the App's page at `https://developers.reddit.com/apps/sub-pulse`.
