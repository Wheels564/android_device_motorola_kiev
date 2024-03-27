# Device is configured for MicroG.

To prevent MicroG from being installed remomve
these lines from lineage_kiev.mk

# Inherit some common PARTNER_GMS stuff.
$(call inherit-product, vendor/partner_gms/products/gms.mk)


