# $OpenBSD: $

COMMENT =	configure systems using labeled scripts

V =	1.8
DISTNAME =	rset-${V}

CATEGORIES =	sysutils

HOMEPAGE =	http://scriptedconfiguration.org/

MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE = Yes

WANTLIB +=	c

TEST_DEPENDS = lang/ruby/2.7

MASTER_SITES =	http://scriptedconfiguration.org/code/ \
		https://gitlab.com/eradman/rset/-/archive/${V}/

MAKE_FILE =	Makefile.bsd
MAKE_FLAGS =	CC="${CC}" LDFLAGS="${LDFLAGS}"
FAKE_FLAGS =	DESTDIR=""

TEST_ENV =	PATH="/usr/local/sbin:${PATH}"
TEST_TARGET =	test

.include <bsd.port.mk>
