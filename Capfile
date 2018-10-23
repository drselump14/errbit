require "capistrano/setup"
require "capistrano/deploy"

require "capistrano/rbenv"
require "capistrano/bundler"
require "capistrano/rails/assets"
require "capistrano/puma"
install_plugin Capistrano::Puma  # Default puma tasks
install_plugin Capistrano::Puma::Nginx  # if you want to upload a nginx site temp

Dir.glob("lib/capistrano/tasks/*.rake").each { |r| import r }
