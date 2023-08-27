# Exiteo Admin

![][urlCrenexiFav]

**[admin.exiteo.com][urlAdminProd]** | [stage-admin.exiteo.com][urlAdminStage]

Exiteo, a wayfinding platform. Administrative portal.

# Setup

## Dependencies & Installation

Same as Exiteo app procedures. **[See Exiteo repository][urlExiteoRepo]**.

# Tooling & Development

Same as Exiteo app procedures. **[See Exiteo repository][urlExiteoRepo]**.

# Development

- **Test**: use `cxa-upload.sh` from any local dir
- **Stage**: releases as step in stage pipeline
  - `npm run deploy:assets stage` within `build.stage.yml`
- **Prod**: releases as step in prod pipeline
  - `npm run deploy:assets prod` within `build.prod.yml`

# Footnotes

## License

- MIT License

## Authors

* **James Blume** - [Crenexi](https://github.com/crenexi)

[urlExiteoRepo]: https://github.com/crenexi/exiteo
[urlAdminProd]: https://admin.exiteo.com
[urlAdminStage]: https://stage-admin.exiteo.com
[urlCrenexiFav]: https://www.crenexi.com/assets/brand/fav_48x48.png
