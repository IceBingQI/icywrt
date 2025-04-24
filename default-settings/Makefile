# SPDX-License-Identifier: GPL-2.0-only
#
# Copyright (C) 2021 Lean <coolsnowwolf@gmail.com>
# Copyright (C) 2021-2024 ImmortalWrt.org

include $(TOPDIR)/rules.mk

PKG_NAME:=default-settings
PKG_RELEASE:=29

PKG_LICENSE:=GPL-2.0-only

include $(INCLUDE_DIR)/package.mk

define Package/default-settings
  SECTION:=luci
  CATEGORY:=LuCI
  TITLE:=LuCI support for Default Settings
  DEPENDS:=+luci
  PKGARCH:=all
endef

define Package/default-settings-chn
  $(Package/default-settings)
  TITLE+= (Optimize for CHN users)
  DEPENDS:=+default-settings +@LUCI_LANG_zh_Hans +luci-i18n-base-zh-cn
endef

define Package/default-settings-chn-bingqi
  $(Package/default-settings)
  TITLE+= (Optimize for CHN users)
  DEPENDS:=+default-settings-chn \
          +kmod-usb-acm +kmod-usb-net \
          +kmod-usb-net-aqc111 \
          +kmod-usb-net-asix \
          +kmod-usb-net-asix-ax88179 \
          +kmod-usb-net-cdc-eem \
          +kmod-usb-net-cdc-ether \
          +kmod-usb-net-cdc-mbim \
          +kmod-usb-net-cdc-ncm \
          +kmod-usb-net-cdc-subset \
          +kmod-usb-net-hso \
          +kmod-usb-net-huawei-cdc-ncm \
          +kmod-usb-net-ipheth \
          +kmod-usb-net-kalmia \
          +kmod-usb-net-rndis \
          +kmod-usb-ohci \
          +kmod-usb-serial \
          +kmod-usb-serial-option \
          +kmod-usb-serial-qualcomm \
          +kmod-usb-storage \
          +kmod-usb-storage-extras \
          +kmod-usb-storage-uas \
          +kmod-usb-uhci +kmod-usb-wdm \
          +kmod-usb2 +kmod-usb3 \
          +kmod-tun +kmod-inet-diag \
          +kmod-ipt-ipset +kmod-netlink-diag \
          +kmod-ip6tables +kmod-ip6tables-extra \
          +kmod-ipt-conntrack +kmod-ipt-conntrack-extra \
          +kmod-nft-arp +kmod-nft-bridge +kmod-nft-compat \
          +kmod-nft-queue +kmod-nft-socket +kmod-nft-tproxy \
          +kmod-fs-btrfs +kmod-fs-exfat +kmod-fs-ext4 \
          +kmod-fs-ntfs3 +kmod-fs-vfat +kmod-fuse \
          +cfdisk +lsblk +fdisk +coremark \
          +pciids +pciutils +usb-modeswitch +usbids +usbutils \
          +luci-app-arpbind +luci-app-cpulimit +luci-app-diskman \
          +luci-app-disks-info +luci-app-eqos +luci-app-hd-idle \
          +luci-app-nlbwmon +luci-app-samba4 \
          +luci-app-sqm +luci-app-ttyd +luci-app-upnp \
          +luci-app-usb-printer +luci-app-vsftpd +luci-app-wol \
          +luci-app-argon-config +luci-theme-argon \
          +automount +autosamba +adb +unzip +shadow-useradd +shadow-userdel
endef

define Package/default-settings-chn-bingqi-normal
  $(Package/default-settings)
  TITLE+= (Optimize for CHN users)
  DEPENDS:=+default-settings-chn \
          +kmod-usb-acm +kmod-usb-net \
          +kmod-usb-net-aqc111 \
          +kmod-usb-net-asix \
          +kmod-usb-net-asix-ax88179 \
          +kmod-usb-net-cdc-eem \
          +kmod-usb-net-cdc-ether \
          +kmod-usb-net-cdc-mbim \
          +kmod-usb-net-cdc-ncm \
          +kmod-usb-net-cdc-subset \
          +kmod-usb-net-hso \
          +kmod-usb-net-huawei-cdc-ncm \
          +kmod-usb-net-ipheth \
          +kmod-usb-net-kalmia \
          +kmod-usb-net-rndis \
          +kmod-usb-ohci \
          +kmod-usb-serial \
          +kmod-usb-serial-option \
          +kmod-usb-serial-qualcomm \
          +kmod-usb-storage \
          +kmod-usb-storage-extras \
          +kmod-usb-storage-uas \
          +kmod-usb-uhci +kmod-usb-wdm \
          +kmod-usb2 +kmod-usb3 \
          +kmod-tun +kmod-inet-diag \
          +kmod-ipt-ipset +kmod-netlink-diag \
          +kmod-ip6tables +kmod-ip6tables-extra \
          +kmod-ipt-conntrack +kmod-ipt-conntrack-extra \
          +kmod-nft-arp +kmod-nft-bridge +kmod-nft-compat \
          +kmod-nft-queue +kmod-nft-socket +kmod-nft-tproxy \
          +kmod-fs-btrfs +kmod-fs-exfat +kmod-fs-ext4 \
          +kmod-fs-ntfs3 +kmod-fs-vfat +kmod-fuse \
          +cfdisk +lsblk +fdisk +coremark \
          +pciids +pciutils +usb-modeswitch +usbids +usbutils \
          +automount +autosamba +adb +unzip +shadow-useradd +shadow-userdel
