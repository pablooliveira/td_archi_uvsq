MAIN=RappelsIEE754.tex

all: formulaire
	@echo 
	@echo 
	@echo "========================================================"
	@echo "Le formulaire se trouve dans le sous répertoire ./build/"
	@echo "========================================================"

formulaire: $(MAIN)
	@mkdir -p ./build/
	pdflatex -jobname=formulaire -output-directory=./build/ $(MAIN)
