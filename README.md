# home-automation releases

Signed `.deb` packages of [digital-sandbox](https://github.com/AShriki/home-automation), published by
its release workflow -- one `.deb` per version with a detached OpenPGP signature (`.sig`) beside it.
Installations check this repository for updates (Settings -> Updates) and install from it.

- **Do not commit here by hand.** Each release rewrites this repository as a single commit holding the
  newest three versions; anything else is replaced.
- Verify a package yourself with `gpgv --keyring <trusted key> <package>.deb.sig <package>.deb`.
  The release signing key is ed25519 `9C78 1669 F8EF FF62 19B6 AA04 563D 7596 4062 2548`.
