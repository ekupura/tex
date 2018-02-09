FROM paperist/alpine-texlive-ja
RUN apk update
RUN apk add curl bzip2
COPY ./jlisting.sty /usr/local/texlive/2017/texmf-dist/tex/latex/listings
RUN mktexlsr
ENV LANG=ja_JP.UTF-8
