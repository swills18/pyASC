#
# show some tests for try_astride etc.
#

#  All 1440 files from 8-nov-2015 with the nice streak in IMG01329
#TESTDIR = ../../20151108_MD01_raw/

#  simple test with 20 files IMG01320.FIT .. IMG01339.FIT from the 20151108_MD01_raw sample
TESTDIR = Test2015

help:
	@echo Some help:
	@echo "run python try_astride -h for input flag descriptions"

clean:
	rm -rf test1

test1:
	./try_astride.py -i $(TESTDIR) -o test1
latest:
	./try_astride.py
cleanall:
	rm -rf *-output

