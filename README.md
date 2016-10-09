# Nginx Config for Brotli and PHP7 FPM

This is a basic nginx file meant to be modified and tinkered with. Out of the box you get SSL requests compressed with Brotli (falling back to gzip when Brotli is unavailable) passed to PHP7 FPM. Make sure to replace `servername.com` with your FQDS.

## Background

[Brotli](https://github.com/google/brotli) is a compression algorithm released by Google that is useful for decreasing the size of text files transmitted for HTTP. Brotli's compression ratio is about 20-30% higher than that of gzip.

You will need to compile nginx with the [nginx Brotli module](https://github.com/google/ngx_brotli) to use this configuration file.

## License
Released under MIT.