FROM buckless/manager

COPY ./buckless-manager.manifest.json /usr/src/buckless-manager/manifest.json
COPY ./images /usr/src/buckless-manager/public/images

RUN npm run build
