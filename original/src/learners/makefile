
all: vfbn1 vfbn2 \
     mostcommonclass vfdt c50wrapper c45wrapper naivebayes cvfdt kmeans vfkm \
          decisionstump vfem bnlearn

.PHONY : vfkm
vfkm:
	(cd vfkm ; ${MAKE})

.PHONY : bnlearn
bnlearn:
	(cd bnlearn ; ${MAKE})

.PHONY : vfbn1
vfbn1:
	(cd vfbn1 ; ${MAKE})

.PHONY : vfbn2
vfbn2:
	(cd vfbn2 ; ${MAKE})

.PHONY : vfem
vfem:
	(cd vfem ; ${MAKE})

.PHONY : kmeans
kmeans:
	(cd kmeans ; ${MAKE})

.PHONY : cvfdt
cvfdt:
	(cd cvfdt ; ${MAKE})

.PHONY : naivebayes
naivebayes:
	(cd naivebayes ; ${MAKE})

.PHONY : c45wrapper
c45wrapper:
	(cd c45wrapper ; ${MAKE})

.PHONY : c50wrapper
c50wrapper:
	(cd c50wrapper ; ${MAKE})

.PHONY : mostcommonclass
mostcommonclass:
	(cd mostcommonclass ; ${MAKE})

.PHONY : decisionstump
decisionstump:
	(cd decisionstump ; ${MAKE})

.PHONY : vfdt
vfdt:
	(cd vfdt ; ${MAKE})

.PHONY : clean
clean: 
	(cd naivebayes ; ${MAKE} clean)
	(cd c50wrapper ; ${MAKE} clean)
	(cd c45wrapper ; ${MAKE} clean)
	(cd mostcommonclass ; ${MAKE} clean)
	(cd decisionstump ; ${MAKE} clean)
	(cd vfdt ; ${MAKE} clean)
	(cd cvfdt ; ${MAKE} clean)
	(cd vfbn1 ; ${MAKE} clean)
	(cd vfbn2 ; ${MAKE} clean)
	(cd kmeans ; ${MAKE} clean)
	(cd vfkm ; ${MAKE} clean)
	(cd vfem ; ${MAKE} clean)

.PHONY : clobber
clobber: clean
	(cd naivebayes ; ${MAKE} clobber)
	(cd c50wrapper ; ${MAKE} clobber)
	(cd c45wrapper ; ${MAKE} clobber)
	(cd mostcommonclass ; ${MAKE} clobber)
	(cd decisionstump ; ${MAKE} clobber)
	(cd vfdt ; ${MAKE} clobber)
	(cd cvfdt ; ${MAKE} clobber)
	(cd vfbn1 ; ${MAKE} clobber)
	(cd vfbn2 ; ${MAKE} clobber)
	(cd kmeans ; ${MAKE} clobber)
	(cd vfkm ; ${MAKE} clobber)
	(cd vfem ; ${MAKE} clobber)
