# Copyright 2017 Dirk Brenken (dev@brenken.org)
# This is free software, licensed under the Apache License, Version 2.0

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI support for Adblock
LUCI_DEPENDS:=+adblock +luci-lib-jsonc +wget
LUCI_PKGARCH:=all

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
