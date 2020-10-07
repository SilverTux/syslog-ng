parserincludedir			= ${pkgincludedir}/parser

EXTRA_DIST += lib/parser/CMakeLists.txt

parserinclude_HEADERS = 			\
	lib/parser/parser-expr.h		\
	lib/parser/parser-expr-parser.h         \
	lib/parser/parser-re.h

parser_sources = 				\
	lib/parser/parser-expr.c		\
	lib/parser/parser-expr-parser.c	\
	lib/parser/parser-expr-grammar.y        \
	lib/parser/parser-re.c

BUILT_SOURCES += 				\
	lib/parser/parser-expr-grammar.y	\
	lib/parser/parser-expr-grammar.c	\
	lib/parser/parser-expr-grammar.h

EXTRA_DIST += lib/parser/parser-expr-grammar.ym
