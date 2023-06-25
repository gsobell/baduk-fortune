# Contributor: @gsobell
# Maintainer:  @gsobell

pkgname=fortune-mod-baduk
pkgver=1
pkgrel=1
pkgdesc="Fortune cookies: Game of Baduk"
arch=('any')
license=('custom:PublicDomain')
url="https://github.com/gsobell/baduk-fortune"
depends=('fortune-mod')
groups=('fortune-mods')
source=("https://raw.githubusercontent.com/gsobell/baduk-fortune/shodan-branch/baduk")
sha256sums=('0c2197d0e02dd10d6930621a9c609e4f9f5edd0c17f4718760548bed5004ace9')

build() {
    strfile ${srcdir}/baduk
}

package() {
	  install -D -m644 ${srcdir}/baduk ${pkgdir}/usr/share/fortune/baduk
	  install -D -m644 ${srcdir}/baduk.dat ${pkgdir}/usr/share/fortune/baduk.dat
}
