COMMENT =  tweak PostgreSQL execution plans using hints

V = 15-1.5
DISTNAME = pg_hint_plan${V}

CATEGORIES = databases
HOMEPAGE = https://pghintplan.osdn.jp/pg_hint_plan.html

# BSD
PERMIT_PACKAGE =Yes

DISTFILES = REL15_1_5_0.tar.gz
MASTER_SITES = https://github.com/ossc-db/pg_hint_plan/archive/refs/tags/

WANTLIB += c m pq

LIB_DEPENDS = databases/postgresql
BUILD_DEPENDS = databases/postgresql,-server
RUN_DEPENDS = databases/postgresql,-server

USE_GMAKE = Yes
CONFIGURE_STYLE = None

WRKSRC = ${WRKDIR}/pg_hint_plan-REL15_1_5_0

.include <bsd.port.mk>
