# $OpenBSD: $

COMMENT =	configure systems using labeled scripts

V =	1.1
DISTNAME =	rset-${V}

CATEGORIES =	sysutils

HOMEPAGE =	http://scriptedconfiguration.org/

MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE = Yes

WANTLIB +=	c

RUN_DEPENDS = www/darkhttpd
TEST_DEPENDS = lang/ruby/2.6

MASTER_SITES =	http://scriptedconfiguration.org/code/ \
		https://github.com/eradman/rset/archive/${V}/

MAKE_FILE =	Makefile.bsd
MAKE_FLAGS =	CC="${CC}" LDFLAGS="${LDFLAGS}"
FAKE_FLAGS =	DESTDIR=""

TEST_ENV =	PATH="/usr/local/sbin:${PATH}"
TEST_TARGET =	test

.include <bsd.port.mk>
