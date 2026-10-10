# entities-multiplayer-fabric-abyssal

An underwater XR zone for the multiplayer fabric as a Godot project: a zone server, an observer client and a headless diagnostic observer.

## What it is for

The zone server serves entity snapshots over a multiplexed transport, and the client renders them as jellyfish and whales. The main scene is the observer, viewed through an operator camera on a desktop or through a headset when one is present. `taskweft_domains/` holds the planning domains its agents load, and `programs/` holds the sandboxed guest programs.

## Build and run

Open `project.godot` in a Godot editor built with the multiplayer fabric's modules and run the main scene. Running `scons` in `programs/` builds the guest programs.

## Licence

MIT. See [LICENSE](LICENSE).
