##===- unittests/Expr/Makefile -----------------------------*- Makefile -*-===##

LEVEL := ../..
include $(LEVEL)/Makefile.config

TESTNAME := RefTest
USEDLIBS := kleaverExpr.a kleeBasic.a
LINK_COMPONENTS := support

include $(LLVM_SRC_ROOT)/unittests/Makefile.unittest

LIBS += $(STP_LDFLAGS)
