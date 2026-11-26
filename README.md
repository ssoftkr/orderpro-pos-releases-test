# OrderPro POS releases

This repository holds only the **installers** of the OrderPro POS app for Windows. It contains no source code.

Test builds (for example signed with a self-signed certificate). Used by the Test server and test PCs only, never by real shops.

- Each version is one Release whose tag is exactly the version number (for example `1.0.1`, without `v`), with `latest.yml`, the `.exe` installer and its `.blockmap`.
- Publish with `npm run release` in `clients/pos_app_electronjs` of the `ssoftkr/orderpro` repository.
- **Never delete** an old Release: rollback needs the files of older versions. **Never edit or replace the files** of a published Release: to fix something, raise the version.