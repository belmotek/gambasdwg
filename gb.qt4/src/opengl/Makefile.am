COMPONENT = gb.qt4.opengl
include $(top_srcdir)/component.am
include $(top_srcdir)/gb.qt.am

gblib_LTLIBRARIES = gb.qt4.opengl.la

gb_qt4_opengl_la_LIBADD = @QTOPENGL_LIB@
gb_qt4_opengl_la_LDFLAGS = -module @LD_FLAGS@ @QTOPENGL_LDFLAGS@
gb_qt4_opengl_la_CPPFLAGS = @QTOPENGL_INC@

gb_qt4_opengl_la_SOURCES = \
 main.h main.cpp \
 CGLarea.h CGLarea_moc.cpp CGLarea.cpp

