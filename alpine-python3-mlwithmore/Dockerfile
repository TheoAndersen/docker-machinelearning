FROM theoandersencarton/alpine-python3-mlbasic

RUN apk add --no-cache gcc g++ musl-dev python3-dev linux-headers \
                       libpng-dev freetype-dev build-base && \
    pip install --upgrade jupyter matplotlib

EXPOSE 8888
