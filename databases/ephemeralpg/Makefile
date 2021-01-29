# $OpenBSD: $

COMMENT =	quickly spin up a temporary PostgreSQL test database

V =	3.1
DISTNAME =	ephemeralpg-${V}

CATEGORIES =	databases
HOMEPAGE =	http://eradman.com/ephemeralpg/
MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE =	Yes

MASTER_SITES =	http://eradman.com/ephemeralpg/code/ \
		https://github.com/eradman/ephemeralpg/archive/${V}/

TEST_DEPENDS =	databases/postgresql,-server

MAKE_FLAGS =	CC="${CC}" LDFLAGS="${LDFLAGS}"
FAKE_FLAGS =	DESTDIR=""

TEST_TARGET =	selftest

.include <bsd.port.mk>
