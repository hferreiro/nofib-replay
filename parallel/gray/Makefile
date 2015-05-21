# -----------------------------------------------------------------------------
#
# (c) 2009 The University of Glasgow
#
# This file is part of the GHC build system.
#
# To understand how the build system works and how to modify it, see
#      http://hackage.haskell.org/trac/ghc/wiki/Building/Architecture
#      http://hackage.haskell.org/trac/ghc/wiki/Building/Modifying
#
# -----------------------------------------------------------------------------

TOP = ../..
include $(TOP)/mk/boilerplate.mk

HS_SRCS = Geometry.hs Construct.hs Misc.hs Interval.hs Intersections.hs CSG.hs Surface.hs Illumination.hs Primitives.hs Data.hs Parse.hs Eval.hs Main.hs RayTrace.hs
SRC_HC_OPTS += -package parallel -package parsec -fexcess-precision

include $(TOP)/mk/target.mk
