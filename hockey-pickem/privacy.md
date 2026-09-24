# Hockey Pick'em — Privacy Policy

_Last updated: 2026-09-24_

This policy explains what the **Hockey Pick'em** app ("the App") for the Reddit Developer Platform stores and how you can delete it. Reddit's own [Privacy Policy](https://www.reddit.com/policies/privacy-policy) continues to apply to your use of Reddit.

## What we store

Per community where the App is installed, in Reddit-hosted storage (Devvit Redis) that only that installation can access:

| Data | Purpose | Retention |
|---|---|---|
| Your Reddit user id (`t2_…`) | Link picks and stats to you | Until you delete it, your account is deleted, or the App is uninstalled |
| Your picks (team, overtime call) and the time you made them | Score the game, show your pick back to you | 60 days after the game is final or void (then expires automatically) |
| Derived stats: points, picks, correct picks, streaks, weekly stats, rank | Leaderboards and your "Me" page | Current season (weekly stats expire after 120 days) |
| Your username (cache) | Show names on the leaderboard | 24 hours |
| Aggregate pick counts per game (not linked to you) | Community split display | 60 days after the game is final |

We do **not** collect email addresses, location, device data, cookies or any content you write. We do not use analytics or advertising trackers.

## Sharing

We do **not** sell or share your data. The App calls one external service, `api-web.nhle.com`, to read public hockey schedules and scores; those requests contain **no information about you**. Your username, points and rank are visible to other members of the community on the leaderboard. If moderators enable leaderboard flair, your rank and points may appear as your user flair in that community.

## Your choices and deletion

- **Delete your data at any time**: open any Hockey Pick'em post → **Me** → *Delete my Pick'em data*. This removes your picks, stats, leaderboard entries and flair tracking in that community immediately.
- **Account deletion**: if you delete your Reddit account, a daily job removes your user id and all related data from the App's storage. Because Reddit reports suspended accounts the same way as deleted ones, the job waits until an account has been unreachable for 7 days before removing its data; use *Delete my Pick'em data* for immediate removal.
- **Post deletion**: when a slate post is deleted, the picks made on it are removed.
- **Other requests**: moderators or players can ask the developer to remove a community's or a player's data (see Contact).

## Children

Reddit requires users to be at least 13. The App does not knowingly collect additional data from anyone.

## Changes and contact

We may update this policy; the date above shows the latest version. Questions or requests: send a Reddit message to the developer account listed on the App's page at `https://developers.reddit.com/apps/hockey-pickem`.
