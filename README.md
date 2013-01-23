[![Code Climate](https://codeclimate.com/badge.png)](https://codeclimate.com/github/Helabs/clientela-crm)

## Clientela

Clientela is full-featured CRM web application written in Ruby on Rails. It runs smoothly using Heroku and Amazon S3.

## Information

### Bug reports

If you discover a problem with Clientela, we would like to know about it. Submit it on the issue tracker: https://github.com/Helabs/clientela-crm/issues

If you found a security bug, do *NOT* use the GitHub issue tracker. Send an email to the maintainers listed at the bottom of the README.

### Todo

* Move to Rails 3.2.x

## Setup development environment

### Requirements

* Ruby 1.9.3
* PostgreSQL
* Sphinx

You can use your regular development environment but Vagrant usage is preferred. If you don't have any idea of what Vagrant is please read [http://www.vagrantup.com/](http://www.vagrantup.com/) and be happy.

After installing Vagrant you can run:

    vagrant up
    vagrant ssh
    bundle install
    rake db:create:all
    rake db:schema:load
    script/rails server
    
and access http://localhost:3000 on your browser.

## Known issues

### spec/controllers/reports_controller_spec.rb:14 fails

Run `compass compile` and try again.

## Additional information

### Contributors

We have a not yet so long list of valued contributors. Check them all at:

https://github.com/Helabs/clientela-crm/contributors

### Maintainers

* Matheus Bras (https://github.com/matheusbras)
* Rodrigo Pinto (https://github.com/rodrigopinto)
* Sylvestre Mergulhão (https://github.com/mergulhao)

## License

Copyright (C) 2012 HE:labs

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License version 3 as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.
