# frozen_string_literal: true

task default: :fmt

task :fmt do
  sh 'rubocop -A'
end

task push: :fmt do
  sh 'git add .'
  sh 'git commit -m "update"'
  sh 'git push'
end
