# Maintainer: VHSgunzo <vhsgunzo.github.io>
pkgname='reshade-shaders-lw'
pkgver='0.1'
pkgrel='1'
pkgdesc='Reshade shaders for Lux Wine'
arch=('any')
url='https://github.com/VHSgunzo/reshade-shaders-lw'
license=('MIT')
provides=("$pkgname" "reshade-shaders-git")
conflicts=(${provides[@]})
source=("reshade.tar.xz::https://raw.githubusercontent.com/VHSgunzo/reshade-shaders-lw/main/reshade.tar.xz")
sha256sums=('SKIP')

package() {
    cp -ar --no-preserve=ownership "$srcdir/opt" "$pkgdir/opt"
}
