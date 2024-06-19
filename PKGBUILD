# Maintainer: rooyca <rooyca.f9rnz at aleeas dot com>
pkgname=sgsd
pkgver=1.0.0
pkgrel=1
pkgdesc="Simple Graphical Shutdown Dialog."
arch=('i686' 'x86_64')
url="https://github.com/Rooyca/sgsd"
license=('MIT')
depends=('python' 'tk')
source=("https://github.com/Rooyca/sgsd/archive/refs/tags/$pkgver.tar.gz")
sha256sums=('39b7871ab8e8095a7c94bddf06888ce1f5dcf95077538fb1a56bdf335399f70a')

build() {
    cd "$srcdir/sgsd-$pkgver"
}

package() {
    cd "$srcdir/sgsd-$pkgver/src"
    install -Dm755 sgsd.py "$pkgdir/usr/bin/$pkgname"
}