endef

define Package/default-settings-chn-bingqi-wifi
  $(Package/default-settings)
  TITLE+= (Optimize for CHN users)
  DEPENDS:=+default-settings-chn-bingqi
endef

define Package/default-settings-chn-bingqi-wifi-d2
  $(Package/default-settings)
  TITLE+= (Optimize for CHN users)
  DEPENDS:=+default-settings-chn-bingqi
endef

define Package/default-settings-chn-bingqi-wifi-hiwifi
  $(Package/default-settings)
  TITLE+= (Optimize for CHN users)
  DEPENDS:=+default-settings-chn-bingqi
endef

define Package/default-settings-chn-bingqi-wifi-jdc
  $(Package/default-settings)
  TITLE+= (Optimize for CHN users)
  DEPENDS:=+default-settings-chn-bingqi
endef

define Package/default-settings-chn-bingqi-wifi-r3g
  $(Package/default-settings)
  TITLE+= (Optimize for CHN users)
  DEPENDS:=+default-settings-chn-bingqi
endef

define Package/default-settings-chn-bingqi-wifi-k2-d
  $(Package/default-settings)
  TITLE+= (Optimize for CHN users)
  DEPENDS:=+default-settings-chn
endef

define Package/default-settings-chn-bingqi-wifi-hiwifi-go
  $(Package/default-settings)
  TITLE+= (Optimize for CHN users)
  DEPENDS:=+default-settings-chn-bingqi-normal
endef

define Build/Compile
endef

define Package/default-settings/install
	$(INSTALL_DIR) $(1)/etc/uci-defaults
	$(INSTALL_BIN) ./files/99-default-settings $(1)/etc/uci-defaults/
endef

define Package/default-settings-chn/install
	$(INSTALL_DIR) $(1)/etc/uci-defaults
	$(INSTALL_BIN) ./files/99-default-settings-chinese $(1)/etc/uci-defaults/
endef

define Package/default-settings-chn-bingqi/install
	$(INSTALL_DIR) $(1)/etc/uci-defaults
	$(INSTALL_BIN) ./files/99-default-settings-chinese-bingqi $(1)/etc/uci-defaults/
endef

define Package/default-settings-chn-bingqi-normal/install
	$(INSTALL_DIR) $(1)/etc/uci-defaults
	$(INSTALL_BIN) ./files/99-default-settings-chinese-bingqi $(1)/etc/uci-defaults/
endef

define Package/default-settings-chn-bingqi-wifi/install
	$(INSTALL_DIR) $(1)/etc/uci-defaults
	$(INSTALL_BIN) ./files/99-default-settings-chinese-bingqi-wifi $(1)/etc/uci-defaults/
endef

define Package/default-settings-chn-bingqi-wifi-d2/install
	$(INSTALL_DIR) $(1)/etc/uci-defaults
	$(INSTALL_BIN) ./files/99-default-settings-chinese-bingqi-wifi-d2 $(1)/etc/uci-defaults/
endef

define Package/default-settings-chn-bingqi-wifi-hiwifi/install
	$(INSTALL_DIR) $(1)/etc/uci-defaults
	$(INSTALL_BIN) ./files/99-default-settings-chinese-bingqi-wifi-hiwifi $(1)/etc/uci-defaults/
endef

define Package/default-settings-chn-bingqi-wifi-jdc/install
	$(INSTALL_DIR) $(1)/etc/uci-defaults
	$(INSTALL_BIN) ./files/99-default-settings-chinese-bingqi-wifi-jdc $(1)/etc/uci-defaults/
endef

define Package/default-settings-chn-bingqi-wifi-r3g/install
	$(INSTALL_DIR) $(1)/etc/uci-defaults
	$(INSTALL_BIN) ./files/99-default-settings-chinese-bingqi-wifi-r3g $(1)/etc/uci-defaults/
endef

define Package/default-settings-chn-bingqi-wifi-k2-d/install
	$(INSTALL_DIR) $(1)/etc/uci-defaults
	$(INSTALL_BIN) ./files/99-default-settings-chinese-bingqi-wifi-k2-d $(1)/etc/uci-defaults/
endef

define Package/default-settings-chn-bingqi-wifi-hiwifi-go/install
	$(INSTALL_DIR) $(1)/etc/uci-defaults
	$(INSTALL_BIN) ./files/99-default-settings-chinese-bingqi-wifi-hiwifi-go $(1)/etc/uci-defaults/
endef

$(eval $(call BuildPackage,default-settings))
$(eval $(call BuildPackage,default-settings-chn))
$(eval $(call BuildPackage,default-settings-chn-bingqi))
$(eval $(call BuildPackage,default-settings-chn-bingqi-normal))
$(eval $(call BuildPackage,default-settings-chn-bingqi-wifi))
$(eval $(call BuildPackage,default-settings-chn-bingqi-wifi-d2))
$(eval $(call BuildPackage,default-settings-chn-bingqi-wifi-hiwifi))
$(eval $(call BuildPackage,default-settings-chn-bingqi-wifi-jdc))
$(eval $(call BuildPackage,default-settings-chn-bingqi-wifi-r3g))
$(eval $(call BuildPackage,default-settings-chn-bingqi-wifi-k2-d))
$(eval $(call BuildPackage,default-settings-chn-bingqi-wifi-hiwifi-go))

