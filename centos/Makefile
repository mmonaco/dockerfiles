IMAGE  ?= mmonaco/centos
OPTS   ?= --pull

image:
	docker build $(OPTS) -t $(IMAGE) .

.PHONY: image
