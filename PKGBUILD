# Maintainer: Ner0

pkgname=cinnamon-applet-informative-sound
pkgver=1.0
pkgrel=1
pkgdesc="A modified version of the original Cinnamon sound applet."
arch=('any')
url="http://cinnamon-spices.linuxmint.com/applets/view/50"
license=('GPL')
groups=('cinnamon-applets')
depends=('cinnamon')
source=("http://cinnamon-spices.linuxmint.com/uploads/applets/QJB8-2HT1-T71S.zip")
md5sums=('8ae72f634024f2d69b82083ec88262ac')

package() {
  find sound\@mikerofone/ -type f -exec install -Dm644 '{}' "$pkgdir/usr/share/cinnamon/applets/{}" \;
}
