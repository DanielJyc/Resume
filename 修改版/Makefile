
PDFC = xelatex
READER = evince

TARGET = cv.pdf
OUTGROWTH = *.out *.log *.aux
SOURCE = cv.tex

$(TARGET): $(SOURCE)
	$(PDFC)	$(SOURCE)
	$(PDFC)	$(SOURCE)

read:
	$(READER) $(TARGET)

clean:
	-rm $(OUTGROWTH)

cleanall:
	-rm $(OUTGROWTH) $(TARGET)

.PHONY:read clean cleanall
