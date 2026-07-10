SUBDIRS = assets

install-data-local:
	$(mkinstalldirs) $(DESTDIR)$(datadir)/themes/sugar-72/gtk-4.0
	$(INSTALL_DATA) $(srcdir)/gtk.css \
		$(DESTDIR)$(datadir)/themes/sugar-72/gtk-4.0/gtk.css
	$(mkinstalldirs) $(DESTDIR)$(datadir)/themes/sugar-100/gtk-4.0
	$(INSTALL_DATA) $(srcdir)/gtk.css \
		$(DESTDIR)$(datadir)/themes/sugar-100/gtk-4.0/gtk.css

uninstall-local:
	rm -f $(DESTDIR)$(datadir)/themes/sugar-72/gtk-4.0/gtk.css
	rm -f $(DESTDIR)$(datadir)/themes/sugar-100/gtk-4.0/gtk.css

EXTRA_DIST = gtk.css
