##############################################################################
## Makefile.am -- Process this file with automake to produce Makefile.in
## Revision: $Id: Makefile.am 608 2015-08-10 20:06:55Z kulshres $
##
## Copyright (C) Andrea Walther, Andreas Kowarz
##
## This file is part of ADOL-C. This software is provided as open source.
## Any use, reproduction, or distribution of the software constitutes 
## recipient's acceptance of the terms of the accompanying license file.
## 
##############################################################################

MAINTAINERCLEANFILES = Makefile.in *~

if ADDEXA
SUBDIRS              = clock hessmat lufact ode sparse tapesave timing \
                       detexam helm lighthouse scal speelpenning taylor pow \
                       checkpointing ext_diff_func fixpoint_exam openmp_exam \
                       cuda param lie
endif

if PAREXA
SUBDIRS              = clock hessmat lufact ode sparse tapesave timing \
                       detexam helm lighthouse scal speelpenning taylor pow \
                       checkpointing ext_diff_func fixpoint_exam openmp_exam \
                       cuda param lie
endif
