# KVServer

Server application built in part 4 of the Elixir tutorial available [here](http://elixir-lang.org/getting-started/mix-otp/dependencies-and-umbrella-apps.html).

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `kv_server` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:kv_server, "~> 0.1.0"}]
    end
    ```

  2. Ensure `kv_server` is started before your application:

    ```elixir
    def application do
      [applications: [:kv_server]]
    end
    ```
