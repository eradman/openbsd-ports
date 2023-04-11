# $OpenBSD: $

COMMENT =	extension for automating failover

V =		2.0
DISTNAME =	pg_auto_failover-${V}

CATEGORIES =	databases
HOMEPAGE =	https://github.com/citusdata/pg_auto_failover
MAINTAINER =	Eric Radman <ericshane@eradman.com>

# PostgreSQL
PERMIT_PACKAGE =	Yes

DISTFILES =	v${V}.tar.gz
MASTER_SITES =	https://github.com/citusdata/pg_auto_failover/archive/

WRKDIST =	${WRKDIR}/pg_auto_failover-${V}

WANTLIB += c crypto curses m pq readline ssl xml2 z

RUN_DEPENDS =	postgresql-server->=14<16:databases/postgresql,-server
BUILD_DEPENDS =	${RUN_DEPENDS} postgresql-client->=14,<16:databases/postgresql,-main \
		devel/gmake

USE_GMAKE = Yes

.include <bsd.port.mk>
