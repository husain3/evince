themedir = $(pkgdatadir)/icons/hicolor
size = 22x22
context = actions

iconsdir = $(themedir)/$(size)/$(context)

icons_DATA = \
	evince-comment-annotation.png				\
	evince-yellow-highlight-annotation.png				\
	evince-magenta-highlight-annotation.png				\
	evince-cyan-highlight-annotation.png				\
	evince-green-highlight-annotation.png				\
	evince-format-text-squiggly.png				\
	evince-format-text-strikethrough.png				\
	evince-format-text-underline.png				\
	eye.png				\
	object-rotate-left.png		\
	object-rotate-right.png		\
	view-page-continuous.png	\
	view-page-facing.png		\
	zoom.png                \
	zoom-fit-page.png		\
	zoom-fit-width.png

noinst_DATA = \
	view-page-continuous.xcf	\
	view-page-facing.xcf		\
	zoom.svg                \
	zoom-fit-page.svg		\
	zoom-fit-width.svg

EXTRA_DIST = \
	$(icons_DATA)	\
	$(noinst_DATA)

-include $(top_srcdir)/git.mk
