if USE_ROCKCHIPMPP
ROCKCHIPMPP_DIR=rockchipmpp
else
ROCKCHIPMPP_DIR=
endif

if USE_VPUDEC
VPUDEC_DIR=vpudec
else
VPUDEC_DIR=
endif

if USE_KMS
KMS_DIR=kms
else
KMS_DIR=
endif

if USE_DRMROCKCHIP
RKXIMAGE_DIR=rkximage
else
RKXIMAGE_DIR=
endif

SUBDIRS = $(ROCKCHIPMPP_DIR) $(VPUDEC_DIR) $(KMS_DIR) $(RKXIMAGE_DIR)

DIST_SUBDIRS = rockchipmpp vpudec kms rkximage

include $(top_srcdir)/common/parallel-subdirs.mak
