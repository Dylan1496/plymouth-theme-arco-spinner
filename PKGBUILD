#Maintainer: Dylan Delgado <dylan1496 at live dot com>

pkgname=plymouth-theme-spinner-arco
pkgver=1.0
pkgrel=1
pkgdesc="A simple plymouth theme based on the spinner theme, with the ArcoLinux logo"
arch=('any')
url="https://github.com/Dylan1496/plymouth-theme-spinner-arco"
license=('GPL')
depends=('plymouth')

install='plymouth-theme-spinner-arco.install'
source=('plymouth-theme-spinner-arco-src.tar.gz::https://github.com/Dylan1496/plymouth-theme-spinner-arco/releases/download/1.0/plymouth-theme-spinner-arco-src.tar.gz'
'plymouth-theme-spinner-arco.install')
md5sums=('27fce6fc6244b4edc011bb4a7b8303ce'
'4ef099e297100813ad97b5cc0a8b021e')

package() {
    cd $srcdir/spinner-arco
    mkdir -p $pkgdir/usr/share/plymouth/themes/spinner-arco
    install -Dm644 * "${pkgdir}"/usr/share/plymouth/themes/spinner-arco
}