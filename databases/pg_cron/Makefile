COMMENT = Run periodic jobs in PostgreSQL

V = 1.6.4
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
BUILD_DEPENDS = databases/postgresql,-server devel/gmake
RUN_DEPENDS = databases/postgresql,-server

USE_GMAKE = Yes
CONFIGURE_STYLE = None

.include <bsd.port.mk>
