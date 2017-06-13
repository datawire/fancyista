.PHONY: default

VERSION=$(shell git describe --tags)
SHELL:=/bin/bash

default:
	@echo "See https://github.com/datawire/fancyista"

version:
	@echo $(VERSION)

virtualenv:
	virtualenv --python=python3 ../venv
	../venv/bin/pip install -r requirements.txt
