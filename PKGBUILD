
pkgname='plymouth-theme-jijicat'
pkgver=1.0
pkgrel=1
pkgdesc='Plymouth theme of a cute cat somewhat like Jiji from the Miyazaki film'
arch=('any')
url='https://github.com/Cynthetika/plymouth-theme-jijicat'
license=('GPL3')
depends=('plymouth')
source=("https://github.com/Cynthetika/plymouth-theme-jijicat/releases/download/$pkgver/$pkgname.tar.gz")
md5sums=('d8772b5662638e880acf219e5ebd14d6')

package() {
  cd "$srcdir/jijicat"
  mkdir -p "$pkgdir/usr/share/plymouth/themes/jijicat"
  install -Dm644 * "$pkgdir/usr/share/plymouth/themes/jijicat"
}

# vim:set ts=2 sw=2 et:
