#
# $FreeBSD$
#
# Build the FreeBSD Handbook (Traditional Chinese).
#

.PATH: ${.CURDIR}/../../share/xml/glossary

MAINTAINER=	doc@FreeBSD.org

DOC?= book

FORMATS?= html-split

INSTALL_COMPRESSED?= gz
INSTALL_ONLY_COMPRESSED?=

# English images
# as these are translated, move them from IMAGES_EN to IMAGES
IMAGES_EN = advanced-networking/isdn-bus.eps
IMAGES_EN+= advanced-networking/isdn-twisted-pair.eps
IMAGES_EN+= advanced-networking/natd.eps
IMAGES_EN+= advanced-networking/net-routing.pic
IMAGES_EN+= advanced-networking/pxe-nfs.png
IMAGES_EN+= advanced-networking/static-routes.pic
IMAGES_EN+= basics/disk-layout.eps
IMAGES_EN+= basics/example-dir1.eps
IMAGES_EN+= basics/example-dir2.eps
IMAGES_EN+= basics/example-dir3.eps
IMAGES_EN+= basics/example-dir4.eps
IMAGES_EN+= basics/example-dir5.eps
IMAGES_EN+= bsdinstall/bsdinstall-adduser1.png
IMAGES_EN+= bsdinstall/bsdinstall-adduser2.png
IMAGES_EN+= bsdinstall/bsdinstall-adduser3.png
IMAGES_EN+= bsdinstall/bsdinstall-boot-loader-menu.png
IMAGES_EN+= bsdinstall/bsdinstall-boot-options-menu.png
IMAGES_EN+= bsdinstall/bsdinstall-newboot-loader-menu.png
IMAGES_EN+= bsdinstall/bsdinstall-choose-mode.png
IMAGES_EN+= bsdinstall/bsdinstall-config-components.png
IMAGES_EN+= bsdinstall/bsdinstall-config-hostname.png
IMAGES_EN+= bsdinstall/bsdinstall-config-keymap.png
IMAGES_EN+= bsdinstall/bsdinstall-config-services.png
IMAGES_EN+= bsdinstall/bsdinstall-config-crashdump.png
IMAGES_EN+= bsdinstall/bsdinstall-configure-network-interface-ipv4-dhcp.png
IMAGES_EN+= bsdinstall/bsdinstall-configure-network-interface-ipv4.png
IMAGES_EN+= bsdinstall/bsdinstall-configure-network-interface-ipv4-static.png
IMAGES_EN+= bsdinstall/bsdinstall-configure-network-interface-ipv6.png
IMAGES_EN+= bsdinstall/bsdinstall-configure-network-interface-ipv6-static.png
IMAGES_EN+= bsdinstall/bsdinstall-configure-network-interface-slaac.png
IMAGES_EN+= bsdinstall/bsdinstall-configure-network-interface.png
IMAGES_EN+= bsdinstall/bsdinstall-configure-network-ipv4-dns.png
IMAGES_EN+= bsdinstall/bsdinstall-configure-wireless-accesspoints.png
IMAGES_EN+= bsdinstall/bsdinstall-configure-wireless-scan.png
IMAGES_EN+= bsdinstall/bsdinstall-configure-wireless-wpa2setup.png
IMAGES_EN+= bsdinstall/bsdinstall-distfile-extracting.png
IMAGES_EN+= bsdinstall/bsdinstall-distfile-fetching.png
IMAGES_EN+= bsdinstall/bsdinstall-distfile-verifying.png
IMAGES_EN+= bsdinstall/bsdinstall-final-confirmation.png
IMAGES_EN+= bsdinstall/bsdinstall-finalconfiguration.png
IMAGES_EN+= bsdinstall/bsdinstall-final-modification-shell.png
IMAGES_EN+= bsdinstall/bsdinstall-keymap-10.png
IMAGES_EN+= bsdinstall/bsdinstall-keymap-select-default.png
IMAGES_EN+= bsdinstall/bsdinstall-mainexit.png
IMAGES_EN+= bsdinstall/bsdinstall-netinstall-files.png
IMAGES_EN+= bsdinstall/bsdinstall-netinstall-mirrorselect.png
IMAGES_EN+= bsdinstall/bsdinstall-part-entire-part.png
IMAGES_EN+= bsdinstall/bsdinstall-part-guided-disk.png
IMAGES_EN+= bsdinstall/bsdinstall-part-guided-manual.png
IMAGES_EN+= bsdinstall/bsdinstall-part-manual-addpart.png
IMAGES_EN+= bsdinstall/bsdinstall-part-manual-create.png
IMAGES_EN+= bsdinstall/bsdinstall-part-manual-partscheme.png
IMAGES_EN+= bsdinstall/bsdinstall-part-review.png
IMAGES_EN+= bsdinstall/bsdinstall-post-root-passwd.png
IMAGES_EN+= bsdinstall/bsdinstall-set-clock-local-utc.png
IMAGES_EN+= bsdinstall/bsdinstall-timezone-confirm.png
IMAGES_EN+= bsdinstall/bsdinstall-timezone-country.png
IMAGES_EN+= bsdinstall/bsdinstall-timezone-region.png
IMAGES_EN+= bsdinstall/bsdinstall-timezone-zone.png
IMAGES_EN+= bsdinstall/bsdinstall-zfs-disk_info.png
IMAGES_EN+= bsdinstall/bsdinstall-zfs-disk_select.png
IMAGES_EN+= bsdinstall/bsdinstall-zfs-geli_password.png
IMAGES_EN+= bsdinstall/bsdinstall-zfs-menu.png
IMAGES_EN+= bsdinstall/bsdinstall-zfs-partmenu.png
IMAGES_EN+= bsdinstall/bsdinstall-zfs-vdev_invalid.png
IMAGES_EN+= bsdinstall/bsdinstall-zfs-vdev_type.png
IMAGES_EN+= bsdinstall/bsdinstall-zfs-warning.png
IMAGES_EN+= geom/striping.pic
IMAGES_EN+= mail/mutt1.scr
IMAGES_EN+= mail/mutt2.scr
IMAGES_EN+= mail/mutt3.scr
IMAGES_EN+= mail/pine1.scr
IMAGES_EN+= mail/pine2.scr
IMAGES_EN+= mail/pine3.scr
IMAGES_EN+= mail/pine4.scr
IMAGES_EN+= mail/pine5.scr
IMAGES_EN+= security/ipsec-network.pic
IMAGES_EN+= security/ipsec-crypt-pkt.pic
IMAGES_EN+= security/ipsec-encap-pkt.pic
IMAGES_EN+= security/ipsec-out-pkt.pic
IMAGES_EN+= virtualization/parallels-freebsd1.png
IMAGES_EN+= virtualization/parallels-freebsd2.png
IMAGES_EN+= virtualization/parallels-freebsd3.png
IMAGES_EN+= virtualization/parallels-freebsd4.png
IMAGES_EN+= virtualization/parallels-freebsd5.png
IMAGES_EN+= virtualization/parallels-freebsd6.png
IMAGES_EN+= virtualization/parallels-freebsd7.png
IMAGES_EN+= virtualization/parallels-freebsd8.png
IMAGES_EN+= virtualization/parallels-freebsd9.png
IMAGES_EN+= virtualization/parallels-freebsd10.png
IMAGES_EN+= virtualization/parallels-freebsd11.png
IMAGES_EN+= virtualization/parallels-freebsd12.png
IMAGES_EN+= virtualization/parallels-freebsd13.png
IMAGES_EN+= virtualization/virtualpc-freebsd1.png
IMAGES_EN+= virtualization/virtualpc-freebsd2.png
IMAGES_EN+= virtualization/virtualpc-freebsd3.png
IMAGES_EN+= virtualization/virtualpc-freebsd4.png
IMAGES_EN+= virtualization/virtualpc-freebsd5.png
IMAGES_EN+= virtualization/virtualpc-freebsd6.png
IMAGES_EN+= virtualization/virtualpc-freebsd7.png
IMAGES_EN+= virtualization/virtualpc-freebsd8.png
IMAGES_EN+= virtualization/virtualpc-freebsd9.png
IMAGES_EN+= virtualization/virtualpc-freebsd10.png
IMAGES_EN+= virtualization/virtualpc-freebsd11.png
IMAGES_EN+= virtualization/virtualpc-freebsd12.png
IMAGES_EN+= virtualization/virtualpc-freebsd13.png
IMAGES_EN+= virtualization/vmware-freebsd01.png
IMAGES_EN+= virtualization/vmware-freebsd02.png
IMAGES_EN+= virtualization/vmware-freebsd03.png
IMAGES_EN+= virtualization/vmware-freebsd04.png
IMAGES_EN+= virtualization/vmware-freebsd05.png
IMAGES_EN+= virtualization/vmware-freebsd06.png
IMAGES_EN+= virtualization/vmware-freebsd07.png
IMAGES_EN+= virtualization/vmware-freebsd08.png
IMAGES_EN+= virtualization/vmware-freebsd09.png
IMAGES_EN+= virtualization/vmware-freebsd10.png
IMAGES_EN+= virtualization/vmware-freebsd11.png
IMAGES_EN+= virtualization/vmware-freebsd12.png

# Images from the cross-document image library
IMAGES_LIB=  callouts/1.png
IMAGES_LIB+= callouts/2.png
IMAGES_LIB+= callouts/3.png
IMAGES_LIB+= callouts/4.png
IMAGES_LIB+= callouts/5.png
IMAGES_LIB+= callouts/6.png
IMAGES_LIB+= callouts/7.png
IMAGES_LIB+= callouts/8.png
IMAGES_LIB+= callouts/9.png
IMAGES_LIB+= callouts/10.png
IMAGES_LIB+= callouts/11.png
IMAGES_LIB+= callouts/12.png
IMAGES_LIB+= callouts/13.png
IMAGES_LIB+= callouts/14.png
IMAGES_LIB+= callouts/15.png

# XML content
SRCS= book.xml

SYMLINKS=	${DESTDIR} index.html handbook.html

URL_RELPREFIX?=	../../../..
DOC_PREFIX?=	${.CURDIR}/../../..

# Fixme!
DOCBOOK_DEPS_DISABLE=YES

.include "${DOC_PREFIX}/share/mk/doc.project.mk"
