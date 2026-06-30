# Maintainer: ChemistMikeLam <43129403+ChemistMikeLam@users.noreply.github.com>

# Common metadata part
pkgbase=local-aur-meta
_pkg_date=20260630
_pkg_ver_of_day=1
pkgver="${_pkg_date}.${_pkg_ver_of_day}"
pkgrel=1
pkgdesc='Meta-package for make and check deps of locally built packages'
url='https://github.com/ChemistMikeLam/local-aur-meta'
license=('0BSD')
arch=('any')

# List of packages
pkgname=(
    'local-aur-meta-elan-lean'
    'local-aur-meta-ibus-mozc-ut'
    'local-aur-meta-miktex'
    'local-aur-meta-xdg-desktop-portal-termfilechooser-hunkyburrito-git'
    'local-aur-meta-xdg-terminal-exec'
)

# Each package's metadata

# Template:
# pacakge_<name>() {
#     pkgdesc='Meta-package for make and check deps of <name>'
#     url='<URL for repo of the PKGBUILD'
#     depends=(<name of the package> <list of make deps> <list of check deps>)
# }

package_local-aur-meta-elan-lean() {
    pkgdesc='Meta-package for make deps of elan-lean'
    url='https://aur.archlinux.org/packages/elan-lean'
    depends=(
        'elan-lean'

        # Make deps
        'cargo'
    )
}

package_local-aur-meta-ibus-mozc-ut() {
    pkgdesc='Meta-package for make deps of ibus-mozc-ut'
    url='https://github.com/ChemistMikeLam/ibus-mozc-ut'
    depends=(
        'ibus-mozc-ut'

        # Make deps
        'git'
        'python'
    )
}

package_local-aur-meta-miktex() {
    pkgdesc='Meta-package for make deps of miktex'
    url='https://aur.archlinux.org/packages/miktex'
    depends=(
        'miktex'

        # Make deps
        'cmake'
        'coreutils'
        'fop'
        'sed'
        'libxslt'
        'qt6-tools'
        'boost'
    )
}

package_local-aur-meta-xdg-desktop-portal-termfilechooser-hunkyburrito-git() {
    pkgdesc='Meta-pacakge for make deps of xdg-desktop-portal-termfilechooser-hunkyburrito-git'
    url='https://aur.archlinux.org/packages/xdg-desktop-portal-termfilechooser-hunkyburrito-git'
    depends=(
        'xdg-desktop-portal-termfilechooser-hunkyburrito-git'

        # Make deps
        'meson'
        'scdoc'
        'git'
    )
}

package_local-aur-meta-xdg-terminal-exec() {
    pkgdesc='Meta-package for make and check deps of xdg-terminal-exec'
    url='https://aur.archlinux.org/packages/xdg-terminal-exec'
    depends=(
        'xdg-terminal-exec'

        # Make deps
        'scdoc'

        # Check deps
        'bats'
    )
}

