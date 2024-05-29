include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-pikpak-webdav
PKG_VERSION:=1.0.0
PKG_RELEASE:=1
PKG_PO_VERSION:=$(PKG_VERSION)-$(PKG_RELEASE)

PKG_LICENSE:=MIT
PKG_MAINTAINER:=ykj363963169 <yenkj@github.com>

LUCI_TITLE:=LuCI Support for pikpak-webdav
LUCI_PKGARCH:=all
LUCI_DEPENDS:=+pikpak-webdav

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
