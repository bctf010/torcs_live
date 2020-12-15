##############################################################################
#
#    file                 : Makefile
#    created              : 2020年 09月 01日 星期二 22:32:46 CST
#    copyright            : (C) 2002 bctf
#
##############################################################################
#
#   This program is free software; you can redistribute it and/or modify
#   it under the terms of the GNU General Public License as published by
#   the Free Software Foundation; either version 2 of the License, or
#   (at your option) any later version.
#
##############################################################################

ROBOT       = Team1
MODULE      = ${ROBOT}.so
MODULEDIR   = drivers/${ROBOT}
SOURCES     = ${ROBOT}.cpp spline.cpp trackdesc.cpp pathfinder.cpp mycar.cpp

SHIPDIR     = drivers/${ROBOT}
SHIP        = ${ROBOT}.xml car3-trb1.rgb logo.rgb
SHIPSUBDIRS = 

PKGSUBDIRS  = ${SHIPSUBDIRS}
src-robots-Team1_PKGFILES = $(shell find * -maxdepth 0 -type f -print)
src-robots-Team1_PKGDIR   = ${PACKAGE}-${VERSION}/$(subst ${TORCS_BASE},,$(shell pwd))

include ${MAKE_DEFAULT}
