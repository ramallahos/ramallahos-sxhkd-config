# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-sxhkd-config
pkgver=1
pkgrel=1
pkgdesc="SXHKD config for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=('sxhkd')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -d "${pkgdir}/etc/skel/.config/sxhkd/"
    install -Dm 644 "sxhkdrc" "${pkgdir}/etc/skel/.config/sxhkd/sxhkdrc"
}
