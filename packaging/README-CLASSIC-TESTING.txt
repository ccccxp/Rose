Rose Classic Test Package
=========================

This is a portable test package. It does not contain an installer.

1. Exit Rose completely.
2. Press Win+R, enter %LOCALAPPDATA%\Rose, and press Enter.
3. Back up the existing classic folder first.
4. Copy everything inside Classic-Resources\classic to
   %LOCALAPPDATA%\Rose\classic. Merge folders and replace files when prompted.
5. Start the test build from Rose\Rose.exe.

Do not copy the whole Classic-Resources folder into the Rose data directory,
and do not create a nested %LOCALAPPDATA%\Rose\classic\classic directory.

Classic-Resources\RESOURCE-SOURCE.txt records the LeagueSkins repository,
branch, and exact commit used by this package.
