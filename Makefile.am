SUBDIRS = @WCM_KERNEL_VER@

DIST_SUBDIRS = 2.6.30 2.6.36 2.6.38 3.7 3.17
EXTRA_DIST = git-version-gen version \
             inputattach/inputattach.c inputattach/README \
	     inputattach/serio-ids.h

.PHONY: generate-version

version: generate-version

generate-version:
	./git-version-gen > version
