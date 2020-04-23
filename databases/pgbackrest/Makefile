# $OpenBSD: $

COMMENT =	reliable postgresql backup & restore

V =		2.26
DISTNAME =	pgbackrest-${V}

CATEGORIES =	databases
HOMEPAGE =	https://pgbackrest.org/
MAINTAINER =	Eric Radman <ericshane@eradman.com>

# MIT
PERMIT_PACKAGE =	Yes

DISTFILES =	${V}.tar.gz
MASTER_SITES =	https://github.com/pgbackrest/pgbackrest/archive/release/

WRKDIST =	${WRKDIR}/pgbackrest-release-${V}
WRKSRC =	${WRKDIST}/src

CONFIGURE_STYLE =  gnu
CONFIGURE_ENV = LDFLAGS="-L/usr/local/lib" LIBS="-L/usr/local/lib"
ALL_TARGET =

WANTLIB += c crypto m perl pq ssl xml2 z

RUN_DEPENDS =		postgresql-server->=11<13:databases/postgresql,-server
BUILD_DEPENDS =		${RUN_DEPENDS} postgresql-client->=11,<13:databases/postgresql,-main \
			devel/gmake

USE_GMAKE = Yes

.include <bsd.port.mk>
