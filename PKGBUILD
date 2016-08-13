# Maintainer: Xin-Xin Wang <xin-xinw@musiclifephilosophy.com>
pkgname=arch-icon
pkgver=1.0.0
pkgrel=1
pkgdesc="The Arch Linux icon for the MATE toolbar"
url="https://github.com/xinxinw1/arch-icon"
install=arch-icon.install
license=('GPL')
arch=('any')

package() {
  # Installing icon
  mkdir -p "$pkgdir/usr/share/pixmaps/"
  install -m 644 arch-icon.png "$pkgdir/usr/share/pixmaps/"
}
