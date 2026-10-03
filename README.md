# neuroFly

An interactive 3D fruit fly brain explorer: a realistic fruit fly loops around a rotten apple in true 3D flight while a whole-brain connectome panel pulses in sync with its flight phases.

**Live demo:** https://shuhaibnc.github.io/neuroFly/

## Features

- Realistic 3D fruit fly — segmented body, paired wings, antennae, halteres, six jointed legs
- True 3D flight: the fly sweeps behind the apple, banks into turns, pitches on climbs and dives, and changes apparent size with depth
- Rotten apple rendered as a lit 3D mesh with dimensional skin, bruising, stem, leaf and surface mold
- Connectome panel: interactive, draggable 3D point cloud built from all 138,625 measured FlyWire v783 neuron anchor positions in their real spatial arrangement
- Neural activity colors shift with the fly's flight phases, and the glow appears only on measured neuron points

## Data & credits

- Neuron positions: [FlyWire](https://flywire.ai) whole-brain dataset (v783)
- Connectome rendering adapted from [Fly Chess](https://github.com/tolatolatop/fly-chess) by tolatolatop
- Fly character proportions inspired by [flyfear](https://github.com/furkancak1r/flyfear) by furkancak1r

## Run locally

Just open `index.html` in a browser — no build step needed, everything is inlined in the single file.

## License

MIT — see [LICENSE](LICENSE).
