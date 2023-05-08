COMMENT = tweak PostgreSQL execution plans using hints

V = 1.5
TAG = REL15_1_5_0
DISTNAME = pg_hint_plan-${V}

CATEGORIES = databases
HOMEPAGE = https://pghintplan.osdn.jp/pg_hint_plan.html

# BSD
PERMIT_PACKAGE = Yes

DISTFILES = ${TAG}.tar.gz
MASTER_SITES = https://github.com/ossc-db/pg_hint_plan/archive/refs/tags/

WANTLIB += c m pq

LIB_DEPENDS = databases/postgresql
RUN_DEPENDS = postgresql-server->=15,<16:databases/postgresql,-server
BUILD_DEPENDS = ${RUN_DEPENDS} devel/gmake

USE_GMAKE = Yes
CONFIGURE_STYLE = None

WRKSRC = ${WRKDIR}/pg_hint_plan-${TAG}

.include <bsd.port.mk>
