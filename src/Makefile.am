#
# Makefile.am for uml/src
#

yncludedir = @yncludedir@/uml

client_DATA =				\
	uml.ycp				\
	uml_source_proposal.ycp		\
	uml_user_proposal.ycp		\
	uml_options_proposal.ycp	\
	uml_disks_proposal.ycp		\
	uml_finish.ycp			\
	inst_uml_source.ycp		\
	inst_uml_user.ycp		\
	inst_uml_options.ycp		\
	inst_uml_disks.ycp		\
	inst_uml_kickoff.ycp		\
	inst_uml_options.ycp		\
	inst_uml_network.ycp		\
	uml_network_proposal.ycp	\
	inst_uml_user.ycp

ynclude_DATA = cmdline.ycp

desktop_DATA =				\
	uml.desktop

module_DATA =				\
	UML.ycp

uml:
	ln -sf . uml

ycpchook = uml

EXTRA_DIST = $(client_DATA) $(ynclude_DATA) $(module_DATA) $(desktop_DATA)

include $(top_srcdir)/Makefile.am.common
