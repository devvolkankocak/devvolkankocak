<a href="https://sophiras.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://sophiras.com/images/brand/sophiras-logo.png">
    <img src="https://sophiras.com/images/brand/sophiras-logo-koyu.png" alt="Sophiras" height="44">
  </picture>
</a>

### Software Architect · Founder of [Sophiras](https://sophiras.com)

I design and build multi-tenant SaaS products end to end: domain model, API, data isolation, security, web and mobile clients, and the infrastructure they run on. At Sophiras, six products share one architecture and one platform.

#### Architecture in production

| Product | What it does |
|---|---|
| [Mağazabulut](https://sophiras.com/en/urunler/magazabulut/) | E-commerce platform: storefront, B2B dealer pricing, marketplace sync (Trendyol, Hepsiburada, N11), virtual POS, shipping, product import |
| [Sahabulut](https://sophiras.com/en/urunler/sahabulut/) | Field service management: work orders, GPS-verified visits, customer portal |
| [Randevubulut](https://sophiras.com/en/urunler/randevubulut/) | Online booking: availability engine, staff calendars, reminders |
| [Menübulut](https://sophiras.com/en/urunler/menubulut/) | QR menu, waiter calls with abuse protection, orders and kitchen display |
| [Mesajbulut](https://sophiras.com/en/urunler/mesajbulut/) | WhatsApp Business response-time monitoring and reports for support teams |
| [Pano](https://sophiras.com/en/urunler/pano/) | Digital signage: design studio, schedules, offline-first players for TV, Android TV and iPad |

#### Principles I build on

- **Tenant isolation by default:** every query is scoped to a tenant; platform admins switch tenants explicitly.
- **CQRS with a validation pipeline:** thin endpoints, handlers per use case, FluentValidation, ProblemDetails errors.
- **Modular packaging:** features are modules a plan or add-on switches on; disabled modules return 403 and disappear from the UI.
- **Offline-first clients:** players and mobile apps keep working when the network drops.
- **Boring, observable operations:** containers behind a single reverse proxy, automatic TLS, backups before every migration, one-command deploys.

#### Stack

`.NET 10` `ASP.NET Core` `EF Core` `PostgreSQL` `SignalR` `React` `TypeScript` `Vite` `Tailwind` `Expo / React Native` `Swift` `Kotlin` `Docker` `Caddy` `Linux`

#### Selected client work

- [Yeniçağ Reklam](https://yenicagreklam.com): website for a sign and advertising production company (design and development)

#### Contact

[sophiras.com](https://sophiras.com) · info@sophiras.com
