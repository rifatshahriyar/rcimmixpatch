Reference Counting Immix (RC Immix)

rcimmix.patch can be applied over the revision 11219 of Jikes RVM 

hg clone -r 11219 http://hg.code.sourceforge.net/p/jikesrvm/code jikesrvm
cd jikesrvm
cat rcimmix.patch | patch -p1
