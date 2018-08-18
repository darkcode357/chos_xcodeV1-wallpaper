pkgname=chos_xcodeV1-wallpaper
pkgver=1.0
pkgrel=1
pkgdesc='Wallpapers for chos GNU/Linux'
arch=(any)
license=(GPL)
url="https://github.com/darkcode357/chos_xcodeV1-wallpaper"
source=("git+$url.git")
sha256sums=('SKIP')

package() {
    install -d ${pkgdir}/usr/share/backgrounds/chos
    install -m644 chos_xcodeV1-wallpaper/backgrounds/chos/* 
"${pkgdir}/usr/share/backgrounds/namib"
}
