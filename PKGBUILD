# Maintainer: @zstg <zestig@duck.com>
pkgname=stratos-bin
pkgver=1.0
pkgrel=1
pkgdesc="Core StratOS scripts"
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
	cp -r $startdir/usr/local/bin/ $srcdir/
}

package() {
    install -d $pkgdir/usr/local/bin/
    cp -a $srcdir/bin/* $pkgdir/usr/local/bin/
}
