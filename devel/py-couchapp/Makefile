# $OpenBSD$

COMMENT =	Standalone CouchDB Application Development Made Simple

MODPY_EGG_VERSION =	0.8.1
DISTNAME =		couchapp-${MODPY_EGG_VERSION}
PKGNAME =		py-${DISTNAME}

CATEGORIES =	devel

HOMEPAGE =	http://www.couchapp.org/

MAINTAINER =	Christian Rueger <cr+openbsd@rueger-net.de>

# Apache2
PERMIT_PACKAGE_CDROM =		Yes

WANTLIB =	${MODPY_WANTLIB}

MASTER_SITES =	https://github.com/couchapp/couchapp/downloads/

MODULES =	lang/python

NO_TEST =	Yes

WRKDIST =	${WRKDIR}/Couchapp-${MODPY_EGG_VERSION}/

.include <bsd.port.mk>
