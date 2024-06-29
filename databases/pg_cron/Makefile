COMMENT = Run periodic jobs in PostgreSQL

V = 1.6.2
TAG = v${V}
DISTNAME = pg_cron-${V}

CATEGORIES = databases
HOMEPAGE = https://github.com/citusdata/pg_cron

# BSD
PERMIT_PACKAGE = Yes

DISTFILES  =	${TAG}.tar.gz
GH_ACCOUNT =	citusdata
GH_PROJECT =	pg_cron
GH_TAGNAME =	${TAG}

WANTLIB += c m pq

LIB_DEPENDS = databases/postgresql
RUN_DEPENDS = postgresql-server->=16,<17:databases/postgresql,-server
BUILD_DEPENDS = ${RUN_DEPENDS} devel/gmake

USE_GMAKE = Yes
CONFIGURE_STYLE = None

.include <bsd.port.mk>
