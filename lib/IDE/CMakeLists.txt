add_swift_library(swiftIDE STATIC
  CodeCompletion.cpp
  CodeCompletionCache.cpp
  CommentConversion.cpp
  Formatting.cpp
  ModuleInterfacePrinting.cpp
  TypeReconstruction.cpp
  REPLCodeCompletion.cpp
  SwiftSourceDocInfo.cpp
  SyntaxModel.cpp
  Utils.cpp
  LINK_LIBS
    swiftFrontend
    swiftClangImporter
    swiftParse
    swiftSema
    swiftAST)

