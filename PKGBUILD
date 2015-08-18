# Contributor: Tony Upton <celticmusicguy at gmail dot com>
# Contributor: Joel Almeida <aullidolunar at gmail dot com>

pkgname=xfce-theme-murrine-unity
pkgver=20110416
pkgrel=4
pkgdesc="A clean and simple Xfwm4 which matches the Murrine Unity GTK theme"
arch=('any')
url="http://code.google.com/p/murrine-unity-project/"
license=('GPL')
depends=('xfwm4')
optdepends=('gtk-xfce-engine' 'gtk-theme-murrine-unity')
source=('http://murrine-unity-project.googlecode.com/files/Murrine-Unity-XFCE-20110416.tar.gz')
md5sums=('3d456c3ccbbb3b5f2379a78fe2bced46')

build() {
	cd "${srcdir}"
}

package() {
	cd "${srcdir}"
	find "Murrine-Unity" -name "*" -type f -exec install -Dm644 {} "$pkgdir/usr/share/themes/{}" \;
}
