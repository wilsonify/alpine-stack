
base:
	docker build --progress=plain --platform=amd64 --tag "ghcr.io/wilsonify/alpine-stack-3.20-base:1.0.0" -f Dockerfile-base .

build:
	docker build --progress=plain --platform=amd64 --tag "ghcr.io/wilsonify/alpine-stack-3.20-build:1.0.0" -f Dockerfile-build .

runtime:
	docker build --progress=plain --platform=amd64 --tag "ghcr.io/wilsonify/alpine-stack-3.20-runtime:1.0.0" -f Dockerfile-runtime .
