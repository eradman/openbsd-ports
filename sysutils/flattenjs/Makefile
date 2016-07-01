# $OpenBSD: $

COMMENT =	print json in an line-oriented format

DISTNAME =	flattenjs-1.0
REV =		b28ad1c1d6d6

CATEGORIES =	sysutils
HOMEPAGE =	https://bitbucket.org/eradman/flattenjs
MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE_CDROM =	Yes

MASTER_SITES =	https://bitbucket.org/eradman/flattenjs/get/

WRKDIST =	${WRKDIR}/eradman-flattenjs-${REV}
FAKE_FLAGS =	DESTDIR=""

RUN_DEPENDS =	lang/node

TEST_TARGET =	test

.include <bsd.port.mk>
