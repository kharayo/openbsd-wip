# $OpenBSD$

COMMENT =	fast XS implementation of MaxMind DB reader

DISTNAME =	MaxMind-DB-Reader-XS-1.000005

CATEGORIES =	net

MAINTAINER =	Frederic Cambus <fcambus@openbsd.org>

# Artistic 2.0
PERMIT_PACKAGE_CDROM =	Yes

WANTLIB +=	c maxminddb perl

MODULES =	cpan

LIB_DEPENDS =	net/libmaxminddb

RUN_DEPENDS =	devel/p5-Moo \
		devel/p5-namespace-autoclean \
		math/p5-Math-Int128 \
		net/p5-MaxMind-DB-Common>=0.040001 \
		net/p5-MaxMind-DB-Reader

TEST_DEPENDS =	devel/p5-Module-Implementation \
		devel/p5-Path-Class>=0.27 \
		devel/p5-Test-Fatal \
		devel/p5-Test-Number-Delta \
		devel/p5-Test-Requires \
		net/p5-MaxMind-DB-Common \
		net/p5-Net-Works>=0.21

CONFIGURE_STYLE = modbuild

CPAN_AUTHOR =	MAXMIND

.include <bsd.port.mk>
