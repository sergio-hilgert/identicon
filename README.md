# Identicon

Elixir project to generate a image based on a string, just like GitHub profile icons.

## How to use

Install the dependencies using: `mix deps.get`

Run the iex with the command: `iex -S mix`

Inside the iex type

```elixir
iex> Identicon.main("your_name")
```
![Identicon](your_name.png)
Format: ![Alt Text](url)

And the image will be saved inside the aplication folder with the name you gave to it. It aways generate the same image for the same string.

