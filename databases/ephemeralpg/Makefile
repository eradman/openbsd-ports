# $OpenBSD: $

COMMENT =	quickly spin up a temporary PostgreSQL test database

DISTNAME =	ephemeralpg-2.6
REV =		a64dcc8705fc

CATEGORIES =	databases
HOMEPAGE =	http://eradman.com/ephemeralpg/
MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE_CDROM =	Yes

MASTER_SITES =	http://eradman.com/ephemeralpg/code/ \
		https://bitbucket.org/eradman/ephemeralpg/get/

WRKDIST =	${WRKDIR}/eradman-ephemeralpg-${REV}
FAKE_FLAGS =	DESTDIR=""

TEST_TARGET =	selftest

.include <bsd.port.mk>
