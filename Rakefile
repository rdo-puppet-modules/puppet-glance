
require 'puppetlabs_spec_helper/rake_tasks'
require 'puppet-lint/tasks/puppet-lint'

# Test for master-patches branch

PuppetLint.configuration.fail_on_warnings = true
PuppetLint.configuration.send('disable_80chars')
PuppetLint.configuration.send('disable_class_parameter_defaults')
