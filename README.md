<!-- tyhp-readme:start -->
# tyhpdef/filament-notifications

Tyhp type definitions for `filament/notifications` `5.8.2`.

```bash
composer require --dev tyhpdef/filament-notifications:5.8.2
```

This is a metapackage. Composer also installs `tyhpdef/filament-notifications-impl` (type files).
Require **this** name, not `tyhpdef/filament-notifications-impl`.

See https://tyhplang.com.

## Maintain `filament/notifications`? Ship the types yourself

If you are a Packagist maintainer of `filament/notifications`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/filament-notifications-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `filament/notifications` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/filament-notifications": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `filament/notifications` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `filament/notifications` with a real constraint,
   `"replace": { "tyhpdef/filament-notifications": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `filament/notifications` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/filament-notifications` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
