Builds a static libsqlcipher, libcrypto and libssl for iOS

When building, make sure to ise UniversalBuild>Any Simulator.  For some reason, if you use iOS device, the amalgamation target will not generate sqlite.c
