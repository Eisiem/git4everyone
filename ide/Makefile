ROOT_DIR = $(dir $(abspath $(dir $(lastword $(MAKEFILE_LIST)))))
#DATE = $(shell date +%Y.%m.%d-%H.%M.%S)
CONTAINER_TOOL = "podman"


makefile-test:
	echo "ROOT_DIR: $(ROOT_DIR)"


# Build container image
docker-build:
	$(CONTAINER_TOOL) build \
	-f "$(ROOT_DIR)ide/" \
	-t "img_git4everyone" \
	$(ROOT_DIR)
	

# Create container
docker-run:
	$(CONTAINER_TOOL) run \
	--rm --replace -i -t \
	--mount type=bind,source="$(ROOT_DIR)",target=/git4everyone,readonly \
	--privileged \
	--workdir="/git4everyone" \
	--name="cont_git4everyone" \
	"img_git4everyone" \
	python src/main.py
	
