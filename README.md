# AFCMS uBlock lists

Tested with:

- Chrome (uBlock Origin Lite)
- Firefox (uBlock Origin)
- Brave (native adblock)

## Activism

Filters offtopic political activism in end user focused online platforms, software and documentation.

Doesn't aim to cover personal user profiles, forums or social networks. 

Currently filtered:

- [Leaflet's Ukraine flag](https://github.com/Leaflet/Leaflet/pull/8109) (any website)
- [npmx.dev's pride noodles](https://github.com/npmx-dev/npmx.dev/pull/2826) ([npmx.dev](https://npmx.dev))
  - May allow to [change the noodle](https://github.com/npmx-dev/npmx.dev/issues/2780) in settings in the future
- [Vikunja's pride logo](https://github.com/Vikunja/Vikunja/pull/2826) (any [vikunja.cloud](https://vikunja.io) instance, need to copy the rule for self-hosted instances)
  - Quite a lot of people complaining about it [in the forum](https://community.vikunja.io/search?q=pride)
  - Configurable per-user
  - [Configurable](https://vikunja.io/docs/config-options/#1-service-allowiconchanges) at the server level, but a [bug](https://github.com/go-vikunja/vikunja/issues/2821) have been reported preventing it from working.
- [Luanti's ContentDB "bigot troll"](https://github.com/luanti-org/contentdb/commit/d1372b0ab932435e7a1765378ea4370e7765cb9f)
- [Leboncoin's pride logo](https://www.leboncoin.fr)
- [Wikipedia's "Wiki Loves Pride" banner](https://www.wikipedia.org)
- [Preact's Ukraine banner](https://preactjs.com)
- [PlatformIO's Ukraine banner](https://platformio.org)
- [Codeberg's pride footer bar](https://codeberg.org)

> [!IMPORTANT]
>
> I strongly dislike in general the idea of putting voluntary political activism and/or virtue signaling in software when not directly related to the software's purpose (ex: a privacy focused app showing a banner criticizing threatening anti-privacy laws is understandable).
>
> The fact that a element is mentioned in this list doesn't automatically mean I don't understand or even support to a degree the political stances behind it.
>
> While I may not support, or even utterly despise some of them, I don't support any personal harassing of the individuals involved in the addition of these elements.