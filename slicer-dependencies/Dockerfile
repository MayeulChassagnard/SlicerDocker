FROM slicer/slicer-base:latest
MAINTAINER 3D Slicer Community <slicer-devel@bwh.harvard.edu>

CMD ./BuildSlicer.sh

# Build-time metadata as defined at http://label-schema.org
ARG BUILD_DATE
ARG IMAGE
ARG VCS_REF
ARG VCS_URL
LABEL org.label-schema.build-date=$BUILD_DATE \
      org.label-schema.name=$IMAGE \
      org.label-schema.description="An image containing all the dependencies to build Slicer itself: ITK, VTK, CTK, Qt, etc." \
      org.label-schema.url="http://www.slicer.org" \
      org.label-schema.vcs-ref=$VCS_REF \
      org.label-schema.vcs-url=$VCS_URL \
      org.label-schema.schema-version="1.0"
