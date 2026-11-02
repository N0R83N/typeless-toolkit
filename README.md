<div align="center">

# Typeless Toolkit

A local desktop companion for managing Typeless accounts, personal dictionaries, backups, and sync.

[Download](https://github.com/Jia131313/typeless-toolkit/releases/latest) · [Documentation](docs/reference.md) · [Issues](https://github.com/Jia131313/typeless-toolkit/issues)

</div>

Runs on Windows (WebView2) and macOS (Tauri). It also includes quota monitoring, account migration, dictionary tools, and compatibility maintenance.

## Quick start from source

Requires Node.js 22.12 or newer.

```bash
npm ci
npm run check
node manager.js
```

The local management page opens at `http://127.0.0.1:7788`.

## Important

Account exports and local login snapshots contain sensitive credentials. Protect them and never attach them to public issues. WebDAV sync encrypts the data you select.

Some optional maintenance features modify Typeless application files or reset device identity. They can stop working after updates and may conflict with the service's terms. Use the toolkit only with accounts and software you are authorized to use, and review the [full documentation](docs/reference.md) before using those features.

This is an independent community project and is not affiliated with Typeless. Released under the [MIT License](LICENSE).