pkgname=triggerlinux-minds
pkgver=1.1
pkgrel=1
pkgdesc="Minds"
arch=('x86_64')
url="https://minds.com"
license=('GPL')
depends=('jade-application-kit-git')
source=("git+https://github.com/realKennyStrawn93/triggerlinux-minds#branch=master")

package() {
  cd $srcdir
  mkdir -p $pkgdir/usr/bin
  mkdir -p $pkgdir/usr/share/applications
  mkdir -p $pkgdir/usr/share/icons/breeze/apps/scalable
  wget -O $pkgdir/usr/share/icons/breeze/apps/scalable/minds.svg https://cdn-assets.minds.com/front/dist/en/assets/logos/bulb.svg
  cp $srcdir/$pkgname/minds.desktop $pkgdir/usr/share/applications
  cp $srcdir/$pkgname/minds $pkgdir/usr/bin
  cp $srcdir/$pkgname/minds-wrapper $pkgdir/usr/bin
}
