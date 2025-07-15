AC_INIT([ThorsSlack], [0.1], [Loki.Astari+ThorsSlack@gmail.com])
AC_PREREQ([2.65])

AC_CONFIG_MACRO_DIR([build/autotools/m4])
AC_CONFIG_AUX_DIR([build/autotools/build])

AX_THOR_FUNC_INIT_BUILD([ThorsSlack], [src/ThorsSlack/ThorsSlack.cpp], [20])


#
# Add extra configuration here
#
AX_THOR_CHECK_USE_THORS_SERIALIZE_HEADER_ONLY
AX_THOR_CHECK_USE_THORS_SERIALIZE


LT_INIT

AX_THOR_FEATURE_HEADER_ONLY_VARIANT([THORSSLACK])
AX_THOR_FUNC_TERM_BUILD([THORSSLACK], [src/ThorsSlack/ThorsSlackConfig.h:config.h.in])

AC_OUTPUT
