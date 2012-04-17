LuaPlus for Marmalade
=====================

This folder contains the mkf file for integrate
LuaPlus into your Marmalade project.

Original LuaPlus homepage is: http://luaplus.org

The LuaPlus source is compiled completely unmodified.

To include LuaPlus in your project, put the luaplus directory within your project directory.
Then you'll need to add this LuaPlus subproject and the include path to it:

subprojects
{
    ./luaplus
}


includepath
{
    ./luaplus
}

