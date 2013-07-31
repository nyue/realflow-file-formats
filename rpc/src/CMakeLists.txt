ADD_LIBRARY ( rpc
  FileReader.cpp
  RPCReader.cpp
  )

INSTALL ( TARGETS
  rpc
  DESTINATION
  lib
  )

INSTALL ( FILES
  FileReader.h
  RPCReader.h
  DESTINATION
  include
  )
