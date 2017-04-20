FROM buckless/manager

COPY ./config /usr/src/buckless-manager/config/profiles
COPY ./images /usr/src/buckless-manager/images
COPY ./manifest.json /usr/src/buckless-manager/manifest.json

RUN yarn build
