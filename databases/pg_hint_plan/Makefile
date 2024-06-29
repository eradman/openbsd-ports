COMMENT = tweak PostgreSQL execution plans using hints

V = 1.5
TAG = REL16_1_6_0
DISTNAME = pg_hint_plan-${V}

CATEGORIES = databases
HOMEPAGE = https://pghintplan.osdn.jp/pg_hint_plan.html

# BSD
PERMIT_PACKAGE = Yes

DISTFILES  =	${TAG}.tar.gz
GH_ACCOUNT =	ossc-db
GH_PROJECT =	pg_hint_plan
GH_TAGNAME =	${TAG}

WANTLIB += c m pq

LIB_DEPENDS = databases/postgresql
RUN_DEPENDS = postgresql-server->=16,<17:databases/postgresql,-server
BUILD_DEPENDS = ${RUN_DEPENDS} devel/gmake

USE_GMAKE = Yes
CONFIGURE_STYLE = None

WRKSRC = ${WRKDIR}/pg_hint_plan-${TAG}

.include <bsd.port.mk>
