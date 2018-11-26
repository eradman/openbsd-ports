# $OpenBSD: $

COMMENT =	run arbitrary commands when files change

DISTNAME =	entr-4.1
REV =		f4e2cbe57708

CATEGORIES =	sysutils

HOMEPAGE =	http://eradman.com/entrproject/

MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE_CDROM = Yes

WANTLIB += c

MASTER_SITES =	http://eradman.com/entrproject/code/ \
		https://bitbucket.org/eradman/entr/get/

MAKE_FILE =	Makefile.bsd
MAKE_FLAGS =	CC="${CC}" LDFLAGS="${LDFLAGS}"
WRKDIST =	${WRKDIR}/eradman-entr-${REV}
FAKE_FLAGS =	DESTDIR=""

TEST_TARGET =	test

.include <bsd.port.mk>
