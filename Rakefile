# Encoding: utf-8

desc "Runs knife cookbook test"
task :syntax do
  sh "rbenv exec bundle exec knife cookbook test \
  #{File.basename(Dir.getwd)} -o cookbooks"
end

task default: ['manifest:verify', 'cookbooks:verify']

namespace :manifest
desc 'Verify manifests'
task :verify do

end

namespace :cookbooks
desc 'Verify cookbooks'
task :verify do

end
