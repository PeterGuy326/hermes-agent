# Authorship Record — DingTalk Gateway (hermes-agent)

This document records the original authorship of the DingTalk gateway
integration and QR-code auth support that was merged into
[NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
via a squash commit that did not include a `Co-authored-by` trailer.

## Original commits on this fork

All authored as `修雨 <huyizhou.hyz@alibaba-inc.com>` (GitHub: [@PeterGuy326](https://github.com/PeterGuy326)).

| Date (UTC) | SHA | Branch | Description |
|---|---|---|---|
| 2026-04-12 12:09:50 | [`94666e0f`](https://github.com/PeterGuy326/hermes-agent/commit/94666e0f) | `dingtalk_fix_0412` | feat(gateway): 增加钉钉平台配置及支持 |
| 2026-04-15 01:27:09 | [`fbcea2ef`](https://github.com/PeterGuy326/hermes-agent/commit/fbcea2ef) | `fix/dingtalk-webhook-domain` | fix(dingtalk): accept oapi.dingtalk.com webhook domain for stream mode reply routing |
| 2026-04-15 01:29:43 | [`4cd402f9`](https://github.com/PeterGuy326/hermes-agent/commit/4cd402f9) | `fix/dingtalk-stream-adapter` | fix(dingtalk): adapt message handler to dingtalk-stream SDK CallbackMessage format |
| 2026-04-15 01:33:49 | [`43d7d5d9`](https://github.com/PeterGuy326/hermes-agent/commit/43d7d5d9) | `feat/dingtalk-qr-auth` | feat(dingtalk): add QR code scan authorization for setup wizard |

Tagged references (immutable evidence even if branches are deleted):

- `authorship/dingtalk-gateway-initial` → `94666e0f`
- `authorship/dingtalk-webhook-domain`  → `fbcea2ef`
- `authorship/dingtalk-stream-adapter`  → `4cd402f9`
- `authorship/dingtalk-qr-auth`         → `43d7d5d9`

## Upstream merge

Squashed into a single upstream commit authored solely by `meng93 <yiweimeng.dlut@hotmail.com>`:

- [`9deeee7b`](https://github.com/NousResearch/hermes-agent/commit/9deeee7b) — feat(dingtalk): add QR code auth support and fix 3 critical bugs (2026-04-13 04:57 UTC)

The earliest commit on this fork (`94666e0f`, 2026-04-12 12:09 UTC) predates
the upstream squash commit by approximately 16 hours and 47 minutes.
