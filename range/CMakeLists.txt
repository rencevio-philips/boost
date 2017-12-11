#
# boost::range
#

install(FILES
	"range.hpp"
	DESTINATION ${INSTALL_DESTINATION}/range
	)

install(DIRECTORY "range"
	DESTINATION ${INSTALL_DESTINATION}/range
    FILES_MATCHING PATTERN "*.hpp"
    )
