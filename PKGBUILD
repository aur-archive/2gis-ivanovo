pkgname=2gis-ivanovo
pkgver=7
pkgrel=1
pkgdesc="Map of Ivanovo for 2GIS, November 2012"
arch=('i686' 'x86_64')
url="http://ivanovo.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.9.0.1')
source=("http://download.2gis.ru/arhives/2GISData_Ivanovo-7.orig.zip")
md5sums=('b9bcd067ec2cdb1f19a10f6d03947eb0')

build() {
  cd $startdir
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Ivanovo.dgdat "${startdir}/pkg/opt/2gis/ivanovo.dgdat" || return 1
  
}
