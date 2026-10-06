# Office document processor sources for LM Studio

Source references and patches for the V1 release of LM Studio's
`office-document-processor` extension pack.

## Sources

| Source | SHA-256 |
| --- | --- |
| [LibreOffice 26.2.5.2](https://download.documentfoundation.org/libreoffice/src/26.2.5/libreoffice-26.2.5.2.tar.xz) | `8ec785ee1fd1a1d9b9d8eba1c8ff7556695ca8f02e1f7a26bef8cd540f669fea` |
| [Culmus 0.140 editable sources](https://sourceforge.net/projects/culmus/files/culmus/0.140/culmus-src-0.140.tar.gz/) | `ba7cb2c8bf7011e23cf37671a383a6a483903cffbdca4a327e85a8dbec4ec73a` |
| [Liberation Sans Narrow 1.07.6 editable sources](https://github.com/liberationfonts/liberation-sans-narrow/files/2579430/liberation-narrow-fonts-1.07.6.tar.gz) | `5244818c804dd590d7852d49ab08b18edaaecc54a70e3f79a0779235c5a751c8` |

Upstream dependency sources and patches are identified by the LibreOffice release's
`download.lst`, `Makefile.fetch`, and `external/` directory.

Our modifications are in [`patches/`](patches/).

## Licenses

Our original LibreOffice modifications and documentation are available under
[MPL 2.0](LICENSE). Upstream code in the patches and linked third-party components
retain their own licenses and notices.

The linked font sources include their GPLv2 terms, font exceptions, copyright notices,
and generation scripts. Culmus includes `GNU-GPL`, `LICENSE`, and `LICENSE-BITSTREAM`;
Liberation Sans Narrow includes `COPYING` and `License.txt`. These fonts are not
relicensed under MPL. This repository does not replace the license notices that must
accompany the binaries.
