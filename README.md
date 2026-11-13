# GlassTube

A native macOS app for YouTube and YouTube Music. Thanks for testing it!

Builds are signed with Developer ID and notarized by Apple.

## Install

1. You need **macOS 26 (Tahoe)** or later.
2. Download the latest `GlassTube-<version>.dmg` from
   [Releases](../../releases).
3. Open it and drag GlassTube to Applications.

Updates arrive in the app: GlassTube ▸ Check for Updates… (it also checks
once a day). You never need to download a DMG again.

## Signing in is optional

Everything works without an account: search, videos, channels, Shorts,
comments (reading), YouTube Music, and a Watch Later, Favorites and History
that live on your Mac.

Sign in (bottom of the sidebar) to get your own Home feed, Subscriptions,
playlists, Liked Music, likes, subscribing and commenting. Your sign-in is
kept in your Mac's Keychain and is only ever sent to YouTube.

## Good to know

- **Songs from YouTube Music** play through YouTube Music's own player,
  hidden inside the app. Signed out, that means YouTube Music's ads before
  some songs; the player bar says when one is playing. Signed in, songs
  play as your account. Music videos and ordinary videos play natively.
- **Songs or videos?** A song can open as its music video or as the song
  alone: use the Song / Video switch above the player, or Settings.
- **Keychain prompt:** if macOS asks whether GlassTube may use its saved
  sign-in, choose **Always Allow**.
- **This is an unofficial app.** YouTube changes things without notice, and
  occasionally a video won't play natively. GlassTube then falls back to
  YouTube's embedded player and says so. If something stops working, an
  update usually follows.

## Tell us what you find

**Help ▸ Send Feedback…** (or **Report…** on any error). Pick *Something's
wrong* or *Idea*, say what happened, and send. You don't need any account.

The sheet shows everything before it's sent: your message, an optional
name or email if you'd like a reply, a picture of the window and any
screenshots you add (⌘⇧4 works well), and the app's log from this session
with sign-in details, tokens and email addresses removed. You can untick
the log or preview it first.

Handy shortcuts: ⌘1 YouTube, ⌘2 YouTube Music, ⌘K search, ⌘D save for
later, ⌘/ for the full list.

---

`appcast.xml` is the [Sparkle](https://sparkle-project.org) update feed the
app reads. Every update in it is signed; the app refuses any that isn't.
