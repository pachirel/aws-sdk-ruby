# Copyright 2013 Amazon.com, Inc. or its affiliates. All Rights Reserved.
#
# Licensed under the Apache License, Version 2.0 (the "License"). You
# may not use this file except in compliance with the License. A copy of
# the License is located at
#
#     http://aws.amazon.com/apache2.0/
#
# or in the "license" file accompanying this file. This file is
# distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF
# ANY KIND, either express or implied. See the License for the specific
# language governing permissions and limitations under the License.

source 'http://rubygems.org'

gemspec

gem 'rake', require: false

group :test do
  gem 'rspec', git: 'git://github.com/rspec/rspec'
  gem 'rspec-core', git: 'git://github.com/rspec/rspec-core'
  gem 'rspec-mocks', git: 'git://github.com/rspec/rspec-mocks'
  gem 'rspec-expectations', git: 'git://github.com/rspec/rspec-expectations'

  gem 'webmock'
  gem 'simplecov', require: false
end

group :docs do
  gem 'yard'
  gem 'rdiscount'
end
