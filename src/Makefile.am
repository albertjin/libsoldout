lib_LTLIBRARIES = libsoldout.la
libsoldout_la_SOURCES = array.c array.h buffer.c buffer.h markdown.c markdown.h renderers.c renderers.h

bin_PROGRAMS = benchmark
benchmark_SOURCES = benchmark.c
benchmark_LDADD = libsoldout.la

bin_PROGRAMS += mkd2html
mkd2html_SOURCES = mkd2html.c
mkd2html_LDADD = libsoldout.la

bin_PROGRAMS += mkd2latex
mkd2latex_SOURCES = mkd2latex.c
mkd2latex_LDADD = libsoldout.la

bin_PROGRAMS += mkd2man
mkd2man_SOURCES = mkd2man.c
mkd2man_LDADD = libsoldout.la

include_HEADERS = markdown.h

