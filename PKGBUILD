pkgname='ecm2bc'
licence=('GPL')
pkgver=1.0
pkgrel=1
arch=("x86_64")
pkgdesc="A tool that converts ecm and ape files into a bin/cue pair (designed for PS1 games)"
install="$pkgname.install"
depends=('ecm-tools' 'ffmpeg')

build() {
    git clone https://github.com/SamuelLira99/ecm2bc.git
}

package() {
    cd "$pkgname"
    sed -i 's/ecm-uncompress/ecm2bin/' ecm2bc
    chmod +x ecm2bc
    sudo mv ecm2bc /usr/local/bin
}
