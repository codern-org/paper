FROM qmcgaw/latexdevcontainer

RUN apt-get update && \
  apt-get -y install --no-install-recommends pandoc texlive-base texlive-xetex \
  texlive-bibtex-extra biber texlive-latex-extra texlive-science \
  texlive-fonts-recommended texlive-fonts-extra texlive-extra-utils && \
  rm -rf /var/lib/apt/lists/*
