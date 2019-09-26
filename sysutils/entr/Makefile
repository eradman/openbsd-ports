# $OpenBSD: $

COMMENT =	run arbitrary commands when files change

V =	4.3
DISTNAME =	entr-${V}

CATEGORIES =	sysutils

HOMEPAGE =	http://eradman.com/entrproject/

MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE_CDROM = Yes

WANTLIB += c

MASTER_SITES =	http://eradman.com/entrproject/code/ \
		https://github.com/eradman/entr/archive/${V}/

MAKE_FILE =	Makefile.bsd
MAKE_FLAGS =	CC="${CC}" LDFLAGS="${LDFLAGS}"
FAKE_FLAGS =	DESTDIR=""

TEST_TARGET =	test

.include <bsd.port.mk>
