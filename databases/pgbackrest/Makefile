# $OpenBSD: $

COMMENT =	reliable postgresql backup & restore

V =		2.38
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
ALL_TARGET =

WANTLIB += bz2 c crypto lz4 ssl z zstd

LIB_DEPENDS = archivers/bzip2 \
		  archivers/lz4 \
		archivers/zstd

RUN_DEPENDS =		postgresql-server->=12<14:databases/postgresql,-server
BUILD_DEPENDS =		${RUN_DEPENDS} postgresql-client->=13,<15:databases/postgresql,-main \
			devel/gmake

USE_GMAKE = Yes

.include <bsd.port.mk>
