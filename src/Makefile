build:
	$(MAKE) -C monitor build
	$(MAKE) -C k8splugin build
	$(MAKE) -C orchestrator build
	$(MAKE) -C ncm build
	$(MAKE) -C dcm build
	$(MAKE) -C rsync build

deploy:
	$(MAKE) -C monitor deploy
	$(MAKE) -C k8splugin deploy
	$(MAKE) -C orchestrator deploy
	$(MAKE) -C ncm deploy
	$(MAKE) -C dcm deploy
	$(MAKE) -C rsync deploy

all:
	$(MAKE) -C monitor all
	$(MAKE) -C k8splugin all
	$(MAKE) -C orchestrator all
	$(MAKE) -C ncm all
	$(MAKE) -C dcm all
	$(MAKE) -C rsync all

clean:
	$(MAKE) -C monitor clean
	$(MAKE) -C k8splugin clean
	$(MAKE) -C orchestrator clean
	$(MAKE) -C ncm clean
	$(MAKE) -C dcm clean
	$(MAKE) -C rsync clean
