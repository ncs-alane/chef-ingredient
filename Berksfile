source 'https://supermarket.chef.io'

metadata

group :test do
  cookbook 'test', path: './test/fixtures/cookbooks/test'
  cookbook 'custom_repo', path: './test/fixtures/cookbooks/custom_repo'  
end

group :integration do
  cookbook 'git'
  cookbook 'apt'
end
