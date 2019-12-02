# $OpenBSD: $

COMMENT =	reliable postgresql backup & restore

V =		2.19
DISTNAME =	pgbackrest-${V}

CATEGORIES =	databases
HOMEPAGE =	https://pgbackrest.org/
MAINTAINER =	Eric Radman <ericshane@eradman.com>

# MIT
PERMIT_PACKAGE =	Yes

DISTFILES =	${V}.tar.gz
MASTER_SITES =	https://github.com/pgbackrest/pgbackrest/archive/release/

CONFIGURE_STYLE =  gnu
ALL_TARGET =

WANTLIB += c crypto m perl pq ssl xml2 z

WRKDIST =	${WRKDIR}/pgbackrest-release-${V}
WRKSRC =	${WRKDIST}/src

RUN_DEPENDS =		postgresql-server->=11<13:databases/postgresql,-server
BUILD_DEPENDS =		${RUN_DEPENDS} postgresql-client->=11,<13:databases/postgresql,-main

.include <bsd.port.mk>