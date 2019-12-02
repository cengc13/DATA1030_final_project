main:
	pdflatex --shell-escape final_report
	bibtex final_report
	pdflatex --shell-escape final_report
	pdflatex --shell-escape final_report

clean:
	rm -rf final_report.aux final_report.log final_report.out final_report.toc _minted-final_report

fast:
	pdflatex --shell-escape final_report
