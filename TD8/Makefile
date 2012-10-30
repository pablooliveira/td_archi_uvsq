MAIN=TD08.tex
DEPS=Dflipflop.pdf SR-design.pdf TD8-4.pdf TD8-compt.pdf TD8-GL.pdf TD8-JK.pdf TD8-seriepara.pdf TD8-T.pdf JKflipflop.pdf SRflipflop.pdf TD8-chrono.pdf TD8-GLD.pdf TD8-inc.pdf TD8-paraserie.pdf TD8-SP.pdf


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


