# ============================================================================
# Name        : Makefile
# Author      : autarch princeps
# Version     :
# Copyright   : 
# Description : Makefile for Hello MPI World in Fortran
# ============================================================================

.PHONY: all clean

all: src/PI_MPI.f90
	mpif90 -O3 -g -o bin/PI_MPI \
		src/PI_MPI.f90

clean:
	rm -f bin/PI_MPI *.mod
