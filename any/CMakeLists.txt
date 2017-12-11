#
# boost::any
#

file(GLOB BOOST_ANY_HEADERS
		"any.hpp")

install(FILES ${BOOST_ANY_HEADERS}
	DESTINATION ${INSTALL_DESTINATION}/any
	)
