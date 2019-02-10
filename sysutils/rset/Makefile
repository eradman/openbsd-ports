# $OpenBSD: $

COMMENT =	configure systems using labeled scripts

DISTNAME =	rset-1.0
REV =	ac19d68ca846

CATEGORIES =	sysutils

HOMEPAGE =	http://scriptedconfiguration.org/

MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE_CDROM = Yes

WANTLIB +=	c

RUN_DEPENDS = www/darkhttpd
TEST_DEPENDS = lang/ruby/2.5

MASTER_SITES =	http://scriptedconfiguration.org/code/ \
		https://bitbucket.org/eradman/rset/get/

MAKE_FILE =	Makefile.bsd
MAKE_FLAGS =	CC="${CC}" LDFLAGS="${LDFLAGS}"
WRKDIST =	${WRKDIR}/eradman-rset-${REV}
FAKE_FLAGS =	DESTDIR=""

TEST_ENV =	PATH="/usr/local/sbin:${PATH}"
TEST_TARGET =	test

.include <bsd.port.mk>
