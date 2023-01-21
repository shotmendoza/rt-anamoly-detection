ROOT_DIR:=$(CURDIR)

run:
	docker run \
	-p 8080:8080 \
	--mount type=bind,source="$(PWD)",destination=/src \
	sho/lp-jupyter

build:
	docker build -t sho/lp-jupyter --file Dockerfile .
