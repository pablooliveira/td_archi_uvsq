MAIN=TD09.tex
DEPS= 10MC1.png 10MC2.png TD9-auto1.pdf TD9-auto2.pdf TD9-automate.png TD9-auto.pdf TD9-transitions.png

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


