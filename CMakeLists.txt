project ( xlsxwriter NONE )

cmake_minimum_required ( VERSION 2.8 )
include ( cmake/dist.cmake )
include ( lua )

install_lua_module ( xlsxwriter.app           xlsxwriter/app.lua           )
install_lua_module ( xlsxwriter.contenttypes  xlsxwriter/contenttypes.lua  )
install_lua_module ( xlsxwriter.core          xlsxwriter/core.lua          )
install_lua_module ( xlsxwriter.format        xlsxwriter/format.lua        )
install_lua_module ( xlsxwriter.packager      xlsxwriter/packager.lua      )
install_lua_module ( xlsxwriter.relationships xlsxwriter/relationships.lua )
install_lua_module ( xlsxwriter.sharedstrings xlsxwriter/sharedstrings.lua )
install_lua_module ( xlsxwriter.strict        xlsxwriter/strict.lua        )
install_lua_module ( xlsxwriter.styles        xlsxwriter/styles.lua        )
install_lua_module ( xlsxwriter.theme         xlsxwriter/theme.lua         )
install_lua_module ( xlsxwriter.utility       xlsxwriter/utility.lua       )
install_lua_module ( xlsxwriter.workbook      xlsxwriter/workbook.lua      )
install_lua_module ( xlsxwriter.worksheet     xlsxwriter/worksheet.lua     )
install_lua_module ( xlsxwriter.xmlwriter     xlsxwriter/xmlwriter.lua     )

install_data    ( README.md LICENSE.txt )
install_example ( examples/             )
install_doc     ( docs/                 )
