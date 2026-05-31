# ari-legal

Canonical legal documents for the **Ari** Telegram bot operated by
**JoCoding Inc.**

| Document | Purpose |
|---|---|
| [`privacy-policy.ko.md`](./privacy-policy.ko.md) | 개인정보 처리방침 (PIPA Art. 30) |
| [`terms.ko.md`](./terms.ko.md) | 이용약관 (서비스 이용약관) |
| [`channel-notice.ko.md`](./channel-notice.ko.md) | 채널 이용 안내 (18+ · AI 고지 · PPV/환불 · 판매자 정보) |
| [`CHANGELOG.md`](./CHANGELOG.md) | Per-version change log |

`privacy-policy.ko.md` and `terms.ko.md` are linked from the bot's
`/start` consent prompt via Telegram URL buttons. The bot tracks each
user's accepted version and re-prompts when either document bumps to a
new version.

`channel-notice.ko.md` is the disclosure copy for the 1-to-many Ari
**channel** (free + PPV photos). Channel viewers never pass `/start`, so
its Section A goes in the channel description and Section B is pinned in
the channel. It is reference copy, not a versioned consent document.

**Contact:** ari.daily.creative@gmail.com

**License:** See [`LICENSE`](./LICENSE). All rights reserved.
