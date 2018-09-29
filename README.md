Using Python 3 to covert MS Outlook .msg files to .eml format.

# Dependencies :

The module requires Python 3 and the [compoundfiles](https://pypi.python.org/pypi/compoundfiles) package.

	pip3 install compoundfiles

The module is also using [compressed_rtf](https://github.com/delimitry/compressed_rtf).

# Setup :

	cp msg2eml.py /usr/local/bin/msg2eml
	
	chmod 711 /usr/local/bin/msg2eml

# How to use :

Either convert a single file by piping:

	msg2eml < some_email.msg > some_email.eml

Or convert a set of files:

	msg2eml *.msg