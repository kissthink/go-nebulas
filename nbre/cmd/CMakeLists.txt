add_subdirectory(nasir)
add_subdirectory(nbre)

if(Release)
else()
add_subdirectory(blockgen)
add_subdirectory(rocksdb)
add_subdirectory(naxer)
add_subdirectory(dummy_neb)
add_subdirectory(jit)
add_subdirectory(hex)
add_subdirectory(graph)
add_subdirectory(nr)
add_subdirectory(trie)
add_subdirectory(dip)
add_subdirectory(math)
add_subdirectory(ff)
endif()
