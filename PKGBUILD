pkgname=darkcold
pkgver=5.0
pkgrel=1
pkgdesc="GTK+ dark theme"
arch=('any')
url="https://github.com/originalseed/darkcold"
license=('GPL')
source=("DarkCold.tar.gz")
sha256sums=('SKIP')

package() {
  install -d -m755 $pkgdir/usr/share/themes

  cd $srcdir
  mv DarkCold $pkgdir/usr/share/themes/
  
  find $pkgdir/usr -type f -name '.directory' -delete
}
