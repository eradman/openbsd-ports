# $OpenBSD: $

COMMENT =	quickly spin up a temporary Postgres test database

DISTNAME =	ephemeralpg-1.3
REV =		00b058281e95

CATEGORIES =	databases
HOMEPAGE =	https://bitbucket.org/eradman/ephemeralpg
MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE_CDROM =	Yes

MASTER_SITES =	https://bitbucket.org/eradman/ephemeralpg/get/

WRKDIST =	${WRKDIR}/eradman-ephemeralpg-${REV}
FAKE_FLAGS =	DESTDIR=""

NO_TEST =	Yes

.include <bsd.port.mk>
