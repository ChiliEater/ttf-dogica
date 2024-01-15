pkgname=ttf-dogica
pkgver=1.012
pkgrel=1
pkgdesc="Bitmap font by Roberto Mocci"
arch=("any")
url="https://www.dafont.com/dogica.font"
license=('custom:SIL Open Font License v1.1')
source=("${pkgname}-${pkgver}.zip::https://dl.dafont.com/dl/?f=dogica")
sha512sums=("d429ad5084d92a09f0068f6939ed5518cbff826ca4948fb1e5c05be306fc07e493de2b3f50a4418e31df510fe37ba837d3a138406e1d647027a256c01e97c450")

package() {
    install -dm 755 "${pkgdir}/usr/share/fonts/TTF"
    
    install -m 644 "TTF/dogica.ttf" "${pkgdir}/usr/share/fonts/TTF/Dogica.ttf"
    install -m 644 "TTF/dogicabold.ttf" "${pkgdir}/usr/share/fonts/TTF/Dogica-Bold.ttf"
    install -m 644 "TTF/dogicapixel.ttf" "${pkgdir}/usr/share/fonts/TTF/Dogica-Pixel.ttf"
    install -m 644 "TTF/dogicapixelbold.ttf" "${pkgdir}/usr/share/fonts/TTF/Dogica-Pixel-Bold.ttf"
    
    install -Dm644 "dogica_license.txt" "${pkgdir}/usr/share/licenses/$pkgname/LICENSE"
}