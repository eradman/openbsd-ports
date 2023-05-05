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

LIB_DEPENDS = databases/postgresql
BUILD_DEPENDS = databases/postgresql,-server devel/gmake
RUN_DEPENDS = databases/postgresql,-server

USE_GMAKE = Yes

.include <bsd.port.mk>
