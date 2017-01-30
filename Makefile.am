ACLOCAL_AMFLAGS = -I m4

SUBDIRS = AutoBouquetsMaker DLNABrowser DLNAServer StreamTV 3GModemManager OpenUitzendingGemist TunerServer OnDemand Fempa LCD4linux RemoteChannelStreamConverter

if HAVE_WIRELESSACCESSPOINT
SUBDIRS += WirelessAccessPoint
endif


if GIGABLUE
SUBDIRS += GigaBlueVFDControl Blindscan AudioEffect
endif

if GBQUADPLUS
SUBDIRS += AudioEffect TransCodingSetup
endif

if GBQUAD
SUBDIRS += AudioEffect TransCodingSetup
endif

if GB800SEPLUS
SUBDIRS += AudioEffect
endif

if GB800UEPLUS
SUBDIRS += AudioEffect
endif
