source 'https://supermarket.chef.io'

metadata

group :integration do
  cookbook 'elasticsearch_test', path: './test/fixtures/cookbooks/elasticsearch_test'

  # not a strict dependency, but necessary for TK testing
  cookbook 'java'
  cookbook 'curl'
end

source 'https://api.berkshelf.com'

cookbook 'apt', git: 'https://github.com/chef-cookbooks/apt.git'
cookbook 'yum', git: 'https://github.com/chef-cookbooks/yum.git'
cookbook 'chef-sugar', git: 'https://github.com/sethvargo/chef-sugar.git'
cookbook 'ark', git: 'https://github.com/chef-cookbooks/ark.git'
