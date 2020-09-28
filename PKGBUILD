    
# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Your Name <youremail@domain.com>
pkgname=alterlinux-hook-osname
pkgver=1.0.0
pkgrel=1
pkgdesc="alterlinux-hook-osname"
prepare() {
}

build() {
}

check() {
}

package() {
        mkdir -p "${pkgdir}/etc/pacman.d/hooks/"
        cp -f os-release "${pkgdir}/etc/alter-os-release"
        cp -f 99_os_release_hook.hook "${pkgdir}/etc/pacman.d/hooks/"

}
