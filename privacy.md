Watch Later Triage: Privacy Policy

Effective date: October 12, 2026. Applies to version 1.0.0.

Watch Later Triage keeps everything on your device. It does not send your YouTube data to the developer, to analytics services, or to any AI service.

Summary

Watch Later Triage is a Chrome extension that helps you search, sort, and clean up your YouTube Watch Later list. It runs in your browser. The developer has no server, no account system, and no access to your data.

Your video list is stored only in your browser's local storage.
There is no analytics and no telemetry.
Nothing is added to, or deleted from, your YouTube account without your explicit confirmation.
You can clear all local data and remove the Google connection at any time.
Data stored on your device

The extension saves the following in your browser's local database (IndexedDB). It never leaves your device.

Watch Later videos: video ID, title, channel name, thumbnail link, duration, and list position
Your own playlists: names and the video IDs inside them (only if you connect your Google account)
Labels the extension and you assign: purpose category, review status, manual corrections, and suggestion decisions
Sync and search state: progress of the last sync, your per-video corrections, records of past delete runs (video IDs), disclosure timestamps, and a cache of your playlists
Usage counts (usage_events): views, searches, and opens with a session ID. They stay on this device and are never sent. Your search text is never recorded.
Google connection status: the date you connected, and no token

This data is not transmitted to the developer or to any third party. Removing the extension, or using "Clear all local data" in the Privacy & data panel, deletes it.

What we collect and share

We collect nothing and share nothing. The developer receives no data from the extension.

No analytics, telemetry, crash reporting, or advertising.
No developer-operated server stores or processes your data.
No AI service receives your video titles, channels, or any other data. Version 1.0.0 contains no AI integration.
We do not sell, rent, or transfer your data, and we do not use it for ads, credit decisions, or profiling.

The extension only contacts these hosts: youtube.com (to read and manage your Watch Later list in your signed-in session), googleapis.com (YouTube Data API and token revocation, only if you connect Google), accounts.google.com (sign-in, only if you connect Google), and i.ytimg.com (video thumbnails, loaded by Chrome when shown, as on YouTube itself). Checking asks youtube.com's public lookup service about each saved video ID. Your sign-in is not sent.

Google account access

Connecting your Google account is optional. Sorting, search, and cleanup of Watch Later work without it. You connect only to use duplicate detection and to move videos into your own playlists.

When you connect, the extension asks for the YouTube permission youtube.force-ssl. This is a broad Google permission that allows managing your YouTube account. The extension uses it only to:

read the names and contents of your own playlists, so it can find duplicates and suggest where a video belongs
add a video to a playlist, or create a playlist, after you confirm that specific action

It never reads or changes your playlists in the background, and never acts without your confirmation. Your access token is kept in memory only. Chrome may re-authorize quietly until you revoke access at myaccount.google.com/permissions. Your Google password is never seen by the extension.

At most 20 playlist writes per day. A batch stops at the limit and tells you how many were added.

Google API Services User Data Policy. The extension's use and transfer of information received from Google APIs adheres to the Google API Services User Data Policy, including the Limited Use requirements. Data from Google APIs is used only to provide the features described here. It is not transferred to others, not used for advertising, and not read by humans.

YouTube session and cookies

YouTube does not let apps read the Watch Later list through its official API. To work around this, the extension reads your list while you are signed in to YouTube in this browser.

It reads YouTube sign-in cookies (SAPISID) to authenticate requests to youtube.com, the same way the YouTube website does.
Only a one-way hash of the cookies is sent, and only to youtube.com. The cookies are not stored by the extension, not logged, and not shared with the developer.
The extension uses these requests to read your Watch Later list and, only after you confirm, to remove videos from it.

These are YouTube's internal, undocumented endpoints. YouTube may change or block them, in which case the extension stops working safely rather than acting on unexpected data.

This is explained in a notice shown before your first full-library sync. The sample sync reads only the page you have open and uses no cookies.

Your controls
Clear all local data: in the Privacy & data panel, this deletes everything the extension stores. It changes nothing on YouTube and does not remove the Google connection.
Remove Google connection: in the Privacy & data panel, this clears the connected state. Press Connect to use Google again. The extension asks Google to revoke access, but Google may keep the permission, so also use the next step.
Revoke access at Google: go to myaccount.google.com/permissions, and remove Watch Later Triage if it is listed. Do this to be certain Google no longer treats the extension as authorized.
Uninstall: removing the extension from Chrome deletes its local data.
Confirmations: every delete and every playlist change asks you first. Categorization runs on your device with fixed rules and sends nothing anywhere.
Security, retention, and other terms

Security. Data stays in your browser profile, protected by Chrome and your device's own security. Because the extension has no server, there is no developer database that could be breached.

Retention. Data stays on your device until you clear it or uninstall the extension. The developer holds no copy.

Children. The extension is not directed at children under 13 and collects no data from anyone.

Changes. If a future version changes how data is handled, this policy will be updated before release and the extension will tell you at the point of any new data use. Any feature that sends data outside your browser will be off by default and need your explicit opt-in.

Not affiliated. Watch Later Triage is an independent tool. It is not affiliated with, endorsed by, or sponsored by YouTube or Google. YouTube and Google are trademarks of Google LLC.

Contact. Questions or requests: marvin-101@live.ca.
