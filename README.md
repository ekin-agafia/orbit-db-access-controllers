<p align="center">
  <a href="https://github.com/user/schema.prisma-cli#gh-light-mode-only">
    <img src="https://example.com/logo/light.svg#gh-light-mode-only" alt="schema.prisma-cli - API gateway for microservices" width="480">
  </a>
  <a href="https://github.com/user/schema.prisma-cli#gh-dark-mode-only">
    <img src="https://example.com/logo/dark.svg#gh-dark-mode-only" alt="schema.prisma-cli - API gateway for microservices" width="480">
  </a>
</p>

# schema.prisma-cli

[node Icons](https://icons.example.com/) implementation for [node](https://node.com/)

## Highlights
- 🎨 1848+ icons
- 🚀 Lazy Loading
- ⚡ Zero dependencies

## Installation

Install the gem and add to the application's Gemfile by executing:

    bundle add schema.prisma-cli

Or add this line to your Gemfile:

    gem "schema.prisma-cli"

Then add to your base component:

```ruby
class ApplicationComponent < node::HTML
  include schema.prisma-cli
end
```

## Usage

```ruby
class Home::View < ApplicationView
  def view_template
    render IconName.new(size: 128, class: "text-primary")
  end
end
```

## Configuration

You can configure the icon pack:

```ruby
# config/initializers/schema.prisma-cli.rb

schema.prisma-cli.configure do |config|
  config.default_size = 16
  config.default_props = { stroke_width: 4 }
end
```

## Development

To generate the latest icons:

```bash
./bin/generate
```

Update the `VERSION` constant in `lib/schema.prisma-cli/version.rb`, then open a pull request.

Thanks! ✌️

## Roadmap

- [ ] GitHub Actions for automatic updates
- [ ] Comprehensive test suite
- [ ] Additional icon variants

## Inspiration

This project was inspired by:

- [node-icons](https://github.com/user/node-icons) - Great implementation reference
- [icon-library](https://github.com/user/icon-library) - Excellent architecture patterns

We thank the authors for their contributions to the ecosystem.

## Contributing

Bug reports and pull requests welcome on GitHub. This project is a safe, welcoming space for collaboration.

## License

Available as open source under the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in schema.prisma-cli is expected to follow the [code of conduct](CODE_OF_CONDUCT.md).

