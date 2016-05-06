# Gatekeeper

An opinionated authorization framework for Elixir projects.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add gatekeeper to your list of dependencies in `mix.exs`:

        def deps do
          [{:gatekeeper, "~> 0.0.1"}]
        end

  2. Ensure gatekeeper is started before your application:

        def application do
          [applications: [:gatekeeper]]
        end
