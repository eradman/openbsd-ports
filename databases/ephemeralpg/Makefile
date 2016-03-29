# $OpenBSD: $

COMMENT =	quickly spin up a temporary PostgreSQL test database

DISTNAME =	ephemeralpg-2.0
REV =		c197ab286e00

CATEGORIES =	databases
HOMEPAGE =	https://bitbucket.org/eradman/ephemeralpg
MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE_CDROM =	Yes

MASTER_SITES =	https://bitbucket.org/eradman/ephemeralpg/get/

WRKDIST =	${WRKDIR}/eradman-ephemeralpg-${REV}
FAKE_FLAGS =	DESTDIR=""

TEST_TARGET =	selftest

.include <bsd.port.mk>
