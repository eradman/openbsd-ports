# $OpenBSD: $

COMMENT =	pipe file listing to an external utility and print delta

DISTNAME =	treedelta-1.0
REV =		ab187adb60d3

CATEGORIES =	sysutils

HOMEPAGE =	http://entrproject.org/

MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE_CDROM = Yes

WANTLIB +=	c

MODULES =	lang/ruby

MASTER_SITES =	http://entrproject.org/code/ \
		https://bitbucket.org/eradman/treedelta/get/

WRKDIST =	${WRKDIR}/eradman-treedelta-${REV}
FAKE_FLAGS =	DESTDIR=""

TEST_TARGET =	test

.include <bsd.port.mk>
