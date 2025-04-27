include $(TOPDIR)/rules.mk

PKG_NAME:=sunxi-tools
PKG_VERSION:=1.4.2
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/sunxi-tools
  SECTION:=utils
  CATEGORY:=Utilities
  TITLE:=Allwinner sunxi tools
  URL:=https://github.com/linux-sunxi/sunxi-tools
  DEPENDS:=+libusb-1.0 +zlib +libfdt
endef

define Package/sunxi-tools/description
  Tools for working with Allwinner sunxi platforms, including FEX scripts,
  NAND partitioning, and more.
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
	$(CP) ./src/* $(PKG_BUILD_DIR)/
endef

define Build/Compile
	$(MAKE) -C $(PKG_BUILD_DIR) \
		CC="$(TARGET_CC)" \
		CFLAGS="$(TARGET_CFLAGS)" \
		LDFLAGS="$(TARGET_LDFLAGS)" \
		PREFIX=/usr \
		DESTDIR=$(PKG_INSTALL_DIR) \
		tools install
endef

define Package/sunxi-tools/install
	$(INSTALL_DIR) $(1)/usr/bin
	$(INSTALL_BIN) $(PKG_INSTALL_DIR)/usr/bin/* $(1)/usr/bin/
endef

$(eval $(call BuildPackage,sunxi-tools))