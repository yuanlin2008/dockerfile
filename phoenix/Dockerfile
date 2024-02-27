FROM elixir

# inotify-tools
RUN apt-get update -y && apt-get install inotify-tools -y

# phx
RUN mix local.hex --force &&\
	mix archive.install hex phx_new --force