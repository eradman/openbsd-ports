# $OpenBSD: $

COMMENT =	improved screen locker based on slock
DISTNAME =	i3lock-2.6
CATEGORIES =	x11

HOMEPAGE =	http://i3wm.org/i3lock/

MAINTAINER =	Eric Radman <ericshane@eradman.com>

EXTRACT_SUFX =	.tar.bz2

# BSD3
PERMIT_PACKAGE_CDROM =	Yes

BUILD_DEPENDS =	devel/gmake

LIB_DEPENDS =	graphics/png graphics/cairo x11/xcb x11/xkbcommon

MASTER_SITES =	${HOMEPAGE}

USE_GMAKE =	Yes
MAKE_FLAGS =	CC="${CC}"
FAKE_FLAGS =	DESTDIR=""

NO_TEST =	Yes

.include <bsd.port.mk>
