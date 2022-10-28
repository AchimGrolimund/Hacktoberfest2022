init:
	@echo make bad
	@echo make good

bad:
	docker build -f .Dockerfile_Bad -t bad_go_image .

good:
	docker build -f .Dockerfile_Good -t good_go_image_scratch .

good_alpine:
	docker build -f .Dockerfile_Good_Alpine -t good_go_image_alpine .


.PHONY: all