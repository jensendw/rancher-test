deploy:
	/usr/local/bin/rancher-compose --url https://rancher.origami42.com -f "rancher-compose.yml" --access-key $(RANCHER_ACCESS_KEY) --secret-key $(RANCHER_SECRET_KEY) --project-name dantest up --upgrade -d -c

all: deploy
