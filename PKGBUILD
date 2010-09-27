# Contributor: Douglas Thrift <douglas@douglasthrift.net>
pkgname=java-xalan
pkgver=2.7.1
pkgrel=1
pkgdesc="XSLT processor for transforming XML documents"
url="http://xml.apache.org/xalan-j/"
arch=("i686" "x86_64")
depends=('j2re' 'java-xerces2')
source=('http://www.apache.org/dist//xml/xalan-j/xalan-j_2_7_1-bin.zip')
md5sums=('99d049717c9d37a930450e630d8a6531')
license=('APACHE')
build() {
  mkdir -p $startdir/pkg/usr/share/java/xalan
  cd $startdir/src/xalan-j_2_7_1
  cp *.jar $startdir/pkg/usr/share/java/xalan
}
