PKG_NAME = pv
PKG_VERS = 1.6.20
PKG_EXT = tar.bz2
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://www.ivarch.com/programs/sources
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS =

HOMEPAGE = http://www.ivarch.com/programs/pv.shtml
COMMENT  = pv - Pipe Viewer - is a terminal-based tool for monitoring the progress of data through a pipeline.
LICENSE  = Artistic License 2.0

GNU_CONFIGURE = 1
CONFIGURE_ARGS = --disable-nls --prefix=$(INSTALL_DIR)/$(INSTALL_PREFIX)

INSTALL_MAKE_OPTIONS = install PREFIX=$(STAGING_INSTALL_PREFIX)

include ../../mk/spksrc.cross-cc.mk
