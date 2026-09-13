# Fantasy Computers

A small collection of standalone, browser-based fantasy computer interfaces. Each machine is a single HTML file with its own styling, controls and simulation logic. There is no build step and no runtime dependency.

## Machines

- **[Reclaimer-IX](reclaimer.html)** - An amber CRT survival terminal where you manage an outpost, upgrade hardware, accept network jobs and decrypt broadcasts.
- **[Retro-8](retro8.html)** - An 8-bit front-panel computer with address and data switches, 16 bytes of RAM, an instruction set and sample programs.
- **[Retro-32](retro32.html)** - A 32-bit mechanical computer with cartridges, a built-in assembler, terminal I/O, memory-mapped hardware and a fantasy SSD.

The collection is introduced by **[index.html](index.html)**, which is the GitHub Pages entry point.

## Run locally

Open `index.html` directly in a browser, or serve the folder with any static web server:

```bash
python3 -m http.server
```

Then visit `http://localhost:8000/`.

## GitHub Pages

Publish the repository from the branch and folder configured in the repository's GitHub Pages settings. GitHub Pages will serve `index.html` as the site root, and the three machine links will work as relative paths.

## Controls

The interfaces are designed for mouse and keyboard use. Each machine includes its own in-app instructions or manual. Browser storage is used by Reclaimer-IX for its local save state; the other machines keep their current session in memory.

## License

MIT. See [LICENSE](LICENSE).
