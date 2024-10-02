# $OpenBSD: $

COMMENT =	configure systems using labeled scripts

V =	3.1
DISTNAME =	rset-${V}

CATEGORIES =	sysutils

HOMEPAGE =	http://scriptedconfiguration.org/

MAINTAINER =	Eric Radman <ericshane@eradman.com>

# ISC
PERMIT_PACKAGE = Yes

WANTLIB +=	c

TEST_DEPENDS = lang/ruby/3.3

SITES =	http://scriptedconfiguration.org/code/ \
		https://github.com/eradman/rset/archive/${V}/

MODULES =	lang/ruby
MODRUBY_BUILDDEP =	No
MODRUBY_RUNDEP =	No

TEST_DEPENDS =	${MODRUBY_BUILD_DEPENDS} \
				www/ruby-webrick,${MODRUBY_FLAVOR}

CONFIGURE_STYLE =	simple

FAKE_FLAGS =	DESTDIR=''
TEST_FLAGS =	RUBY=${RUBY}

.include <bsd.port.mk>
