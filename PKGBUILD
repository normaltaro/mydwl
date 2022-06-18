# Maintainer: Devin J. Pohly <djpohly+arch@gmail.com>
pkgname=dwl
pkgver=0.3.1
pkgrel=1
pkgdesc="Simple, hackable dynamic tiling Wayland compositor (dwm for Wayland)"
arch=('x86_64')
url="https://github.com/djpohly/dwl"
license=('GPL')
depends=('wlroots>=0.15')
makedepends=('wayland-protocols')
optdepends=('xorg-xwayland: for XWayland support')
source=()

build() {
	cd ..
	make
}

package() {
	cd ..
	make PREFIX="$pkgdir/usr/" install
}
