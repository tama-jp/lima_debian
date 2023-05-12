# lima_debian


Dockerデスクトップは、削除

brew install lima
% brew install lima docker
docker-compose を使う予定がある場合
docker-compose のインストール

$ brew install docker-compose
$ mkdir -p ~/.docker/cli-plugins
$ ln -sfn /usr/local/opt/docker-compose/bin/docker-compose ~/.docker/cli-plugins/docker-compose


vim ~/.docker/config.json

　"credsStore": "desktop"　から、　"credStore": "desktop"　に変更


limactl list

limactl start docker.yml

limactl start docker

limactl stop docker
limactl delete docker
limactl start docker.yml
