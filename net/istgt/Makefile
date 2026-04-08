# $OpenBSD: $

COMMENT =	iSCSI target for Linux and BSD

VERSON =	20150713
DISTNAME =	istgt-${VERSON}
CATEGORIES =	net
HOMEPAGE =	http://shell.peach.ne.jp/aoyama/
SITES =	http://www.peach.ne.jp/archives/istgt/

# BSD
PERMIT_PACKAGE=	Yes

CONFIGURE_ARGS =	--sysconfdir=${PREFIX}/share/examples/istgt
CONFIGURE_STYLE =	simple

NO_TEST =	Yes

.include <bsd.port.mk>
