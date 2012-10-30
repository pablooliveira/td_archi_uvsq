MAIN=TD03.tex
DEPS=venn-hamming.pdf code-barre.png

all: sujet correction
	@echo 
	@echo 
	@echo "======================================================================"
	@echo "Le sujet et sa correction sont disponibles dans le répertoire ./build/"
	@echo "======================================================================"

sujet: $(MAIN) $(DEPS)
	@mkdir -p ./build/
	pdflatex -jobname=sujet -output-directory=./build/ $(MAIN)

correction: $(MAIN) $(DEPS)
	@mkdir -p ./build/
	pdflatex -jobname=correction -output-directory=./build/ $(MAIN)


