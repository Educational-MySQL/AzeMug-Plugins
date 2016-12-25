# cmake configuration file for AzeMug Authentication plugin

MYSQL_ADD_PLUGIN(azemug_auth azemug_auth.cc
    MODULE_ONLY MODULE_OUTPUT_NAME "azemug_auth")

INSTALL(FILES azemug_auth.ini DESTINATION ${INSTALL_PLUGINDIR})