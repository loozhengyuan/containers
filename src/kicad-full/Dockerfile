ARG KICAD_VERSION=8.0.3
FROM "kicad/kicad:${KICAD_VERSION}"

# NOTE: Required in order to reference the prior ARG instruction
# https://docs.docker.com/reference/dockerfile/#understand-how-arg-and-from-interact
ARG KICAD_VERSION

USER root

RUN git clone \
        --branch "${KICAD_VERSION}" \
        --depth 1 \
        https://gitlab.com/kicad/libraries/kicad-packages3D.git \
        /usr/share/kicad/3dmodels

USER kicad
