# Maintainer: Your Name <your-email@example.com>
pkgname=cool-rain-1
pkgver=1.0.0
pkgrel=1
pkgdesc="A beautiful ASCII rain animation for your terminal"
arch=('any')
url="https://github.com"
license=('MIT')
depends=('bash' 'ncurses')
source=("cool-rain")
sha256sums=('SKIP')
package() {
    install -Dm755 "${srcdir}/cool-rain" "${pkgdir}/usr/bin/cool-rain"
}
