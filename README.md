# fonts-conf
Some fonts configuration...

Leave these:

	/etc/fonts/conf.d/10-autohint.conf
	/etc/fonts/conf.d/10-scale-bitmap-fonts.conf

Remove these:

	/etc/fonts/conf.d/10-hinting-*.conf

Set freetype (e.g. in `~/.bash_profile`):

	export FREETYPE_PROPERTIES="truetype:interpreter-version=35"
  
