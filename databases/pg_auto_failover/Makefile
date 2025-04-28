COMMENT =	extension for automating failover

V =		2.2
DISTNAME =	pg_auto_failover-${V}

CATEGORIES =	databases
GH_ACCOUNT =	hapostgres
GH_PROJECT =	pg_auto_failover
GH_TAGNAME =	v${V}
MAINTAINER =	Eric Radman <ericshane@eradman.com>

# PostgreSQL
PERMIT_PACKAGE =	Yes

WRKDIST =	${WRKDIR}/pg_auto_failover-${V}

WANTLIB += c crypto curses m pq readline ssl xml2 z

LIB_DEPENDS = databases/postgresql
BUILD_DEPENDS = databases/postgresql,-server devel/gmake
RUN_DEPENDS = databases/postgresql,-server

USE_GMAKE = Yes

.include <bsd.port.mk>
