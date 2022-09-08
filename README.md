# README

Reproduction of https://github.com/kaspth/conventional_extensions/issues/4


Run

```
bin/rails r "puts Foo"
```

```
/Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/bundler/gems/conventional_extensions-d879e930e5dd/lib/conventional_extensions/loader.rb:8:in `dirname': no implicit conversion of false into String (TypeError)
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/bundler/gems/conventional_extensions-d879e930e5dd/lib/conventional_extensions/loader.rb:8:in `initialize'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/bundler/gems/conventional_extensions-d879e930e5dd/lib/conventional_extensions.rb:9:in `new'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/bundler/gems/conventional_extensions-d879e930e5dd/lib/conventional_extensions.rb:9:in `load_extensions'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/bundler/gems/conventional_extensions-d879e930e5dd/lib/conventional_extensions.rb:22:in `inherited'
	from /Users/lachlansylvester/Blake/ce/app/models/foo.rb:1:in `<top (required)>'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/gems/zeitwerk-2.6.0/lib/zeitwerk/kernel.rb:27:in `require'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/gems/zeitwerk-2.6.0/lib/zeitwerk/kernel.rb:27:in `require'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/gems/railties-7.0.3.1/lib/rails/commands/runner/runner_command.rb:46:in `<main>'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/gems/railties-7.0.3.1/lib/rails/commands/runner/runner_command.rb:46:in `eval'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/gems/railties-7.0.3.1/lib/rails/commands/runner/runner_command.rb:46:in `perform'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/gems/thor-1.2.1/lib/thor/command.rb:27:in `run'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/gems/thor-1.2.1/lib/thor/invocation.rb:127:in `invoke_command'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/gems/thor-1.2.1/lib/thor.rb:392:in `dispatch'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/gems/railties-7.0.3.1/lib/rails/command/base.rb:87:in `perform'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/gems/railties-7.0.3.1/lib/rails/command.rb:48:in `invoke'
	from /Users/lachlansylvester/.asdf/installs/ruby/3.0.4/lib/ruby/gems/3.0.0/gems/railties-7.0.3.1/lib/rails/commands.rb:18:in `<top (required)>'
	from bin/rails:4:in `require'
	from bin/rails:4:in `<main>'
```