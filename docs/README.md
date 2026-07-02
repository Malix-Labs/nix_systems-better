# Nix: Systems Better

Externally extensible flake systems for microarchitecture levels

An implementation of https://github.com/nix-systems/nix-systems/issues/16 for https://github.com/nix-systems

## Usage

### As a flake

```nix
inputs.systems.url = "github:Malix-Labs/nix_systems-better?dir=x86_64/generic/v3";
```

### Without flakes

```nix
import "${nix_systems-better}/x86_64/generic/v3"
```

## Available Paths

* `x86_64/generic/v1` (v2, v3, v4)
* `x86_64/specific/zen`
* `x86_64/generic` (All generic)
* `x86_64/specific` (All specific)
* `x86_64` (All x86_64)
* `/` (All systems)
