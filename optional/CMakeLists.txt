#
# boost::optional
#

install(FILES
	"none.hpp" "none_t.hpp" "optional.hpp"
	DESTINATION ${INSTALL_DESTINATION}/optional
	)

install(DIRECTORY "optional"
	DESTINATION ${INSTALL_DESTINATION}/optional
    FILES_MATCHING PATTERN "*.hpp"
    )
