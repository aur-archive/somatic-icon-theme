# Maintainer: Edoardo Maria Elidoro <edoardo.elidoro@gmail.com>
# Contributor: Will Smith (Factory, rpj8) <iliketoast@gmail.com>

pkgname=somatic-icon-theme
_pkgname=Somatic
pkgver=0.2
pkgrel=3
pkgdesc="The Somatic icons have been used with permission from David Lanham - http://www.dlanham.com"
arch=(any)
url="http://www.gnome-look.org/content/show.php/Somatic?content=64638"
license=('Free for Personal Use')
source=(http://pkgbuild.com/~barthalion/arch/aur/ICON-${_pkgname}-$pkgver.tar.xz)
md5sums=('da5012063be34801675728693a92d3e5')

package() {
  install -d "$pkgdir"/usr/share/icons/
  cp -r "$srcdir"/${_pkgname}-$pkgver "$pkgdir"/usr/share/icons/
  chmod 644 "$pkgdir"/usr/share/icons/${_pkgname}-$pkgver/index.theme
}
