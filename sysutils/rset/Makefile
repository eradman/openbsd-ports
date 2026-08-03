# $OpenBSD: $

COMMENT =	configure systems using labeled scripts

V =	3.4
DISTNAME =	rset-${V}

CATEGORIES =	sysutils

HOMEPAGE =	http://scriptedconfiguration.org/

MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE = Yes

WANTLIB +=	c

SITES =	http://scriptedconfiguration.org/code/ \
		https://github.com/eradman/rset/archive/${V}/

CONFIGURE_STYLE =	simple

FAKE_FLAGS =	DESTDIR=''
TEST_FLAGS =	RUBY=${RUBY}

.include <bsd.port.mk>
