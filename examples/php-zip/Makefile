install:
	cd app && composer install --prefer-dist --optimize-autoloader --no-dev --no-interaction

artifacts:
	cp -r app $(ARTIFACTS_DIR)/app
	cp -r nginx $(ARTIFACTS_DIR)/nginx
	cp -r php $(ARTIFACTS_DIR)/php
	cp -r bootstrap $(ARTIFACTS_DIR)/bootstrap

build-Function: install artifacts
