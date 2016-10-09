# Nginx Config for Brotli and PHP7 FPM

This is a basic nginx file meant to be modified and tinkered with. Out of the box you get SSL requests compressed with Brotli (falling back to gzip when Brotli is unavailable) passed to PHP7 FPM. Make sure to replace `servername.com` with your FQDS.

## License
Released under MIT.