pkgname=2gis-ivanovo
pkgver=14
pkgrel=1
pkgdesc="Map of Ivanovo for 2GIS, June 2013"
arch=('i686' 'x86_64')
url="http://ivanovo.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.5.1')
source=("http://download.2gis.ru/arhives/2GISData_Ivanovo-14.orig.zip")
md5sums=('bdf672ea3c5f78d0ec0cf9c10c52e7dc')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Ivanovo.dgdat" "${pkgdir}/opt/2gis/ivanovo.dgdat" || return 1
  
}
