# $OpenBSD: $

COMMENT =	quickly spin up a temporary PostgreSQL test database

V =	2.9
DISTNAME =	ephemeralpg-${V}

CATEGORIES =	databases
HOMEPAGE =	http://eradman.com/ephemeralpg/
MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE =	Yes

MASTER_SITES =	http://eradman.com/ephemeralpg/code/ \
		https://gitlab.com/eradman/ephemeralpg/-/archive/${V}/

TEST_DEPENDS =	databases/postgresql,-server

TEST_TARGET =	selftest

.include <bsd.port.mk>
