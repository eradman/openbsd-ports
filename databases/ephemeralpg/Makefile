# $OpenBSD: $

COMMENT =	quickly spin up a temporary PostgreSQL test database

V =	2.8
DISTNAME =	ephemeralpg-${V}

CATEGORIES =	databases
HOMEPAGE =	http://eradman.com/ephemeralpg/
MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE =	Yes

MASTER_SITES =	http://eradman.com/ephemeralpg/code/ \
		https://github.com/eradman/ephemeralpg/archive/${V}/

FAKE_FLAGS =	DESTDIR=""

TEST_TARGET =	selftest

.include <bsd.port.mk>
