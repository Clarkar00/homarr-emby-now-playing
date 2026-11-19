# Changelog

## Workshop revision 1

First release. The Workshop stores the manifest with Homarr's default request fields written out (`source`, `auth`, `trigger`, `permission`); behavior is unchanged.

- Live TV rows show the program airing on the channel: title, episode, time slot and progress, with the channel logo.
- DVR and VOD tags based on folder paths you set. Recordings still in progress show *Still recording · ends …*.
- Direct Play / Direct Stream stay gray. Remux is labeled REMUX. Real transcoding turns orange and says what is converted (audio, video or both), with the reason on hover.
- Resolution, HDR / Dolby Vision and audio format chips; LAN / WAN / Tailscale with bitrate; IPv4 and IPv6.
- Avatars, channel logos, and title links to Emby.
- Optional posters in their own column (*Title artwork*).
- Optional Stop button with a confirm step. It is the widget's only action (`POST /Sessions/{id}/Playing/Stop`) and is off by default.
- Light and dark themes, 12h / 24h time, up to 12 listed streams (extra streams are counted in the footer).
