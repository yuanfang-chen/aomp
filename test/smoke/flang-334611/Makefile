include ../../Makefile.defs

TESTNAME     = flang-334611
TESTSRC_MAIN = flang-334611.f90
TESTSRC_AUX  =
TESTSRC_ALL  = $(TESTSRC_MAIN) $(TESTSRC_AUX)

FLANG        = flang
OMP_BIN      = $(AOMP)/bin/$(FLANG)
CC           = $(OMP_BIN) $(VERBOSE)

include ../Makefile.rules
