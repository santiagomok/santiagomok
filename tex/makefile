.PHONY: clean all 

CC = xelatex
LOG_DIR = log

$(LOG_DIR)/resume.pdf: resume.tex awesome-cv.cls | $(LOG_DIR)
	$(CC) -output-directory=$(LOG_DIR) $<

$(LOG_DIR):
	mkdir $@

clean:
	rm -rf $(LOG_DIR)
