ADD_EXECUTABLE ( rpc_test
  main.cpp
  )

TARGET_LINK_LIBRARIES ( rpc_test
  rpc
  ${ZLIB_LIBRARY}
  )
