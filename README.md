# PortableUtils

rm -rf gdbserver
LDFLAGS=-static ./configure --with-static-standard-libraries --disable-shared --enable-static
LDFLAGS=-static ./configure --with-static-standard-libraries --disable-shared --enable-static --enable-tui
