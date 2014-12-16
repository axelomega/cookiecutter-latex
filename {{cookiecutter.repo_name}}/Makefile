MAIN?={{ cookiecutter.main_file_name }}.tex

.PHONY: pdf

all:
	pdflatex $(MAIN)
	pdflatex $(MAIN)

clean:
	$(RM) $(MAIN).aux
