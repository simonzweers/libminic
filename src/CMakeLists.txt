list (
	APPEND SOURCES
	"llist.c"
)

add_library(
	minic STATIC
	${SOURCES}
)

