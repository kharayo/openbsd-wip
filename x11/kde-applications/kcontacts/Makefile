# $OpenBSD$

COMMENT =	address book API for KDE
DISTNAME =	kcontacts-${VERSION}
CATEGORIES =	devel mail

KDE5 =		Yes

SHARED_LIBS +=  KF5Contacts               0.0 # 5.5

WANTLIB += ${COMPILER_LIBCXX} KF5Codecs KF5ConfigCore KF5CoreAddons
WANTLIB += KF5I18n Qt5Core Qt5DBus Qt5Gui m

BUILD_DEPENDS +=devel/gettext-tools

LIB_DEPENDS =	devel/kf5/kcodecs \
		devel/kf5/kconfig \
		devel/kf5/ki18n \
		devel/kf5/kcoreaddons

.include <bsd.port.mk>
