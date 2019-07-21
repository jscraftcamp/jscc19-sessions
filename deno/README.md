## Deno Try-out

_session by Jörn ([@NarigoDF](https://twitter.com/NarigoDF))_

We created a [deno-try-out repository](https://github.com/Narigo/deno-try-out) with a few commits on our way.

- Visual Studio Code complains about typescript `.ts` extension in import URLs.
  Deno needs them.
- You can add the `types.d.ts` by copying the output of `deno types`.
- You can use `--allow-read <directory>` to always allow reading of files inside
  a directory.
- Deno caches all downloads somewhere and does not need to re-download them. Use
  `deno --reload` to force it to reload.
- Saying "always allow" when asked, will ask again when restarting the program.
  Allow once will ask for permission for the same file again and again. Allow
  always will never ask for read permissions anymore. Starting a server will ask
  just once for network permission as it will only listen on a port.
