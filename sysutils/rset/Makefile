# $OpenBSD: $

COMMENT =	configure systems using labeled scripts

DISTNAME =	rset-0.3
REV =		bca13846695d

CATEGORIES =	sysutils

HOMEPAGE =	http://scriptedconfiguration.org/

MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE_CDROM = Yes

WANTLIB +=	c l
LDFLAGS +=	'-ll'

RUN_DEPENDS = www/darkhttpd
TEST_DEPENDS = lang/ruby/2.5

MASTER_SITES =	http://scriptedconfiguration.org/code/ \
		https://bitbucket.org/eradman/rset/get/

MAKE_FILE =	Makefile.bsd
MAKE_FLAGS =	CC="${CC}" LDFLAGS="${LDFLAGS}"
WRKDIST =	${WRKDIR}/eradman-rset-${REV}
FAKE_FLAGS =	DESTDIR=""

TEST_TARGET =	test

.include <bsd.port.mk>
