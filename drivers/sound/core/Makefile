################################################################################
#
#   Copyright (c) 2017 Minoca Corp.
#
#    This file is licensed under the terms of the GNU General Public License
#    version 3. Alternative licensing terms are available. Contact
#    info@minocacorp.com for details. See the LICENSE file at the root of this
#    project for complete licensing information.
#
#   Module Name:
#
#       Sound Core
#
#   Abstract:
#
#       This module implements the sound core support library. It provides
#       generic support infrastructure for all sound drivers.
#
#   Author:
#
#       Chris Stevens 27-Apr-2017
#
#   Environment:
#
#       Kernel
#
################################################################################

BINARY = sound.drv

BINARYTYPE = driver

BINPLACE = bin

OBJS = sound.o     \

DYNLIBS = $(BINROOT)/kernel \

include $(SRCROOT)/os/minoca.mk

