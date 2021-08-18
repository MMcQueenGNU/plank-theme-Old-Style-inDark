# Maintainer: McQueen <clear3239@yahoo.com>
_pkgname=Old-Style-inDark-Extend
_pkgname2=Old-Style-inDark-Slim
_pkgname3=Old-Style-inDark
pkgname=plank-theme-old-style-indark
pkgver=1.0.1
pkgrel=1
pkgdesc='Collections of Old-Style-InDark Plank Themes'
arch=(any)
url='https://www.pling.com/p/1345008/'
_url="https://github.com/MMcQueenGNU"
license=('CC-BY-SA')
source=("$_url/$pkgname/archive/refs/tags/v$pkgver.tar.gz")

sha256sums=('10edf5e360457fbc7ecf1d250974f4bbfb8b00c6d7e64e52ace802d010333f17')

build() {
	true
}

package() {
	cd $srcdir/$pkgname
	mkdir -p $pkgdir/usr/share/plank/themes/$_pkgname
	mkdir -p $pkgdir/usr/share/plank/themes/$_pkgname2
	mkdir -p $pkgdir/usr/share/plank/themes/$_pkgname3
	install -m 755 dock.theme $pkgdir/$_pkgname/usr/share/plank/themes/$_pkgname/
	install -m 755 dock.theme $pkgdir/$_pkgname2/usr/share/plank/themes/$_pkgname2/
	install -m 755 dock.theme $pkgdir/$_pkgname3/usr/share/plank/themes/$_pkgname3/
}

