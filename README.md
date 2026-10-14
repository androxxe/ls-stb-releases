# ls-stb-releases — release artifacts

Repositori ini **hanya berisi aset rilis** (`school-stb-daemon`, `install.sh`, `sha256sums.txt`).
Source code ada di repo private: [androxxe/hansip-mobile-monorepo](https://github.com/androxxe/hansip-mobile-monorepo).

> **Jangan commit manual ke repo ini.** Aset di-upload otomatis oleh GitHub Actions
> (`.github/workflows/release-stb-daemon.yml`, tag `stb-school-v*`). Tidak ada source di sini.

## Install di STB

```bash
curl -fsSL https://github.com/androxxe/ls-stb-releases/releases/latest/download/install.sh | sudo bash -s -- --help
```

Repo rilis pasangan: [androxxe/ho-stb-releases](https://github.com/androxxe/ho-stb-releases)

Dokumentasi lengkap: `specs/shared/stb-daemon-deployment.md` di monorepo.