# app-manager-debug-rev-02forge

    version 0.6.5
    load_balancers schedulers

simple data store for small scale

## Installation

You can use this gem by putting the following inside your Gemfile:

    gem "app-manager-debug-rev-02forge"

Now install:

    bundle install

And that's it!

## Usage

```ruby
class MyController
  include app-manager-debug-rev-02forge
  
  def action
    app-manager-debug-rev-02forge!(:success)
  end
end
```

## Changes

Version 0.6.5 changes:
    
    - Initial release

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Copyright

Copyright (C) 2025 load_balancers schedulers

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.

