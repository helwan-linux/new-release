pkgname=hel-release
pkgver=1.0
pkgrel=4
pkgdesc="Helwan Linux 5.0 Meta Package"
arch=('any')
url="https://github.com/helwan-linux/new-release"
provides=('hel-release')
replaces=('hel-release')
conflicts=('hel-release')

depends=(
    # helwan-packages
	hpm
	momo
	welcome_lts
	hel-ai-gate
	helfetch
	hel-store
	hel-terminal
	hel-process
	helufw
	hel-web-server
	hel-sync
	#hel-stream
	hel-bootfix
	hel-builder

	#other-helwan-packages##
	hel-tutorial
	hel-markdown
	hel-usb-writer
	hel-sec-audit
	hel-text-editor
	hel-diagram
	hel-netfix
	hel-iso-signer

	#helwan-Games##
	hel-blocks
	#hel-mycar
	hel-space-fight
	hel-solitaire
	hel-cmd-runner
	hel-maze
	hel-senet
	hel-mines
	hel-prism
	hel-snake
	hel-pong
	hel-memory
	hel-2048

	
	#Flash
	udisks2
	gvfs
	gvfs-mtp
	mtpfs
	android-tools
	ntfs-3g
	exfatprogs
	libmtp
	android-udev

	#BackGround
	

	)

package() {
    mkdir -p "$pkgdir/usr/share/helwan"
    echo "Helwan Linux 5.0" > "$pkgdir/usr/share/helwan/version"
}
