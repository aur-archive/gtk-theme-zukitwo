# Contributor: grimi <grimi at poczta dot fm>
# Maintainer: grimi <grimi at poczta dot fm>

pkgname=gtk-theme-zukitwo
pkgver=20121201
pkgrel=1
pkgdesc="Theme for gtk3, gtk2, metacity, xfwm4, gnome-shell and unity..."
arch=('any')
url="http://gnome-look.org/content/show.php/Zukitwo?content=140562"
license=('GPL')
depends=('gtk-engines' 'gtk-engine-murrine')
provides=('zukitwo-themes')
conflicts=('zukitwo-themes')
source=("${pkgname}-${pkgver}.zip::http://gnome-look.org/CONTENT/content-files/140562-Zukitwo.zip")
md5sums=('412ef3165d4083afbec71c5dec830ca0')


package() {
  find Zukitwo*/ -type f \
      -exec install -Dm644 "{}" "$pkgdir/usr/share/themes/{}" \;
}

# vim:set ts=2 sw=2 et:
