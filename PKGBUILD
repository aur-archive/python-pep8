# Maintainer: Your Name <youremail@domain.com>
_pkgname=pep8
pkgname=python-pep8
pkgver=1.3.3
pkgrel=3
pkgdesc="Python style guide checker."
arch=('any')
url="http://pypi.python.org/pypi/${_pkgname}/$pkgver"
license=('MIT')
groups=()
depends=('python' 'python-distribute')
makedepends=()
provides=()
conflicts=('pep8')
replaces=()
backup=()
options=(!emptydirs)
install=
source=("http://pypi.python.org/packages/source/p/${_pkgname}/${_pkgname}-$pkgver.tar.gz")
md5sums=('093a99ced0cc3b58c01549d7350f5a73')

package() {
  cd "$srcdir/${_pkgname}-$pkgver"
  python setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et:
