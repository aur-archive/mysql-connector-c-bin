# Maintainer: Javier Fuentes Muñoz <jfuentes@zenlabs.cl>

pkgname=mysql-connector-c-bin
pkgver=6.0.2
pkgrel=2
pkgdesc="MYSQL C Connector, compiled from mysql"
arch=('x86_64')
replace=('mysql-connector-c')
url="http://www.mysql.com/"
license=('GPL')

source=("http://cdn.mysql.com/Downloads/Connector-C/mysql-connector-c-$pkgver-linux-glibc2.3-x86-64bit.tar.gz")

md5sums=('6a177fbff664a1badc884a2916ebf3c8')

package(){
  mv $srcdir/mysql-connector-c-$pkgver-linux-glibc2.3-x86-64bit/ $pkgdir/usr/
}