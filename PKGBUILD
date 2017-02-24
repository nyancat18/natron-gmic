# Maintainer: Det <nimetonmaili g-mail>
# Contributors: Achilleas Pipinellis, speed145a, Schnouki

pkgname=openfx-gmic-bin
pkgver=1.01
pkgrel=2
pkgdesc="GMIC OpenFX plugins for Natron"
arch=('x86_64')
url="https://github.com/triceratops1/natron-gmic"
license=('GPL2')
depends=('gmic' 'natron' 'ffmpeg')
optdepends=('natron-plugins: Extra plugins for Natron')
source=("https://github.com/NatronVFX/openfx-gmic/releases/download/1.0beta1/GMIC.ofx.bundle-1.0beta1-Linux-64-release.tgz"
)
sha256sums=('1293ce4382a3b872c2c33ceed24b370cc73ad8f350ac66af32585cc9c595aca7')
sha384sums=('d39c8d61a9392d085898af82f25740ff06cc6009794a1459aa78c3a6f7b28ebb9ff26ba569b4b4b2640a6caad672ae49')
sha512sums=('e719eddeab8d16a5140621b86d9dd042c16ea0fedc296619f9e3ae6b10668195da223e97fb8497b50a8f095e8a75a4e1f6f8a27d1c01fffddf3a39677cf1229b')

package() {
  # Create directories
  msg2 "Creating directory structure..."
  mkdir -p "$pkgdir"/usr/OFX/Plugins/
 
  cp -r "$srcdir"/GMIC.ofx.bundle "$pkgdir"/usr/OFX/Plugins/

  
}
