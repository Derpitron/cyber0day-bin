# Maintainer: @derpitron <aadhithyanm@protonmail.com>
pkgname=cyber0day-bin
pkgver=1.1
pkgrel=0
pkgdesc="Core StratOS scripts, modified for cyber0day"
arch=('any')
license=('GPL3')
depends=('bash' 'python' 'dialog')
optdepends=(
	'flatpak: Universal package manager'
 	'yay: package manager'
)
source=()
md5sums=()

prepare() {
	cp -r "$startdir"/usr/local/bin/ "$srcdir"/
}

package() {
    install -d "$pkgdir"/usr/local/bin/
    cp -a "$srcdir"/bin/* "$pkgdir"/usr/local/bin/
}
