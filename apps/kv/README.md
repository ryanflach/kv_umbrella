# KV

Outcome of an interactive tutorial for Elixir, available [here](http://elixir-lang.org/getting-started/mix-otp/introduction-to-mix.html).

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `kv` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:kv, "~> 0.1.0"}]
    end
    ```

  2. Ensure `kv` is started before your application:

    ```elixir
    def application do
      [applications: [:kv]]
    end
    ```
