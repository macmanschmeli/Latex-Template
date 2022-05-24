all:
	-pdflatex -interaction=nonstopmode report.tex > log.txt
	@del log.txt
	@echo ===============================================
	@echo Error Summary
	@echo ===============================================
	-@findstr "Error" report.log
	@echo ===============================================
	@echo Warning Summary
	@echo ===============================================
	-@findstr "Warning" report.log
	@echo ===============================================
