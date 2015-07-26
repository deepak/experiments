# NOTE:
# - first target is run by default. which is test here
# - format is:
#   target: <space-sperated-dependencies>
#   	<commands>
#   the whitespace at the head of each line must be a tab, not spaces
#   for eg. see target all
# - when echo is called as `@echo`
#   only the output is shown
#   and with plain `echo` the command is also shown
#   for debugging - i guess
# - see default rules with:
#   make -p > default_rules
#   to print only the
#   make -p -f /dev/null > only_default_rules
# - compiler flags and vars like CFLAGS and LDLIBS
#   will differ from system to system.
#   autotools is supposed to help here

test:
	@echo "only echo"
	echo "echo this and show the actual command"
	ls -l ~/

run:
	@echo run

all: test run
	@echo all
