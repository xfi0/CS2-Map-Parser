# CS2-Map-Parser

Easily convert CS2 maps to `.vphys` and/or `.tri` files.

## Features

- Parse Counter-Strike 2 map files
- Convert to `.vphys` (Valve Physics) format
- Convert to `.tri` (triangle mesh) format

## Dependencies

- [Valve Resource Format (VRF)](https://github.com/ValveResourceFormat/ValveResourceFormat) - MIT
- [ValvePak](https://github.com/SteamDatabase/ValvePak) - MIT

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/xfi0/CS2-Map-Parser.git
   cd CS2-Map-Parser
   ```
2. Restore dependencies:
   ```bash
   dotnet restore
   ```
3. Build the project:
   ```bash
   dotnet build
   ```

## Usage

```bash
CS2-Map-Parser.exe -i <path-to-map.vpk> -o <output-directory> --format vphys
```

## License
MIT
