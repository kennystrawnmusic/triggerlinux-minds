pkgname=jak-social-minds
pkgver=1.0
pkgrel=1
pkgdesc="Minds"
arch=('x86_64')
url="https://minds.com"
license=('GPL')
depends=('jade-application-kit-git')
source=("https://github.com/realKennyStrawn93/triggerbox-minds")

package() {
  cd $srcdir
  mkdir -p $pkgdir/usr/bin
  mkdir -p $pkgdir/usr/share/applications
  cp $srcdir/minds.desktop $pkgdir/usr/share/applications
  cp $srcdir/minds $pkgdir/usr/bin
  cp $srcdir/minds-wrapper $pkgdir/usr/bin
}
