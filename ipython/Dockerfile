FROM hasani
LABEL maintainer=@sufinameh
RUN conda update conda && \
	conda install --quiet --yes ipython && \
	conda clean -tipsy
CMD ["ipython"]
