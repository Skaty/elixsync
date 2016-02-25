# Elixsync
[![Build Status](https://travis-ci.org/Skaty/elixsync.svg?branch=master)](https://travis-ci.org/Skaty/elixsync)

A file synchronisation tool that runs on elixir

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add elixsync to your list of dependencies in `mix.exs`:

        def deps do
          [{:elixsync, "~> 0.0.1"}]
        end

  2. Ensure elixsync is started before your application:

        def application do
          [applications: [:elixsync]]
        end
