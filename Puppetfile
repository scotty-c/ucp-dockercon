#!/usr/bin/ruby env

require "socket"
$hostname = Socket.gethostname

forge 'http://forge.puppetlabs.com'

mod 'garethr/docker', :git => 'https://github.com/garethr/garethr-docker.git'
mod 'puppetlabs/apt'
mod 'puppetlabs/docker_ucp', :git => 'https://github.com/puppetlabs/puppetlabs-docker_ucp.git'
mod 'puppetlabs/stdlib'
mod 'maestrodev/wget'
mod 'saz/dnsmasq'
