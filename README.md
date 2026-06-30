# Hermes Marketing Skills

Marketing skills for Hermes Agent.

## Skills

| Skill | Path | Use |
| --- | --- | --- |
| `copywriting` | `marketing/copywriting/` | Write and adapt marketing copy. |
| `cro` | `marketing/cro/` | Improve conversion paths. |
| `developer-marketing` | `marketing/developer-marketing/` | Plan technical audience campaigns. |
| `seo-audit` | `marketing/seo-audit/` | Review organic search readiness. |
| `hermes-tweet` | `marketing/hermes-tweet/` | Use the Hermes Tweet plugin for X/Twitter search, monitoring, publishing, and gated social actions. |

## Hermes Tweet Setup

```bash
hermes plugins install Xquik-dev/hermes-tweet --enable
hermes tools list
```

Set `XQUIK_API_KEY` in the Hermes runtime environment before authenticated reads.
Keep `HERMES_TWEET_ENABLE_ACTIONS` unset unless the workflow needs approved
account actions.
