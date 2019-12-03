COMMENT =		extension and service for automated failover
GH_ACCOUNT =		citusdata
GH_PROJECT =		pg_auto_failover
GH_TAGNAME =		v1.0.5

CATEGORIES =		databases

# PostgreSQL
PERMIT_PACKAGE =	Yes

WANTLIB =		c crypto pq ssl

LIB_DEPENDS =		databases/postgresql
BUILD_DEPENDS =		databases/postgresql,-server
RUN_DEPENDS =		databases/postgresql,-server

USE_GMAKE =		Yes

.include <bsd.port.mk>
