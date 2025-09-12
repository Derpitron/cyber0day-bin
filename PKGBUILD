# Maintainer: @zstg <zestig@duck.com>
pkgname=stratos-bin
pkgver=1.0
<<<<<<< HEAD
pkgrel=9
||||||| parent of 0babc53 (Change theme name)
pkgrel=4
=======
pkgrel=5
>>>>>>> 0babc53 (Change theme name)
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
	cp -r "$startdir"/usr/local/bin/ "$srcdir"/
}

package() {
    install -d "$pkgdir"/usr/local/bin/
    cp -a "$srcdir"/bin/* "$pkgdir"/usr/local/bin/
}
