.PHONEY=all
URL_ROOT=https://raw.githubusercontent.com/Mcompetitions/M4-methods/master/Dataset

all: Monthly-test.csv Monthly-train.csv

Monthly-test.csv:
	wget $(URL_ROOT)/Test/$@

Monthly-train.csv:
	wget $(URL_ROOT)/Train/$@
