#
# boost::variant
#

install(FILES
	"variant.hpp"
	DESTINATION ${INSTALL_DESTINATION}/variant
	)

install(DIRECTORY "variant"
	DESTINATION ${INSTALL_DESTINATION}/variant
    FILES_MATCHING PATTERN "*.hpp"
    )
