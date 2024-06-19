# Maintainer: rooyca <rooyca.f9rnz at aleeas dot com>
pkgname=sgsd
pkgver=1.0.0
pkgrel=1
pkgdesc="Simple Graphical Shutdown Dialog."
arch=('i686' 'x86_64')
url="https://github.com/Rooyca/sgsd"
license=('MIT')
depends=('python' 'tk')
source=("https://github.com/Rooyca/sgsd/archive/refs/tags/v$pkgver.tar.gz")
sha256sums=('')

build() {
    cd "$srcdir/sgsd-$pkgver"
}

package() {
    cd "$srcdir/sgsd-$pkgver"
    install -Dm755 sgsd.py "$pkgdir/usr/bin/sgsd"
}
