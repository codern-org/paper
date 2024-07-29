FROM qmcgaw/latexdevcontainer

RUN apt-get update && \
  apt-get -y install --no-install-recommends pandoc texlive-xetex \
  texlive-latex-extra texlive-extra-utils texlive-bibtex-extra biber && \
  rm -rf /var/lib/apt/lists/*
