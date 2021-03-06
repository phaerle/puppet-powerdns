source 'https://rubygems.org'

group :test do
  gem 'rake'
  gem 'puppet', ENV['PUPPET_GEM_VERSION'] || '>= 3.8.0'
  gem 'puppet-syntax'
  gem 'puppet-lint'
  gem 'puppet-doc-lint'
  gem 'puppet-lint-absolute_classname-check'
  gem 'puppet-lint-leading_zero-check'
  gem 'puppet-lint-trailing_comma-check'
  gem 'puppet-lint-version_comparison-check'
  gem 'puppet-lint-classes_and_types_beginning_with_digits-check'
  gem 'puppet-lint-unquoted_string-check'
  gem 'puppet-lint-variable_contains_upcase'
  gem 'puppet-lint-undef_in_function-check'
  gem 'puppet-lint-file_ensure-check'
  gem 'puppet-lint-empty_string-check'
  gem 'puppetlabs_spec_helper'
  gem 'rspec'
  gem 'rspec-core'
  gem 'rspec-puppet'
  gem 'rspec-puppet-facts'
  gem 'rspec-puppet-utils'
  gem 'metadata-json-lint'
  gem 'net-http-persistent'                   , require: false if RUBY_VERSION >= '2.3.0'
  gem 'rubocop'                               , require: false if RUBY_VERSION >= '2.0.0'
  gem 'net-http-persistent'       , '2.9.4'   , require: false if RUBY_VERSION < '2.3.0'
  gem 'rubocop'                   , '0.41.2'  , require: false if RUBY_VERSION < '2.0.0'
  gem 'rubocop-rspec'             , '~> 1.6'  , require: false if RUBY_VERSION >= '2.3.0'
  gem 'google-api-client'         , '<= 0.9.4', require: false if RUBY_VERSION < '2.0.0'
  gem 'json_pure'                 , '<= 2.0.1', require: false if RUBY_VERSION < '2.0.0'
  gem 'codeclimate-test-reporter'             , require: false
  gem 'simplecov'                             , require: false
end

group :development do
  gem 'travis'
  gem 'travis-lint'
  gem 'puppet-blacksmith'
end

group :acceptance do
  gem 'beaker'                  , require: false if RUBY_VERSION >= '2.2.5'
  gem 'beaker-rspec'            , require: false if RUBY_VERSION >= '2.2.5'
  gem 'serverspec'
  gem 'beaker-puppet_install_helper'
end
