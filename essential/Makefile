all:
	mex -O fst_accumulate.c
	mex -O fst_addvec.c -lblas
	mex -O fst_dgemm.c -lblas
	mex -O fst_diagmul.c -lblas
	mex -O fst_dspamm.c -lblas
	mex -O fst_dspammt2.c -lblas
	mex -O fst_dspammt.c -lblas
	mex -O fst_dsymm.c -lblas
	mex -O fst_dsyrk.c -lblas
	mex -O fst_dtrmm.c -lblas
	mex -O fst_dtrsm.c -lblas
	mex -O fst_flipdims.c -lblas
	mex -O fst_getsparse.c -lblas
	mex -O fst_invchol.c -llapack
	mex -O fst_muldiag.c -lblas
	mex -O fst_permute.c -lblas
	mex -O fst_reshape.c -lblas
	mex -O fst_sumpos.c -lblas
	mex -O save_sparse.c -lblas

clean:
	rm -f *.o *.mexglx *~ \#*
